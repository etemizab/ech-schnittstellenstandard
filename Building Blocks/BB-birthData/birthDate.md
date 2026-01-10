# BB-03 – birthData (Geburtsangaben)

![Version](https://img.shields.io/badge/version-0.1.0-blue)
&nbsp;&nbsp;Alle Versionen: [v0.1.0](README.md)

---

**Standard:** eCH-0011 – Datenstandard Personendaten  
**Block-Version:** 0.1.0  
**Status:** Draft  
**Quelle im Standard:** Kapitel 3.3.3 – birthData

---

## 1. Zweck & fachliche Bedeutung

Der Building Block **Geburtsangaben (birthData)** beschreibt grundlegende Informationen zur Geburt einer Person.  
Er stellt einen stabilen und grundsätzlich unveränderlichen Bestandteil der Personenidentität dar.

---

## 2. Abgrenzung & Granularität

| Aspekt | Beschreibung |
|------|-------------|
| **Granularität** | Meso |
| **Rolle** | Beschreibung eines historischen Ereignisses |
| **Prozesslogik** | Keine – rein beschreibend |

---

## 3. Struktur & Attribute

| Attribut | Pflicht | Beschreibung |
|---------|---------|--------------|
| `dateOfBirth` | ja | Geburtsdatum |
| `placeOfBirth` | ja | Geburtsort |
| `sex` | ja | Geschlecht |

---

## 4. Abhängigkeiten

| Typ | Beschreibung |
|-----|-------------|
| Intern | Keine |
| Extern | Optionale externe Referenzen, z. B. Ortsangaben |

---

## 5. Verwendungskontext

- Bestandteil von **BB-02 – Person**
- Basisinformation für Register, Identifikation und Abgleichprozesse

---

## 6. Versionierung

| Version | Datum | Beschreibung |
|--------|-------|--------------|
| 0.1.0 | YYYY-MM-DD | Initiale Überführung aus eCH-0011 v9.0.0 |

---

## 7. Quellen

- Verein eCH  
  **eCH-0011 – Datenstandard Personendaten**, Version 9.0.0  
  Kapitel 3.3.3 – *birthData*

---

### Feedback

[Ankündigungen von eCH](https://github.com/etemizab/ech-schnittstellenstandard/discussions/categories/announcements)
· [Fehler melden](https://github.com/etemizab/ech-schnittstellenstandard/discussions/categories/q-a)
· [Verbesserung vorschlagen](https://github.com/etemizab/ech-schnittstellenstandard/discussions/categories/ideas)
· [Alle Diskussionen](https://github.com/etemizab/ech-schnittstellenstandard/discussions)

