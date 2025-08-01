# SVD-based-Image-Denoising-and-Metrics-Evaluation

This project applies Singular Value Decomposition (SVD) to denoise and compress images from the CIFAR-10 dataset. Gaussian noise is added to clean images, then truncated SVD is used to reconstruct cleaner versions. Evaluation is done using PSNR, SSIM, and MSE.

## Features
- Add Gaussian noise to images
- Apply SVD to RGB channels
- Denoise using top-k or thresholded singular values
- Visualize original vs. denoised images
- Hyperparameter tuning (k)
- Plot PSNR, SSIM, MSE vs. k

## Dataset
- CIFAR-10 (60,000 images across 10 classes)

## Requirements
- PyTorch
- NumPy
- Matplotlib
- scikit-image
