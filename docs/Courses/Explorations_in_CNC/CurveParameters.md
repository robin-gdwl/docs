# Curve Parameters

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/5qHz0eRNOwA?si=P6SrEFpPLunuqYoU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>


## Kurvenparameter

Ein Kurvenparameter ist ein Wert, der verwendet wird, um einen bestimmten Punkt auf einer Kurve zu evaluieren oder zu lokalisieren. Er muss innerhalb der Kurven-Domain liegen, welche den gültigen Wertebereich der Parameter für diese Kurve definiert.  
Parameter ermöglichen es, die Kurve zu analysieren und mit ihr zu interagieren, indem Werte innerhalb der Domain auf Positionen entlang der Kurve abgebildet werden. Wenn eine Kurve reparametrisiert wird, wird ihre Domain normalisiert und reicht von 0 bis 1, was die Arbeit mit Parametern erleichtert, unabhängig von der ursprünglichen Domain oder Länge der Kurve.

## Zusammenhang zwischen Kurvenparameter und Kurvenlänge

Der Kurvenparameter und die Kurvenlänge stehen zwar in Beziehung, sind aber nicht dasselbe. Der Kurvenparameter gibt eine Position entlang der Kurve innerhalb der ParameterDomain an, was nicht unbedingt der tatsächlichen Entfernung entlang der Kurve (Länge) entspricht. Selbst nach der Reparametrisierung der Kurve auf eine Domain von 0 bis 1 entspricht ein Parameterwert wie 0,5 nicht immer dem Mittelpunkt der Kurve in Bezug auf die physische Länge.  
Um den tatsächlichen Mittelpunkt oder Teilsegmenten zu finden, muss man die Kurvenlänge an einem bestimmten Parameter auswerten oder spezielle Komponenten wie „Evaluate Length“ oder „Curve Middle“ verwenden. 
Der Parameter ist somit eine normalisierte Koordinate zur Lokalisierung von Punkten, misst aber nicht direkt die Entfernung entlang der Kurve.  

___ 
