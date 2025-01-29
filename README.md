# Deep-Learning-for-Face-Mask-Detection

## Performed Operations
This project develops a deep learning-based classifier to determine whether a face mask is being worn. The following operations have been performed:

1. **Data Preparation:** A dataset consisting of masked and unmasked face images was collected and preprocessed.
2. **Data Augmentation:** Techniques such as flipping, brightness adjustment, and zooming were applied.
3. **Model Training:** The DenseNet121 and EfficientNetB0 transfer learning model was customized and trained according to the dataset.
4. **Optimization:** The Adam and SGD optimization algorithm was used to enhance the training process.
5. **Stopping Strategies:** EarlyStopping and ReduceLROnPlateau callbacks were implemented to prevent overfitting.
6. **Evaluation of Results:** The trained model was evaluated using metrics such as accuracy, confusion matrix, and ROC curve.

## Dataset and Preprocessing

Dataset Link : https://www.kaggle.com/datasets/omkargurav/face-mask-dataset

The dataset consists of images of masked and unmasked faces. Images were processed using data augmentation techniques to enhance training efficiency. Preprocessing steps include:

- Image resizing

- Data augmentation (flipping, brightness adjustment, zooming, etc.)

- Normalization

## Model Training

The project employs the DenseNet121 model. Training was carried out in the following steps:

- Dataset Preparation: The data was split into training and test sets.

- Model Architecture: The DenseNet121 model was modified by adding fully connected layers.

- Optimization: The Adam optimization algorithm was used for training.

- Stopping Criteria: EarlyStopping and ReduceLROnPlateau callbacks were implemented.

## Results and Evaluation

The performance of the trained model was evaluated using the following metrics:

- Accuracy

- Confusion Matrix

- ROC Curve and AUC Score

- Precision, Recall, and F1-Score Values

