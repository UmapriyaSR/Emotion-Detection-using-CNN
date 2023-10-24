# Emotion-Detection-using-CNN
Facial Emotion Detection using CNN and comparison with EfficientNet model
Objective:
To build a model using a convolutional neural network that can classify a person's emotion
Dataset description:
The dataset contains two folders named Train and Test. These folders have approximately 35,000 images of 
seven different human emotions, such as anger, disgust, fear, happiness, neutral, sadness, and surprise.
Built a data augmentation for train data to create new data with translation, rescale and flip, and rotation transformations,rescaling the image at 48x48
Built a custom CNN model and varied the no of layers , loss functions, epochs to study the behaviour of the model.
Also built a transfer learning model using EfficientNetV2 to compare the CNN, still experimenting to get better accuracy values.
