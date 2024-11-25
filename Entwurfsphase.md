## Zielplattform 

- Inhalt: Struktur des Systems und Aufteilung in Komponenten
Ungefähr eine bis zwei Seiten
- OSGi Framework
- Applikationsserver: Apache Karaf. Basiert auf OSGi bzw. verwendet OSGi als Kerntechnologie. Ermöglicht sogenannte Hot Deployments -> Installation, Aktualisierung und Entfernung von Bundles zur Laufzeit. Verwaltung von Bundles im Feature-Management (Features-Modul).

- keine Standalone-Applikation, sondern eine Erweiterung der Anwendungsmodule.
- DB-System Postgres. Datenbankversionierung wird mit Liquibase durchgeführt. Was ist liquibase? Wieso ist es wichtig, Datenbanken zu versionieren?
- Java als Programmiersprache. OSGi (Open Services Gateway Initiative) -> Modularisierung-Framework für Java zur Unterteilung von Code in Module bzw. In diesem Teil soll beschrieben werden, was OSGi ist und welche Vorteile es mit sich bringt.
- Eventuell noch CLI von Karaf erwähnen.
- Docker: Die Anwendung und die Datenbank werden in getrennten Docker Containern bereitgestellt

## Architekturdesign

- Backend: Modulare Architektur (API, Service und Parent). IAM - System zur Authentifizierung, Autorisierung und Benutzerverwaltung
- Frontend: ZK Frameworks
- ORM (Eclipselink und Jakarta (früher javax)): Mapping von Datenbanktabellen und Entitäten
- Entitäten werden vom DAO Handler gekapselt und als DTO-Klassen zurückgegeben (DAO - Data access object, DTO - Data transfer object)

## Entwurf der Benutzeroberfläche

- Auf Prototyp der Benutzeroberfläche verweisen
- Einfache Bedienung und gleich am Dashboard ersichtlich
- Der Anmeldeverlauf wird beim Betätigen des entsprechenden Schalters eingeblendet
- Tabellenform: Anmeldeeinträge in tabellarischer Form mit Datum, IP-Adresse und Client-Informationen, absteigend

## Datenmodell

- Verweis auf erstelltes Datenmodell und Auflistung der Entitäten
- Warum wurden genau diese Tabellen erstellt?

## Geschäftslogik

- Verweis auf Klassendiagramm. Beschreibung der Zuständigkeiten von jeder Klasse.

## Maßnahmen zur Qualitätssicherung (optional)


## Pflichtenheft / Datenverarbeitungskonzept
Verweis auf Pflichtenheft im Anhang
