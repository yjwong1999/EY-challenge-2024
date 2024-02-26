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

## Repo Structure
```
EY-challenge-2024
├── challenge_1_submission_images       (EY Challenge Phase 1 Submission's test images)
│   ├── Submission data
├── pretrained                          (pretrained experiments for building detections, so that you can skip Module 1: BuildingDetection.ipynb)
│   ├── detect
│   │   ├── train
│   │   │   ├── weights                 (pretrained weights for building detections)
│   │   ├── val
├── 1 BuildingDetection.ipynb           (Module 1: To pretrain a YOLOv8n model using Msft Building Footprint dataset)
├── 2 Finetuner.ipynb                   (Module 2: To finetune the pretrained model from Module 1 on EY Training Dataset)
```


## Download dataset
https://drive.google.com/file/d/1usJRoHRydBFtp65uovEioWXkdMBPioXO/view?usp=drive_link
https://drive.google.com/file/d/1R6pTpvyxucpSubhQgTUIyGGwbk5ardU7/view?usp=drive_link

