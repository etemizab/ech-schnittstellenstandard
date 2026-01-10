# BB-08 – nationalityData (Staatsangehörigkeit)

![Version](https://img.shields.io/badge/version-0.1.0-blue)
&nbsp;&nbsp;Alle Versionen: [v0.1.0](nationalityData.md)

---

**Standard:** eCH-0011 – Datenstandard Personendaten  
**Block-Version:** 0.1.0  
**Status:** Draft  
**Quelle im Standard:** Kapitel 3.3.6 – nationalityData

---

## 1. Zweck & fachliche Bedeutung

Der Building Block **Staatsangehörigkeit (nationalityData)** beschreibt die rechtliche Zugehörigkeit einer Person zu einem oder mehreren Staaten.  
Er berücksichtigt sowohl den aktuellen Status als auch zusätzliche Informationen zu einzelnen Staatsangehörigkeiten.

---

## 2. Abgrenzung & Granularität

| Aspekt | Beschreibung |
|------|-------------|
| **Granularität** | Meso |
| **Rolle** | Rechtlicher Identitätsaspekt |
| **Besonderheit** | Mehrfachzugehörigkeit – mehrere Staatsangehörigkeiten möglich |

---

## 3. Struktur & Attribute

| Attribut | Pflicht | Beschreibung |
|---------|---------|--------------|
| `nationalityStatus` | ja | Status der Staatsangehörigkeit |
| `countryInfo` | nein | Informationen zu einzelnen Staaten |

---

## 4. Abhängigkeiten

| Typ | Beschreibung |
|----|-------------|
| Extern | eCH-0008 – Staaten / Ländercodes |

---

## 5. Verwendungskontext

- Bestandteil von **BB-02 – Person**
- Migrations-, Register- und Statistikprozesse

---

## 6. Versionierung

| Version | Datum | Beschreibung |
|--------|-------|--------------|
| 0.1.0 | YYYY-MM-DD | Initiale Überführung aus eCH-0011 v9.0.0 |

---

## 7. Quellen

- Verein eCH  
  **eCH-0011 – Datenstandard Personendaten**, Version 9.0.0  
  Kapitel 3.3.6 – *nationalityData*

---

### Feedback

[Ankündigungen von eCH](https://github.com/etemizab/ech-schnittstellenstandard/discussions/categories/announcements)
· [Fehler melden](https://github.com/etemizab/ech-schnittstellenstandard/discussions/categories/q-a)
· [Verbesserung vorschlagen](https://github.com/etemizab/ech-schnittstellenstandard/discussions/categories/ideas)
· [Alle Diskussionen](https://github.com/etemizab/ech-schnittstellenstandard/discussions)

