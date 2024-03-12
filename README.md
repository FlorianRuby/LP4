# Lern-Periode 4

Florian Ruby

20.2 bis 2.4.2024

## Grob-Planung

1. Wo stehen Sie mit Ihren Noten? In welchen Modulen waren Sie besonders stark; in welchen sind die ungenügend? Welche davon sind besonders wichtig?
     Seit der letzten LP haben wir noch keine neuen NOten bekommen, deswegen stehen diese immernoch genau gleich.
3. Was hatten Sie sich am Ende von LP2 vorgenommen? Was war Ihr VBV? Wie könnten Sie diesen besonders gut üben?
     Am Ende der LP2 habe ich mir vorgenommen strikter bei dem Projekt zu sein und nicht von meinem originallen Projekt abzuweichen.
5. **Neu**: Was möchten Sie Neues lernen?
     Wie man mit Winforms arbeitet und grosse Mengen an Bilder mit dazugehörigen Daten in Winforms benutzen kann
7. Was wäre ein geeignetes Projekt für diese LP4?
     Flaggen Tiktaktoe 
## 20.2.2024

✍️ Heute habe ich mich für ein neues Projekt entschieden, ein Tiktaktoe bei welchem man Flaggen auf dem 3x3 Feld sieht und nie Namen der jeweiligen Ländern auschreiben muss zu welchen die Flaggen gehören, es sollte auch verschiedene Schwierigkeitsstufen geben. Nachdem ich mir Gedanken über mein Projekt gemacht habe, habe ich an der LB des Moduls 164 weitergearbeitet und bin jetzt etwa zur hälfte fertig. 

Ich habe mir überlegt das ich zuerst ein normales Tiktaktoe programmiere und danach and dem Flaggen Tiktaktoe arbeite. 

## 27.2.2024

- [X] Mit Winforms experimentieren
- [X] Felder erstellen mit Klick funktion
- [X] Sieger bestimmungsfunktion

| Testfall-Nummer | Ausgangslage (Given) | Eingabe (When) | Ausgabe (Then) | Erfüllt? |
| --------------- | -------------------- | -------------- | -------------- | -------- |
| 1 | VS mit winforms geöffnet | Objekte einfügen | Objekte erscheinen | X |
| 2 | Felder  | Klick auf Feld  |  Änderung der Farbe des Feldes oder signalisierung zu welchem Spieler das Feld gehört | X |
| 3 | 3 Felder in einer Reihe/Linie | Automatisch | Fenster das signalisiert wer gewonnen hat | X |

✍️ Heute habe ich die Grundbasis für das TicTacToe, sprich ein normales TicTacToe ohne Flaggen erstellt, welches ich mithilfe eines Youtube Videos geschafft habe. Ich kann jetzt alle verschiedenen Felder anklicken, ich sehe welcher Spieler die jeweiligen Felder angeklickt hat oder wer an der Reihe ist, man sieht nun wer gewonnen/verloren hat oder falls es ein Unentschieden gab und man sieht auch wer wie oft schon gewonnen hat. 

☝️ Vergessen Sie nicht, bis einen ersten Code auf github hochzuladen, und in der Spalte **Erfüllt?** einzutragen, ob Ihr Code die Test-Fälle erfüllt

## 05.03.2024

- [X] Entschieden welche Flaggen ich benutzen will (welche Länder, simplifizierte Versionen oder nicht etc.)
- [X] Alle Flaggen in gleicher Grösse und Qualität als Datei bekommen
- [X] Entscheiden zu welcher Schwierigkeit welche Flagge gehört (einfach, mittel, schwer)
- [X] Flaggen testweise in Winforms einfügen

| Testfall-Nummer | Ausgangslage (Given) | Eingabe (When) | Ausgabe (Then) | Erfüllt? |
| --------------- | -------------------- | -------------- | -------------- | -------- |
| 1 | Browser | Liste an Flaggen finden | Entscheidung für Flaggen (Liste) getroffen | Ja |
| 2 | Browser  | Suche nach Flaggen & falls nicht in richtiger Grösse = zuschneiden |  Flaggen Dateien in richtiger Grösse etc in einem Ordner | Ja |
| 3 | Flaggen Dateien | Einteilung | Flaggen Datei entweder in Ordner einfach, mittel oder schwer  | Ja |
| 4 | Flaggen Dateien | winforms code/Toolbox item | Flagge wird angezeigt |  |

✍️ Heute habe ich mich für alle Länder entschlossen, welche ich einbeziehen will. Ich habe mich für die 193 UN Mitgliedstaaten entschieden und habe darauf hin ein Dokument mit allen Ländern Alphabetisch sortiert erstellt. Ich habe ausserdem auch jede einezelne Flagge heruntergeladen und dann diese nach der Schwierigkeit in entweder Einfach, Mittel oder Schwierig einsortiert. Ich habe dazu für jede einzelne Schwierigkeitsstufe ein Dokument erstellt mit den Namen der einzelnen Länder. Heute habe ich es allerdings nicht geschafft diese Flaggen bereits in Winforms einzufügen. 

## 12.03.2024

- [X] Flaggen testweise in Winforms einfügen
- [X] Flaggen und Flaggennamen als Array speichern und Zufallsgenerator für diese
- [X] Alle Flaggen in gleicher Grösse und Qualität in Winforms einfügen
- [X] Alle Flaggen in gleicher Grösse und Qualität in Winforms einfügen 

| Testfall-Nummer | Ausgangslage (Given) | Eingabe (When) | Ausgabe (Then) | Erfüllt? |
| --------------- | -------------------- | -------------- | -------------- | -------- |
| 1 | Alle Flaggen als einzelne Datei | Flagge in Winforms einfügen | Flagge erscheint | Ja |
| 2 | Flaggen und Länder als Liste + Zufallsgenerator  | Programm startet | Länder Name wird angezeigt | Nein |
| 3 | Flaggen und Länder als Liste + Zufallsgenerator | Programm startet | Länder Name **& Flagge** wird angezeigt  | Nein |
| 4 | Flaggen und Länder als Liste + Zufallsgenerator | Programm startet | Länder Name **& Flagge** wird angezeigt  | Nein |

✍️ Heute habe ich mich um die Implementierung des Zufallsgenerator und der Flaggen gekümmert, ich habe den ganzen Code geschrieben und er sollte in der Theorie eigentlich auch funktionieren aber meine PictureBox's zeigen bisher noch keine Flagen an. Ich werde mich beim nächsten mal darum kümmern diesen Fehler zu beheben.

## 19.03.2024

- [ ] Flaggen werden angezeigt
- [ ] Flaggen werden angezeigt
- [ ] Box in welcher man Namen der Flagge eingeben kann
- [ ] Check ob der Name richtig oder Falsch ist 

| Testfall-Nummer | Ausgangslage (Given) | Eingabe (When) | Ausgabe (Then) | Erfüllt? |
| --------------- | -------------------- | -------------- | -------------- | -------- |
| 1 | Flaggen und Länder als Liste + Zufallsgenerator | Programm startet | Flagge erscheint automatisch |  |
| 2 | Flaggen und Länder als Liste + Zufallsgenerator | Programm startet | Flagge erscheint automatisch |  |
| 3 | Flaggen werden angezeigt | neues Box fenster | Ländernamen sind eingebbar  |  |
| 4 | Flaggen werden angezeigt | Name eingeben | Richtiger/Falscher Name wird erkannt  |  |

## Reflexion

Formen Sie Ihre Zusammenfassungen in Hinblick auf Ihren VBV zu einem zusammenhängenden Text von 100 bis 200 Wörtern (wieder mit Angabe in Klammern).
