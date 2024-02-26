# EY-challenge-2024

## Setup environment
```bash
# Clone the repo
git clone https://github.com/yjwong1999/EY-challenge-2024.git
cd EY-challenge-2024

# Create conda environment
conda create --name ey-challenge python=3.8.10 -y
conda activate ey-challenge
```

## Download dataset
https://drive.google.com/file/d/1usJRoHRydBFtp65uovEioWXkdMBPioXO/view?usp=drive_link
https://drive.google.com/file/d/1R6pTpvyxucpSubhQgTUIyGGwbk5ardU7/view?usp=drive_link

```
EY-challenge-2024
├── ultralytics
├── datasets
│   ├── images
│   │   ├── train
│   │   ├── val
│   │   ├── test
│   ├── detection-ocr            (Head 1 for Task 1)
│   │   ├── labels
│   │   │   ├── train
│   │   │   ├── val
│   │   │   ├── test
│   ├── detection-license-plate  (Head 2 for Task 2)
│   │   ├── labels
│   │   │   ├── train
│   │   │   ├── val
│   │   │   ├── test
│   ├── detection-car-colour     (Head 3 for Task 3)
│   │   ├── labels
│   │   │   ├── train
│   │   │   ├── val
│   │   │   ├── test
```
