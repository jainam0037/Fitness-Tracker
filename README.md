# Fitness Tracker with Python

## Welcome to the Fitness Tracker Project!
This project is designed to help you learn data science and machine learning through a hands-on approach by creating a fitness tracker with Python. This tracker will classify barbell exercises and count repetitions using accelerometer and gyroscope data.

## Project Overview

### Introduction
The Fitness Tracker project aims to provide a practical learning experience for data science and machine learning enthusiasts. The project focuses on the Quantified Self concept, where individuals use technology to collect data on various aspects of their daily lives, in this case, fitness activities.

### Data Processing
- **Reading and Cleaning:** Load raw sensor data, clean it by handling missing values and noise.
- **Processing:** Process the data to extract relevant segments corresponding to different exercises.
- 

### Data Visualization
- **Time Series Plotting:** Create functions to visualize time series data for better understanding of sensor readings during exercises.
- **Exercise Visualization:** Plot sensor data for individual exercises to identify patterns and trends.

![Bench Screenshot]([https://github.com/jainam0037/Airbnb-Dashboard/blob/main/image.png?](https://github.com/jainam0037/Fitness-Tracker/blob/main/reports/figures/Bench%20(E).png)



### Outlier Detection
- **Noise Identification:** Implement methods to detect and handle noisy data points that could affect model performance.

### Feature Engineering
- **Feature Extraction:** Extract meaningful features from time series data such as mean, standard deviation, and frequency domain features to enhance model performance.

### Predictive Modeling
- **Model Building:** Build and evaluate machine learning models to classify different barbell exercises.
- **Algorithm Selection:** Experiment with different algorithms such as Random Forest, SVM, and Neural Networks to find the best model.

### Repetition Counting
- **Algorithm Development:** Develop algorithms to count exercise repetitions using the processed sensor data.
- **Accuracy Evaluation:** Evaluate the accuracy of repetition counting algorithms and refine them for better performance.

## Target Audience
This project is suitable for:
- **Beginners:** Detailed explanations and step-by-step guidance for those new to data science and machine learning.
- **Intermediate Learners:** Advanced techniques and insights for those with some experience in the field.
- **Fitness Enthusiasts:** Learn how to process and analyze fitness-related sensor data to gain insights into workout routines.

## Data Source
The data used in this project was collected using a Meta Motion sensor from Ambient Lab during gym workouts. The dataset includes exercises such as:
- Bench Press
- Deadlift
- Overhead Press
- Barbell Row
- Squats

Data was collected from five participants performing these exercises.

## Requirements
### Basic Knowledge
- Python programming
- Data science concepts


### Project Template
- Download the project template from this [GitHub repository](#).

## Action Items
- Clone the repository: `git clone https://github.com/your-repo/fitness-tracker.git`
- Navigate to the project directory: `cd fitness-tracker`
- Install the required libraries: `pip install -r requirements.txt`
- Follow the notebook instructions to start exploring the data and building models.

## Project Details

### Model Architecture
- **Layers:** The model architecture includes a series of convolutional layers followed by fully connected layers to capture spatial and temporal features from the sensor data.
- **Learning Rate:** The initial learning rate is set to 0.001 and adjusted using learning rate scheduling techniques.
- **Loss Function:** Mean Squared Error (MSE) for regression tasks and Cross-Entropy Loss for classification tasks.
- **Optimizer:** Adam optimizer is used for its efficiency and effectiveness in training deep learning models.
- **Early Stopping:** Implemented early stopping to monitor validation loss and prevent overfitting during training.

### Training Details
- **Data Augmentation:** Applied techniques such as noise addition and signal shifting to increase dataset diversity.
- **Batch Size:** Set batch size to 32 for training the models.
- **Epochs:** Trained the models for 100 epochs with early stopping based on validation performance.

## Conclusion
The Fitness Tracker project provides a comprehensive learning experience in data science and machine learning, focusing on real-world applications in fitness tracking. By completing this project, you'll gain valuable skills in data processing, feature engineering, model building, and evaluation, all within the context of a practical application.

