#Project Overview
This project leverages Convolutional Neural Networks (CNNs) to analyze Statistical Process Control (SPC) charts and detect patterns indicative of in-control and out-of-control processes. By combining deep learning techniques with SPC principles, the project aims to provide a robust solution for monitoring and maintaining process quality in various industries.

#Features
Model Implementation:
1D-CNN: Processes time-series data from control charts.
2D-CNN: Analyzes images of SPC charts for pattern detection.
Performance Metrics: Includes accuracy, F1 score, precision, and recall for evaluating model effectiveness.
Future Prospects: Potential applications in real-world scenarios such as healthcare, finance, and manufacturing.
Dataset
The dataset consists of SPC charts generated to simulate in-control and out-of-control scenarios:

Format:
Categories:
In-control (label: 1)
Out-of-control (label: 0)
Note: The dataset is preprocessed and split into training and testing sets.
1D-CNN (70/30) split
2D-CNN (60/40) split

Results
Model    Accuracy	  Precision	  Recall	  F1 Score
1D-CNN	 98.48%	    98.53%	    98.48%    98.48%
2D-CNN	 98.86%	    98.88%	    98.86%    98.86%
