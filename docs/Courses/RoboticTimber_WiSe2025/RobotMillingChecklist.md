# Robot Milling Checkliste 

## Grasshopper 

<details>
<summary>Das Richtige Template nutzen </summary>
  - [Robotic Milling Template 04 (Braunschweig)](https://drive.google.com/open?id=1BTYLmifNSKZzLOphXPaQaZf8orgWw2bb&usp=drive_fs)
  - Falls ihr eine ältere Version vom Template nutzt müsst ihr die "Start Spindle" Gruppe austauschen. 
</details>

<details>
<summary>Roboter IP Prüfen</summary>
  - Stellt sicher, dass der Roboter mit dem Netzwerk verbunden ist.
  - Prüft die IP-Adresse des Roboters in der info auf dem panel (Menü rechts oben -> "Info").
  - Verwendet diese IP-Adresse in Grasshopper
</details>

<details>
<summary>Referenzpunkte Festlegen und Einmessen</summary>
  - Je nach Methode müssen zwischen 1 und 3 Referenzpunkte eingemessen werden.
  - Überlegt euch vorher, an welchen Features ihr eure Geometrie ausrichten wollt (Ecken, Mittelpunkte, Scanpoints etc.)
</details>

<details>
<summary>Roboter Simulation Abspielen und überprüfen</summary>
  - Simulationsslider auf 0 stellen
  - "Play" Button in der "Robot Simulation" Komponente klicken
  - Simulation vollständig ablaufen lassen
    - Prüfen ob der Roboter Kollisionen mit der Geometrie oder der Umgebung hat
  - Falls es zu Kollisionen oder unerwarteten Drehungen kommt müssen zwischenpunkte hinzugefügt werden oder die Z-Achsen Ausrichtung der Fräspfad planes angepasst werden.
</details>

<details>
<summary>Roboter Simulation Abspielen und überprüfen</summary>
  - Simulationsslider auf 0 stellen
  - "Play" Button in der "Robot Simulation" Komponente klicken
  - Simulation vollständig ablaufen lassen
    - Prüfen ob der Roboter Kollisionen mit der Geometrie oder der Umgebung hat
  - Falls es zu Kollisionen oder unerwarteten Drehungen kommt müssen zwischenpunkte hinzugefügt werden oder die Z-Achsen Ausrichtung der Fräspfad planes angepasst werden.
</details>

## Roboter 

<details>
<summary>Roboter einschalten und Bremsen lösen</summary>
  - Roboter einschalten
  - unten links auf dem Bedienpanel den "Enable" Knopf (Roter Kreis) drücken
  - Bremsen lösen (3PE Taste drücken und "Start" drücken)
</details>

</details>