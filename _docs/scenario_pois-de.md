---
title:  Szenarien POIs - Dynamische Heatmap
permalink: /de/docs/scenario_pois/
lang: de
---

#### Beschreibung des Features
GOAT ermöglicht die Entwicklung eigener Szenarien zu Points-of-Interest (POI), wie z.B. Modifikation des Standorts eines Supermarktes oder Hinzufügen einer neue Schule. Das entwickelte Szenario kann zu der vorhandenen Siedlungsstruktur hinzugefügt und die Änderungen in der Erreichbarkeit durch dynamische Heatmaps bewertet werden. 

#### Mögliche Anwendungsszenarien
Die Szenarien Entwicklung zu POIs kann zur Beantwortung verschiedener Planungsfragen verwendet werden, einige Beispiele hierfür sind:
- Wie verändert sich die Erreichbarkeit zu Supermärkten in einer Nachbarschaft, wenn den Standort eines Supermarktes geändert wird?
- Wie verändert sich die Erreichbarkeit zu Schulen, wenn eine neue Schule hinzugefügt wird?
- Wie gut sind die Kindergärten über die Stadt verteilt? Wo wäre eine gute Position für einen neuen Kindergarten? 


#### Schritt-für-Schritt-Anleitung für eine beispielhafte Planungsaufgabe
##### 1 Szenario zum Bau eines neuen Kindergartens
###### 1.1 Planungsfrage
- Wie gut sind die Kindergärten aktuell über die Stadt verteilt? 
- In welchen Stadtteilen gibt es Defizite in der fußläufigen Erreichbarkeit? 
- Und wie könnten diese behoben werden?
- Wo wäre eine gute Position für einen neuen Kindergarten? 


###### 1.2 Arbeitsschritte
1. Lassen Sie sich als Thematische Daten die Kindergärten anzeigen.  
<img class="img-responsive" src="../../img/Docs/training materials/Scenario_POIs/kindergarten.png" style="height:200px;">

2. Blenden Sie den Layer „Walkability-Bevölkerungs-Index” aus den „Grundkarten Erreichbarkeit” ein. Dieser zeigt, wie gut die fußläufige Erreichbarkeit zu den gewählten Zielen räumlich über die Bevölkerung verteilt ist. Blaue Färbung bedeutet ein Überangebot und rote Färbung ein Unterangebot. In Gelb dargestellten Flächen sind vorhandene Versorgung und Bevölkerung ausgeglichen.  
<img class="img-responsive" src="../../img/Docs/training materials/Scenario_POIs/walkability_popoulation_index.png">

3. Gehen Sie nun in das Fenster zur Szenarienentwicklung und wählen Sie den „Point of Interest” Layer.  
<img class="img-responsive" src="../../img/Docs/training materials/Scenario_POIs/PointofInterest.png" style="height:200px;">

4. Bearbeiten Sie die Kindergärten so (bestehende Kindergärten verschieben oder neue Kindergärten hinzufügen), dass auch die Stadtteile mit Erreichbarkeitsdefiziten abgedeckt werden. Um einen Kindergarten zu verschieben, müssen sie diesen zunächst über das Kreis-Werkzeug auswählen.  
<img class="img-responsive" src="../../img/Docs/training materials/Scenario_POIs/circle_tool.png" style="height:200px;">

5. Durch Scrollen der Karte aktualisiert sich die Heatmap zum Walkability-Bevölkerungs-Index automatisch. Die veränderten Kindergärten werden nun direkt in die Berechnung mit einbezogen.  
<img class="img-responsive" src="../../img/Docs/training materials/Scenario_POIs/new_kindergarden.png">








 