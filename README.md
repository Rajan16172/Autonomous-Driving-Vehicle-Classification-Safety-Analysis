# ai-automotive-project
Public repository · Python · Deep Learning · Computer Vision · EDA
# Autonomous Driving: Vehicle Classification & Safety Analysis

An AI/ML capstone project completed as part of the Generative AI and Machine Learning Professional Certificate Program at E&ICT Academy, IIT Kanpur.

## Overview

This project explores two complementary aspects of autonomous driving:

1. **Vehicle Classification:** A deep learning model using transfer learning with MobileNetV2 to classify vehicle images into four categories.
2. **Tesla Crash Safety Analysis:** Exploratory data analysis of crash incidents to investigate fatality patterns, vehicle-model trends, geographic distribution, and reported Autopilot involvement.

## Part 1: Vehicle Classification

**Objective:** Develop an image classification model for vehicle perception applications.

### Dataset and preprocessing
- 4,914 labeled vehicle images.
- Consolidated the original eight classes into four categories: car, truck, bus, and two-wheeler.
- Resized images to 224 × 224 pixels.
- Used an 80% training and 20% testing split.

### Model and approach
- Transfer learning with ImageNet-pretrained MobileNetV2.
- Frozen pretrained base model.
- Custom classification head using Global Average Pooling, Dropout, and Dense layers.
- Softmax activation and Adam optimizer with a learning rate of 0.0001.

### Result

**Validation accuracy: 70.92%**

This result provides a baseline for the vehicle image classification task. Further evaluation would be needed to establish performance across different real-world driving conditions.

## Part 2: Tesla Crash Safety Analysis

**Objective:** Explore crash incident data to understand fatality patterns and reported Autopilot involvement.

### Analysis workflow
- Dataset exploration and data cleaning.
- Treatment of missing values in death-related count variables, as documented in the report.
- Handling of outliers during preprocessing.
- Statistical summaries and visualization-based analysis across temporal and geographic dimensions.

### Key findings reported
- 78% of incidents involved a single fatality.
- 38.5% involved Tesla driver deaths.
- Approximately 15.8% were classified as verified Autopilot-related fatal events.
- Most recorded incidents were in the United States.

These figures describe the dataset analyzed in this project; they should not be interpreted as population-wide crash rates or as proof of causation.

## Skills Demonstrated

- Python-based machine learning workflow
- Deep learning and transfer learning
- MobileNetV2 and image classification
- Image preprocessing and class consolidation
- Exploratory data analysis (EDA)
- Data cleaning and outlier handling
- Statistical analysis and data visualization
- Automotive AI and autonomous-driving safety analysis

## Conclusion

This capstone combines computer vision and safety-oriented data analytics to explore perception and incident-analysis challenges in autonomous driving.

The work demonstrates an academic application of AI/ML techniques to automotive problems. It is not a production-ready autonomous-driving system.

## Project Status

Academic capstone completed in March 2026.

## Author

**Rajan Singh Rawat**

Automotive Wiring Harness Design Engineer | Machine Learning | Generative AI | Automotive Applications
