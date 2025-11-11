# eCH-schnittstellenstandard, Personendaten-Standard

## 1 Einleitung
- 1.1 Status(#1-1-status)
- 1.2 Anwendungsgebiet(#1-2-Anwendungsgebiet)
- 1.3 Abgrenzung(#1-3-Abgrenzung)
- 1.4 Konventionen(#1-4-Konventionen)

## 2 Datenmodell

### 2.1 Geburtsdaten
- <a href="schemas/person/birthData.json">Geburts-Daten v1.0</a>
- <a href="schemas/person/birthData.json">Geburts-Daten v2.0</a>
- <a href="schemas/person/birthData.json">Geburts-Daten v2.1</a>
- <a href="schemas/person/birthData.json">Geburts-Daten v2.2</a>

### 2.1 Namensdaten
- <a href="schemas/person/nameData.json">Geburts-Daten v1.0</a>
- <a href="schemas/person/nameData.json">Geburts-Daten v1.1</a>
- <a href="schemas/person/nameData.json">Geburts-Daten v1.2</a>
- <a href="schemas/person/nameData.json">Geburts-Daten v2.0</a>

### 2.1 Herkunfsdaten
- <a href="schemas/person/nationalityData.json">Geburts-Daten v1.0</a>
- <a href="schemas/person/nationalityData.json">Geburts-Daten v1.1</a>
- <a href="schemas/person/nationalityData.json">Geburts-Daten v2.0</a>
- <a href="schemas/person/nationalityData.json">Geburts-Daten v2.1</a>

## 3 Spezifikation

## 4 Sicherheitsüberlegungen

## 5 Haftungsausschluss/Hinweise auf Rechte Dritter

## 6 Urheberrechte

## Anhänge
- Referenzen / Bibliografie
- Mitarbeit / Überprüfung
- Abkürzungen / Glossar
- Änderungen zu Vorversion
- Abbildungsverzeichnis
- Tabellenverzeichnis
  
---
<a id="1-einleitung"></a>
## 1. Einleitung · Version: ![v1.0.0](https://img.shields.io/badge/version-1.0.0-blue)
### 1.1 Status · Version: ![v1.0.0](https://img.shields.io/badge/version-1.0.0-blue)

**In Entwicklung:** Das vorliegende Repository befindet sich in der initialen Entwicklungsphase im Rahmen eines Integrationsseminars Data Science an der ZHAW School of Management and Law. Dieses Projekt wird in Kooperation mit dem Verein eCH durchgeführt und dient der prototypischen Umsetzung eines ausgewählten Schnittstellenstandards auf GitHub. Ziel ist die Transformation statischer PDF-Spezifikationen in eine modulare, versionierte und kollaborativ weiterentwickelbare Struktur.

Das Repository stellt eine experimentelle Implementierung dar, die iterativ entwickelt wird. Feedback und Beiträge aus der eCH-Community sind ausdrücklich erwünscht und können über GitHub Issues und Discussions eingebracht werden. Nach Abschluss der Entwicklungsphase und erfolgreicher Evaluation wird eine Überführung in einen stabilen Status angestrebt.

Alle Versionen: [v1.0.0](README.md)

---
**Feedback**: [Ankündigungen von eCH](https://github.com/etemizab/ech-schnittstellenstandard/discussions/categories/announcements) ·  [Fehler melden](https://github.com/etemizab/ech-schnittstellenstandard/discussions/categories/q-a) · [Verbesserung vorschlagen](https://github.com/etemizab/ech-schnittstellenstandard/discussions/categories/ideas) · [Alle Diskussionen](https://github.com/etemizab/ech-schnittstellenstandard/discussions)

---

<a id="1.2-Anwendungsgebiet"></a>
### 1.2 Anwendungsgebiet · Version: ![v1.0.0](https://img.shields.io/badge/version-1.0.0-blue)

Der vorliegende Standard – am Beispiel von **eCH-0011 Datenstandard Personendaten** – definiert zusammen mit den Datenstandards eCH-0044 (Personenidentifikation) und eCH-0045 (Stimm- und Wahlrecht) das Format und die erlaubten Werte zum elektronischen Austausch von Personen-, Aufenthalts- und Niederlassungsinformationen zwischen den Behörden der Schweiz. Die Schnittstelle basiert auf dem **Registerharmonisierungsgesetz (RHG)** und dem darin definierten Amtlichen Katalog der Merkmale.

### Zweck der Schnittstelle

Die eCH-0011 Schnittstelle ermöglicht es Behörden, Personendaten elektronisch, korrekt und medienbruchfrei auszutauschen. Dabei wird eine **einheitliche, schweizweit eindeutige Personenidentifikation** gewährleistet, deren Kern die AHV-Versichertennummer bildet. Dies ist essentiell für eine koordinierte und effiziente Verwaltung von Personenregistern über Kantons- und Gemeindegrenzen hinweg.

### Konkrete Anwendungsfälle

Die eCH-0011 Schnittstelle regelt insbesondere:

- **Austausch zwischen Einwohnerregistern** bei Zuzug bzw. Wegzug von Personen zwischen Gemeinden
- **Austausch mit zentralen Behörden** wie dem Bundesamt für Statistik
- **Integration mit anderen Systemen** wie dem Zentralen Ausländerregister (ZAR) oder InfoStar
- **Abfrage von Personendaten** durch berechtigte Behörden und öffentliche Verwaltungen

### Datenbereiche

Der Standard definiert folgende Informationskategorien zu einer Person:

- Personenidentifikation (AHV-Nummer, Amtlicher Name, Vornamen, Geschlecht, Geburtsdatum)
- Namen (lediger Name, Aliasname, Rufname, Namen im ausländischen Pass)
- Geburts- und Todesinformationen
- Zivilstandsdaten
- Staatsangehörigkeit und Aufenthaltsstatus
- Kontaktadaten (Zustelladressen, Korrespondenzsprache)
- Heimatorte und weitere Zusatzinformationen

### Zielgruppen

Die Schnittstelle richtet sich an:

- **Kantonale und kommunale Behörden** für die Verwaltung von Einwohnerregistern
- **Bundesbehörden** und Statistikämter für zentrale Datenabfragen
- **Behörden anderer Verwaltungsebenen**, die auf Personendaten angewiesen sind
- **Softwareentwickler und Systemintegratoren**, die Verwaltungslösungen implementieren

Die Modularisierung dieser Schnittstelle auf GitHub trägt dazu bei, dass der Standard nicht nur als statisches PDF-Dokument vorliegt, sondern als **lebendiger, maschinenlesbarer Standard**, der direkt in Implementierungsprojekten eingesetzt werden kann und eine kontinuierliche Weiterentwicklung durch Feedback-Mechanismen ermöglicht.

Alle Versionen: [v1.0.0](README.md)

---
**Feedback**: [Ankündigungen von eCH](https://github.com/etemizab/ech-schnittstellenstandard/discussions/categories/announcements) ·  [Fehler melden](https://github.com/etemizab/ech-schnittstellenstandard/discussions/categories/q-a) · [Verbesserung vorschlagen](https://github.com/etemizab/ech-schnittstellenstandard/discussions/categories/ideas) · [Alle Diskussionen](https://github.com/etemizab/ech-schnittstellenstandard/discussions)

---

<a id="1.3-Abgrenzung"></a>
### 1.3 Abgrenzung · Version: ![v1.0.0](https://img.shields.io/badge/version-1.0.0-blue)

Der vorliegende Standard beschränkt sich darauf, **Datenformate und Strukturen zu definieren**. Das vollständige Austauschformat für konkrete Schnittstellen wird durch eigenständige Standards bzw. konkrete Umsetzungsprojekte bestimmt. Es bleibt diesen Standards überlassen, aus den in eCH-0011 definierten Datenmodellen die vollständigen Austauschformate für konkrete Anwendungsfälle abzuleiten.

**Im Scope des Standards enthalten:**

- Definition und Struktur von **Kerndatenelementen** zu einer Person (Personenidentifikation, Namen, Geburtsangaben, Konfession, Zivilstand, Staatsangehörigkeit)
- Optionale Dateneelemente (Todesangaben, Kontaktdaten, Korrespondenzsprache)
- Datentypen und deren technische Spezifikation im XML-Schema-Format
- Schnittstellen zum Personenmeldewesen und Behördendatenaustausch

**Explizit ausgenommen (Out of Scope):**

- **Detaillierte geschäftliche Logik**: Der Standard definiert nicht, wie und wann Daten ausgetauscht werden oder welche Geschäftsprozesse dahinterstecken
- **Personenidentifikation**: Diese wird durch den separaten Standard **eCH-0044** definiert, einschliesslich AHV-Nummern und lokaler Identifikatoren
- **Stimm- und Wahlrecht**: Diese spezialisierten Merkmale werden im Standard **eCH-0045** geregelt
- **Zusätzliche Personendaten**: Ergänzende Angaben zu Bezugspersonen, Heimatorten und weitere Zusatzdaten sind im Standard **eCH-0021** dokumentiert
- **Austauschformat für konkrete Anwendungsfälle**: Z.B. der Austausch zwischen Einwohnerregistern bei Zuzug/Wegzug (definiert in eCH-0020), der Austausch mit dem Bundesamt für Statistik oder mit Systemen wie ZAR und Infostar
- **Sicherheit und Datenschutz**: Der Standard setzt voraus, dass alle Behörden die geltenden Datenschutzgesetze und Sicherheitsvorschriften einhalten; diese werden nicht im Standard definiert
- **Implementierungsrichtlinien**: Technische Umsetzungsdetails und Implementierungsvorgaben für konkrete Systeme sind nicht Gegenstand des Standards

Diese Abgrenzung ermöglicht eine klare Modularität: eCH-0011 kann als Basis für verschiedene spezialisierte Austauschformate genutzt werden, ohne dass jedes Mal die Gesamtspezifikation neu geschrieben werden muss.

Alle Versionen: [v1.0.0](README.md)

---
**Feedback**: [Ankündigungen von eCH](https://github.com/etemizab/ech-schnittstellenstandard/discussions/categories/announcements) ·  [Fehler melden](https://github.com/etemizab/ech-schnittstellenstandard/discussions/categories/q-a) · [Verbesserung vorschlagen](https://github.com/etemizab/ech-schnittstellenstandard/discussions/categories/ideas) · [Alle Diskussionen](https://github.com/etemizab/ech-schnittstellenstandard/discussions)

---
<a id="1.4-Konventionen"></a>
### 1.4 Konventionen · Version: ![v1.0.0](https://img.shields.io/badge/version-1.0.0-blue)

Die folgenden Konventionen regeln die **Notation, Formatierung und Referenzierung** in diesem Standard:

**1.4.1 Dateiformat und Kodierung**

- **Zeichensatz**: Alle Daten sind gemäss [eCH-0018] in **UTF-8** zu kodieren
- **Schreibweise ausländischer Namen**: Die Schreibweise folgt den Weisungen des EJPD (Eidgenössisches Justiz- und Polizeidepartement)
- **XML-Schema**: Die formale Spezifikation verwendet die Syntax von **XML Schema (XSD)**

**1.4.2 Referenzierung und Abhängigkeiten**

- Werden Spezifikationen aus anderen Standards berücksichtigt, wird auf diese in der Form **[Referenz]** bezug genommen
- Detaillierte Angaben zu den Referenzen sind im Anhang dokumentiert
- Zu jedem Element wird der zugehörige Datentyp (type) dokumentiert

**1.4.3 Begriffe und Optionalität**

Der Begriff **"optional"** im Kontext dieses Standards ist im Sinne der XML-Schema-Spezifikation verwendet und bedeutet: "*Es gibt Fälle, wo zu diesem Element keine Daten vorhanden sind*"

- **Zwingend (mandatory)**: Das Element muss immer vorhanden sein, wenn es Daten dazu gibt
- **Optional (optional)**: Das Element kann fehlen, wenn die Information nicht verfügbar ist
- **Mehrfach (multiple)**: Das Element kann mehrmals vorkommen (z.B. mehrere Heimatorte)

Ein Merkmal, das im **Amtlichen Katalog der Merkmale (KAT)** als "*obligatorisch falls geführt*" beschrieben wird, muss im XML-Schema als optionales Element definiert werden, da es Personen gibt, für die diese Daten nicht vorhanden sind.

**1.4.4 Versionierung**

- **Major Changes**: Wesentliche Änderungen der Struktur oder Semantik (z.B. Version 8.x → 9.x)
- **Minor Changes**: Kleine ergänzende Änderungen, z.B. neue optionale Elemente
- Die aktuelle Version ist **9.0.0** (Stand April 2022)
- Jede Version wird mit einem eigenen XSD-Schema bereitgestellt (z.B. eCH-0011-9-0.xsd)

**1.4.5 UML-Datenmodell**

Das Datenmodell wird in **UML-Notation** beschrieben und zeigt die definierten Klassen und ihre logischen Abhängigkeiten. Das Modell bildet einen **Zustand zu einem bestimmten Zeitpunkt** ab – nicht die historischen Änderungen von Daten.

**1.4.6 Referenzierte Standards**

Dieser Standard arbeitet eng mit folgenden eCH-Standards zusammen:

| Standard | Bereich | Beschreibung |
|----------|---------|-------------|
| **eCH-0044** | Personenidentifikation | Eindeutige Personenidentifikatoren und AHV-Nummern |
| **eCH-0045** | Stimm- und Wahlrecht | Beschränkungen auf Stimm- und Wahlrecht |
| **eCH-0021** | Personenzusatzdaten | Ergänzende Daten zu Bezugspersonen und Heimatorten |
| **eCH-0020** | Meldeprozesse | Austauschformat für Zuzug/Wegzug-Ereignisse |
| **eCH-0010** | Adressdaten | Format für Zustelladressen |
| **eCH-0018** | XML-Standards | Allgemeine Anforderungen zur XML-Kodierung |

**1.4.7 Dokumentstruktur**

- **Kapitel 2**: Überblick über das Gesamtdatenmodell
- **Kapitel 3**: Detaillierte Spezifikation aller Datenelemente
- **Kapitel 4+**: Sicherheit, Haftungsausschluss, Anhänge (Glossar, Abkürzungen, Änderungshistorie)

**1.4.8 Rechtliche und datenschutztechnische Betrachtung**

Alle in diesem Standard beschriebenen Daten unterliegen dem **Datenschutzgesetz**. Sie dürfen nur ausgetauscht werden, wenn:
- Die rechtlichen Grundlagen für den Datenaustausch vorhanden sind
- Die entsprechenden Sicherheitsvorschriften eingehalten werden
- Kantonale Vorgaben beachtet werden

Alle Versionen: [v1.0.0](README.md)

---
**Feedback**: [Ankündigungen von eCH](https://github.com/etemizab/ech-schnittstellenstandard/discussions/categories/announcements) ·  [Fehler melden](https://github.com/etemizab/ech-schnittstellenstandard/discussions/categories/q-a) · [Verbesserung vorschlagen](https://github.com/etemizab/ech-schnittstellenstandard/discussions/categories/ideas) · [Alle Diskussionen](https://github.com/etemizab/ech-schnittstellenstandard/discussions)

---

