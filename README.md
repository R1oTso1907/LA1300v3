
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
Als ein 🤷‍♂️ möchte ich 🤷‍♂️, damit

| US-№          |Verbindlichkeit|    Typ  |Beschreibung       |
| ------------- | ------------- |---------|-----------        |
|1   | Muss  |   funktional      |Als Spieler möchte ich eine Zahl haben, damit ich die erraten kann.  |
| 2 | Muss  |   Funktional      |  Als Spieler möchte ich Zahlen eingeben, damit ich die generierte Zahl raten kann. |
|3  | Muss  |   Funktional    | Als Spieler möchte ich genau wissen, wie weit ich von der Zahl entfernt bin, damit ich mehrmals raten kann, um dann die richtige Zahl zu erraten.|
| 4 | Muss  |Funktional  | Als Spieler möchte ich eine Meldung erhalten, wenn ich die richtige Zahl errate, damit ich merke, dass ich richtig geraten habe.                  |
|5  | Muss  |Funktional | Als Spieler möchte ich wissen, wie viele Versuche ich gebraucht habe, damit ich mich verbessern kann.   |
| 6| Muss  |Funktional|Als Spieler möchte ich auf Fehler hingewiesen werden, damit Fehleingaben vermieden werden.  |


✍️ Jede User Story hat eine ganzzahlige Nummer (1, 2, 3 etc.), eine Verbindlichkeit (Muss oder Kann?), und einen Typ (Funktional, Qualität, Rand). Die User Story selber hat folgende Form: *Als ein 🤷‍♂️ möchte ich 🤷‍♂️, damit 🤷‍♂️*.


### 1.3 Testfälle

| TC-№  | Ausgangslage |Eingabe |  Erwartete Ausgabe     |                   
| ------| ------------- |-------|  -----------------     |
| 1.1| Zahl eingeben  |  34     | Die eingegebene Zahl ist zu hoch/niedrig                       |            
| 1.2| Zahl eingeben  |e       |  Falsche Eingabe. Bitte geben sie eine Zahl zwischen 1 und 100 ein            |
| 1.3| Zahl eingeben  |  37     | Das ist die Korrekte Zahl                      |            
| 2.1| Es wirde korrekt geraten  |64       | Das ist die korrekte Zahl            |


✍️ Die Nummer hat das Format `N.m`, wobei `N` die Nummer der User Story ist, die der Testfall abdeckt, und `m` von `1` an nach oben gezählt. Beispiel: Der dritte Testfall, der die zweite User Story abdeckt, hat also die Nummer `2.3`.



## 2 Planen


| AP-№ | Frist |Zuständig|Beschreibung|geplante Zeit |
|
| -------| ----- |---------| -----------| ------------ |
| Content| Conten|      d   |   d         |    d          |
| Content| Conten|      d   |        d    |   d           |
| Content| Conten|       d  |       d     |    d          |


Total: 


✍️ Die Nummer hat das Format `N.m`, wobei `N` die Nummer der User Story ist, auf die sich das Arbeitspaket bezieht, und `m` von `A` an nach oben buchstabiert. Beispiel: Das dritte Arbeitspaket, das die zweite User Story betrifft, hat also die Nummer `2.C`.


✍️ Ein Arbeitspaket sollte etwa 45' für eine Person in Anspruch nehmen. Die totale Anzahl Arbeitspakete sollte etwa Folgendem entsprechen: `Anzahl R-Sitzungen` ╳ `Anzahl Gruppenmitglieder` ╳ `4`. Wenn Sie also zu dritt an einem Projekt arbeiten, für welches zwei R-Sitzungen geplant sind, sollten Sie auf `2` ╳ `3` ╳`4` = `24` Arbeitspakete kommen. Sollten Sie merken, dass Sie hier nicht genügend Arbeitspakte haben, denken Sie sich weitere "Kann"-User Stories für Kapitel 1.2 aus.


## 3 Entscheiden


✍️ Dokumentieren Sie hier Ihre Entscheidungen und Annahmen, die Sie im Bezug auf Ihre User Stories und die Implementierung getroffen haben.


## 4 Realisieren


| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |

| ---- | ----- | --------- | ------------- | ----------------- |

| 1.A  |       |           |               |                   |

| ...  |       |           |               |                   |


✍️ Tragen Sie jedes Mal, wenn Sie ein Arbeitspaket abschließen, hier ein, wie lang Sie effektiv dafür hatten.


## 5 Kontrollieren


### 5.1 Testprotokoll


| TC-№ | Datum | Resultat | Tester |

| ---- | ----- | -------- | ------ |

| 1.1  |       |          |        |

| ...  |       |          |        |


✍️ Vergessen Sie nicht, ein Fazit hinzuzufügen, welches das Test-Ergebnis einordnet.


### 5.2 Exploratives Testen


| BR-№ | Ausgangslage | Eingabe | Erwartete Ausgabe | Tatsächliche Ausgabe |

| ---- | ------------ | ------- | ----------------- | -------------------- |

| I    |              |         |                   |                      |

| ...  |              |         |                   |                      |


✍️ Verwenden Sie römische Ziffern für Ihre Bug Reports, also I, II, III, IV etc.


## 6 Auswerten


✍️ Fügen Sie hier eine Verknüpfung zu Ihrem Lern-Bericht ein.
