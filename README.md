## Post-Disaster Transportation Network Accessibility 

![web interface](./img/webInterface.png)

> The web page can be found [here](https://shangjiadong.github.io/netAcce/).

### Introduction

Pacific Northwest region is highly prone to a M9 Cascadia Subduction Zone earthquake.  This poses a great threat on the network’s functionality. The accessibility to critical facility and mobility on the network is of our concern. This project will collaborate with [O-HELP](ohelp.oregonstate.edu) and incorporate different hazard probabilities and their potential impact on transportation network in order to investigate the accessibility and mobility after the disaster. The project is part of the [Cascadia Lifeline Program (CLiP)](http://cascadia.oregonstate.edu/) at Oregon State University. 

### Objective 

The accessibility to critical facilities such as hospital, fire station,  restoration warehouse etc. are essential for post-disaster recovery, without which will result in a catastrophe. An earthquake can induce landslide or liquefaction, which will lead to potential failure of the roadway, and further paralyze the traffic. This project aims to develop a framework to analyze the accessibility on transportation network under different scales of network disruption. First we create a model in VISSUM to approximate the real-life traffic scenario. Under different disruptions, the link capacity will be reduced to simulate the disastrous effect on transportation network. Here, travel time is calculated to represent the accessibility on the network. After the simulation, the travel time both on links and from zone to zone will be extracted and visualized with web application. 

### Web Architecture 

The website can be divided into five sections: homepage, about the project, map services, past projects portfolio, and contact information. 

Homepage set the tune of the visualization. It gives a short clip on past phases of the project, and provides a quick link to the detailed information. It also briefly illustrates the background of the project, provides a link to the program, and acknowledges the sponsors of the project. 

About page gives a more detailed background description of the project. Also, it introduces the team members, and lists the sponsors. 

Map services is the main function of the this web application. It contains two maps: 2D map and 3D map. 

![2D map](./img/map2d.PNG)

2D map visualize the travel time from a bird view. The map shows the travel time from each zone to the Portland International Airport. Different colors represent the different levels of travel time. I chose to use a bivariate color ramp. Because green normally stands for the uncongested traffic, and red indicates the high volume. Therefore, using green for the low travel time, and red for high travel time is very intuitive. There is also interactive feature on the map. When the mouse hoover the state, the zone will be highlighted and the travel time will be showed in the legend panel. 









