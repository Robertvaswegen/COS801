# SPC Analysis with 1D-CNN and 2D-CNN Models

## Project Overview
This project leverages Convolutional Neural Networks (CNNs) to analyze **Statistical Process Control (SPC)** charts and detect patterns indicative of **in-control** and **out-of-control** processes. 

---

## Features
### Model Implementation:
- **1D-CNN**: Processes time-series data from control charts.  
- **2D-CNN**: Analyzes images of SPC charts for pattern detection.

### Performance Metrics:
- Accuracy
- Precision
- Recall
- F1 Score

### Future Prospects:
Potential applications include:
- **Healthcare**: Monitoring patient vitals for abnormalities.
- **Finance**: Identifying fraudulent transactions.
- **Manufacturing**: Real-time anomaly detection on production lines.

---

## Dataset
The dataset consists of **SPC charts** generated to simulate **in-control** and **out-of-control** scenarios.

### Format:
- **1D Data** for 1D-CNN
- **Images** for 2D-CNN

### Categories:
- **In-control** (`label: 1`)  
- **Out-of-control** (`label: 0`)  

### Splits:
- **1D-CNN**: 70% training, 30% testing  
- **2D-CNN**: 60% training, 40% testing  

**Note**: The dataset is preprocessed and split into training and testing sets.

---

## Results
| **Model**   | **Accuracy** | **Precision** | **Recall** | **F1 Score** |
|-------------|--------------|---------------|------------|--------------|
| **1D-CNN**  | 98.48%       | 98.53%        | 98.48%     | 98.48%       |
| **2D-CNN**  | 98.86%       | 98.88%        | 98.86%     | 98.86%       |

---

