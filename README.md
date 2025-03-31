# Malaria CNN Detection

## Dataset Overview
- The dataset consists of images of blood cells categorized into:
  - **Parasitized**: Cells infected with malaria.
  - **Uninfected**: Normal cells without infection.
- The dataset is stored in **cell_images/**, which contains both categories.

## Model Overview
- A Convolutional Neural Network (CNN) model was used for malaria cell detection.
- The model was trained using TensorFlow/Keras.
- Key layers include convolutional, pooling, and fully connected layers.

## Training Details
- **Loss Function**: Categorical Crossentropy
- **Optimizer**: Adam
- **Epochs**: 30 
- **Batch Size**: 32
- **Validation Split**: 20%

## Results
- **Validation Loss**: 0.2567
- **Validation Accuracy**: 91.34%

## Notes
- Please download the dataset from [Kaggle](https://www.kaggle.com/datasets/iarunava/cell-images-for-detecting-malaria).
