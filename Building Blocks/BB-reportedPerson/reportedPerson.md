# BB-01 – reportedPersonType (ReportedPerson)

![Version](https://img.shields.io/badge/version-0.1.0-blue)
&nbsp;&nbsp;Alle Versionen: [v0.1.0](reportedPerson.md)

---

**Standard:** eCH-0011 – Datenstandard Personendaten  
**Block-Version:** 0.1.0  
**Status:** Draft  
**Quelle im Standard:** Kapitel 3.2 – reportedPersonType

---

## 1. Zweck & fachliche Bedeutung

Der Building Block **ReportedPerson (reportedPersonType)** dient als oberstes Austauschobjekt im Standard eCH-0011.  
Er fasst die fachlichen Informationen zu einer Person sowie zu einem oder mehreren Meldeverhältnissen zusammen und bildet damit die vollständige Meldung im Kontext des Einwohnerwesens ab.

Der Block selbst enthält keine fachlichen Detailinformationen, sondern fungiert als strukturierender Container für andere Building Blocks.

---

## 2. Abgrenzung & Granularität

| Aspekt | Beschreibung |
|------|-------------|
| **Granularität** | Container (oberhalb der Meso-Ebene) |
| **Rolle** | Aggregation und Austausch |
| **Abgrenzung** | Kein eigenständiger Fachblock – keine eigenen Attribute mit fachlicher Bedeutung |

Der Block wird bewusst nicht als eigenständiger Meso-Building-Block betrachtet, da er keinen eigenen fachlichen Lebenszyklus besitzt.

---

## 3. Struktur & enthaltene Building Blocks

| Enthaltener Block | Kardinalität | Beschreibung |
|------------------|--------------|--------------|
| **BB-02 – Person** | 1 | Zentrale Personeninformationen |
| **BB-13 – Meldeverhältnis** | 1..n | Wohn- und Aufenthaltsverhältnisse |

---

## 4. Abhängigkeiten

| Typ | Beschreibung |
|----|-------------|
| Intern | BB-02 – Person (contains) |
| Intern | BB-13 – Meldeverhältnis (contains) |
| Extern | Keine direkten externen Referenzen |

---

## 5. Verwendungskontext

- Root-Element beim Austausch von Personendaten
- Einstiegspunkt für API-basierte Schnittstellen
- Übermittlung vollständiger Personenmeldungen

---

## 6. Versionierung

| Version | Datum | Beschreibung |
|--------|-------|--------------|
| 0.1.0 | YYYY-MM-DD | Initiale Überführung aus eCH-0011 v9.0.0 |

---

## 7. Quellen

- Verein eCH  
  **eCH-0011 – Datenstandard Personendaten**, Version 9.0.0  
  Kapitel 3.2 – *reportedPersonType*

---

### Feedback

[Ankündigungen von eCH](https://github.com/etemizab/ech-schnittstellenstandard/discussions/categories/announcements)
· [Fehler melden](https://github.com/etemizab/ech-schnittstellenstandard/discussions/categories/q-a)
· [Verbesserung vorschlagen](https://github.com/etemizab/ech-schnittstellenstandard/discussions/categories/ideas)
· [Alle Diskussionen](https://github.com/etemizab/ech-schnittstellenstandard/discussions)

