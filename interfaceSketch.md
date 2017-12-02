# Post-disaster Network Accessibility Map

Natural hazards like earthquake, will lead to the destruction of the network. 
It will also trigger the occurrence of other hazards, i.e. land slide, liquefaction etc. 
This will severely affect the travel time on the network. Therefore, be able to estimate 
the travel time on the network is critical to the post-disaster recovery. 

## Objective

This project aims to develop a web GIS tool that visualizes the travel time under different network 
failure scenarios. 

## Scenarios 
### Worst Case

I have travel time calculated for different scenarios on Portland Network. I will need a base map, 
and GIS shapefile layer with time attributes visualized on the map. There will be a dropdown list 
to select the scenario, and legend to show the categories of the time.


### Best Case

There will be several shapefiles and also different hazards probability shapefiles as the input. 
I will use an open source package/algorithm to calculate the travel time on the network with the 
conditional probability as the hazards layer indicates. 

Even more, I hope the map can show some interactive features so I can create the arbitrary scenarios. 
For examples, I hope I can hover on the transportation network, and select the links that need to be 
destroyed. And then I can use the algorithm to calculate the travel time on the network without these 
links. 

## Data Resource

| Layer |  Source |
| ------------ | ------------- |
| Oregon Transportation Network | [Oregon Transportation GIS shapefile](http://spatialdata.oregonexplorer.info/geoportal/details;id=a3f15e64538a43ad9fea7f14dce4075b) |
| Oregon Landslide Probability Map | [ Oregon Landslide Probability raster file](http://web.engr.oregonstate.edu/~gillinsd/O-Help/) |

![Oregon Transportation Network](/img/oregonTransportationNetwork.jpg)

![Oregon Landslide Probability Map](/img/oregonLandSlideProb.png) 

## Interface Sketch

![main page](/img/mainPage.jpg)

> This page is the main page of the website. It contains the menu and project description.

![Project background](/img/page2.jpg)

> This page is created to show the past two phase's work on this project. 

![Interactive Map](/img/page3.jpg)

> This page displays the Isochrone of travel time of the network. Different scenarios can be selected, and then a final Isochrone map will be rendered.

![Team](/img/page4.jpg)

> This page gives an introduction on the project team members. 

