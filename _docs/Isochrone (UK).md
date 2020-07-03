---
title: Isochrone
permalink: /docs/Isochrone/
---

#### Description of the feature
Isochrones are isolines connecting all points that can be reached from a specific starting point within a certain time interval.
GOAT allows the calculation of isochrones that take factors such as speed, infrastructure network, and traveling time into account. This can be adjusted automatically by choosing between the following modes: walking (standard or elderly), cycling (standard or pedelec), and wheelchair. Isochrones can be used as an indicator of accessibility in a specific location. 

#### Possible use cases
Isochrones can be used to answer different planning questions, some examples can be:
- How many supermarkets can be reached from a certain point in 10 minutes walking?
- How many people can access a public transport station within 5 minutes cycling? 
- Compare the accessibility by foot and by a wheelchair


#### Step-by-step tutorials for exemplary planning tasks
##### 1 Acessibility to supermarkets
###### 1.1 Planning question

How many supermarkets can be reached from a certain point in 10 minutes walking?

###### 1.2 Step-by-Step guide

1. Display all supermarkets by enabling the amenity "Supermarket" in the Thematic Data Filter under the category "Shop".  
<img class="img-responsive" src="../../img/Docs/training materials/Isochrone/amenity_supermarket.png" title="amenity supermarket" style="height:200px;">

2. Zoom in into the area where you want to calculate the isochrone.

3. Set the isochrone range to 10 minutes.  
<img class="img-responsive" src="../../img/Docs/training materials/Isochrone/isochrone_range_walking.png" title="Adjusting isochrone range" style="height:200px;">

4. Place the starting point for the isochrone.  
<img class="img-responsive" src="../../img/Docs/training materials/Isochrone/starting-point-isochrone.png" title="Starting point isochrone" style="height:150px;">

5. After the calculation has been carried out, a window with the results opens automatically. From this window you can see the number of supermarkets that can be reached within 10 minutes.  
<img class="img-responsive" src="../../img/Docs/training materials/Isochrone/isochrone_supermarkets.png" title="Reached supermarkets">


##### 2 Bicycle Routing 
###### 2.1 Planning question
How many people can reach the train station within 5 minutes by bike? 
###### 2.2 Work steps
1. Change the routing mode to “cycling”.  
<img class="img-responsive" src="../../img/Docs/training materials/Isochrone/cycling-mode.png" title="Routing mode cycling" style="height:200px;">


2. Set the isochrone range to 5 minutes.  
<img class="img-responsive" src="../../img/Docs/training materials/Isochrone/isochrone-range.png" title="Adjusting isochrone range" style="height:200px;">


3. Place the starting point for the isochrone calculation on the station.  
<img class="img-responsive" src="../../img/Docs/training materials/Isochrone/starting-point-isochrone.png" title="Starting point isochrone" style="height:150px;">


4. After the calculation has been carried out, a window with the results opens automatically. From this window you can see the population that can reach the train station within 5 minutes cycling.  
<img class="img-responsive" src="../../img/Docs/training materials/Isochrone/isochrone_trainstation.png" title="Reached population">



##### 3 Wheelchair routing
###### 3.1 Planning questions
- How does the 10-minute accessibility of an hospital differ from pedestrian on persons with reduced mobility?
- Where are barriers in the network and how could they be improved? 

###### 3.2 Work steps

1. Select the routing mode "walking".  
<img class="img-responsive" src="../../img/Docs/training materials/Isochrone/walking-mode.png" title="Routing mode walking" style="height:200px;">

2. Set the isochrone range to 10 minutes.  
<img class="img-responsive" src="../../img/Docs/training materials/Isochrone/isochrone_range_walking.png" title="Adjusting isochrone range" style="height:200px;">

3. Place the starting point for the isochrone calculation at the entrance of the Hospital.  
<img class="img-responsive" src="../../img/Docs/training materials/Isochrone/starting-point-isochrone.png" title="Starting point isochrone" style="height:150px;">

4. Select the routing mode "wheelchair" and repeat the calculation.  
<img class="img-responsive" src="../../img/Docs/training materials/Isochrone/wheelchair-mode.png" title="Routing mode wheelchair" style="height:200px;">

5. Now it gets visible, how accessibility differs when regarding a person with reduces mobility (red isochrone) in compare to a pedestrian (blue isochrone).  
<img class="img-responsive" src="../../img/Docs/training materials/Isochrone/isochrone_wheelchair.png" title="Isochrone comparison">

6. To find the barriers in the network, display the street network used for both isochrones. From this you can see which roads were used for the corresponding routing.  
<img class="img-responsive" src="../../img/Docs/training materials/Isochrone/additional-layer.png" title="Activate additional layers" style="height:150px;">

 