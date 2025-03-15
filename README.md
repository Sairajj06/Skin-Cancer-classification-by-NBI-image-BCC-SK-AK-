# Skin Cancer Classification (BCC, SK, AK) using NBI Images

Overview

This repository contains a deep learning model trained to classify skin cancer into three categories: Basal Cell Carcinoma (BCC), Seborrheic Keratosis (SK), and Actinic Keratosis (AK). The unique aspect of this project is the conversion of RGB skin lesion images into Narrow Band Imaging (NBI) images before training the model.

Dataset

The dataset consists of skin lesion images with three classes:

BCC (Basal Cell Carcinoma)

SK (Seborrheic Keratosis)

AK (Actinic Keratosis)

The dataset is split as follows:

Training Set: 70%

Validation Set: 20%

Test Set: 10%

Methodology

Image Conversion: The RGB images were converted to NBI format to enhance feature extraction.

Model Architecture: EfficientNet was used as the backbone for the classification model.

Training: The model was trained using TensorFlow/Keras with appropriate data augmentation techniques.

Evaluation: The trained model was evaluated using accuracy, precision, recall, and F1-score.

Results

The model achieved an accuracy of 78% on the test dataset.

Performance metrics:

Precision: 79%

Recall: 78%

F1-Score: 78%

Future Improvements

Enhancing the NBI conversion process for better feature extraction.

Testing with additional deep learning architectures.

Expanding the dataset for improved generalization.

Contributors

Sairaj Jagtap (sairajjagta3@gmail.com)
Yash Raneja (yashraneja2006@gmail.com)

