
# Projekt-Dokumentation
Ensar Yildirim

| Datum  | Version |Zusammenfassung|
| ------------- | ------------- |-----|
| 16.08.2023 | |   Ich habe meine Kenntnisse in C# wieder aufgefrischt und mich erneut damit beschäftigt.|
| 23.08.2023 | 0.0.1 |Ich habe damit begonnen, zu codieren.|
|30.08.2023|1.0.0| Die Programmierung wurde abgeschlossen.|


## 1 Informieren


### 1.1 Ihr Projekt



"Number Guessing" ist ein spannendes Projekt, bei dem man versucht, die geheimnisvolle Zahl durch kluge Vermutungen zu enthüllen.

### 1.2 User Stories

| US-№          |Verbindlichkeit|    Typ  |Beschreibung       |
| ------------- | ------------- |---------|-----------        |
|1   | Muss  |   funktional      |Als Spieler möchte ich eine Zahl haben, damit ich die erraten kann.  |
| 2 | Muss  |   Funktional      |  Als Spieler möchte ich Zahlen eingeben, damit ich die generierte Zahl raten kann. |
|3  | Muss  |   Funktional    | Als Spieler möchte ich genau wissen, wie weit ich von der Zahl entfernt bin, damit ich mehrmals raten kann, um dann die richtige Zahl zu erraten.|
| 4 | Muss  |Funktional  | Als Spieler möchte ich eine Meldung erhalten, wenn ich die richtige Zahl errate, damit ich merke, dass ich richtig geraten habe.                  |
|5  | Muss  |Funktional | Als Spieler möchte ich wissen, wie viele Versuche ich gebraucht habe, damit ich mich verbessern kann.   |
| 6| Muss  |Funktional|Als Spieler möchte ich auf Fehler hingewiesen werden, damit Fehleingaben vermieden werden.  |




### 1.3 Testfälle

| TC-№  | Ausgangslage |Eingabe |  Erwartete Ausgabe     |                   
| ------| ------------- |-------|  -----------------     |
| 1.1| Zahl eingeben  |  34     | Die eingegebene Zahl ist zu hoch/niedrig                       |            
| 1.2| buchstabe eingegeben  |e       |  Falsche Eingabe. Bitte geben sie eine Zahl zwischen 1 und 100 ein            |
| 1.3| Zahl eingeben  |  37     | Anzahl Versuche                     |            
| 2.1| Es wirde korrekt geraten  |64       | Das ist die korrekte Zahl            |





## 2 Planen


| AP-№ | Frist |Zuständig|Beschreibung|geplante Zeit |
| -------| ----- |---------| -----------| ------------ |
| 1.A    | 23.08.2023|Ensar Yildirim|  zufällige Zahl generieren|    15 min     |
| 2.A| 23.08.2023|      Ensar Yildirim   |Zahl eingeben können|   15 min           |
| 3.A| 23.08.2023|       Ensar Yildirim  |   genauere Informationen zu den geratenen Zahlen (Wie weit es entfernt ist)|    55 min|
| 4.A| 23.08.2023|      Ensar Yildirim   |    überprüfen ob Zahl richtig ist      |25 min|
| 5.A| 23.08.2023|      Ensar Yildirim   |     Versuche zählen|   20 min         |
| 6.A| 23.08.2023|       Ensar Yildirim  |      Fehler abfangen|    25 min       |

Total: 145 min




## 3 Entscheiden
Ich halte an meinem aktuellen Plan fest und werde mich bemühen, die Anforderungen umzusetzen.



## 4 Realisieren


| AP-№	  | Datum |Zuständig|geplante Zeit|tatsächliche Zeit|
| --------| ----- |-------- |------------ |---------------- |
| 1.A | 23.08.2023| Ensar Yildirim        | 15 min          |  10 min               |
| 2.A | 23.08.2023 | Ensar Yildirim        | 15 min           |   10 min             |
| 3.A | 23.08.2023| Ensar Yildirim        | 55 min          |  70 min               |
| 4.A | 23.08.2023 | Ensar Yildirim        | 25 min           |  20 min              |
| 5.A | 23.08.2023| Ensar Yildirim        | 20 min          |  15 min               |
| 6.A | 23.08.2023 | Ensar Yildirim        | 25 min           |  20 min              |




## 5 Kontrollieren


### 5.1 Testprotokoll


|  TC-№	  | Datum  |Resultat|
| ------------- | ------------- | ---------------|
| 1.1  |30.08.2023   |   OK             |
| 1.2| 30.08.2023   |    OK            |
| 1.3  | 30.08.2023   |  OK              |
| 2.1|30.08.2023   |     OK           |



Beim Testen habe ich keine Fehler gefunden. Alles lief nach Plan.



