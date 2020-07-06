---
title: Szenarien - Wege
permalink: /de/tutorials/scenario-ways/
lang: de
---

#### Beschreibung des Features
GOAT ermöglicht die Entwicklung eigener Szenarien, wie z.B. Modifikation des Netzwerks oder Bau einer neuen Brücke. Das entwickelte Szenario kann zu dem aktuellen Netzwerk hinzugefügt und Änderungen der Erreichbarkeit durch Isochronen bewertet werden. 

#### Mögliche Anwendungsfälle (Planungsfragen)
- Wie verändert sich die Erreichbarkeit durch den Bau einer neuen Fahrradbrücke über einen Fluss?
- Wie verändert sich die Erreichbarkeit mit dem Rohlstuhl durch den Bau einer barrierefreien Wegeverbindung? 
- Welche Variante eines neuen Radweges erschließt die höchste Anzahl an Anwohner?



#### Schritt-für-Schritt-Anleitung für eine beispielhafte Planungsaufgabe
##### 1 Szenario zu neuer Fahrradbrücke
###### 1.1 Planungsfrage
Wie verändert sich die Erreichbarkeit durch den Bau einer neuen Fahrradbrücke über einen Fluss? 
###### 1.2 Arbeitsschritte
1. Gehen Sie in das Fenster zur Szenarienentwicklung und wählen Sie den „Wege“ Layer.  
<img class="img-responsive" src="../../img/Docs/training materials/Scenario_building/scenario_ways.png" style="height:150px;">


2. Zoomen Sie zu der Stelle, an der Sie eine neue Fahrradbrücke bauen wollen und wählen Sie mittels des Kreis-Werkzeuges das umliegenden Straßennetz aus.  
<img class="img-responsive" src="../../img/Docs/training materials/Scenario_building/circle_scenario.png" title="Kreis-Werkzeug">

3. Zeichnen Sie an der gewünschten Stelle eine neue Wegeverbindung, wählen als Wegetyp „Brücke“ aus und klicken Sie auf „Speichern“. Die gezeichneten Wege werden nun rechts in der Tabelle aufgeführt. Um diese Wege in die Datenbank zu integrieren, müssen diese über den Button „Hochladen“ hochgeladen werden.  
<img class="img-responsive" src="../../img/Docs/training materials/Scenario_building/bridge_building.png">

4. Nun können Sie die Auswirkung der neuen Wegeverbindung auf die Erreichbarkeit analysieren, indem Sie sich die Standard- und die Scenario-Isochrone berechnen lassen. Wählen Sie hierzu den Routingmodi „Fahrrad“ aus und setzen den Berechnungsmodus auf „Standard und Scenario“.  
<img class="img-responsive" src="../../img/Docs/training materials/Scenario_building/modified_network.png">

5. Platzieren Sie den Startpunkt für die Isochronenberechnung in der Nähe der neuen Brücke. Als Ergebnis wird Ihnen in Rot die Isochrone in der Ausgangslage und in Grün die Isochrone unter Berücksichtigung der neuen Wegeverbindung angezeigt.  
<img class="img-responsive" src="../../img/Docs/training materials/Scenario_building/result-isochrone.png">

