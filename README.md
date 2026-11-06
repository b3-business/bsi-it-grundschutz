---
updatedAt: 2026-11-05T11:48:25.000Z
siteIndex: ./llms.txt
---

# IT-Grundschutz-Kompendium (Edition 2023)

Das IT-Grundschutz-Kompendium des BSI (Edition 2023, 6. Auflage) als Markdown-Repository: 111 IT-Grundschutz-Bausteine in 10 Baustein-Kategorien sowie einleitende und ergänzende Dokumente. Jede Datei ist ein eigenständiges Dokument; die Übersicht einer Baustein-Kategorie steht in deren `README.md`, die Struktur aller Bausteine in [struktur.md](struktur.md). Die Zuordnung der Anforderungen zu den elementaren Gefährdungen (Kreuzreferenz-Tabelle, KRT) steht am Ende jedes Baustein-Dokuments.

Abgerufen von der offiziellen BSI-Website: [BSI IT-Grundschutz-Kompendium Edition 2023](https://www.bsi.bund.de/DE/Themen/Unternehmen-und-Organisationen/Standards-und-Zertifizierung/IT-Grundschutz/IT-Grundschutz-Kompendium/it-grundschutz-kompendium_node.html) am 4. November 2026.

Einzelne Teile wurden automatisiert überarbeitet, um die Agent-gestützte Analyse und Verarbeitung zu erleichtern.
Dies betrifft insbesondere die KRT-Tabellen (Kreuzreferenz-Tabellen für elementare Gefährdungen). 
Überwiegend sind die Inhalte unverändert aus den offiziellen Dokumenten extrahiert.

## Aufbau

```
.
├── vorwort.md
├── neues-im-kompendium.md
├── it-grundschutz-basis-fuer-informationssicherheit.md
├── schichtenmodell-und-modellierung.md
├── rollen.md
├── glossar.md
├── elementare-gefaehrdungen.md
├── struktur.md
├── aenderungen-2023.md
├── errata-2023.md
├── iso-zuordnung.md
├── isms/  (1 Bausteine, Übersicht: isms/README.md)
├── orp/  (5 Bausteine, Übersicht: orp/README.md)
├── _con/  (9 Bausteine, Übersicht: _con/README.md)
├── ops/  (14 Bausteine, Übersicht: ops/README.md)
├── der/  (7 Bausteine, Übersicht: der/README.md)
├── app/  (20 Bausteine, Übersicht: app/README.md)
├── sys/  (25 Bausteine, Übersicht: sys/README.md)
├── ind/  (7 Bausteine, Übersicht: ind/README.md)
├── net/  (11 Bausteine, Übersicht: net/README.md)
└── inf/  (12 Bausteine, Übersicht: inf/README.md)
```

## Baustein-Kategorien

| Kategorie | Bausteine | Kurzbeschreibung |
|---|---|---|
| [ISMS Sicherheitsmanagement](isms/README.md) | 1 | Übersicht über den einzigen IT-Grundschutz-Baustein der Kategorie „ISMS Sicherheitsmanagement“ mit Titel und Verweis auf den Baustein. |
| [ORP Organisation und Personal](orp/README.md) | 5 | Übersicht über die 5 IT-Grundschutz-Bausteine der Kategorie „ORP Organisation und Personal“ mit Titel und Verweisen auf die einzelnen Bausteine. |
| [CON Konzepte und Vorgehensweisen](_con/README.md) | 9 | Übersicht über die 9 IT-Grundschutz-Bausteine der Kategorie „CON Konzepte und Vorgehensweisen“ mit Titel und Verweisen auf die einzelnen Bausteine. |
| [OPS Betrieb](ops/README.md) | 14 | Übersicht über die 14 IT-Grundschutz-Bausteine der Kategorie „OPS Betrieb“ mit Titel und Verweisen auf die einzelnen Bausteine. |
| [DER Detektion und Reaktion](der/README.md) | 7 | Übersicht über die 7 IT-Grundschutz-Bausteine der Kategorie „DER Detektion und Reaktion“ mit Titel und Verweisen auf die einzelnen Bausteine. |
| [APP Anwendungen](app/README.md) | 20 | Übersicht über die 20 IT-Grundschutz-Bausteine der Kategorie „APP Anwendungen“ mit Titel und Verweisen auf die einzelnen Bausteine. |
| [SYS IT-Systeme](sys/README.md) | 25 | Übersicht über die 25 IT-Grundschutz-Bausteine der Kategorie „SYS IT-Systeme“ mit Titel und Verweisen auf die einzelnen Bausteine. |
| [IND Industrielle IT](ind/README.md) | 7 | Übersicht über die 7 IT-Grundschutz-Bausteine der Kategorie „IND Industrielle IT“ mit Titel und Verweisen auf die einzelnen Bausteine. |
| [NET Netze und Kommunikation](net/README.md) | 11 | Übersicht über die 11 IT-Grundschutz-Bausteine der Kategorie „NET Netze und Kommunikation“ mit Titel und Verweisen auf die einzelnen Bausteine. |
| [INF Infrastruktur](inf/README.md) | 12 | Übersicht über die 12 IT-Grundschutz-Bausteine der Kategorie „INF Infrastruktur“ mit Titel und Verweisen auf die einzelnen Bausteine. |

## Einleitung und Grundlagen

| Dokument | Kurzbeschreibung |
|---|---|
| [Vorwort](vorwort.md) | Der BSI-IT-Grundschutz leitet aus der Informationssicherheit praktikable Empfehlungen ab und stellt ein Instrumentarium für die Institution bereit. |
| [Neues im IT-Grundschutz-Kompendium](neues-im-kompendium.md) | Überblick über die Edition 2023: 111 Bausteine, davon zehn neue, drei entfallene und 21 gegenüber der Edition 2022 überarbeitete IT-Grundschutz-Bausteine. |
| [IT-Grundschutz – Basis für Informationssicherheit](it-grundschutz-basis-fuer-informationssicherheit.md) | Bedeutung der Informationssicherheit: Informationen als wesentlicher Wert und Abhängigkeit aller Geschäftsprozesse von einer zuverlässig funktionierenden IT. |
| [Schichtenmodell und Modellierung](schichtenmodell-und-modellierung.md) | Nachbildung des Informationsverbunds mit IT-Grundschutz-Bausteinen: Erfassung der Prozesse, Anwendungen, IT-Systeme und relevanten Sicherheitsanforderungen. |
| [Rollen](rollen.md) | Erläuterung der Rollen und Verantwortlichkeiten in IT-Grundschutz-Projekten, vom Auditteam und der Bauleitung bis zu den Benutzenden. |
| [Glossar](glossar.md) | Erläuterung der wichtigsten Begriffe rund um Informationssicherheit und IT-Grundschutz als gemeinsame Terminologie für das gesamte Kompendium. |
| [Elementare Gefährdungen](elementare-gefaehrdungen.md) | Elementare Gefährdungen wie Feuer mit direkten und Folgeschäden an Menschen, Gebäuden und IT als grundlegende Bedrohungsquellen der Informationssicherheit. |

## Struktur

| Dokument | Kurzbeschreibung |
|---|---|
| [Struktur des IT-Grundschutz-Kompendiums](struktur.md) | Systematik des IT-Grundschutz-Kompendiums Edition 2023: die System-Bausteine APP, SYS, IND, NET, INF und die Prozess-Bausteine ISMS, ORP, CON, OPS, DER. |

## Änderungen, Korrekturen und Zuordnung

| Dokument | Kurzbeschreibung |
|---|---|
| [Änderungen in der Edition 2023 des IT-Grundschutz-Kompendiums](aenderungen-2023.md) | Dokumentiert alle Änderungen der Edition 2023 gegenüber der Edition 2022, Baustein für Baustein, inkl. neuer, entfallener und überarbeiteter Bausteine. |
| [Errata zum IT-Grundschutz-Kompendium Edition 2023](errata-2023.md) | Korrigiert Fehler im IT-Grundschutz-Kompendium Edition 2023 (Korrekturstand: 26. März 2026). |
| [Zuordnung ISO/IEC 27001 / 27002 zum IT-Grundschutz](iso-zuordnung.md) | Ordnungsmäße Zuordnung zwischen ISO/IEC 27001:2022 (Klauseln 1–10 und Anhang A) und den IT-Grundschutz-Bausteinen. |
