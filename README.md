# Lebendiger Adventskalender Marienthal

Interaktive Karte für den Nachbarschafts-Adventskalender in Hamburg-Marienthal (1.–24. Dezember).
Jeder Stern steht für ein Türchen. Ein Klick zeigt Adresse, Gastgeber und Uhrzeit.

## Adressen ändern
Die Daten stehen in `index.html` im Block `<script type="application/json" id="advent-data">`.
Pro Türchen: `street`, `host`, `from`, `to`, `note` sowie die Kartenposition `x`/`y`.

Positionen bequem setzen: Seite mit `#admin` am Ende der Adresse öffnen, Sterne verschieben,
„Als JSON kopieren“ klicken und den Inhalt in den Datenblock einfügen.
