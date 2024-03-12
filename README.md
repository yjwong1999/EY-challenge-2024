# EY-challenge-2024

We are among the Top 10 entrants of **EY Open Science Data Challenge 2024** 

## Business Idea: Data Fleet is What You Need
- Data is often compared to oil, but like oil, data needs to be refined and transformed to unleash its true potential.

## Repo Structure
```
EY-challenge-2024
├── challenge_1_submission_images       (EY Challenge Phase 1 Submission's test images)
│   ├── Submission data
├── pretrained                          (pretrained experiments for building detections, so that you can skip Module 1: BuildingDetection.ipynb)
│   ├── detect
│   │   ├── train
│   │   │   ├── weights                 (pretrained weights for building detections)
├── 1 BuildingDetection.ipynb           (Module 1: To pretrain a YOLOv8n model using Msft Building Footprint dataset)
├── 2 Finetuner.ipynb                   (Module 2: To finetune the pretrained model from Module 1 on EY Training Dataset)
├── challenge_1_submission_images.zip   (Just the zip file of EY Challenge Phase 1 test images)
```

## Setup environment
```bash
# Clone the repo
git clone https://github.com/yjwong1999/EY-challenge-2024.git
cd EY-challenge-2024

# Create conda environment
conda create --name ey-challenge python=3.8.10 -y
conda activate ey-challenge
```

## Training
1. Start with `1 BuildingDetection.ipynb` to pretrain a YOLOv8n model using Msft Building Footprint dataset. A pretrained experiments outputs (including the weights) of Module 1 are provided in `pretrained` directory. So unless you want to modify the training pipeline for Module 1, you can skip this and directly go to Module 2.
2. With the pretrained model, you can proceed to `2 Finetuner.ipynb`. In this module, you will fine-tune the pretrained model from Module 1 on the EY Training Dataset


## Download dataset (if dataset is not in Roboflow)
1. [Microsoft Building Dataset (only Puerto Rico region)](https://drive.google.com/file/d/1usJRoHRydBFtp65uovEioWXkdMBPioXO/view?usp=drive_link)
2. [EY-Challenge Phase 1 test set](https://drive.google.com/file/d/1R6pTpvyxucpSubhQgTUIyGGwbk5ardU7/view?usp=drive_link)
