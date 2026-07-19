# Einstieg
Sobald die App aufgerufen wird, soll der User auf einer Liste mit Kunden landen. Die Liste soll 20 Einträge anzeigen und Pagination haben. Zudem sollen oben ein Freitextfeld zur Suche und später möglicherweise weitere Filter vorhanden sein. Rechts oberbald der Tabelle soll ein Button mit zwei Teilen stehen: Links "Neu" und rechts davon ein kleiner Arrow nach unten, welcher eine Navigation mit 3 Platzhalter haben soll.  

## Daten
Die Daten werden aus einem .json File mit folgendem Format geholt: 

{
  "nummer": "123456",
  "typ": "doppelmitglied",
  "name": "Max und Anna Muster",
  "nutzer": [
    { "vorname": "Max", "nachname": "Muster" },
    { "vorname": "Anna", "nachname": "Muster" }
  ],
  "adresse": { "strasse": "Strasse 1", "plz": "8717", "ort": "Benken" },
  "status": "gekuendigt",
  "status_datum": "2024-01-17"
}

In der Tabelle soll aber nur folgendes angezeigt werden: 

- nummer
- name
- Adresse.strasse
- Adresse.plz
- Adresse.ort
- status

Die Daten werden in @data/mitglieder.json gespeichert, aktuell ist darin nur das obige Beispiel erfasst. In Zukunft werden da aber unterschiedliche Fälle und ca. 50 Daten aufgeführt. 