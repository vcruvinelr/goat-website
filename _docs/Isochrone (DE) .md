---
title: Isochrone (DE)
permalink: /docs/Isochrone (DE)/
---

#### Beschreibung des Features
Isochronen sind Isolinien, die alle Punkte verbinden, die von einem bestimmten Startpunkt aus innerhalb eines bestimmten Zeitintervalls erreicht werden können.
GOAT ermöglicht die Berechnung von Isochronen mit der Berücksichtigung von Faktoren wie Geschwindigkeit, Infrastrukturnetz und Reisezeit. Dies kann automatisch angepasst werden, indem zwischen Gehen (Standard oder Senior), Radfahren (Standard oder Pedelec) und Rollstuhl ausgewählt wird. Isochronen können als Indikator für die Erreichbarkeit an einem bestimmten Ort verwendet werden. 

#### Mögliche Anwendungsszenarien
Isochronen können zur Beantwortung verschiedener Planungsfragen verwendet werden, einige Beispiele können genannt werden:
- Wie viele Supermärkte können von einem bestimmten Punkt aus innerhalb von 10 Gehminuten erreicht werden?
- Wie viele Menschen können eine ÖV Haltestelle innerhalb von 5 Minuten mit dem Fahrrad erreichen? 
- Vergleich der Erreichbarkeit zu Fuss und mit dem Rollstuhl


#### Schritt-für-Schritt-Anleitung für die beispielhaften Planungsaufgaben
##### 1 Erreichbarkeit zu Supermärkten
###### 1.1 Planungsfrage
Wie viele Supermärkte können ab einem bestimmten Punkt innerhalb von 10 Gehminuten erreicht werden?
###### 1.2 Arbeitsschritte
1. Zoomen Sie zu dem Bereich, in dem Sie die Isochrone berechnen möchten.

2. Wählen Sie im Menü „Filter Thematische Daten“ die Einrichtung Supermarkt.  
<img class="img-responsive" src="../../img/Docs/training materials/Isochrone/amenity_supermarket.png" title="amenity supermarket" style="height:200px;">

3. Stellen Sie die Isochronen Reichweite auf 10 Minuten.  
<img class="img-responsive" src="../../img/Docs/training materials/Isochrone/isochrone_range_walking.png" title="Adjusting isochrone range" style="height:200px;">

4. Platzieren Sie den Startpunkt für die Isochronenberechnung in einem beliebigen Punkt.

5. Nachdem die Berechnung ausgeführt wurde, öffnet sich automatisch ein Fenster mit den Ergebnissen. Diesem können Sie die errichbare Supermärkte entnehmen.  
<img class="img-responsive" src="../../img/Docs/training materials/Isochrone/supermarkets_reached.png" title="Reached supermarkets" style="height:200px;">

6. Wenn Sie möchten, dass die erreichbaren Supermärkte angezeigt werden, klicken Sie auf Layer und aktivieren Sie POIs.  
<img class="img-responsive" src="../../img/Docs/training materials/Isochrone/pois_layers.png" title="Layer POIs" style="height:200px;">




##### 2 Fahrradrouting
###### 2.1 Planning question
Wie viele Menschen können den Bahnhof innerhalb von 5 Minuten mit dem Fahrrad erreichen? 
###### 2.2 Work steps
1. Ändern Sie den Routingmodi zu „Radfahrer“.  
<img class="img-responsive" src="../../img/Docs/training materials/Isochrone/cycling-mode.png" title="Routing mode cycling" style="height:200px;">


2. Stellen Sie die Isochronen Reichweite auf 5 Minuten.  
<img class="img-responsive" src="../../img/Docs/training materials/Isochrone/isochrone-range.png" title="Adjusting isochrone range" style="height:200px;">


3. Platzieren Sie den Startpunkt für die Isochronenberechnung auf dem Bahnhof.  
<img class="img-responsive" src="../../img/Docs/training materials/Isochrone/starting-point-isochrone.png" title="Starting point isochrone" style="height:200px;">


4. Nachdem die Berechnung ausgeführt wurde, öffnet sich automatisch ein Fenster mit den Ergebnissen. Diesem können Sie die erreichte Bevölkerung entnehmen.  
<img class="img-responsive" src="../../img/Docs/training materials/Isochrone/population-reached.png" title="Reached population" style="height:200px;">



##### 3 Rollstuhlrouting
###### 3.1 Planungsfrage
- Wie unterscheidet sich die 10-minütige Erreichbarkeit des Klinikums von Fußgänger zu mobilitätseingeschränkter Person? 
- Wo befinden sich Barrieren im Netzwerk und wie könnten diese behoben werden? 


###### 3.2 Work steps

1. Wählen Sie den Routingmodi „Fußgänger“.  
<img class="img-responsive" src="../../img/Docs/training materials/Isochrone/walking-mode.png" title="Routing mode walking" style="height:200px;">

2. Stellen Sie die Isochronen Reichweite auf 10 Minuten.  
<img class="img-responsive" src="../../img/Docs/training materials/Isochrone/isochrone_range_walking.png" title="Adjusting isochrone range" style="height:200px;">

3. Platzieren Sie den Startpunkt für die Isochronenberechnung am Eingang des Klinikums.  
<img class="img-responsive" src="../../img/Docs/training materials/Isochrone/starting-point-isochrone.png" title="Starting point isochrone" style="height:200px;">

4. Wählen Sie den Routingmodi „Rollstuhl“ und wiederholen Sie die Berechnung.  
<img class="img-responsive" src="../../img/Docs/training materials/Isochrone/wheelchair-mode.png" title="Routing mode wheelchair" style="height:200px;">

5. Lassen Sie sich für beide Isochronen das verwendete Straßennetzwerk anzeigen. Diesem können Sie entnehmen, welche Straßen für das entsprechende Routing verwendet wurden.  
<img class="img-responsive" src="../../img/Docs/training materials/Isochrone/additional-layer.png" title="Activate additional layers" style="height:200px;">

 