# A survey of Malware detection using machine learning models

Abstract:
Malware detection remains a critical challenge in cybersecurity, as attackers constantly evolve tactics to evade defences. This paper surveys and analyses traditional machine learning and deep learning techniques for malware detection, comparing their effectiveness on two distinct datasets: EMBER 2018, covering malware attacks from 2006 to 2018, and CIC-EvasivePDF2022, which focuses on recent evasive PDF malware samples. Through a comprehensive examination of traditional machine learning models such as Random Forest, XGBoost, AdaBoost, Logistic Regression, and K Nearest Neighbours, alongside deep learning models including Convolutional Neural Networks, Multi-Layer Perceptrons, RNN-LSTM combinations, and Transformer architectures, each model’s accuracy, adaptability, and capacity to handle imbalanced datasets, an inherent challenge in cybersecurity, are evaluated. Additionally, ensemble methods such as stacking and voting classifiers are explored to enhance model performance by combining the strengths of machine learning and neural network approaches. The findings reveal that machine learning models perform exceptionally well on structured malware data, achieving accuracies of 99.6% on EMBER and 99.3% on CIC-EvasivePDF2022. In contrast, deep learning models demonstrate advantages in detecting evasive, complex malware, with CNN and RNN-LSTM models achieving accuracies up to 98.1% and 96.2% on CIC-EvasivePDF2022, respectively. Ensemble methods are also highly effective, with voting classifier achieving 99.1% accuracy on CIC-EvasivePDF2022. These results suggest that both machine learning and deep learning approaches offer a robust solution to the diverse challenges of malware detection.


Overview

Malware detection remains a critical challenge in cybersecurity as malicious software evolves to bypass defenses. This project investigates the use of both traditional machine learning and deep learning algorithms for malware classification, utilizing two significant datasets:

EMBER2018: Covers attacks from 2006 to 2018.
CIC-EvasivePDF2022: Focuses on recent evasive PDF malware.
The goal is to evaluate and compare various algorithms to enhance malware detection capabilities.

Key Features

Datasets:

EMBER2018,
CIC-EvasivePDF2022

Algorithms:

Traditional Machine Learning Models:

Random Forest (RF),
XGBoost,
AdaBoost,
Logistic Regression,
K Nearest Neighbors (KNN)

Deep Learning Models:

Convolutional Neural Networks (CNNs),
Multi-Layer Perceptron (MLP),
RNN-LSTM combinations,
Transformer models

Ensemble Methods: Explores stacking and voting classifiers that combine RF, XGBoost, and neural networks.

Imbalanced Dataset Handling: Focuses on strategies for addressing common challenges in malware detection related to imbalanced datasets.

Results

The study reveals strengths and limitations of various machine learning and deep learning algorithms in detecting a wide range of malware types over different time periods. The comparative analysis emphasizes the necessity of employing diverse methods to enhance detection capabilities.

Contributing

Contributions are welcome! Please submit a pull request or open an issue for any improvements or suggestions.
