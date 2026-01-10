# BB-02 – personType (Person)

![Version](https://img.shields.io/badge/version-0.1.0-blue)
&nbsp;&nbsp;Alle Versionen: [v0.1.0](person.md)

---

**Standard:** eCH-0011 – Datenstandard Personendaten  
**Block-Version:** 0.1.0  
**Status:** Draft  
**Quelle im Standard:** Kapitel 3.3 – personType

---

## 1. Zweck & fachliche Bedeutung

Der Building Block **Person (personType)** beschreibt die grundlegende Identität einer natürlichen Person im Kontext des Einwohnerwesens.  
Er fungiert als zentrales Fachobjekt und bündelt mehrere spezialisierte Building Blocks, welche unterschiedliche Aspekte der Person beschreiben.

---

## 2. Abgrenzung & Granularität

| Aspekt | Beschreibung |
|------|-------------|
| **Granularität** | Meso (fachlich geschlossener Datentyp) |
| **Rolle** | Zentrales Kernobjekt |
| **Abgrenzung** | Keine Aufenthaltsinformationen – Wohn- und Meldeverhältnisse sind bewusst ausgelagert |

Diese Trennung erlaubt eine klare Abgrenzung zwischen Identität und Aufenthaltsbezug.

---

## 3. Struktur & enthaltene Building Blocks

| Enthaltener Block | Pflicht | Beschreibung |
|------------------|---------|--------------|
| **BB-03 – Personenidentifikation** | ja | Eindeutige Identifikation |
| **BB-04 – Namensangaben** | ja | Namen und Namensvarianten |
| **BB-05 – Geburtsangaben** | ja | Angaben zur Geburt |
| **BB-06 – Konfession** | ja | Religionszugehörigkeit |
| **BB-07 – Zivilstand** | ja | Zivilstandsangaben |
| **BB-08 – Staatsangehörigkeit** | ja | Nationalitäten |
| **BB-09 – Todesangaben** | nein | Angaben zum Todesfall |
| **BB-10 – Kontaktangaben** | nein | Zustell- und Kontaktinformationen |
| **BB-11 – Heimatort** | bedingt | Schweizer Personen |
| **BB-12 – Ausländerkategorie** | bedingt | Personen ohne Schweizer Staatsangehörigkeit |

---

## 4. Abhängigkeiten

| Typ | Beschreibung |
|----|-------------|
| Intern | Referenzen auf spezialisierte Person-Building-Blocks |
| Extern | Indirekte externe Referenzen über diese Blocks |

---

## 5. Verwendungskontext

- Bestandteil von **BB-01 – ReportedPerson**
- Basisobjekt für Personenabfragen und Register

---

## 6. Versionierung

| Version | Datum | Beschreibung |
|--------|-------|--------------|
| 0.1.0 | YYYY-MM-DD | Initiale Überführung aus eCH-0011 v9.0.0 |

---

## 7. Quellen

- Verein eCH  
  **eCH-0011 – Datenstandard Personendaten**, Version 9.0.0  
  Kapitel 3.3 – *personType*

---

### Feedback

[Ankündigungen von eCH](https://github.com/etemizab/ech-schnittstellenstandard/discussions/categories/announcements)
· [Fehler melden](https://github.com/etemizab/ech-schnittstellenstandard/discussions/categories/q-a)
· [Verbesserung vorschlagen](https://github.com/etemizab/ech-schnittstellenstandard/discussions/categories/ideas)
· [Alle Diskussionen](https://github.com/etemizab/ech-schnittstellenstandard/discussions)

