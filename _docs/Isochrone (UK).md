---
title: Isochrone
permalink: /docs/Isochrone/
---

#### Description of the feature
Isochrones are isolines connecting all points that can be reached from a specific starting point within a certain time interval.
Isochrones are mostly used to represent travel times, for example, to draw a 15-minute radius around a particular starting point. GOAT allows the calculation of isochrones that take factors such as speed, infrastructure network, and traveling time into account. This can be adjusted automatically by choosing between the following modes: walking (standard or elderly), cycling (standard or pedelec), and wheelchair. 
Isochrone can be used as an indicator of accessibility in a specific location. The isochrones in the figure below connect all points that can be reached by foot in five and ten minutes walking from the Technical University of Munich. In this example shops such as supermarkets, chemists, and convenience-store that can be reached within the calculated isochrone are shown. In this case, 5 km/h was selected as speed factor.
In case there is an intrest in knowing more about the technical part of calculating isochrones please check this [link](https://www.open-accessibility.org/docs/alphashape/).
<img class="img-responsive" src="../../img/Docs/training materials/Isochrone/isochrone_TUM.png" alt="5- and 10-minute-isochrone from TUM" title="5- and 10-minute-isochrone from TUM">

#### Possible use cases
Isochrones can be used to answer different planning questions, some examples can be:
- How many supermarkets can be reached from a certain point in 10 minutes walking?
- How many people can access a public transport station within 5 minutes cycling? 
- Compare the accessibility by foot and by a wheelchair


#### Step-by-step tutorial for an exemplary planning task
##### 1 Bicycle Routing 
###### 1.1 Planning question
How many people can reach the train station Fürstenfeldbruck within 5 minutes by bike? 
###### 1.2 Work steps
1. Change the routing mode to “cycling” 
<img class="img-responsive" src="../../img/Docs/training materials/Isochrone/cycling-mode.png" title="Routing mode cycling">


2. Set the isochrone range to 5 minutes
<img class="img-responsive" src="../../img/Docs/training materials/Isochrone/isochrone-range.png" title="Adjusting isochrone range">


3. Place the starting point for the isochrone calculation on the station
<img class="img-responsive" src="../../img/Docs/training materials/Isochrone/starting-point-isochrone.png" title="Starting point isochrone">


4. After the calculation has been carried out, a window with the results opens automatically. From this window you can see the population reached
<img class="img-responsive" src="../../img/Docs/training materials/Isochrone/population-reached.png" title="Reached population">

###### 1.3 Solution
Approximately 2425 people can reach the train station Fürstenfeldbruck within 5 minutes by bike

##### 2 Wheelchair routing
###### 2.1 Planning questions
- How does the 10-minute accessibility of the hospital differ from pedestrian on persons with reduced mobility?
- Are the results realistic? 
- Where are barriers in the network and how could they be imrpoved? 

###### 2.2 Work steps

1. Select the "walking" routing mode
<img class="img-responsive" src="../../img/Docs/training materials/Isochrone/walking-mode.png" title="Routing mode walking">

2. Set the isochrone range to 10 minutes
<img class="img-responsive" src="../../img/Docs/training materials/Isochrone/isochrone_range_walking.png" title="Adjusting isochrone range">

3. Place the starting point for the isochrone calculation at the entrance of the Hospital
<img class="img-responsive" src="../../img/Docs/training materials/Isochrone/starting-point-isochrone.png" title="Starting point isochrone">

4. Select the routing mode "wheelchair" and repeat the calculation
<img class="img-responsive" src="../../img/Docs/training materials/Isochrone/wheelchair-mode.png" title="Routing mode wheelchair">

5. Display the street network used for both isochrones. From this you can see which roads were used for the corresponding routing
<img class="img-responsive" src="../../img/Docs/training materials/Isochrone/additional-layer.png" title="Activate additional layers">

 