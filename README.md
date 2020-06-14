# DarthJarJar-Dromous_SCDFXIBM
A life saving application designed to automatically detect road accidents.

---

## Short description of the problem and the idea:
In 2018,there were a total 7680 car accidents in Singapore - a shocking figure! Therefore, we decided to help the victims of these tragic incidents by creating Dromous (Greek for traffic). Dromous employs models created using Watson Machine Learning and Watson Visual Recognition in order to differentiate cars from other objects captured by cameras. The cameras will be connected using Wifi receiver to phone and hence establishing a connection to the cloud. This will allow the cameras to transmit data to the visual recognition model on the cloud (use of IoT), for the AI to determine the passing by of cars. A SD card is also connected to the camera so that the recording never stops even when the phone is not connected via Wifi. The AI model is also trained with multpile images and types of car crashes which it can detect from camera footage and automatically alert SCDF to provide immediate support for the victims and hence save the lives of those involved.

---

the above image has been created using python libraries pandas, numpy and folium in order to create a map centred in Singapore with markers indicating positions of cameras placed on Singapore highways. The data for camera positions has been taken from data.gov.sg and the code written to generate the map is also present at [Camera Map Singapore Code](https://github.com/DJrocks192s/DarthJarJar-Dromous_SCDFXIBM/blob/master/MaterialsFolder/Camera%20Map%20Singapore%20Code.ipynb)

---

## Pitch video:

[![Watch the video](https://github.com/DJrocks192s/DarthJarJar-Dromous_SCDFXIBM/blob/master/MaterialsFolder/pitch%20video%20starting%20screen.png)](https://youtu.be/2zeULYH6-kI)

---

## Architecture

![alt text][logo]

[logo]: https://github.com/DJrocks192s/DarthJarJar-Dromous_SCDFXIBM/blob/master/MaterialsFolder/Dromous%20Architecture(1).jpg "Dromous Architecture"
---

## Link to the detailed solution
www.google.com

---

## Project Roadmap

![alt text][logo2]

[logo2]: https://github.com/DJrocks192s/DarthJarJar-Dromous_SCDFXIBM/blob/master/MaterialsFolder/Dromous%20Roadmap.jpg "Dromous Roadmap"

---

## Getting Started

---

## Technology used to build Dromous
The code used to train our model is given [here](https://github.com/DJrocks192s/DarthJarJar-Dromous_SCDFXIBM/blob/master/MaterialsFolder/Visual%20Recognition%20Model%20Code.ipynb). We have only included the training of one image adding the object "car" to a visible car in the image. We used similar code for around 150 images that we used to train the model.
