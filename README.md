# DarthJarJar-Dromous_SCDFXIBM
A life saving application designed to automatically detect road accidents.

---

## Short description of the problem and the idea:
Seeing that there were 7680 car accidents in Singapore in 2018, we decided to help the victims of these tragic incidents by creating Dromous (Greek for traffic). Our application uses models created using Watson Machine Learning Model and Watson Visual Recognition Model in order to detect cars from any other objects present in camera footage. The cameras will be connected using Wifi receiver to phone and hence to the cloud in order to transmit data to the visual recognition model on the cloud (use of IoT) in order for the AI to determine the passing by of cars. A SD card is also connected to the camera so that the recording never stops even when the phone is not connected via Wifi. The AI model is also trained with multpile images and types of car crashes which it can detect from camera footage and automatically alert SCDF to provide immediate support for the victims and hence save the lives of those involved.

---

![alt text][logo1]

[logo1]: https://github.com/DJrocks192s/DarthJarJar-Dromous_SCDFXIBM/blob/master/Singapore%20Camera%20Map.png "Map"

---

the above image has been created using python libraries pandas, numpy and folium in order to create a map centred in Singapore with markers indicating positions of cameras placed on Singapore highways. The data for camera positions has been taken from data.gov.sg and the code written to generate the map is also present at [Camera Map Singapore Code](https://github.com/DJrocks192s/DarthJarJar-Dromous_SCDFXIBM/blob/master/Camera%20Map%20Singapore%20Code.ipynb)

---

## Pitch video:

[Pitch Video](https://www.powtoon.com/s/eJQDamfhRVJ/1/m)

---

## Architecture

![alt text][logo]

[logo]: https://github.com/DJrocks192s/DarthJarJar-Dromous_SCDFXIBM/blob/master/Dromous%20Architecture(1).jpg "Dromous Architecture"
---

## Link to the detailed solution
www.google.com

---

## Project Roadmap

---

## Getting Started

---

## Technology used to build Dromous
The code used to train our model is given [here](https://github.com/DJrocks192s/DarthJarJar-Dromous_SCDFXIBM/blob/master/Visual%20Recognition%20Model%20Code.ipynb). We have only included the training of one image adding the object "car" to a visible car in the image. We used similar code for around 150 images that we used to train the model.
