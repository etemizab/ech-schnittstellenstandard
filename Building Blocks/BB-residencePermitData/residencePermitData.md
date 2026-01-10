# BB-12 – residencePermitData (Ausländerkategorie)

![Version](https://img.shields.io/badge/version-0.1.0-blue)
&nbsp;&nbsp;Alle Versionen: [v0.1.0](residencePermitData.md)

---

**Standard:** eCH-0011 – Datenstandard Personendaten  
**Block-Version:** 0.1.0  
**Status:** Draft  
**Quelle im Standard:** Kapitel 3.3.11 – residencePermitData

---

## 1. Zweck & fachliche Bedeutung

Der Building Block **Ausländerkategorie (residencePermitData)** beschreibt den ausländerrechtlichen Status einer Person ohne Schweizer Staatsangehörigkeit.  
Er enthält Informationen zur Art der Aufenthaltsbewilligung sowie zu deren zeitlicher Gültigkeit.

---

## 2. Abgrenzung & Granularität

| Aspekt | Beschreibung |
|------|-------------|
| **Granularität** | Meso |
| **Rolle** | Rechtlicher Aufenthaltsstatus |
| **Abgrenzung** | Nicht gleich Wohnsitz – keine Adress- oder Meldeinformationen |

---

## 3. Struktur & Attribute

| Attribut | Pflicht | Beschreibung |
|---------|---------|--------------|
| `residencePermit` | ja | Art der Aufenthaltsbewilligung |
| `validFrom` | nein | Gültig ab |
| `validTo` | nein | Gültig bis |
| `entryDate` | nein | Datum der Einreise |

---

## 4. Abhängigkeiten

| Typ | Beschreibung |
|----|-------------|
| Extern | eCH-0006 – Aufenthaltsbewilligungen |

---

## 5. Verwendungskontext

- Bestandteil von **BB-02 – Person**
- Migrations- und ausländerrechtliche Verfahren

---

## 6. Versionierung

| Version | Datum | Beschreibung |
|--------|-------|--------------|
| 0.1.0 | YYYY-MM-DD | Initiale Überführung aus eCH-0011 v9.0.0 |

---

## 7. Quellen

- Verein eCH  
  **eCH-0011 – Datenstandard Personendaten**, Version 9.0.0  
  Kapitel 3.3.11 – *residencePermitData*

---

### Feedback

[Ankündigungen von eCH](https://github.com/etemizab/ech-schnittstellenstandard/discussions/categories/announcements)
· [Fehler melden](https://github.com/etemizab/ech-schnittstellenstandard/discussions/categories/q-a)
· [Verbesserung vorschlagen](https://github.com/etemizab/ech-schnittstellenstandard/discussions/categories/ideas)
· [Alle Diskussionen](https://github.com/etemizab/ech-schnittstellenstandard/discussions)
