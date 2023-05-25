# Pet Classifier

## Description
Pet Classifier is a deep learning model that classifies images of cats and dogs. It is trained using a Convolutional Neural Network (CNN) architecture and achieves high accuracy on the test data.

## Dataset
The dataset consists of a collection of images of pets, including cats and dogs. The images have different sizes and lighting conditions. The dataset is split into training and test sets.

## Processing Techniques
The images are preprocessed using data augmentation techniques such as random shearing, zooming, and horizontal flipping. The pixel values are normalized to the range [0, 1]. This helps in improving the model's performance and generalization.

## Model Architecture
The model is based on a CNN architecture. It consists of two convolutional layers with pooling, followed by a dense layer and a dropout layer. The final layer uses the softmax activation function for multi-class classification.

## Training and Evaluation
The model is trained on the training data with the Adam optimizer and categorical cross-entropy loss. The accuracy and loss are monitored during training. The model is evaluated on the test data to assess its performance.

## Screenshots

### Training Accuracy and Loss
![image](https://github.com/heathbrew/Pet-Classifier/assets/55629425/4f07c566-d4e2-46dd-9e41-eb5b34e7b2d8)
![image](https://github.com/heathbrew/Pet-Classifier/assets/55629425/29bac72d-69a8-4c89-baf1-371877b65846)


### Confusion Matrix
![image](https://github.com/heathbrew/Pet-Classifier/assets/55629425/101793d3-abb0-45b8-86be-821391309835)

