# Human Emotion Detection in Audio Data with Deep Neural Networks Using Cross-Dataset

## Overview
This repository contains the implementation of a research project aimed at enhancing human emotion detection from audio data using deep neural networks (DNNs), specifically Convolutional Neural Networks (CNNs). By combining two powerful datasets, the Ryerson Audio-Visual Database of Emotional Speech and Song (RAVDESS) and the Toronto Emotional Speech Set (TESS), this model demonstrates high accuracy across various emotions.

## Project Team
- **Sandushi Weraduwa** - Undergraduate, Department of Industrial Management, University of Kelaniya, Sri Lanka - sandushiw98@gmail.com
- **Minuli Kannangara** - Undergraduate, Department of Industrial Management, University of Kelaniya, Sri Lanka - kkminuli@gmail.com
- **Shiran SuriyaPathiraja** - Undergraduate, Department of Industrial Management, University of Kelaniya, Sri Lanka - shiranay22083@gmail.com

## Objectives
1. **Versatile Emotion Classification Model**: Develop a system that can adapt to various characteristics of audio data sets for effective emotion detection.
2. **Model Generalization**: Enhance accuracy on unseen inputs and reduce performance fluctuations.
3. **Advanced Feature Extraction Techniques**: Implement sophisticated signal processing methods to accurately detect emotions from diverse datasets.

## Technologies Used
- Python
- TensorFlow/Keras
- Librosa for audio feature extraction (MFCCs)

## Model Performance
Our CNN model achieved an F1 score of 0.94 on the test set, showing robust performance across different emotions:
- Highest accuracy for 'Calm' emotion: 0.97
- Lowest accuracy for 'Sad' emotion: 0.91

## Repository Contents
- `model/` - Contains the trained CNN model files.
- `data/` - Sample data from RAVDESS and TESS datasets used for training and testing.
- `src/` - Source code for the emotion detection model and preprocessing scripts.
- `notebooks/` - Jupyter notebooks illustrating the model training and evaluation processes.

## How to Use
1. Clone the repository.
2. Install dependencies using `pip install -r requirements.txt`.
3. Run the Jupyter notebooks in the `notebooks/` directory to see the model in action.



