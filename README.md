# 🖼️ Single Image Super-Resolution using Deep Learning  
**Final Project – Deep Learning and its Applications to Signal and Image Processing and Analysis**  
Course Number: 361.2.1120  
Submission Date: 27.06.2025  

## 📌 Project Overview
This project focuses on solving the **Single Image Super-Resolution (SISR)** problem: generating high-resolution images from low-resolution inputs using deep neural networks. Two models are compared:
- **Baseline**: SRResNet – a well-known architecture based on residual learning.
- **Our Model**: A Super-Resolution model built completely from scratch, It's somewhat similar as EDSR. It features deeper residual blocks without BatchNorm for better detail preservation, adaptive learning rate scheduling, and improved normalization layers. This model is both a ground-up implementation and an enhancement over the original EDSR architecture.


We evaluated performance using **PSNR**, **SSIM**, and **FID**, and included an **ablation study** replacing L1 loss with MSE to assess the effect of the loss function.


## 🚀 How to Run
The entire code is contained in a single Jupyter Notebook:  
**`SISR_Final_Project.ipynb`**

### ✅ Requirements:
- Python 3.8+
- Google Colab or local Jupyter
- PyTorch
- torchvision
- numpy, matplotlib, tqdm, etc.

### 📂 Running via Google Colab:
1. **Upload the notebook to your Google Drive.**
2. **Open it in Google Colab.**
3. The dataset (DIV2K) is loaded using Kaggle API or pre-uploaded patches.
4. Press **Run All** (או להריץ תא תא) – the notebook includes training both SRResNet and our custom model, as well as evaluation, ablation, and visualizations.

### 📌 Notes:
- Training is done on ×4 downscaled images from DIV2K.
- Results include **PSNR/SSIM/FID**, side-by-side visual comparisons, and loss curves.

## 📊 Evaluation Metrics
We evaluate using:
- **PSNR (Peak Signal-to-Noise Ratio)** – pixel-wise accuracy
- **SSIM (Structural Similarity Index)** – perceptual similarity
- **FID (Fréchet Inception Distance)** – realism of generated images

## 🔍 Ablation Study
We compare:
- **L1 Loss (baseline)** – better at preserving details  
- **MSE Loss (ablation)** – faster convergence but slightly worse perceptual quality  

We show that L1 outperforms MSE in final results despite slower convergence.

## 📷 Sample Results
- Examples where both models succeed/fail
- Case studies where our custom model outperforms SRResNet
- Visual examples from validation set crops

## 👥 Authors
- Student 1 – Full Name – ID  
- Student 2 – Full Name – ID

## 🔗 GitHub Link
[👉 Project Repository](https://github.com/your-username/super-resolution-project)  
> *(You can also paste this link in the Word report as a clickable hyperlink with CTRL+K)*

