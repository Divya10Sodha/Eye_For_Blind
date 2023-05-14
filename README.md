# EYE FOR BLIND


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- Deep learning model which can explain the contents of an image in the form of speech through caption generation with an attention mechanism on Flickr8K dataset has been generated. This kind of model is a use-case for blind people so that they can understand any image with the help of speech.
- It is an application of both deep learning and natural language processing. The features of an image were extracted by a CNN-based encoder and decoded by an RNN model.
- The project is an extended application of Show, Attend and Tell: Neural Image Caption Generation with Visual Attention paper.
- The dataset is taken from the Kaggle website and it consists of sentence-based image descriptions having a list of 8,000 images that are each paired with five different captions which provide clear descriptions of the salient entities and events of the image.


**Business Objective:-**
- There are many visually impaired people and it gets extremely tough for them to carry out daily activities, one of which is reading.
- In an initiative to help them experience the beauty of the images, Facebook had earlier launched a unique feature earlier that can help blind people operate the app on their mobile phones. The feature could explain the contents of an image that their friends have posted on Facebook. So, say, if someone posted a picture with their dog in the park, the application would speak out the contents and may describe it like, “This image may contain a dog standing with a man around the trees.”
- Taking an inspiration from this initiative, this project is an attempt to learn the basic architecture behind it. Here, we will convert an image to text description first, which is the central part on which the project is more focused. Then, using a simple text-to-speech API, we will extract the text description/caption and convert it to audio.
- In future scope, an attempt will be to make the model more robust and deploy the project on our local system using a Flask-based model to generate audio-based content for any image.


## Technques Used
- Text and Image preprocessing
- Data Visualization (bar plot/ Wordcloud Map)
- Data preparation using Tensorflow
- Custom model building using Tensorflow
- Model training and model evaluation (INCEPTIONV3)
- Traditional CNN-RNN model based on encoder-decoder architecture
- Attention model along with Teacher Forcing
- Greedy search vs Beam search and BLEU Score for evaluation


## Acknowledgements
- This project was inspired by the Upgrad Team and IIIT Bangalore and helped me to learn a lot.


## Contact
Created by [@Divya10Sodha] - feel free to contact me!
