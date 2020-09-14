---
type: work
layout: default
modal-id: lincolnuniversity
img: lincolnuniversity.png
alt: image-alt
project-date: 2019 - 2020
position: MSc Robotics and Autonomous Systems
location: Lincoln, UK
description: "
The School of Computer Science at the University of Lincoln is home to the Lincoln Centre for Autonomous Systems (L-CAS), one of Europe's leading research groups in Robotics and Autonomous Systems (RAS), and a leading UK centre for research in robotics for agriculture and food production “from farm to fork”.<br>
The MSc Robotics and Autonomous Systems is designed to equip students with the advanced knowledge and skills needed to develop the innovative solutions required by the emerging global industry in Robotics and Autonomous Systems (RAS), and across many other sectors where RAS skills are applicable. These may include agri-food, automation, industry 4.0, healthcare, logistics, military, nuclear, security, and transport. The programme can also prepare students to continue their study in a research capacity, allowing them to further specialise and focus their interests.<br>
Course content is informed by research carried out at the University of Lincoln, especially in the Lincoln Centre for Autonomous Systems and associated entities, and in RAS and related areas. This aims to ensure that content remains consistently underpinned by the latest thinking.

<h3>HackRF one</h3>
The objective of this project is to transfer binary data from one HackRF One to another using a modulation for the transmitter and a demodulation on the receiver.<br>
To achieve this objective several projects had to be created like FM including RDS, WiFi snipper, Morce code, OFDM modulation and several other technologies.
<br><img src='img/portfolio/hackrfone.png'>

<h3>An integrated system for robotic weed control: deployment, mapping and targeted spraying</h3>
The objective of the project is to have a simulated robot called Throvald to run across the field of crops and find the bad weeds so that it can spray them. With image processing extracts the middle point of the recognized weed and all of the points are published as a pointCloud. Another node gets these points and desides if it needs to spray and publishes all the collected points so that it will be visualized on Rviz.<br>
In order to collect the bad weeds from the images the background had to be removed and then find the weeds. The implementation works with color matching through HSV images, though I also tried with convolutional neural network (CNN).<br>
One option to locate the weeds is by training a model, but this was very time consuming because of the annotation that had to be done. I used this annotation tool though there are many more. For the training I used a tool called mrcnn and followed their tutorial about baloon training. The training took more than 35 hours. The final result wasn't as satisfying as it should and it takes more than 3 seconds to get a result for each picture, so it wasn't usable for a real time application like we wanted.
<br><img src='img/portfolio/ros_recognition.png' width='50%'> <img src='img/portfolio/ros_weedspray.png' width='40%'>


<h3>Neural Classification for Sign Language Recognition</h3>
Master's thesis for classifying American Sign Language using Convolutional Neural Network. Collected data from Secondary and Primary sources which were combined for better accuracy. This way a large dataset was created which was combined with augmentation to have more variety. This was meant to be tested on a Pepper Robot but the social distancing made it impossible.
<br><img src='img/portfolio/signs.jpg' width='50%'>

<h3>Cat & Dog Classifciation (CNN)</h3>
In order to classify a set of objects, which in this case is cats and dogs, a model has to be created and to achieve that the classifier CNN (Convolutional Neural Network) was selected. The library tensorflow makes the tuning of most parameters an easy task and at the same time supports the usage of Cuda to interface with the supported GPU of the computers.<br>
By training the model, the input images go through a number of layers. In each of them a 3x3 kernel slides over the input image and multiplies all the values. An activation function is applied to make the model nonlinear so that it can better learn. <br>
The output is passed to max pooling which uses a 2x2 filter to slide across the output and finds the maximum value to address the issue of  overfitting. Also a dropout is used to remove a random set of neurons in that layer which helps the new data to have better effect.<br>
The next step is to pass through the fully connected layer which applies weights to predict the correct label and gives the final probabilities for each label. These weights in the training step include the Forward Pass which assigns random values to the layer, the Loss Function which is trying to adjust the weights to minimize the loss, the Backward Pass which determines which weights contributed most to the loss and adjust them and finally the final weights are updated with a specific learning rate.
<br><img src='img/portfolio/ml_cnn.png' width='70%'>


<h3>Machine translation English to German (RNN)</h3>
Uses a sequence2sequence model for creating a Machine translation from English to German using sentences which are given. The same type of model is used for multiple applications like translator, speech recognition, chatbots, video captioning and others. A sequence to sequence model can transform one sequence of words to another which might be a different size.<br>
The sequence2sequence model consists of the encoder and the decoder which use an RNN gate to fix the problem of short-term memory of word sequence.<br>
The encoder inputs every word into the gate and outputs a vector and a hidden state which is used for the next word. The decoder takes the encoder vector and outputs a sequence of words for the translation.
<br><img src='img/portfolio/ml_rnn.png' width='70%'>



"

---
