# Robot Program Template

Das Robot Program Template ist eine Grasshopper Definition die Bausteine zum Erstellen von Roboterprogrammen in Grasshopper beinhaltet.
In den folgenden Tutorials seht ihr einen Überblick darüber wie ihr das Template Nutzen könnt und erklärungen zu den verschiedenen Gruppen.
Das Template kann über diesen Link herunter geladen werden: 
[RobotProgramTemplate_03.gh](https://drive.google.com/open?id=1SsbWhpt9Ixfm1ay0z9v5edq3FKKxWsxn&usp=drive_fs)

______
![Robot Program Template Canvas Overview](/RobotProgramTemplate_03.gh.png)

### Teil 1: Setup 
<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/Jcs14sc_ZFg?si=-tSmyixQ81Ex4ePj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

**Checkliste**

- Roboter-IP-Adresse in Grasshopper festlegen.
- Korrekte Roboter Modell in Grasshopper auswählen.
- Simulations-Schieberegler auf Null setzen.
- Startpose festlegen, indem Gelenkwerte vom Roboter-Pendant (Registerkarte "Move" / "Bewegen") übernommen werden.
- (Optional) Umgebung im Rhino/Grasshopper modellieren.
- Werkzeug-TCP (Position und Orientierung) mit der Messfunktion des Roboters messen.
- Gemessenen TCP als Standard-TCP auf dem Roboter-Pendant festlegen.
- In Grasshopper die Position des Werkzeugs abrufen
- TCP-Daten von der Roboter-Komponente kopieren.
- TCP-Daten in der Werkzeugdefinitionsgruppe einfügen.


### Teil 2: Orient
<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/9BAcOcc4xtM?si=37ALhHSh7vH5JmVj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

**Checkliste**

- Werkzeug-TCP in Grasshopper festlegen
- Den Roboter mit dem TCP-Taster oder dem Tool selbst zum neuen Ursprungspunkt (linke obere Ecke der Zeichenfläche) bewegen.
- Roboterposition abrufen (Get Robot Data) und diese Werte kopieren
- Die Positionsdaten in das entsprechende Feld in Grasshopper einfügen.
- Für den Punkt rechts und den Punkt nach unten wiederholen.
- Die erstellten Werte verwenden, um eine neue Orientierungsebene zu erstellen
- Korrekten Quadranten der Geometrie in Bezug auf das Basiskoordinatensystem sicherstellen.
- Bei Bedarf Grundgeometrie verschieben


### Teil 3: Send to Robot
<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/PxDVQCtc5ak?si=3wUyL0x-ksVh6Yh9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

**Checkliste**

- Korrekte Ebene/Kurve auswählen
- Kurventeilung-Geometrietyp auswählen
- Kurventeilung überprüfen
- Ebene spiegeln (falls erforderlich).
- Rückzüge hinzufügen, indem die erste und die letzte Ebene versetzt werden.
- Tiefe einstellen, um Kontakt zu verhindern oder herzustellen.
- Werkzeuggeschwindigkeit auf einen sicheren Wert einstellen.
- Blendradius für Glätte einstellen.
- Ziel bei Bedarf drehen
- Auf Fehler überprüfen und diese im Roboterprogramm beheben.
- Simulation überprüfen
- Roboter in den Remote-Modus setzen.
- Einen eindeutigen Programmnamen erstellen.
- Programm auf den Roboter hochladen.
- Roboter wieder in den Local-Modus setzen.
- Sicherstellen dass das neue Programm geladen wurde
- Programm ausführen
- Testen und korrigieren
- Wiederholen.

Bei Fragen meldet euch gerne per mail. 