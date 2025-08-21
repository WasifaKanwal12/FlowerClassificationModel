**Flower Classification with ResNet-50**

This project classifies images of flowers into 5 categories (daisy, dandelion, roses, sunflowers, tulips) using a fine-tuned ResNet-50 model.

**Key Features:**
- Uses TensorFlow/Keras and OpenCV
- Automatically downloads the flower dataset
- Preprocesses images (resize, normalize)
- Replaces final layer of ResNet-50 for 5-class classification
- Saves trained model for reuse
- Includes image upload and prediction interface

**Results:**
- Training Accuracy: ~96%
- Test Accuracy: ~66%

**Usage:**
1. Run in Google Colab
2. Upload a flower image when prompted
3. View model prediction and confidence

**Note:** Model shows some overfitting; data augmentation recommended for improvement.

=