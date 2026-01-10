# BB-XX – dwellingAddressType (Wohnadresse)

![Version](https://img.shields.io/badge/version-0.1.0-blue)
&nbsp;&nbsp;Alle Versionen: [v0.1.0](dewellingAddress.md)

---

**Standard:** eCH-0011 – Datenstandard Personendaten  
**Block-Version:** 0.1.0  
**Status:** Draft  
**Quelle im Standard:** Kapitel 3.4.5 – dwellingAddressType

---

## 1. Zweck & fachliche Bedeutung

Der Building Block **Wohnadresse (dwellingAddressType)** beschreibt die konkrete Wohnsituation einer Person innerhalb eines Meldeverhältnisses.  
Er enthält sowohl adressbezogene Informationen als auch wohnungs- und haushaltsbezogene Identifikatoren.

---

## 2. Abgrenzung & Granularität

| Aspekt | Beschreibung |
|------|-------------|
| **Granularität** | Meso |
| **Rolle** | Physischer Aufenthaltsort |
| **Abgrenzung** | Nicht für Zustellung – Zustelladressen sind separat modelliert |

---

## 3. Struktur & Attribute

| Attribut | Pflicht | Beschreibung |
|---------|---------|--------------|
| `address` | ja | Physische Adresse |
| `EGID` | nein | Gebäudeidentifikator |
| `EWID` | nein | Wohnungsidentifikator |
| `householdId` | nein | Haushalt |
| `movingDate` | nein | Einzugsdatum |

---

## 4. Abhängigkeiten

| Typ | Beschreibung |
|----|-------------|
| Extern | eCH-0010 – Adressstandard |

---

## 5. Verwendungskontext

- Bestandteil von **BB-13 – Meldeverhältnis**
- Wohnsitzverwaltung und Statistik

---

## 6. Versionierung

| Version | Datum | Beschreibung |
|--------|-------|--------------|
| 0.1.0 | YYYY-MM-DD | Initiale Überführung aus eCH-0011 v9.0.0 |

---

## 7. Quellen

- Verein eCH  
  **eCH-0011 – Datenstandard Personendaten**, Version 9.0.0  
  Kapitel 3.4.5 – *dwellingAddressType*

---

### Feedback

[Ankündigungen von eCH](https://github.com/etemizab/ech-schnittstellenstandard/discussions/categories/announcements)
· [Fehler melden](https://github.com/etemizab/ech-schnittstellenstandard/discussions/categories/q-a)
· [Verbesserung vorschlagen](https://github.com/etemizab/ech-schnittstellenstandard/discussions/categories/ideas)
· [Alle Diskussionen](https://github.com/etemizab/ech-schnittstellenstandard/discussions)


