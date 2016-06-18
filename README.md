# Modul-133-Blog
Dies ist eines der Projekte, die ich im Modul 133 an der gibb erstellt habe. Es ging darum mithilfe von PHP einen Blog zu realisieren. Die Einträge sollten dabei in einer Datei oder in einer SQLite-Datenbank gespeichert werden. Ich persönlich habe es mit einer SQLite-Datenbank gelöst.

## Systemanforderungen
* PHP-Version 5.5+
* mod_rewrite

## Funktionen
Der Blog verfügt über die folgenden Funktionen:

* Registrierung von neuen Benutzern
* Ein- und ausloggen von Benutzern
* Anzeigen der Blog-Einträge, absteigend sortiert
* Eingeloggte Benutzer können Einträge verfassen
* Eigene Einträge können bearbeitet und gelöscht werden
* Erstellen von Kommentaren bei Fremden Einträgen
* Eigene Kommentare löschen
* Administrator kann Benutzer löschen
* Administrator kann Benutzer zu Admins befördern

## Verwendete Frontend-Bibliotheken
* jQuery
* Bootstrap CSS

## Standard-Benutzer
Benutzername         |  Passwort     | Admin
---------------------|---------------|------
root                 | root          | Ja
john.doe             | Test          | Nein
benutzer@benutzer.ch | qwertzuiopP1$ | Nein
admin@admin.ch       | qwertzuiopP1$ | Ja

## Aufbau / Struktur
Nachfolgend ist die Ordnerstruktur des Blogs erklärt:

* Assets/
  * Dateien für das Frontend (CSS, JS, Fonts)
* Core/
  * Hauptbestandteil des Codes. Hier befinden sich die Hauptklassen die den Blog antreiben.
* Database/
  * Hier befindet sich die Datenbankdatei für SQLite.
* Views/
  * Hier befinden sich die Views die dann für den Benutzer sichtbar sind.

## Installation
1. Das Repository klonen.
2. Einstellungen in config.php anpassen.
