# BB-06 – religionData (Konfessionsangaben)

![Version](https://img.shields.io/badge/version-0.1.0-blue)
&nbsp;&nbsp;Alle Versionen: [v0.1.0](religionData.md)

---

**Standard:** eCH-0011 – Datenstandard Personendaten  
**Block-Version:** 0.1.0  
**Status:** Draft  
**Quelle im Standard:** Kapitel 3.3.4 – religionData

---

## 1. Zweck & fachliche Bedeutung

Der Building Block **Konfessionsangaben (religionData)** beschreibt die religiöse Zugehörigkeit einer Person.  
Er wird im Standard eCH-0011 als eigenständiger fachlicher Aspekt geführt und kann sich im Lebensverlauf einer Person ändern.

---

## 2. Abgrenzung & Granularität

| Aspekt | Beschreibung |
|------|-------------|
| **Granularität** | Meso (fachlich geschlossener Datentyp) |
| **Rolle** | Ergänzende Personeninformation |
| **Abgrenzung** | Keine Ableitungen – keine logischen Schlussfolgerungen oder Bewertungen |

---

## 3. Struktur & Attribute

| Attribut | Pflicht | Beschreibung |
|---------|---------|--------------|
| `religionCode` | ja | Konfessionszugehörigkeit (Code) |
| `validFrom` | nein | Gültig ab |

---

## 4. Abhängigkeiten

| Typ | Beschreibung |
|----|-------------|
| Extern | Codesysteme gemäss eCH-Definitionen |

---

## 5. Verwendungskontext

- Bestandteil von **BB-02 – Person**
- Statistische und verwaltungsinterne Zwecke

---

## 6. Versionierung

| Version | Datum | Beschreibung |
|--------|-------|--------------|
| 0.1.0 | YYYY-MM-DD | Initiale Überführung aus eCH-0011 v9.0.0 |

---

## 7. Quellen

- Verein eCH  
  **eCH-0011 – Datenstandard Personendaten**, Version 9.0.0  
  Kapitel 3.3.4 – *religionData*

---

### Feedback

[Ankündigungen von eCH](https://github.com/etemizab/ech-schnittstellenstandard/discussions/categories/announcements)
· [Fehler melden](https://github.com/etemizab/ech-schnittstellenstandard/discussions/categories/q-a)
· [Verbesserung vorschlagen](https://github.com/etemizab/ech-schnittstellenstandard/discussions/categories/ideas)
· [Alle Diskussionen](https://github.com/etemizab/ech-schnittstellenstandard/discussions)
