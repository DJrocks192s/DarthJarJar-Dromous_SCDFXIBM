# DarthJarJar-Dromous_SCDFXIBM
A life saving application that "Integrates With a Smart Environment" designed to automatically detect road accidents.

---

## Short Description:

### The Problem:

In 2018,there were almost 8000 road casualties in Singapore. Furthermore, Singapore has a road fatality rate of 2.8%, which is higher than many other large cities, more than double of Tokyo's, in fact. A big part of the problem comes from the delay between accident and aid. In life-threatening situations, every second makes a difference, and the time between an accident actually occuring, and the emergency services being called up, either by a victim or a witness, is a large portion of that.

### The Solution

We wanted to implement a system that could cut out that time entirely, by automatically detecting road accidents, and alerting emergency services. Therefore, our team (Darth Jar Jar) of 4 high school students (Samud Suhas Shetty, Devam Jain, Preetish Juneja and Madhav Lodha), decided to create Dromous. Our solution is an AI-enabled service that automatically detects road accidents, and alerts the relevant authorities.

Our solution is made up of four components:
1. Hardware, in the form of our self-designed plug-in module to in-car cameras, and pre-existing on road cameras
2. Software, in the form of the IBM Watson Machine Learning and Watson Visual Recognition systems
3. Python code, written to identify the location of crashes based on the location of on-road cameras
4. A web app, to signal the end user of the site, time and confidence level of the occurunce of an accident

---

## Pitch video:

[![Watch the video](https://github.com/DJrocks192s/DarthJarJar-Dromous_SCDFXIBM/blob/master/MaterialsFolder/pitch%20video%20starting%20screen.png)](https://youtu.be/2zeULYH6-kI)

---

## Architecture

![alt text][logo]

[logo]: https://github.com/DJrocks192s/DarthJarJar-Dromous_SCDFXIBM/blob/master/MaterialsFolder/Dromous%20Architecture(1).jpg "Dromous Architecture"
---

## Link to the detailed solution
[DESCRIPTION](https://github.com/DJrocks192s/DarthJarJar-Dromous_SCDFXIBM/blob/master/MaterialsFolder/DESCRIPTION.md)

---

## Project Roadmap

![alt text][logo2]

[logo2]: https://github.com/DJrocks192s/DarthJarJar-Dromous_SCDFXIBM/blob/master/MaterialsFolder/Dromous%20Roadmap.jpg "Dromous Roadmap"

---

## Getting Started

##### In order to see a sample of the working of our AI model, follow the link [here](https://dataplatform.cloud.ibm.com/studio/watson-vision-combined/d7e670d3-e6a6-42df-b14f-5b59d4f7bf80/view/objects?project_id=1fabf3ad-01f9-47c6-8594-bede42f9a743&training_definition_id=036b6927-e955-4e63-8763-ccfa3e4cf1a5&context=wdp), and go to the Test tab. Please note that you must accept the invitation to collaborate on the project (SCDFXIBM_Hackathon_TeamDarthJarJar) from preetishjuneja2004@gmail.com before being able to access it.From there, insert an image of cars on the highway, such as the one you can find [here](https://github.com/DJrocks192s/DarthJarJar-Dromous_SCDFXIBM/blob/master/MaterialsFolder/ch1.jpg). You should see that the AI identifies vehicles and differentiates them from other objects.

##### To view our hardware model for the in-car camera, you can follow [this link](https://a360.co/3hsN7vt). Please be patient as the site takes time to load.

##### To view the location software, follow [this link](https://github.com/DJrocks192s/DarthJarJar-Dromous_SCDFXIBM/blob/master/MaterialsFolder/Camera%20Map%20Singapore%20Code.ipynb). With this you should be able to see an interactive map of road cameras in Singapore, with clickable camera locations. These will indicate the location of an accident if any of the cameras identify one.
---

## Technology used to build Dromous
Technologies used to build the software include:
 1. [IBM Watson Visual Recognition Model](https://dataplatform.cloud.ibm.com/studio/watson-vision-combined/d7e670d3-e6a6-42df-b14f-5b59d4f7bf80/view/objects?project_id=1fabf3ad-01f9-47c6-8594-bede42f9a743&training_definition_id=036b6927-e955-4e63-8763-ccfa3e4cf1a5&context=wdp)
 2. [IBM Watson Machine Learning Model](https://dataplatform.cloud.ibm.com/analytics/notebooks/v2/683f27e4-c6ca-494b-b6fd-2c21ad492626/view?projectid=1fabf3ad-01f9-47c6-8594-bede42f9a743&context=wdp)
3. [Fusion 360 (CAD software)(Please be patient for it to load)](https://a360.co/3hsN7vt)
4. [NodeRED App Attempt](https://drive.google.com/drive/folders/1Q5gRBJs6PpXVmlbyriSBuKN01Wwnql15?usp=sharing)
5. [IBM Internet of Things Platform](https://developer.ibm.com/technologies/iot/tutorials/how-to-create-an-internet-of-things-platform-starter-application/)
