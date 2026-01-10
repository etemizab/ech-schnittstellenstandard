# BB-09 – deathData (Todesangaben)

![Version](https://img.shields.io/badge/version-0.1.0-blue)
&nbsp;&nbsp;Alle Versionen: [v0.1.0](deathData.md)

---

**Standard:** eCH-0011 – Datenstandard Personendaten  
**Block-Version:** 0.1.0  
**Status:** Draft  
**Quelle im Standard:** Kapitel 3.3.7 – deathData

---

## 1. Zweck & fachliche Bedeutung

Der Building Block **Todesangaben (deathData)** beschreibt Informationen zum Tod einer Person.  
Er wird nur verwendet, wenn ein Todesfall eingetreten ist, und ergänzt die Personenbeschreibung um dieses Ereignis.

---

## 2. Abgrenzung & Granularität

| Aspekt | Beschreibung |
|------|-------------|
| **Granularität** | Meso |
| **Rolle** | Ereignisbezogene Information |
| **Optionalität** | Der Block ist nicht zwingend Bestandteil jeder Person |

---

## 3. Struktur & Attribute

| Attribut | Pflicht | Beschreibung |
|---------|---------|--------------|
| `deathDate` | nein | Datum des Todes |
| `deathPeriod` | nein | Zeitraum des Todes |
| `placeOfDeath` | nein | Sterbeort |

---

## 4. Abhängigkeiten

| Typ | Beschreibung |
|----|-------------|
| Extern | Optionale externe Referenzen, z. B. Ortsangaben |

---

## 5. Verwendungskontext

- Bestandteil von **BB-02 – Person**
- Statistik, Registerpflege, Abschluss von Meldeverhältnissen

---

## 6. Versionierung

| Version | Datum | Beschreibung |
|--------|-------|--------------|
| 0.1.0 | YYYY-MM-DD | Initiale Überführung aus eCH-0011 v9.0.0 |

---

## 7. Quellen

- Verein eCH  
  **eCH-0011 – Datenstandard Personendaten**, Version 9.0.0  
  Kapitel 3.3.7 – *deathData*

---

### Feedback

[Ankündigungen von eCH](https://github.com/etemizab/ech-schnittstellenstandard/discussions/categories/announcements)
· [Fehler melden](https://github.com/etemizab/ech-schnittstellenstandard/discussions/categories/q-a)
· [Verbesserung vorschlagen](https://github.com/etemizab/ech-schnittstellenstandard/discussions/categories/ideas)
· [Alle Diskussionen](https://github.com/etemizab/ech-schnittstellenstandard/discussions)

