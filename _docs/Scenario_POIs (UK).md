---
title: Scenarios POIs - Dynamic Heatmap
permalink: /docs/Scenario POIs/
---

#### Description of the feature
GOAT allows you to develop your own Point-of-Interest (POI) scenarios, such as modifying the location of a supermarket or adding a new school. The developed scenario can be added to the current land-use structure, and changes in accessibility can be evaluated by the dynamic heatmap.  

#### Possible use cases
Land use development scenarios can be used to answer various planning questions, such as:
- How does accessibility to supermarkets in a neighbourhood change when the location of a supermarket is changed?
- How does accessibility to schools change when a new school is added?


#### Step-by-step tutorial for the exemplary planning task
##### 1 Scenario on accessibility to kindergartens
###### 1.1 Planning question
- How well are the kindergartens currently distributed over the city? 
- In which parts of the city are there deficits in pedestrian accessibility? 
- And how could these be remedied?


###### 1.2 Work steps

1. Select the kindergartens as Thematic Data.  
<img class="img-responsive" src="../../img/Docs/training materials/Scenario_POIs/kindergarten.png" style="height:300px;">


2. Display the layer "Walkability-Population-Index" from the "Accessibility" layers. This shows how well the walking accessibility to the selected destinations is spatially distributed over the population. Blue coloring means oversupply and red coloring means undersupply. Areas shown in yellow indicate that existing supply and population are balanced.  
<img class="img-responsive" src="../../img/Docs/training materials/Scenario_POIs/walkability_popoulation_index.png">

3. Now go to the menu for scenario development and select the "Point of Interest" Layer.  
<img class="img-responsive" src="../../img/Docs/training materials/Scenario_POIs/PointofInterest.png" style="height:200px;">

4. Edit the kindergartens (move existing kindergartens or add new kindergartens) in such a way that the districts with accessibility deficits are also covered. To move a kindergarten, you must first select it using the circle tool.  
<img class="img-responsive" src="../../img/Docs/training materials/Scenario_POIs/circle_tool.png" style="height:200px;">

5. By scrolling the map, the heat map for the walkability population index is updated automatically. The changed kindergartens are now directly included in the calculation.  
<img class="img-responsive" src="../../img/Docs/training materials/Scenario_POIs/new_kindergarden.png">








 