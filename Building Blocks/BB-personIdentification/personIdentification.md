# BB-03 – personIdentificationType (Personenidentifikation)

![Version](https://img.shields.io/badge/version-0.1.0-blue)
&nbsp;&nbsp;Alle Versionen: [v0.1.0](personIdentification.md)

---

**Standard:** eCH-0011 – Datenstandard Personendaten  
**Block-Version:** 0.1.0  
**Status:** Draft  
**Quelle im Standard:** Kapitel 3.3.1 – personIdentificationType

---

## 1. Zweck & fachliche Bedeutung

Der Building Block **Personenidentifikation (personIdentificationType)** stellt die eindeutige Identifikation einer Person sicher.  
Er basiert auf dem externen Standard **eCH-0044** und ermöglicht die eindeutige Referenzierung einer Person über standardisierte Identifikatoren.

---

## 2. Abgrenzung & Granularität

| Aspekt | Beschreibung |
|------|-------------|
| **Granularität** | Meso (referenzierter Datentyp) |
| **Rolle** | Identifikation |
| **Abgrenzung** | Keine fachlichen Attribute – ausschliesslich Identifikationsmerkmale |

---

## 3. Struktur (fachliche Übersicht)

| Attribut | Pflicht | Beschreibung |
|---------|---------|--------------|
| `identificationNumber` | ja | Eindeutige Personenkennung |
| `identificationType` | ja | Typ der Kennung |

---

## 4. Abhängigkeiten

| Typ | Beschreibung |
|----|-------------|
| Extern | eCH-0044 – Personenidentifikation |

---

## 5. Verwendungskontext

- Bestandteil von **BB-02 – Person**
- Referenzierung in anderen fachlichen Kontexten

---

## 6. Versionierung

| Version | Datum | Beschreibung |
|--------|-------|--------------|
| 0.1.0 | YYYY-MM-DD | Initiale Referenz auf eCH-0044 |

---

## 7. Quellen

- Verein eCH  
  **eCH-0011 – Datenstandard Personendaten**, Version 9.0.0  
  Kapitel 3.3.1 – *personIdentificationType*

---

### Feedback

[Ankündigungen von eCH](https://github.com/etemizab/ech-schnittstellenstandard/discussions/categories/announcements)
· [Fehler melden](https://github.com/etemizab/ech-schnittstellenstandard/discussions/categories/q-a)
· [Verbesserung vorschlagen](https://github.com/etemizab/ech-schnittstellenstandard/discussions/categories/ideas)
· [Alle Diskussionen](https://github.com/etemizab/ech-schnittstellenstandard/discussions)

