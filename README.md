# Vehicle detection using cascade learning and smart traffic light actuation using raspberry pi 
The following model is for using on raspberry pi.
Due to its slightly lower performance we have used a cascade learning which divides the objects into positive and negative classes which then the model learns to detect.


# Process for building a smart traffic light is as follows: 
Data collection: Sensors such as cameras, radar, and loop detectors are installed at intersections to collect real-time data on traffic flow, vehicle and pedestrian counts, and other variables.

Analysis: The data collected by the sensors is sent to a central control system that uses algorithms to analyze the information and determine the best traffic signal timing patterns for each intersection.


<img width="221" alt="image" src="https://github.com/PranavBhanot/SMART-TRAFFIC-LIGHT-MANAGEMENT-USING-IOT-AND-DEEP-LEARNING-/assets/74693658/5af1a5f1-dd3a-42e6-98db-985102cd313d">
Adjustment: The control system then adjusts the timing of the traffic lights based on the analysis to improve the flow of traffic, reduce congestion, and improve safety.

Monitoring: The system continually monitors the traffic flow and adjusts the signal timing as needed to respond to changing traffic patterns.

# Statistics
According to a report by the Ministry of Road Transport and Highways, India had 4.12 lakh road accidents in 2021, resulting in 1.53 lakh deaths and 3.84 lakh injuries.
According to a study conducted by a global consultancy firm, traffic congestion
costs the economy Rs 1.47 lakh crore annually.
The study was conducted during peak hours in Delhi, Mumbai, Bengaluru and Kolkata.
Traffic congestion increases vehicle emissions and degrades ambient air quality, and recent studies have shown excess morbidity and mortality for drivers, commuters and individuals living near major roadways.
<img width="547" alt="image" src="https://github.com/PranavBhanot/SMART-TRAFFIC-LIGHT-MANAGEMENT-USING-IOT-AND-DEEP-LEARNING-/assets/74693658/82c89f71-ac04-46db-8caa-9b9dc66970fe">

# Unique Features
Decentralized traffic control, resilient to network outages.
All computations are done on-board and thus, do not depend on any external softwares and cloud services.
A raspberry pi is highly portable and easy to setup.

# Procedure
Input: The system uses cameras to capture images of the traffic flow at each intersection and analyzes them on the microcomputer. 

Output: The system analyzes the data and calculates the optimal traffic light duration for each intersection using a fuzzy logic algorithm. The system then sends commands to the traffic lights via Wi-Fi to adjust their timing accordingly.
![image](https://github.com/PranavBhanot/SMART-TRAFFIC-LIGHT-MANAGEMENT-USING-IOT-AND-DEEP-LEARNING-/assets/74693658/3626cf84-74f0-408a-aeab-494b0f6cf791)


Processing: The system uses the on board Raspberry Pi computer to run a highly efficient model which analyses video frames from the camera to determine the number of cars in the frame. It handles input from 4 different camera systems and decides optimal traffic light timings based on the inputs. 

# Pros: 
The system has several advantages over conventional traffic light systems that use fixed timing or manual control. Some of these advantages are:
It can reduce traffic congestion and improve traffic flow by adapting to real-time traffic conditions.
It can save fuel consumption and reduce emissions by minimizing idling time and stop-and-go movements1.
It can enhance road safety by reducing accidents caused by human errors or impatient drivers.
It can provide useful information for traffic management and planning purposes by collecting and analyzing data from various sources

# Good aspects:
The system has some good aspects that make it attractive for potential users or customers. Some of these aspects are:
It is easy to install and operate as it does not require major changes in the existing infrastructure or hardware.
It is cost-effective as it uses low-cost devices such as cameras and sensors that are widely available in the market.
It is scalable as it can be deployed in different locations and scenarios with minimal modifications.
It is flexible as it can accommodate different types of vehicles such as cars, buses, trucks etc.
It is decentralized, therefore won’t go down even if the connectivity is poor
Therefore, we believe that our smart traffic light system is a valuable solution for improving traffic management in smart cities.
