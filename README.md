## Tooth Wear Classification Tool


This script uses a pre-trained VGG16 neural network model to classify images of teeth as either "worn" or "not worn" based on their similarity to a reference image. The tool preprocesses images, extracts features, and computes cosine similarity to make the classification.

## Key Features:

1. Utilizes a pre-trained VGG16 model for feature extraction.
2. Classifies new tooth images based on similarity to a reference image.
3. Provides a classification result indicating whether the tooth is "worn" or "not worn".

## How to Use:

1. Ensure you have the necessary libraries installed: OpenCV, NumPy, TensorFlow, Keras, and scikit-learn.
2. Replace '/content/tooth.jpeg' with the path to your reference image.
3. Replace '/content/worntooth.jpeg' with the path to the new image you want to classify.
4. Run the script.
4. The classification result will be printed, indicating whether the new tooth image is "worn" or "not worn".
