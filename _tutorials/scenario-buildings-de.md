---
title:  Szenarien - Gebäude
permalink: /de/tutorials/scenario-buildings/
lang: de
---

#### Beschreibung des Features
GOAT ermöglicht Veränderungen in der Bebauung, wie z.B. die Errichtung eines neuen Wohngebietes oder das Abreißen eines alten Gebäudes. Das entwickelte Szenario wird zur vorhandenen Siedlungsstruktur hinzugefügt und im Anschluss können Änderungen in der Erreichbarkeit aufgezeigt werden. 

#### Mögliche Anwendungsfälle (Planungsfragen)
- Wie verändert die Errichtung eines neuen Wohngebietes die Erreichbarkeit zu Schulen in einer bestimmten Nachbarschaft?
- Ist die Bevölkerung in einem neuen Wohngebiet mit den Dingen des täglichen Bedarfs erschlossen?
- Wo bestehen Potenziale für die weitere Siedlungsentwicklung?

#### Schritt-für-Schritt-Anleitung für eine beispielhafte Planungsaufgabe
##### 1 Szenario zu neuer Wohnbebauung
###### 1.1 Planungsfrage
- Wie viele zusätzliche Bewohner haben innerhalb von 10 Gehminuten Zugang zu einer Grundschule, wenn ein bestehendes Wohngebiet nachverdichtet wird?


###### 1.2 Arbeitsschritte
1. Blenden Sie den Layer „Gebäude” aus der Kategorie „Gebäude und Flächennutzung” und den Layer „Bevölkerung” aus der Kategorie „Grundkarten Erreichbarkeit” ein. Diese zeigen alle vorhandenen Gebäude (in rot: Gebäude mit Wohnnutzung, in weiß: Gebäude ohne Wohnnutzung) und die Bevölkerungsdichte an (umso dünkler der Hintergrund, umso höher die Bevölkerungsdichte).  {% include image.html src="../../uploads/training materials/Scenario_buildings/building_layer.png"  %}

2. Gehen Sie nun in das Fenster zur Szenarienentwicklung und wählen Sie den „Gebäude” Layer.  {% include image.html src="../../uploads/training materials/Scenario_buildings/scenario_buildings.png" maxheight="200px"  %}

3. Mittels der Bearbeitungstools können Sie neue Gebäude zeichnen und bearbeiten. Bestimmen Sie für neue Gebäude jeweils die Art der Nutzung und die Anzahl der Stockwerke. Außerdem muss für jedes Gebäude mindestens ein Eingang gesetzt werden. Nachdem dies getan wurde, erscheint das Gebäude in Grün.  {% include image.html src="../../uploads/training materials/Scenario_buildings/draw.png"  %}

4. Um die veränderten Gebäude in die Datenbank zu integrieren, müssen diese über den Button „Hochladen“ hochgeladen werden.  {% include image.html src="../../uploads/training materials/Scenario_buildings/upload.png" maxheight="300px"  %}

5. Durch Scrollen der Karte aktualisiert sich die Heatmap zur Bevölkerungsdichte automatisch. Die veränderten Gebäude werden nun direkt in die Berechnung mit einbezogen.   

6. Lassen Sie sich als Thematische Daten die Grundschulen anzeigen.  

7. Wechseln Sie zum Isochronenberechnugsmodus „Multi“, stellen den Berechnungsmodus auf „Standard und Szenario“ und wählen die Methode „Ortsteil“ aus. Wählen Sie dann in der Karte per Mausklick den Ortsteil, in dem Sie die Nachverdichtung durchgeführt haben.  {% include image.html src="../../uploads/training materials/Scenario_buildings/multiisochrones.png" maxheight="300px"  %}

8. Klicken Sie auf „Berechnen“.  {% include image.html src="../../uploads/training materials/Scenario_buildings/calculate.png" maxheight="200px"  %}

9. Die resultierenden Multi-Isochronen zeigen die Einzugsbereiche der Grundschulen (hier für den Modus „Fußgänger“ mit 5 Minuten Einzugsbereich in hellgrün und 10 Minuten Einzugsbereich in dunkelgrün). Der zugehörigen Tabelle kann entnommen werden, wie viele zusätzliche Menschen durch die Nachverdichtung nun im 10-minütigen Einzugsbereich der Grundschule wohnen.  {% include image.html src="../../uploads/training materials/Scenario_buildings/result.png" %}

 