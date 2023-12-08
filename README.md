# Image classification of five sports celebrities 
## Sport persons are: 
1. Virat kohli
2. Serena Williams
3. Roger Federer
4. Maria Sharapova
5. Lionel Messi
## Libraries Used:
1. Numpy
2. Matplotlib
3. cv2
4. Tensorflow
5. scikit-learn
6. tqdm
7. PIL
## Chosen Model:
 The chosen model is a Convolutional Neural Network (CNN) implemented using TensorFlow and Keras. The architecture includes convolutional layers, max-pooling layers, flattening, and fully connected layers. It is designed to classify images of five different celebrities: Virat Kohli, Serena Williams, Roger Federer, Maria Sharapova, and Lionel Messi.
# Training Process:
## 1. Data Loading and Preprocessing:
  - Images of each celebrity are loaded, resized to (128, 128) pixels, and organized into a dataset with corresponding labels.
  - The dataset is split into training and testing sets.

## 2. Model Architecture:
   - The CNN model is built with layers for convolution, max-pooling, flattening, and fully connected operations.
   - The model is compiled using the Adam optimizer and sparse categorical crossentropy loss.
## 3. Training:
   - The model is trained on the training set for 50 epochs with a batch size of 32.
   - Training progress is monitored, and a validation split of 30% is used to assess model performance during training.
## 4. Evaluation:
     - The trained model is evaluated on the test set, and accuracy is reported.
     - Classification metrics, such as precision, recall, and F1-score, are provided through a classification report.


## Critical Findings:
      Accuracy: The final accuracy on the test set is printed, indicating the model's overall performance.
      Classification Report: Provides a detailed breakdown of the model's performance for each class, offering insights into precision, recall, and F1-score for 
     individual celebrities.
      The code will preprocess each image, pass it through the trained model, and print the predicted label for each image based on the celebrity classes
 



