# BB – contactData (Kontaktangaben)

![Version](https://img.shields.io/badge/version-0.1.0-blue)
&nbsp;&nbsp;Alle Versionen: [v0.1.0](contactData.md)

---

**Standard:** eCH-0011 – Datenstandard Personendaten  
**Block-Version:** 0.1.0  
**Status:** Draft  
**Quelle im Standard:** Kapitel 3.3.8 – contactData

---

## 1. Zweck & fachliche Bedeutung

Der Building Block **Kontaktangaben (contactData)** beschreibt die postalischen und optionalen elektronischen Kontaktinformationen einer Person.  
Er dient primär der Zustellung von amtlicher Korrespondenz.

---

## 2. Abgrenzung & Granularität

| Aspekt | Beschreibung |
|------|-------------|
| **Granularität** | Meso |
| **Rolle** | Kommunikations- und Zustellinformation |
| **Abgrenzung** | Keine Wohnsitzdefinition – Wohnadressen werden im Meldeverhältnis geführt |

---

## 3. Struktur & Attribute

| Attribut | Pflicht | Beschreibung |
|---------|---------|--------------|
| `contactAddress` | ja | Zustelladresse |
| `identification` | nein | Referenzierte Identifikatoren |

---

## 4. Abhängigkeiten

| Typ | Beschreibung |
|----|-------------|
| Extern | eCH-0010 – Adressstandard |
| Extern | eCH-0044 – Personenidentifikation (optional) |

---

## 5. Verwendungskontext

- Bestandteil von **BB-02 – Person**
- Zustellung von amtlichen Dokumenten und Mitteilungen

---

## 6. Versionierung

| Version | Datum | Beschreibung |
|--------|-------|--------------|
| 0.1.0 | YYYY-MM-DD | Initiale Überführung aus eCH-0011 v9.0.0 |

---

## 7. Quellen

- Verein eCH  
  **eCH-0011 – Datenstandard Personendaten**, Version 9.0.0  
  Kapitel 3.3.8 – *contactData*

---

### Feedback

[Ankündigungen von eCH](https://github.com/etemizab/ech-schnittstellenstandard/discussions/categories/announcements)
· [Fehler melden](https://github.com/etemizab/ech-schnittstellenstandard/discussions/categories/q-a)
· [Verbesserung vorschlagen](https://github.com/etemizab/ech-schnittstellenstandard/discussions/categories/ideas)
· [Alle Diskussionen](https://github.com/etemizab/ech-schnittstellenstandard/discussions)

