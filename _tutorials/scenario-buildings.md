---
title:  Scenarios Buildings - Dynamic Heatmap
permalink: /tutorials/scenario-buildings/
---

#### Description of the feature
GOAT allows the development of own scenarios for changes in the building structure, such as the construction of a new residential area or the demolition of an old building. The developed scenario can be added to the existing urban structure and the changes in accessibility can be evaluated using the dynamic heatmaps. 

#### Possible use cases (planning questions)
- How does a new residential area effect the accessibility to schools in a certain neighbourhood?
- Is the population in a new residential area served with the everyday necessities?
- Where is the potential for further settlement development?

#### Step-by-step tutorial for the exemplary planning task
##### 1 Scenario on new residential development
###### 1.1 Planning question
- How many additional residents have access to a primary school within a 10-minute walk if an existing residential area will be redensified?


###### 1.2 Step-by-Step guide
1. Display the layer "Buildings" from the category "Buildings and landuse" and the layer "Population" from the category "Accessibility". These show all existing buildings (in red: buildings with residential use, in white: buildings without residential use) and the population density (the darker the background, the higher the population density).  {% include image.html src="../../uploads/training materials/Scenario_buildings/building_layer.png"  %}


2. Navigate to the scenario development menu and select the "Building" layer.  {% include image.html src="../../uploads/training materials/Scenario_buildings/scenario_buildings.png" maxheight="200px"  %}

3. Using the editing tools, you can draw and edit new buildings. Specify the type of use and the number of floors for each new building. In addition, you must set at least one entrance for each building. Once you have done this, the building will appear in green.  {% include image.html src="../../uploads/training materials/Scenario_buildings/draw.png"  %}

4. In order to integrate the modified buildings into the database, they must be uploaded using the "Upload" button.  {% include image.html src="../../uploads/training materials/Scenario_buildings/upload.png" maxheight="300px"  %}

5. By scrolling the map, the heat map for population density is updated automatically. The changed kindergartens are now directly included in the calculation.    

6. Display the primary schools as Thematic Data.   

7. Switch to the "Multi" isochrone calculation mode, set the calculation mode to "Modified network (double calculation)" and select the "Study Area" method. Then select the district on the map where you have carried out the redensification with a mouse click.  {% include image.html src="../../uploads/training materials/Scenario_buildings/multiisochrones.png" maxheight="300px"  %}

8. Click on "Calculate".  {% include image.html src="../../uploads/training materials/Scenario_buildings/calculate.png" maxheight="200px"  %}

9. The resulting multi-isochrones show the catchment areas of the primary schools (here for the mode "pedestrian" with 5 minutes catchment area in light green and 10 minutes catchment area in dark green). The associated table shows how many additional people now live in the 10-minute catchment area of the primary school as a result of the redensification.  {% include image.html src="../../uploads/training materials/Scenario_buildings/result.png" %}

 