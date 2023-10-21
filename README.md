# RashCheck: Lyme Disease Early Detection

Welcome to the RashCheck project, a web application developed for the Women Who Code Hackathon for Social Good 2023. RashCheck is designed to empower individuals to perform early self-assessments for potential Lyme Disease symptoms from the comfort of their own homes. It utilizes machine learning and image analysis to detect Erythema Migrans rashes, a common early indicator of Lyme Disease.

## Table of Contents
- [Introduction](#introduction)
- [Challenges Statement](#challenges-statement)
- [Proposed Solution](#proposed-solution)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)

## Introduction
Lyme Disease is a significant public health concern transmitted through tick bites. Early detection is crucial for effective treatment and to prevent severe complications. RashCheck addresses the challenge of delayed diagnosis by providing a user-friendly platform for individuals to assess the likelihood of Lyme Disease based on uploaded rash images.

## Challenges Statement
Our project aims to address the challenge of delayed Lyme Disease diagnosis due to limited access to healthcare and poor recognition of early symptoms. Through a user-friendly web app, utilizing machine learning and image analysis, our solution, RashCheck, empowers individuals to perform early self-assessments of potential Lyme Disease symptoms, contributing to timely treatment, reduced complications, and improved public health outcomes. RashCheck leverages Flask, Streamlit, and a CNN Inception-v3 model to provide remote and accessible early detection, benefiting society by promoting health empowerment and well-being.

## Proposed Solution
RashCheck bridges the gap between initial symptoms and professional medical evaluation by providing a user-friendly, accessible tool for the early detection of Lyme Disease based on the appearance of rashes, specifically targeting the identification of Erythema Migrans rashes. It serves as a valuable resource in the fight against Lyme Disease, ultimately contributing to better public health outcomes.

## Features
- Upload and analyze images of rashes.
- Predict whether the rashes are potentially Lyme Disease-related.
- Promote early detection and prompt medical attention.
- Accessible from anywhere with an internet connection.

## Tech Stack
- Python
- Flask
- Streamlit
- OpenCV
- Keras (TensorFlow backend)

## Getting Started

### Prerequisites
- Python 3.6+
- An internet connection
- A web browser

### Installation
1. Clone this repository to your local machine: git clone https://github.com/syiraleey/lyme_disease_detection.git
2. Navigate to the project directory.
3. Install the required Python packages using pip: pip install -r requirements.txt

## Usage
1. Run the Flask web app: lyme_disease_prediction.py
2. Open a web browser and go to `http://localhost:8501` to access RashCheck.
3. Follow the on-screen instructions:
- Click the "Choose an image" button to upload a rash image.
- Click the "Predict" button to analyze the image.
- The result, indicating whether the rashes are potentially Lyme Disease-related, will be displayed.
