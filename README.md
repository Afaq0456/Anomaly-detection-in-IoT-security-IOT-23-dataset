# Anomaly-detection-in-IoT-security-IOT-23-dataset

### Introduction
The expansion of IoT devices has reformed the way we connect with the digital world, leading to complexities in managing and securing IoT networks. This chapter provides a comprehensive analysis of a dataset capturing network activity logs during IoT-related communication, detailing its features and labels designed to identify potentially risky connections. Various AI and deep learning models, including Decision Trees, Random Forests, Gradient Boosting, Convolutional Neural Networks (CNN), and Artificial Neural Networks (ANN), are presented and evaluated for IoT network traffic classification.

### Dataset Overview
The dataset includes network activity logs with features such as Timestamp, Source IP Address, Duration, Bytes Exchanged, Packet Counts, and Connection State Features. Labels are designed to elucidate connections associated with potentially hazardous activities, offering comprehensive insights for network security researchers and analysts.

### Evaluation Metrics
Key evaluation metrics include Precision, Recall, F1 Score, and Support. These metrics offer a thorough understanding of the model's accuracy in identifying and categorizing abnormalities in IoT network traffic.

### Decision Tree Model
The Decision Tree model achieved an accuracy of 72.93% on the test set, with commendable precision and recall for classes like 'Attack' and 'DDoS.' However, it faced challenges in predicting classes with imbalanced data.

### Random Forest Model
The Random Forest model achieved an accuracy of 72.86% on the test set, showcasing its robustness across different folds during cross-validation.

### Gradient Boosting Classifier
The Gradient Boosting Classifier achieved an accuracy of 72.81% on the test set, demonstrating its effectiveness in correcting errors sequentially and predicting different classes effectively.

### Convolutional Neural Network (CNN)
The CNN model achieved an accuracy of 68.12% on the test set, excelling in capturing intricate patterns and spatial hierarchies within the data.

### Artificial Neural Network (ANN)
The ANN model achieved an accuracy of 68.39% on the test set, exhibiting competitive accuracy but facing challenges in handling imbalanced data and classes with limited samples.

### Conclusion
Decision tree-based models outperformed deep learning models in IoT network traffic classification, showcasing superior accuracy and robustness. Deep learning models, while effective in capturing complex patterns, faced limitations in handling imbalanced data and classes with limited samples. The study provides valuable insights for choosing models in IoT security applications, emphasizing the need to balance interpretability and accuracy based on specific requirements.

## Limitations
- Class imbalance in the dataset challenges the models, particularly deep learning ones, in effectively learning and generalizing patterns for underrepresented classes.
- The complexity of network traffic patterns may require more sophisticated feature engineering or domain-specific insights for optimal model performance.
- The study's focus on a specific dataset raises questions about the generalizability of the models to diverse IoT environments, necessitating further investigation.

## Note
The dataset used in this project, IoT-23, was created by Sebastian Garcia, Ahmed Patel, and Maria Jose Erquiaga and is available at Zenodo. For more information on the dataset labeling methodology, refer to the [Stratosphere Laboratory's website](https://www.stratosphereips.org/datasets-iot23).

