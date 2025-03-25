# Super Resolution Imaging Project

### Authors
- Sri Varsha Adavath [011860642]
- Lalith Mohan Midde [011848601]

## Overview

### Introduction
Super Resolution Imaging (SRI) is a technique for reconstructing high-resolution images from low-resolution inputs. This technology is essential in applications where image clarity is critical, such as satellite imaging and medical diagnostics. The objective of our project is to enhance image resolution and quality using advanced deep learning techniques.

### Problem Statement
Low-resolution images often lack critical details, making accurate interpretation and analysis challenging. Enhancing these images through super-resolution techniques addresses these challenges by significantly improving image clarity.


## Dataset & Preprocessing

**Primary Dataset:**  
- NASA Geographical Objects Multilabel Dataset (Satellite Images)

**Secondary Dataset:**  
- Sculpture images (used for runtime validation)

**Preprocessing Steps:**
- Normalization of images
- Data augmentation (rotation, flipping, scaling)


## Methodology

**Baseline Model:**
- SRCNN (Super Resolution Convolutional Neural Network)

**Advanced Model:**
- SRGAN (Super Resolution Generative Adversarial Network)

**Loss Functions:**
- Content Loss
- Perceptual Loss
- Adversarial Loss

**Training Strategy:**
- Hybrid CNN-GAN architecture to optimize image quality

## Evaluation Metrics

**Quantitative Metrics:**
- Peak Signal-to-Noise Ratio (PSNR)
- Structural Similarity Index (SSIM)

**Qualitative Metrics:**
- Visual inspection for qualitative analysis

**Dataset Size Rationale:**  
A smaller dataset was initially used for rapid runtime validation and to ensure model reliability.



## Results
The combined CNN and GAN models demonstrated significant improvements in super resolution imaging quality, confirming the effectiveness of our methodology.



## Future Work
Future enhancements include:
- Experimentation with larger datasets
- Refinement of training strategies
- Exploration of additional advanced model architectures for improved performance and efficiency



## Conclusion
This project successfully illustrated the potential of deep learning methods, specifically CNN and GAN architectures, in significantly enhancing image quality and detail for real-world applications.

## License
This project is licensed under the MIT License. See the LICENSE file for details.
