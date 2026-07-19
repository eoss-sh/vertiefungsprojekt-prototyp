# Neuerafassung
Die Neuerafssung soll über den "Neu" Button gestartet werden. Nach dem Klick soll ein Modal aufgehen, welches einige Funktionen hat: 

1. Der User tippt die Daten in Freitext "Max Muster"
2. Sofort sind drei Optionen unter der Eingabe oben verfügbar: 
    - Erafssung Mitgliedschaft "Eingabe"
    - Erfassung Doppelmitgliedschaft "Eingabe"
    - Erfassung Firmenmitgliedschaft "Eingabe"
3. Darunter soll Kundenliste gefiltert werden und treffer anzeigen, die mit der Eingabe des Users übereinstimmen. Wir wollen wir aber eine grosse Kundeliste simulieren und daher soll eine künstliche Pause von 500ms eingebaut werden - erst danach sollen die Kundentreffer, die passen angezeigt werden.
4. keine Option soll automatisch ausgewählt werden, der user kann mit Tastatur (Pfeile und Enter) oder mit der Maus eine Auswahl treffen
5. Danach soll ein Multi Step Wizard gestartet werden, die Daten sollen übernommen werden - erste Eingabe als Vornahem, zweite Eingabe als Nachname. Im moment soll das aber nur auf einer neuen Unterseite /neuaufnahme als Text angezeigt werden. Der Multi Step Wizard folgt dann in den folgenden Schritten. Der Schritt ein s Des Wizards ist die Daten erafssung und die Maske ist je nach Fall oben (Einzelmitgliedschaft, Doppelmitgliedschaft und Firmenmitgliedschaft) unterschiedlich sein - dies für das Setups des ersten Steps. 

Das gleiche modal soll auch mit Command + K geöffnet werden könnten. 
Ebenfalls haben wir auf dem Arrow-Menü mit den Drei Dummy Einträgen Links - diese sollen den obigen drei Einträgen Mitgliedschaft, Doppelmitgliedschaft oder Firmenmitgliedschaft entpsrechen. 

Als Referenz habe ich unter ./picker.png ein Bild des Wireframes angefügt. 