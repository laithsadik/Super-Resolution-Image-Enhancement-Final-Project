# 🖼️ Single Image Super-Resolution using Deep Learning  
**Final Project – Deep Learning and its Applications to Signal and Image Processing and Analysis**  
Course Number: 361.2.1120  
Submission Date: 27.06.2025  

## 📌 Project Overview
This project focuses on solving the **Single Image Super-Resolution (SISR)** problem: generating high-resolution images from low-resolution inputs using deep neural networks. Two models are compared:
- **Baseline**: SRResNet – a well-known architecture based on residual learning.
- **Our Model**: A Super-Resolution model built completely from scratch, It's somewhat similar as EDSR. It features deeper residual blocks without BatchNorm for better detail preservation, adaptive learning rate scheduling, and improved normalization layers. This model is both a ground-up implementation and an enhancement over the original EDSR architecture.


We evaluated performance using **PSNR**, **SSIM**, and **FID**, and included an **ablation study** replacing L1 loss with MSE to assess the effect of the loss function.


