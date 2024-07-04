# Real-Time-Gesture-Recognition-for-Sign-Language-Translaion
[![forthebadge](https://forthebadge.com/images/badges/made-with-python.svg)](https://forthebadge.com) 
![custom-badge](https://raw.githubusercontent.com/mxdyyy/badge/7bbc06cca83b680ed421674221d629ebd9eab43f/built-on-jupyter-notebook.svg)
![custom-badge](https://raw.githubusercontent.com/mxdyyy/badge/e283407160e7c08b17db40211c9418f2a41807a7/built-by-team-dorkyduos%20(1).svg)
[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com)
### Welcome to the DorkyDuos team's GitHub repository for our project on Real-Time Action Recognition
This project aims to develop a real-time sign language detection system using Long Short-Term Memory (LSTM) neural networks. The system translates sign language gestures into understandable text or speech, facilitating effective communication between the deaf community and the general population.

## Team Members
- **Madhav N (Team Leader)**  
  Branch: B.Tech Information Technology
- **Mathangi N**  
  Branch: B.Tech Computer Science Engineering (AI & DS)

## Table of Contents
- [Introduction](#introduction)
- [Abstract](#abstract)
- [Problem Statement](#problem-statement)
- [Metrics](#metrics)
- [Solution](#solution)
- [Dataset](#dataset)
- [Working](#working)
- [Model Architecture](#model-architecture)
- [Primary Goals and Key Uniqueness](#primary-goals-and-key-uniqueness)
- [Business Model](#business-model)
- [Proof of Concept](#proof-of-concept)
- [Contributors](#contributors)

## Introduction
Sign language serves as a critical means of communication for the hearing impaired. However, the lack of real-time interpretation tools poses significant challenges in facilitating effective communication between the deaf community and the general population. Developing a robust real-time sign language detection system can bridge this gap by instantly translating sign language gestures into understandable text or speech.

## Abstract
This project aims to develop an advanced system for real-time sign action detection through video input utilizing Long Short-Term Memory (LSTM) neural networks. The proposed system employs deep learning techniques to model temporal dependencies in sequential data, significantly enhancing communication accessibility for individuals with hearing impairments.

## Problem Statement
To develop a real-time sign language detection system to accurately interpret and translate sign language gestures into text or speech. The system should be capable of recognizing a wide range of sign language gestures in various environmental conditions and provide instant feedback.

## Metrics
- **Accuracy:** Measure of the system's correct interpretation of sign language gestures.
- **Speed:** Response time in translating gestures into text or speech.
- **Robustness:** Performance in diverse environmental conditions (lighting, background noise, etc.).
- **Vocabulary Coverage:** Ability to recognize a wide range of sign language gestures.
- **User Feedback:** Feedback from the deaf community on the system's usability and accuracy.

## Solution
Our solution involves utilizing advanced technologies, including machine learning, computer vision, and deep learning techniques, to build a real-time sign language detection system. The primary purpose of the system is to accurately interpret and translate sign language gestures in real-time, providing instant responses from live video input.

## Dataset
Due to the lack of an existing suitable dataset online, we created our own image and video dataset. Each folder represents an action to be detected, and each action has 3 videos processed into 30 frames.

## Working
1. **Import and Install Dependencies**
2. **Keypoints using MP Holistic**
3. **Extract KeyPoint Values**
4. **Setup Folders For Collection**
5. **Collect KeyPoint Values for Training and Testing**
6. **Preprocess Data and Create Labels and Features**
7. **Build and Train LSTM Neural Network**
8. **Make Predictions**
9. **Evaluation using Performance Metrics like Confusion Matrix and Accuracy**

## Model Architecture
1. **Input video data**
2. **Data preprocessing**
3. **Training and testing**
4. **Decision Making**
5. **Output**

## Primary Goals and Key Uniqueness
### Primary Goals
- Achieve high accuracy in recognizing a diverse set of sign language gestures.
- Provide real-time translation with minimal latency.
- Ensure robustness in varying environmental conditions.
- Foster seamless communication between the deaf and hearing communities.

### Key Uniqueness
- **Dataset:** Built from scratch, containing frames converted into numpy arrays exported from videos.
- **Real-Time Monitoring:** Potential to provide real-time monitoring of workplace environments.
- **Consistent and Objective Analysis:** Automated AI systems offer consistent and objective analysis, reducing potential bias.
- **Automated Approach:** Significantly speeds up the detection process and reduces reliance on manual intervention.

## Business Model
- **Subscription Model:** Offer a subscription-based service to companies and organizations.
- **API Access:** Provide an API and charge a fee based on usage.
- **Data Insights Subscription:** Offer insights and analytics based on collected data.
- **Freemium Model:** Offer a basic version for free with limited features, with a premium upgrade available.
- **White Label Solution:** Develop a white-label version for other companies to customize and rebrand.

## Proof of Concept
- **HELLO:** Live input video detecting the gesture for "HELLO".
- **THANK YOU:** Live input video detecting the gesture for "THANK YOU".
- **FINE:** Live input video detecting the gesture for "FINE".
- **I LOVE YOU:** Live input video detecting the gesture for "I LOVE YOU".
- **HOW ARE YOU:** Live input video detecting the gesture for "HOW ARE YOU".

[Video of Live Input Footage](https://drive.google.com/file/d/1NYw3qUR5ls4kRQBDCiF9f4NdSBRBNVVt/view?usp=sharing)

## Contributors
- **Madhav N**: [madhavnarayanan2004@gmail.com](mailto:madhavnarayanan2004@gmail.com)
- **Mathangi N**: [mathanginarayanan2004@gmail.com](mailto:mathanginarayanan2004@gmail.com)
