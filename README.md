# Tempiture: Automated Outdoor Smoker

##### 4180 Final Project
##### Team: Brooke Gardner, Madeline Miller, Sean Macikowski

This is the software component of Tempiture. Our team for the final project built off of [this](https://kyleflan.wordpress.com/2017/10/20/tempiture-a-raspberry-pi-powered-wireless-grilling-thermometer-system/) original project. We used the recommended parts list and assembly, with the exception of different probes, which required ecessary changes to probes.json. We added a small RC servo connected to GPIO25 for control, the Pi's 5V output power, and ground, and used node-red to automate the servo for opening and closing of the vent. We also added temperature notifications on the Grafana server using slack, which are sent to Sean's slack application on his phone. 

Grafana server video can be found [here](https://www.youtube.com/watch?v=OvtE233BwOE). 
Servo automation using node-red video can be found [here]( https://www.youtube.com/watch?v=Ok8Tr13rT9w&feature=youtu.be).
Our final presentation can be found [here](https://docs.google.com/presentation/d/1cIFl13KUGAkXRPAjDDhsqZjXKBVD_HlZkl6B9_slUFA/edit?usp=sharing).
