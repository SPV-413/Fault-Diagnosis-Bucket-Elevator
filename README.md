# Fault Diagnosis of Bucket Elevator - Drive Pulley using Machine Learning 
This project focuses on fault diagnosis of a bucket elevator drive pulley using machine learning techniques. The study involves fabricating controlled wear conditions, acquiring vibrational data, extracting statistical features, and applying ML models to detect faults.

## Objectives
- Develop an automated fault detection system for bucket elevator drive pulleys.
- Use accelerometer-based vibration analysis for real-time condition monitoring.
- Implement machine learning models to classify different pulley wear conditions.
- Reduce unscheduled maintenance, breakdowns, and industrial accidents.

## Methodology
### 1. Fabrication of Fault Conditions
Three drive pulleys were fabricated with artificial wear faults using machining and sandpaper:
- Good Condition – No wear present.
- Pulley Shaft Wear – Fault introduced in the pulley shaft.
- Pulley Outer Layer Wear – Fault introduced on the pulley surface.

### 2. Data Acquisition
- Hardware Used:
  - Accelerometer sensor for vibration measurement.
  - Data Acquisition (DAQ) System for signal conversion.
  - Laptop for data processing and analysis.
- Collected Data:
Vibrational signals under three conditions (good, pulley shaft wear, pulley outer layer wear).

### 3. Feature Extraction
Extracted statistical features from the vibration data, such as:
- Mean, Median & Mode
- Maximum & Minimum
- Standard Error & Range
- Kurtosis
- Skewness
- Standard Deviation & Sample Variance

### 4. Machine Learning Model Implementation
Used MATLAB’s Machine Learning & Deep Learning Toolbox to train and evaluate the models:
- Decision Tree (DT)
- Artificial Neural Network (ANN)
- Support Vector Machine (SVM)

### 5. Model Comparison Report
| Model Name                 | Accuracy (Validation) | Total Cost (Validation) | Prediction Speed | Training Time |
|----------------------------|----------------------|-------------------------|------------------|--------------|
| Decision Tree (DT)         |  87.7%                | 37                  |  ~1200 obs/sec             |  14.976 sec          |
| Artificial Neural Network (ANN) | 93.7%          | Not applicable                    | ~2300 obs/sec           | 3.1368 sec         |
| Support Vector Machine (SVM)   | 94%          | 18                     | ~800 obs/sec             | 13.439 sec       |


## Results & Conclusion
- The Support Vector Machine (SVM) model achieved the highest accuracy in classifying pulley conditions.
- This model can be integrated into real-time monitoring systems to improve reliability and efficiency.

## Key Benefits
- Early fault detection prevents unexpected failures.
- Reduces maintenance costs by implementing predictive maintenance.
- Enhances worker safety by minimizing operational risks.

## Contact
For any inquiries, reach out via GitHub or email.
