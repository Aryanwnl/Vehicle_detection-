
#  Vehicle Detection using Convolutional Neural Networks (CNN)

This project presents a deep learning-based vehicle detection system using Convolutional Neural Networks (CNNs). The primary objective is to accurately classify vehicle images into categories such as cars, trucks, buses, and bikes, which has practical applications in areas like traffic monitoring, smart parking systems, and intelligent transportation infrastructure.

The dataset used for training and evaluation consists of labeled vehicle images that are preprocessed through resizing, normalization, and augmentation techniques like rotation, flipping, and zooming to enhance generalization and robustness.

The model architecture is developed using TensorFlow and Keras, and includes several Conv2D layers with ReLU activation for feature extraction, MaxPooling2D for downsampling, BatchNormalization for training stability, and Dropout layers to reduce overfitting. The final output layer uses softmax activation to support multi-class classification. The model is compiled with the Adam optimizer and categorical cross-entropy loss, and trained on the processed dataset split into training, validation, and test sets.

Evaluation is done using accuracy metrics, classification reports (precision, recall, F1-score), and training history visualizations for both accuracy and loss. These assessments provide insights into model performance and its ability to generalize to unseen data.
