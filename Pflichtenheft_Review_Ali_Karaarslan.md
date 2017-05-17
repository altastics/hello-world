# Pflichtenheft Review von Ali Karaarslan
Verbesserungen (wie z.B. Rechtschreibfehler verbessert oder Wörter hinzugefügt) habe ich als **Fett** markiert.

## 2 Produkteinsatz
- Gute Einleitung, kurz und knapp (im positiven Sinne)
### 2.1 Beschreibung des Problembereichs
- Zeile 12: Einige Grammatikfehler: "Das Spiel besteht aus einem quadratischen Spielfeld mit wählbarer Anzahl **an** Feldern,...". Der Satz "Außerdem haben an den Rand angrenzende Felder je zwei Startpositionen pro anliegendem Rand." klingt irgendwie komisch.
- Sonst ist alles gut.

### 2.2 Glossar
- Zeile 33: "..., oder sich **regelwidrig** verhalten hat."
- Zeile 66: "...vor dem **letzten** Spielzug des Spieles..."
- Zeiel 105: "...oder sie die **letzte** nicht wegen Disqualifikation ausgeschiedene Figur ist."
- Zeile 114: "Hierzu ist ihm genau eine Spielfigur **zugeordnet**."

Insgesamt sehr gut, hier und da ein paar Rechtschreibfehler ;)

## Produkteinsatz, Modell des Problembereichs

### 2.3 Modell des Problembereichs
 - Sehr gut gemacht, deckt die Aufgaben des Tsuro-Spiels vollständig und verständlich ab.
#### 2.3.1 Tsuro Spiel
- Zeile 16: "Des weiteren **gehört** zu einer Figur eine Startposition, von welcher aus die Figur einen Pfad beschreitet."
#### 2.3.3 Engine und Clients
- Zeile 27: **KI** Teilnehmer statt AI Teilnehmer.

## Produkteinsatz Prozesse
### 2.4 Geschäftsprozesse
- Man könnte vom Zustand "betroffene Spieler entfernen" direkt ein Fluss zum Entscheidungsknoten führen, welches [mehrere **gewinnen**] und [einer der Spieler gewinnt] als Flüsse hat, und so den Entscheidungsknoten davor sparen, falls das von euch besser angesehen wird. Sonst ist alles sehr gut.

#### 2.4.1 Beschreibung der Geschäftsprozesse
- Gut und konsistent zum Aktivitätendiagramm beschrieben.

## 3 Produktfunktionen

### 3.1 Spielekonfigurator
- Zeile 5: "Der Spielkonfigurator ist eine eigenständige Komponente und wird als **unabhängiges** Programm geliefert."
- Use Case Spielekonfigurator simpel und gut gehalten.
- GUI: Spielekonfigurator hält das Wichtigste in einem Fenster.

#### 3.1.1 Neue Konfigurationen erstellen und 3.1.2 Feld sperren
- Alles gut gemacht, konnte keine Fehler, Widersprüche oder ähnliches finden.

### 3.2 PC Beobachter

#### 3.2.1 Mit einem Server verbinden
- Beim Diagramm bei Abbildung 10 sollte es vielleicht noch möglich sein, wenn ein Verbindungsaufbau nicht erfolgreich ist, das ganze Prozess zu beenden und nicht solange nach einer gültigen Adresse eines Servers gefragt wird, bis eine gefunden wurde.

### 3.3 Smartphone-Teilnehmer
- Abbildung 14: Use-Case: Smartphone-Teilnehmer: Warum erbt denn der Smartphone-Teilnehmer vom PC-Beobachter? (Diese Transition wurde beim Modell des Problembereichs als erben bezeichnet, bei Use-Cases ist vielleicht etwas anderes gemeint?)

## 4 Produktcharakteristiken
### 4.2 Nicht-funktionale Anforderungen

- Alles sieht sehr gut und vollständig aus. Allerdings würde ich statt "Type" **Typ** schreiben, da der Rest ebenfalls auf Deutsch ist.
