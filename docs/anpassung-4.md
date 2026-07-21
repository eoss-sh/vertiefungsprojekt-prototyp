# Anpassung 4 - Doppelnamen
Verwandte Konzept-Annahme (KA): 6

Die Erfassung des Doppelnamens soll initial vom System gemacht werden und der User soll diese danach überschreiben können.

## Umsetzung
Die User haben im Schritt 1 des Falls Doppelmitgliedschaft jeweils vergessen, den Namen des Doppelmitglieds zu erfassen. Daher soll dieser name erstmals automatisch generiert werden. Die Generierung soll wie folgt passieren: 

## Anrede
Nutzer 1 - Frau + Nutzer 2 - Herr = Frau und Herr
Nutzer 1 - Frau + Nutzer 2 - Frau = Frauen
Nutzer 1 - Herr + Nutzer 2 - Herr = Herren
Nutzer 1 - Mann + Nutzer 2 - Frau = Herr und Frau

## Name
Vorname Nutzer 1 & " " & Nachname Nutzer 1 & " " & und & " " & Vorname Nutzer 2 & " " & Nachname Nutzer 2

Sobald etwas im Feld des Namens steht, soll dieses nicht mehr aktualisiert werden. Die Aktualisierung soll erst passieren, wenn alle vier Felder (Nutzer 1 Vor- und Nachname + Nutzer 2 Vor- und Nachname) ausgefüllt sind und das Feld Doppelname noch leer ist.