---
title:  Szenarien Gebäude - Dynamische Heatmap
permalink: /de/tutorials/scenario-buildings/
lang: de
---

#### Beschreibung des Features
GOAT ermöglicht die Entwicklung eigener Szenarien zu Änderungen in der Gebäudestruktur, wie z.B. das Errichten eines neuen Wohngebietes oder das Abreißen eines alten Gebäudes. Das entwickelte Szenario kann zu der vorhandenen Siedlungsstruktur hinzugefügt und die Änderungen in der Erreichbarkeit durch dynamische Heatmaps bewertet werden. 

#### Mögliche Anwendungsszenarien
Die Szenarien Entwicklung zu Gebäuden kann zur Beantwortung verschiedener Planungsfragen verwendet werden, einige Beispiele hierfür sind:
- Wie verändert die Errichtung eines neuen Wohngebietes die Erreichbarkeit zu Schulen in einer bestimmten Nachbarschaft?


#### Schritt-für-Schritt-Anleitung für eine beispielhafte Planungsaufgabe
##### 1 Szenario zu neuer Wohnbebauung
###### 1.1 Planungsfrage
- Wie viele zusätzliche Bewohner haben innerhalb von 10 Gehminuten Zugang zu einer Grundschule, wenn ein bestehendes Wohngebiet nachverdichtet wird?


###### 1.2 Arbeitsschritte
1. Blenden Sie den Layer „Gebäude” aus der Kategorie „Gebäude und Flächennutzung” und den Layer „Bevölkerung” aus der Kategorie „Grundkarten Erreichbarkeit” ein. Diese zeigen alle vorhandenen Gebäude (in rot: Gebäude mit Wohnnutzung, in weiß: Gebäude ohne Wohnnutzung) und die Bevölkerungsdichte an (umso dünkler der Hintergrund, umso höher die Bevölkerungsdichte).  
<img class="img-responsive" src="../../img/Docs/training materials/Scenario_buildings/building_layer.png">

2. Gehen Sie nun in das Fenster zur Szenarienentwicklung und wählen Sie den „Gebäude” Layer.  
<img class="img-responsive" src="../../img/Docs/training materials/Scenario_buildings/scenario_buildings.png" style="height:200px;">

3. Mittels der Bearbeitungstools können Sie neue Gebäude zeichnen und bearbeiten. Bestimmen Sie für neue Gebäude jeweils die Art der Nutzung und die Anzahl der Stockwerke. Außerdem muss für jedes Gebäude mindestens ein Eingang gesetzt werden- Nachdem dies getan wurde, erscheint das Gebäude in Grün.  
<img class="img-responsive" src="../../img/Docs/training materials/Scenario_buildings/draw.png">

4. Um die veränderten Gebäude in die Datenbank zu integrieren, müssen diese über den Button „Hochladen“ hochgeladen werden.  
<img class="img-responsive" src="../../img/Docs/training materials/Scenario_buildings/upload.png" style="height:300px;">

5. Durch Scrollen der Karte aktualisiert sich die Heatmap zur Bevölkerungsdichte automatisch. Die veränderten Gebäude werden nun direkt in die Berechnung mit einbezogen.   

6. Lassen Sie sich als Thematische Daten die Grundschulen anzeigen.  

7. Wechseln Sie zum Isochronenberechnugsmodus „Multi“, stellen den Berechnungsmodus auf „Standard und Szenario“ und wählen die Methode „Ortsteil“ aus. Wählen Sie dann in der Karte per Mausklick den Ortsteil, in dem Sie die Nachverdichtung durchgeführt haben.  
<img class="img-responsive" src="../../img/Docs/training materials/Scenario_buildings/multiisochrones.png" style="height:300px;">

8. Klicken Sie auf „Berechnen“.  
<img class="img-responsive" src="../../img/Docs/training materials/Scenario_buildings/calculate.png" style="height:200px;">

9. Die resultierenden Multi-Isochronen zeigen die Einzugsbereiche der Grundschulen (hier für den Modus „Fußgänger“ mit 5 Minuten Einzugsbereich in hellgrün und 10 Minuten Einzugsbereich in dunkelgrün). Der zugehörigen Tabelle kann entnommen werden, wie viele zusätzliche Menschen durch die Nachverdichtung nun im 10-minütigen Einzugsbereich der Grundschule wohnen. 
<img class="img-responsive" src="../../img/Docs/training materials/Scenario_buildings/result.png">

 