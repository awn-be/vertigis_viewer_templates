# Changelog

Alle Änderungen an den Viewer Templates werden in diesem File dokumentiert.

Das Format basiert auf [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),

## Guiding Principles
- Changelogs sind für Menschen, nicht Maschinen.
- Gleiche change Typen sollten gruppiert werden.
- Die aktuellste Version kommt zuerst.
- Für jede Version wird das Releasedatum erfasst.

## Veränderungstypen
- **Added** für neue Features.
- **Changed** für Anpassungen von bestehender Funktionalität.
- **Deprecated** für Features welche bald gelöscht werden.
- **Removed** für Features welche gelöscht wurden.
- **Fixed** für Bugfixes.
- **Security** für Sicherheitsrelevante Themen.

<br /> <br />

## [Unreleased]

## [Released]

## 2026-10-20
**Fixed**
- Messen/Editieren in geladenem Projekt (https://github.com/awn-be/vertigis_admin/issues/60)

**Added**
- Koordinatenanzeige hinzugefügt (https://github.com/awn-be/vertigis_admin/issues/28)
- Masstabsleiste hinzugefügt (https://github.com/awn-be/vertigis_admin/issues/29)

## 2026-10-15
**Changed**
- app_template_bgi_fr: Übersetzung Grundkarten bereinigt

**Added**
- ResultatTabelle: Funktion "Resultat entfernen" bei den Ereignis-Aktionen hinzugefügt

## 2026-10-06
**Changed**
- XLSX-Export: Benutzerdefinierter Befehl erweitert mit "geometryFormat": "NONE"
  https://github.com/awn-be/vertigis_admin/issues/57
- Drucken: weitere Druckmassstäbe eingefügt (100'000, 200'000, 400'000).

## 2026-08-24

**Removed**

- advanced edit Tools in mobile templates (de/fr)
## 2026-08-18
**Added**
- Click on table row in attribute table, zooms to feature. For implementation details see: https://github.com/awn-be/vertigis_admin/issues/6
