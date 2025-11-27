# Night-Time-Pedestrian-Detection-using-RGB-Thermal-Fusion

This repository contains 5 Colab notebooks implementing a complete pipeline for multimodal pedestrian detection using RGB + Thermal (IR) images and YOLO models.

## 📁 Notebooks

1. NB1 – Fusion: Load LLVIP dataset, pair RGB–IR frames, apply simple fusion.
2. NB2 – Pseudo-Labels: Generate annotations using a COCO-pretrained model.
3. NB3 – YOLO Training: Train YOLOv8n on fused images + pseudo labels.
4. NB4 – Attention Fusion: Apply thermal-guided attention and compare results.
5. NB5 – Demo: Simple, presentation-ready notebook to run inference.

## 🔗 Dataset

LLVIP Dataset (RGB + Thermal paired images):
https://bupt-ai-cz.github.io/LLVIP/

Download and store in Google Drive before running the notebooks.

## 🧠 Models

The notebooks train and evaluate:

1. RGB-only YOLO
2. Thermal-only YOLO
3. Simple-fusion YOLO
4. Attention-fusion YOLO

The best model weights (best.pt) are generated during training.

📌 Note:<br>
This repository contains no datasets.<br>
Download LLVIP separately from the official source and update paths in the notebooks.
