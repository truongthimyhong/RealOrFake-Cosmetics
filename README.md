# RealOrFake-Cosmetics
AI Models for Detecting Authentic and Counterfeit Cosmetics
# RealOrFake-Cosmetics
A CNN-based solution to differentiate authentic and counterfeit cosmetics
## Project Overview

This project leverages Artificial Intelligence (AI) 🤖 to distinguish between genuine and counterfeit cosmetics through packaging image analysis. By employing advanced technology, this solution aims to promote informed consumer choices and protect users from the risks posed by fake cosmetics in the market.

## Problem Statement

As the cosmetics market continues to grow, the prevalence of counterfeit products has surged, posing significant threats to consumer health and brand reputation. Traditional anti-counterfeiting measures like holograms and barcodes are increasingly ineffective. This project harnesses the power of AI to provide a reliable method for identifying genuine cosmetics, addressing the urgent need for consumer protection.

## Solution

The project utilizes a Convolutional Neural Network (CNN) to classify images of cosmetic packaging as real or fake. Through image processing, augmentation, and analysis, the model learns to detect subtle differences in packaging, ensuring accurate identification even with minor variations. The system is designed for deployment on mobile devices 📱, enabling users to verify cosmetics anytime, anywhere.

## Academic Context

This project was developed as part of the course *"Applications of Artificial Intelligence in Business"* at the School of Economics, University of Da Nang.

## Objectives

- Classify images of cosmetics as real or fake for popular brands in Vietnam.  
- Focus on image classification using AI, specifically Convolutional Neural Networks (CNN).  
- Deploy the model on mobile devices for convenient, on-the-go cosmetic verification.

## Tools and Libraries 🛠️

- **Programming Language**: Python  
- **Core Libraries**: `os`, `numpy`, `matplotlib`, `tensorflow`, `OpenCV`, `sklearn`  
- **AI Model**: Convolutional Neural Network (CNN)

## Implementation Steps

1. Import and set up required libraries.  
2. Collect and preprocess data (Real/Fake).  
3. Split data into training (60%) and testing (40%) sets.  
4. Augment data through techniques like rotation, flipping, and shifting.  
5. Build a CNN model with layers: `Conv2D`, `MaxPooling2D`, `Flatten`, `Dense`.  
6. Train the model and monitor accuracy and loss metrics.  
7. Deploy the model for predictions via image uploads or webcam input.


