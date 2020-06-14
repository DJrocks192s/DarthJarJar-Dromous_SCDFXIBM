# Dromous Description
Our solution is an AI-enabled service that automatically detects road accidents, and alerts the relevant authorities. The moments between an accident and medical response are the most crucial in determining the likelihood of survival for victims of such an incident.
Singapore's road fatality is low on a global scale, but compared to other large cities, it is quite elevated. Given this oppurtunity to make a change, and knowig that every singles life saved on the road is important, we decided to come up with a solution to cut down on the time between accident and aid.

Our solution is made up of four components:
1. Hardware, in the form of our self-designed plug-in module to in-car cameras, and pre-existing on road cameras
2. Software, in the form of the IBM Watson Machine Learning and Watson Visual Recognition systems
3. Python code, written to identify the location of crashes based on the location of on-road cameras
4. A web app, to signal the end user of the site, time and confidence level of the occurunce of an accident

![alt text][CLOUD]

[CLOUD]: https://github.com/DJrocks192s/DarthJarJar-Dromous_SCDFXIBM/blob/master/MaterialsFolder/CLOUD.jpg "CLOUD"


# 1. Hardware

For this project, we wanted to leverage as much existing hardware as possible, in order to minimize cost, 
and maximize feasability. However, we also wanted to have multiple data points from which our AI could detect accidents, 
for maximum accuracy. To strike a balance between feasibility, cost and accuracy, we developed a bi-faceted solution. 
We designed our own in-car camera plug-in module, using CAD models of pre-excisting hardware. This module plugs into the SD card slot of in-
car cameras, and allows the video from the camera to be streamed using mobile data to an IoT software, so that our AI can access it. The total
cost of the components is SGD 25. This, along with its compact nature, and the fact that in-car cameras are already prevalent,
make it a feasible solution.

![alt text][Camera1]

[Camera1]: https://github.com/DJrocks192s/DarthJarJar-Dromous_SCDFXIBM/blob/master/MaterialsFolder/Camera%201.png "Camera 1"

![alt text][Camera2]

[Camera2]: https://github.com/DJrocks192s/DarthJarJar-Dromous_SCDFXIBM/blob/master/MaterialsFolder/Camera%202.png "Camera 2"

Furthermore, we plan to use the pre-existing road camera network that LTA (Land Transport Authority) has in place to monitor highways, in order to give multiple data points for any highway accidents. This will also be connected to IoT and the Cloud solution in a similar manner. We believe that this hardware solution can strike a balance between accuracy, feasibiity, and cost.

# 2. Software

The IBM solution that we found best suits our needs was the Visual Image Recognition software. We combined this with Machine Learning and Cloud Object Storage technology from IBM, to create our solution. We trained our AI to be able to detect vehicles. and differentiate them from other on-road objects, as shown. The code used to train our model is given [here](https://github.com/DJrocks192s/DarthJarJar-Dromous_SCDFXIBM/blob/master/MaterialsFolder/Visual%20Recognition%20Model%20Code.ipynb)

![alt text][Screenshot]

[Screenshot]: https://github.com/DJrocks192s/DarthJarJar-Dromous_SCDFXIBM/blob/master/MaterialsFolder/Screenshot%202020-06-13%20at%2011.47.18%20PM.png "Screenshot"

The We believe that with further expertise we will be able to train it to identify crashed vehicles from regular ones. Our AI is constantly learning and improving as we feed it images, and the more time we give it, the better it will get. We receieve the data for the AI from our system of in-car and on-road cameras, which the AI can analyse, and identify certain objects with a confidence level. If the confidence level for an accident is higher than a threshold, it wil send a signal to our web app, and alert the end user (SCDF) of an accident. This is the crux of our project.

# 3. Code

While detecting accidents in isolation may be somewhat functional, the detection can be made a lot more useful by providing the location and time of the accident to SCDF, so that they can co-ordinate a response immediately, based on the given information. Hence, we coded a map-format database using Python libraries Pandas, NumPy and Folium, with the locations of on-road cameras in Singapore, so that when an accident is detected by a camera, we can identify exactly where it is. 

![alt text][logo1]

[logo1]: https://github.com/DJrocks192s/DarthJarJar-Dromous_SCDFXIBM/blob/master/MaterialsFolder/Singapore%20Camera%20Map.png "Map"

The code we wrote for this can be found on this [link(Camera Map Singapore Code)](https://github.com/DJrocks192s/DarthJarJar-Dromous_SCDFXIBM/blob/master/MaterialsFolder/Camera%20Map%20Singapore%20Code.ipynb). This solution can be expanded to integrate with our in-car module, ie, the location of vehicles that detect accidents can also be monitored, to the same effect.

# 4. User Interface

In order to display the output of our system to the end user, SCDF, in a manner that is precise, yet has enough information to co-ordinate a response, while also being instantaneous (as that is the premise of our whole project), led us to mock up a web app.

![alt text][logo1]

[logo1]: https://github.com/DJrocks192s/DarthJarJar-Dromous_SCDFXIBM/blob/master/MaterialsFolder/Dromous%20Website.jpg "Map"

This is the layout of our web app, which will show location, confidence level, time detected, and images retrieved from the on-road and in-car cameras detecting the accident. 

# Conclusion

In conclusion, our system has been designed with one goal in mind. Saving lives. Our execution of this goal is through automating the system of alerting the authourities about road accidents. We believe that by shaving off the minutes of delay between an accident occuring, and the first call for 995 (especially when accidents happen in situations where the accident happens in isolation, the victim is unconcious, or no motorists stop to check for the victim's safety), we can have a significant impact on the fatality rate of road accidents, and reduce the chance of chronic injuries in Singapore

