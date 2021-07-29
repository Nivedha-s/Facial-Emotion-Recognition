# Facial-Emotion-Recognition

#### The CNN will classify the image into one of the seven emotional states  namely -  angry, disgusted, fearful, happy, neutral, sad and surprised.  

**Dataset used :**<br/>
FER-2013 dataset <br/>
The data consists of 48x48 pixel grayscale images of faces. The faces have been automatically registered so that the face is more or less centred and occupies about the same amount of space in each image.
The training set consists of 28,709 examples and the public test set consists of 3,589 examples. <br/><br/>
**Model used :**<br/>
VGG16 pre-trained model is fine-tuned <br/>
The model takes images of dimension (50, 50, 3) and the output is one of the seven emotion classes. The base model(i.e VGG16 model) layers is set to non-trainable. 

<br/>
References <br/>
https://www.kaggle.com/msambare/fer2013
