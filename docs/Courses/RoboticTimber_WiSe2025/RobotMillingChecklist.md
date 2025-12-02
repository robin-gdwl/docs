# Robot Milling Checkliste 

## Grasshopper 

<details>
<summary>Das Richtige Template nutzen </summary>
<ul>
  <li>[Robotic Milling Template 04 (Braunschweig)](https://drive.google.com/open?id=1BTYLmifNSKZzLOphXPaQaZf8orgWw2bb&usp=drive_fs)  </li>
  <li>Falls ihr eine ältere Version vom Template nutzt müsst ihr die "Start Spindle" Gruppe austauschen.   </li>
</details>

<details>
<summary>Roboter IP Prüfen</summary>
<ul>
  <li>Stellt sicher, dass der Roboter mit dem Netzwerk verbunden ist.  </li>
  <li>Prüft die IP-Adresse des Roboters in der info auf dem panel (Menü rechts oben -> "Info").  </li>
  <li>Verwendet diese IP-Adresse in Grasshopper  </li>
</details>

<details>
<summary>Referenzpunkte Festlegen und Einmessen</summary>
<ul>
  <li>Je nach Methode müssen zwischen 1 und 3 Referenzpunkte eingemessen werden.  </li>
  <li>Überlegt euch vorher, an welchen Features ihr eure Geometrie ausrichten wollt (Ecken, Mittelpunkte, Scanpoints etc.)  </li>
</details>

<details>
<summary>Roboter Simulation Abspielen und überprüfen</summary>
<ul>
  <li>Simulationsslider auf 0 stellen  </li>
  <li>"Play" Button in der "Robot Simulation" Komponente klicken  </li>
  <li>Simulation vollständig ablaufen lassen  </li>
    <li>Prüfen ob der Roboter Kollisionen mit der Geometrie oder der Umgebung hat  </li>
  <li>Falls es zu Kollisionen oder unerwarteten Drehungen kommt müssen zwischenpunkte hinzugefügt werden oder die Z-Achsen  Ausrichtung der Fräspfad planes angepasst werden. </li>
</details>

<details>
<summary>Roboter Simulation Abspielen und überprüfen</summary>
<ul>
  <li>Simulationsslider auf 0 stellen  </li>
  <li>"Play" Button in der "Robot Simulation" Komponente klicken  </li>
  <li>Simulation vollständig ablaufen lassen  </li>
    <li>Prüfen ob der Roboter Kollisionen mit der Geometrie oder der Umgebung hat  </li>
  <li>Falls es zu Kollisionen oder unerwarteten Drehungen kommt müssen zwischenpunkte hinzugefügt werden oder die Z-Achsen  Ausrichtung der Fräspfad planes angepasst werden. </li>
</details>

## Roboter 

<details>
<summary>Roboter einschalten und Bremsen lösen</summary>
  <ul>
  <li>Roboter einschalten</li>
  <li>unten links auf dem Bedienpanel den "Enable" Knopf (Roter Kreis) drücken</li>
  <li>Bremsen lösen (3PE Taste drücken und "Start" drücken)</li>
  </ul>
</details>

<details>
<summary>Linarachse einschalten </summary>
  <ul>
  <li>Drehschalter an der Steuerungsbox auf "AN" stellen</li>
  </ul>
</details>

<details>
<summary>Spindel einstecken und  einschalten </summary>
<ul>
<li>Starkstromkabel der Spindel in die Steckdose an der Wand stecken</li>
<li>Prüfen, ob der Stecker richtig sitzt </li>
<li>Warten bis die Steuerungsbox der Spindel grün leuchtet</li>
<li>Falls die Spindel nicht automatisch startet, den "Reset" Knopf an der Steuerungsbox drücken</li>
</ul>
</details>

<details>
<summary>Spindel einstecken und  einschalten </summary>
<ul>
  <li>Starkstromkabel der Spindel in die Steckdose an der Wand stecken</li>
  <li>Prüfen, ob der Stecker richtig sitzt </li>
  <li>Warten bis die Steuerungsbox der Spindel grün leuchtet</li>
  <li>Falls die Spindel nicht automatisch startet, den "Reset" Knopf an der Steuerungsbox drücken</li>
</ul>
</details>
