---
title: Szenarien Entwicklung
permalink: /docs/Scenario Building/
---

#### Beschreibung des Features
GOAT ermöglicht die Entwicklung eigene Szenarien, wie z.B. modifikation im Netzwerk oder Bau einer neuen Brücke. Das entwickelte Szenario kann zu der aktuellen Netzwerk hinzugefügt werden, und Ändrungen der Erreichbarkeit können durch Isochronen bewertet werden. 

#### Mögliche Anwendungsszenarien
Isochronen können zur Beantwortung verschiedener Planungsfragen verwendet werden, einige Beispiele können genannt werden:
- Wie verändert sich die Erreichbarkeit durch den Bau einer neuen Fahrradbrücke über den Fluss?
- Wie verändert sich die Erreichbarkeit mit dem Rohlstuhl durch den Bau einer barrierfreie Straße? 



#### Schritt-für-Schritt-Anleitung für eine beispielhafte Planungsaufgabe
##### 1 Szenario zu neuer Fahrradbrücke
###### 1.1 Planungsfrage
Wie verändert sich die Erreichbarkeit durch den Bau einer neuen Fahrradbrücke über den Fluss? 
###### 1.2 Arbeitsschritte
1. Gehen Sie in das Fenster zur Szenarienentwicklung und wählen Sie den Wege Layer
<img class="img-responsive" src="../../img/Docs/training materials/Scenario_building/scenario_ways.png">


2. Zoomen Sie zu der Stelle, an der Sie eine neue Fahrradbrücke bauen wollen und wählen Sie mittels des Kreis-Werkzeuges das umliegenden Straßennetz aus
<img class="img-responsive" src="../../img/Docs/training materials/Scenario_building/circle_scenario.png" title="Kreis-Werkzeug">

3. Zeichnen Sie an der gewünschten Stelle eine neue Wegeverbindung, wählen als Wegetyp „Brücke“ aus und klicken Sie auf „Speichern“. Die gezeichneten Wege werden nun       rechts in der Tabelle aufgeführt. Um diese Wege in die Datenbank zu integrieren, müssen diese über den Button „Hochladen“ hochgeladen werden
<img class="img-responsive" src="../../img/Docs/training materials/Scenario_building/bridge_building.png">
4. Nun können Sie die Auswirkung der neuen Wegeverbindung auf die Erreichbarkeit analysieren, indem Sie sich die Standard- und die Scenario-Isochrone berechnen lassen. Wählen Sie hierzu den Routingmodi „Fahrrad“ aus und setzen den Berechnungsmodus auf „Standard und Scenario“
<img class="img-responsive" src="../../img/Docs/training materials/Scenario_building/modified_network.png">
5. Platzieren Sie den Startpunkt für die Isochronenberechnung in der Nähe der neuen Brücke. Als Ergebnis wird Ihnen in Orange die Isochrone in der Ausgangslage und in Grün die Isochrone unter Berücksichtigung der neuen Wegeverbindung angezeigt.
<img class="img-responsive" src="../../img/Docs/training materials/Scenario_building/result-isochrone.png">







 