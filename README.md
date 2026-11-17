# Verstärkerboard

Verstärkerboard für die Klasse. Das Board läuft als Web-App in Safari auf dem iPad. Das Board braucht keine installierte App.

## Funktionen

- Jedes Kind hat eine Bahn mit einer Spielfigur. Die Spielfigur wandert von „Start“ zum Ziel „Schulhof“.
- „Alle ▶“ schiebt alle Kinder ein Feld weiter. „◀ Alle“ schiebt alle Kinder ein Feld zurück.
- Die Pfeile neben einem Namen schieben ein einzelnes Kind vor oder zurück.
- Ein Tipp in die Bahn rechts von der Spielfigur schiebt das Kind weiter. Ein Tipp links davon schiebt das Kind zurück.
- „↶“ macht den letzten Schritt rückgängig.
- Der Timer zählt jedes Intervall herunter. Am Ende ertönt ein Ton, und „Alle ▶“ blinkt.
- Optional schiebt der Timer alle Kinder automatisch weiter.
- Wenn alle Kinder im Ziel sind, zeigt das Board „Alle auf den Schulhof!“ mit Fanfare.

## Einstellungen (Zahnrad)

- Anzahl Felder: 6 bis 10.
- Minuten pro Feld: 1:00 bis 5:00. Das Board zeigt die Gesamtdauer an.
- Automatisch weiterschieben: ein oder aus.
- Ton: ein oder aus.
- Namen der Kinder: ein Name pro Zeile.
- „Neue Stunde“ setzt alle Kinder auf Start und setzt den Timer zurück.

## Datenschutz

Das Board speichert Namen und Positionen nur im Browser des iPads (`localStorage`). Die Namen stehen nicht im Repository und gehen nicht ins Internet.

## Auf dem iPad einrichten

1. Öffnen Sie die Adresse der Web-App (GitHub Pages) in Safari.
2. Tippen Sie auf „Teilen“.
3. Tippen Sie auf „Zum Home-Bildschirm“.
4. Starten Sie das Board über das neue Symbol auf dem Home-Bildschirm.

Nach dem ersten Öffnen funktioniert das Board ohne Internet.

**Wichtig:** Starten Sie das Board immer über dasselbe Symbol. Safari und das Home-Bildschirm-Symbol haben getrennte Speicher.

## Ton

iPadOS gibt Ton erst nach einer Berührung frei. Tippen Sie deshalb einmal auf „Start“. Schalten Sie den Stummschalter des iPads aus.

## Update

Erhöhen Sie nach jeder Änderung den Wert `VERSION` in `sw.js`. Das iPad lädt die neue Fassung beim nächsten Start mit Internet.
