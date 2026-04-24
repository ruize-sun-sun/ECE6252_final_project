# ECE6252_final_project

## Description

This project studies model compression using MobileNetV2 on a phone classification dataset.

We compare three models:
- Original model
- Distilled (compressed) model
- Quantized model

The goal is to reduce model size and latency while keeping good accuracy.

---


## How to Run
Open the notebook:
model.ipynb
Run all cells to train the model and reproduce the results.



## Models
The trained models are included:

- original_model.pth
- distilled_model.pth
- quant_model.pth

---



## Dataset

The dataset is not included due to size.
Download here:
https://drive.google.com/drive/folders/1UYDvgQgaj4DnOQIx18Wx3eC3oB-i35Zs?usp=drive_link

After downloading, place it in the following structure:

phone_dataset
  - train
  - val
  - test

model.ipynb

