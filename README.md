# Hausarbeit-Java
Moin, bitte um hillfe zur fehlerlösung bei meiner Hausarbeit

Das hier ist eine nicht geordneter nach keinen Richtlinien geführter Versuch von jemandem mit wenig Erfahrung der eine Hausarbeit schreiben soll.
Es soll auch erstmal nur laufen können. Symantik, Richtigkeit etc. krieg ich nichtmehr hin.
Es ist alles in einem Packet und wurde anfangs nach Control Model View geschrieben aber halbwegs aufgegeben dank unverständniss meienrseits.

Es soll eine Grafische Oberfläche entstehen mit einem Eingabefenster, Einem Ablaufsfesnter. Zellen sollen hierbei Generation durchleben udn je 
nach Anzahl lebender Nachbarn altern, sterben oder wiedergeboren werden.
Es ist zuschaltbar ob die Nachbarschaft am Ende auf der anderen Seite fortläuft und ob die Felder zufällig belegt werden oder manuell.
Die Überlebensregel sagt wieviele Nachbarn ein Überleben sichern
Sterberegel eben andersrum
Beim Altern wird die Farbe schrittweise von Rot nach Blau geändert

Die Codeschnipsel sollten so eigentlich vorhanden sein.
Das Problem derzeit ist das nach Wechsel von Eingabedialog zum Generationsfenster keine Zellen gezeichnet werden.
Habe nachgeschaut und aus unersichtlichen Günden haben die Zellen ein alle ein Alter von -1 was Tod bedeutet obwohl welche leben sollten.
Auch ist die Farbe die ich eigentlich mit 3 RGB Werten eingebe pro Zelle bei allen -1

Bei die MausListener um Manuel die Zellen zu Plazieren weiß ich nicht genau wie das am besten realisiert werden soll. 
