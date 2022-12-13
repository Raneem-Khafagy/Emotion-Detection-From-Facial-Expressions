# Emotion Detection From Facial Expressions

## Abstract
Emotional AI can read people's feelings through facial expressions, and gestures and adjust its demeanor accordingly. People have the upper hand in recognizing different emotions, but AI is catching up with its ability to analyze large volumes of data.

This was a Community prediction kaggle Competition [Emotion Detection From Facial Expressions](https://www.kaggle.com/competitions/emotion-detection-from-facial-expressions/overview)

## Data
I used [facial_expressions dataset](https://github.com/muxspace/facial_expressions) 
**['anger', 'surprise', 'disgust', 'fear', 'neutral', 'happiness','sadness', 'contempt']** 
I worked with a total of 13682 image 10945 for trainig, another 2737 for validation and 1369 for evaluation.


## Model Design
#### I used two model architectures:
 **VGG-16 convolutional neural network** 
I worked with a b&w image its input_shape = (224,224)
and the output layer was a softmax layer with 8 classes

<p align="center">
  <img src="conv-layers-vgg16.jpg" width="80%" title="conv-layers-vgg16">
</p>

 **Mobile Net**
I used Keras.applications to load the architecture of mobile net V1, pertained on 'Imagenet'

## Results

