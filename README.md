# Lab-7-Traditional-vs-AI-Gaussian-Filters

This MATLAB script demonstrates an approach to image denoising, comparing traditional and AI-based noise reduction techniques for a grayscale image with Gaussian noise.

Noise Modeling	Gaussian noise was simulated using MATLAB's imnoise() function, with a specific standard deviation (σ = 0.04). This allows controlled introduction of random variations to the image.

Denoising Techniques	Two primary denoising approaches were explored: - Traditional Method: Wiener filter (adaptive local noise reduction)- AI Method: Pre-trained DnCNN deep learning network.

Image Quality Metrics	Quantitative evaluation using PSNR and SSIM provided objective measures of noise reduction effectiveness, comparing:
  
- Original image
- Noisy image
- Wiener filtered image
- AI-filtered image |


<img width="1864" height="586" alt="Screenshot 2025-11-06 at 10 12 21" src="https://github.com/user-attachments/assets/812a3193-7831-405e-81ff-7ad3a3d332ae" />
<img width="680" height="202" alt="Screenshot 2025-11-16 at 12 12 17" src="https://github.com/user-attachments/assets/51dd13e1-ee5d-4cbe-b290-132c59a8aea0" />
