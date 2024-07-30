### Traffic Sign Classification with TensorFlow

This project aims to develop a neural network using TensorFlow to classify traffic signs from images, utilizing the German Traffic Sign Recognition Benchmark (GTSRB) dataset.

#### Features
1. **Data Preparation**:
   - Images are preprocessed using OpenCV for resizing and normalization.
   - Data augmentation techniques are applied to enhance the diversity of the training dataset.

2. **Model Development**:
   - A convolutional neural network (CNN) is constructed with TensorFlow.
   - The architecture includes convolutional layers for feature extraction, pooling layers for downsampling, and fully connected layers for final classification.

3. **Evaluation**:
   - The model's performance is validated using a separate test dataset.
   - Predictions are made on unseen data to evaluate real-world applicability.

4. **Documentation**:
   - Comprehensive documentation of the experimentation process, including hyperparameter tuning and model iterations.

#### Dataset
The GTSRB dataset can be accessed via the following links:
- [GTSRB - Training and Testing Dataset](https://cdn.cs50.net/ai/2023/x/projects/5/gtsrb.zip)
- [GTSRB Small - Training and Testing Dataset](https://cdn.cs50.net/ai/2023/x/projects/5/gtsrb-small.zip)

#### Code Modifications
This implementation includes several enhancements for improved model performance and additional functionality.

#### Additional Resources
For further information, visit the [project page](https://cs50.harvard.edu/ai/2020/projects/5/traffic/).