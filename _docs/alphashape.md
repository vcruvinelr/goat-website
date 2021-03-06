---
title: Isochrone as Alphashape
permalink: /docs/alphashape/
---

GOAT allows you to calculate and visualize isochrones using alpha shapes. GOAT is using the function 
[pgr_pointsAsPolygon](https://docs.pgrouting.org/v2.0.0-alpha/src/driving_distance/doc/dd_points_as_polygon.html) from the library `pgRouting` to generate alpha shapes. The result of this function is an isochrone (polygon) representing the area from a set of points that can be reached in a dedicated time.
<td> {% include image.html src="docs/technical_documentation/alphashape/isochrone_as_alphashape.png" %} </td>

#### 1. Alphashape
Alpha shapes or α-shapes are often used to generalize bounding polygons around a given sets of points. Depending on the chosen alpha parameter the precision of the isochrone can differ. The following example illustrates how alpha shapes are generated depending on the alpha-parameter. 
##### 1.1. Points from the network
<td> {% include image.html src="docs/technical_documentation/alphashape/set_points.png" %} </td>

##### 1.2. Convex Hull 
In the first case is the α-parameter=0. This means that the form generated from the calculation resembles all data points. This is called convex hull. 
<td> {% include image.html src="docs/technical_documentation/alphashape/convex_hull.png" %} </td>

##### 1.3. Concave Hull
By decreasing the alpha parameter value, generated polygon will fit better the sample data. 
A Concave hull describes better the shape of the point cloud than the convex hull.  
<td> {% include image.html src="docs/technical_documentation/alphashape/concave_hull.png" %} </td>

##### 2. Level of detail isochrones
GOAT allows you to choose the level of detail to calculate isochrones. 
The level of detail of the isochrone depends on the alpha-parameter. In the front-end of GOAT the level of detail of isochrones is categorized into six groups from 0 to 5 as following: 
- Level of detail 0: α-parameter = 0.00003
- Level of detail 1: α-parameter = 0.000003
- Level of detail 2: α-parameter = 0.0000025
- Level of detail 3: α-parameter = 0.000002
- Level of detail 4: α-parameter = 0.0000017
- Level of detail 5: α-parameter = 0.0000015

The following example shows how the shape of the isochrone fits better to the network by increasing the level of detail.

<td> {% include image.html src="docs/technical_documentation/alphashape/levelofdetails.png" %} </td>

<span style="color:red">Note: Using very high level of detail can generate errors.</span>


