# mission-morgenstart

Bosses Aufsteh und Fertigmach Helfer

Gamifizierte Morgen-Checkliste als Web-App (GitHub Pages + Firebase Firestore für den Abgleich zwischen mehreren Geräten).

- `index.html` – die App (eine Datei, kein Build-Schritt)
- `vendor/` – Firebase JS SDK 10.12.2 (compat-Builds, aus dem npm-Paket `firebase`)
- `audio/` – NASA-Originalaufnahmen (gemeinfrei, via Wikimedia Commons): Apollo 8 Liftoff, Apollo 11 „The Eagle has landed“ und „One small step“, Apollo 13 „Houston, we've had a problem“
- `firestore.rules` – Zugriffsregeln für Firestore (in der Firebase-Konsole unter Firestore → Regeln einfügen)

Persönliche Angaben (Name des Kindes, Medikamentennamen) stehen nicht im Code, sondern werden in der App eingetragen und nur in Firestore gespeichert.
