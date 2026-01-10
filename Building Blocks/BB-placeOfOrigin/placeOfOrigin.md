# BB-11 – placeOfOrigin (Heimatort)

![Version](https://img.shields.io/badge/version-0.1.0-blue)
&nbsp;&nbsp;Alle Versionen: [v0.1.0](placeOfOrigin.md)

---

**Standard:** eCH-0011 – Datenstandard Personendaten  
**Block-Version:** 0.1.0  
**Status:** Draft  
**Quelle im Standard:** Kapitel 3.3.10 – placeOfOrigin

---

## 1. Zweck & fachliche Bedeutung

Der Building Block **Heimatort (placeOfOrigin)** beschreibt den rechtlich definierten Heimatort einer Person.  
Er ist insbesondere für Personen mit Schweizer Staatsangehörigkeit relevant und stellt eine dauerhafte rechtliche Zuordnung dar, unabhängig vom aktuellen Wohnort.

---

## 2. Abgrenzung & Granularität

| Aspekt | Beschreibung |
|------|-------------|
| **Granularität** | Meso |
| **Rolle** | Rechtliche Herkunftsangabe |
| **Abgrenzung** | Nicht gleich Wohnort – keine Aufenthalts- oder Adressinformation |

---

## 3. Struktur & Attribute

| Attribut | Pflicht | Beschreibung |
|---------|---------|--------------|
| `originName` | ja | Name des Heimatorts |
| `canton` | ja | Kanton des Heimatorts |
| `originId` | nein | Eindeutige Identifikation des Heimatorts |

---

## 4. Abhängigkeiten

| Typ | Beschreibung |
|----|-------------|
| Extern | eCH-0135 – Heimatort-Identifikationen |
| Extern | eCH-0007 – Gemeinden und Kantone |

---

## 5. Verwendungskontext

- Bestandteil von **BB-02 – Person**
- Rechtliche und registerbezogene Auswertungen

---

## 6. Versionierung

| Version | Datum | Beschreibung |
|--------|-------|--------------|
| 0.1.0 | YYYY-MM-DD | Initiale Überführung aus eCH-0011 v9.0.0 |

---

## 7. Quellen

- Verein eCH  
  **eCH-0011 – Datenstandard Personendaten**, Version 9.0.0  
  Kapitel 3.3.10 – *placeOfOrigin*

---

### Feedback

[Ankündigungen von eCH](https://github.com/etemizab/ech-schnittstellenstandard/discussions/categories/announcements)
· [Fehler melden](https://github.com/etemizab/ech-schnittstellenstandard/discussions/categories/q-a)
· [Verbesserung vorschlagen](https://github.com/etemizab/ech-schnittstellenstandard/discussions/categories/ideas)
· [Alle Diskussionen](https://github.com/etemizab/ech-schnittstellenstandard/discussions)

