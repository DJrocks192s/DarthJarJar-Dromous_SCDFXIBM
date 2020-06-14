# Dromous Description
Our solution is an AI-enabled service that automatically detects road accidents, and alerts the relevant authorities. The moments between an accident and medical response are the most crucial in determining the likelihood of survival for victims of such an incident.
Singapore's road fatality is low on a global scale, but compared to other large cities, it is quite elevated. Given this oppurtunity to make a change, and knowig that every singles life saved on the road is important, we decided to come up with a solution to cut down on the time between accident and aid.

Our solution is made up of four components:
1. Hardware, in the form of our self-designed plug-in module to in-car cameras, and pre-existing on road cameras
2. Software, in the form of the IBM Watson Machine Learning and Watson Visual Recognition systems
3. Python code, written to identify the location of crashes based on the location of on-road cameras
4. A web app, to signal the end user of the site, time and confidence level of the occurunce of an accident

# 1. Hardware
For this project, we wanted to leverage as much existing hardware as possible, in order to minimize cost, 
and maximize feasability. However, we also wanted to have multiple data points from which our AI could detect accidents, 
for maximum accuracy. To strike a balance between feasibility, cost and accuracy, we developed a bi-faceted solution. 
We designed our own in-car camera plug-in module, using CAD models of pre-excisting hardware. 
