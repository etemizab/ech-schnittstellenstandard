# BB-XX – nameData (Namensangaben)

![Version](https://img.shields.io/badge/version-0.1.0-blue)
&nbsp;&nbsp;Alle Versionen: [v0.1.0](nameData.md)

---

**Standard:** eCH-0011 – Datenstandard Personendaten  
**Block-Version:** 0.1.0  
**Status:** Draft  
**Quelle im Standard:** Kapitel 3.3.2 – nameData

---

## 1. Zweck & fachliche Bedeutung

Der Building Block **Namensangaben (nameData)** beschreibt die offiziellen Namen einer Person.  
Er umfasst Vor- und Nachnamen sowie optionale Namensvarianten wie Rufnamen oder ausländische Namensformen.

---

## 2. Abgrenzung & Granularität

| Aspekt | Beschreibung |
|------|-------------|
| **Granularität** | Meso |
| **Rolle** | Beschreibung der Namensidentität |
| **Abgrenzung** | Keine Identifikationsfunktion – Namen sind nicht eindeutig |

---

## 3. Struktur & Attribute

| Attribut | Pflicht | Beschreibung |
|---------|---------|--------------|
| `officialFirstName` | ja | Amtlicher Vorname |
| `officialLastName` | ja | Amtlicher Nachname |
| `aliasName` | nein | Alternativer Name |
| `foreignName` | nein | Ausländische Namensform |

---

## 4. Abhängigkeiten

| Typ | Beschreibung |
|----|-------------|
| Intern | Keine |
| Extern | Keine |

---

## 5. Verwendungskontext

- Bestandteil von **BB-02 – Person**
- Anzeige- und Suchzwecke

---

## 6. Versionierung

| Version | Datum | Beschreibung |
|--------|-------|--------------|
| 0.1.0 | YYYY-MM-DD | Initiale Überführung aus eCH-0011 v9.0.0 |

---

## 7. Quellen

- Verein eCH  
  **eCH-0011 – Datenstandard Personendaten**, Version 9.0.0  
  Kapitel 3.3.2 – *nameData*

---

### Feedback

[Ankündigungen von eCH](https://github.com/etemizab/ech-schnittstellenstandard/discussions/categories/announcements)
· [Fehler melden](https://github.com/etemizab/ech-schnittstellenstandard/discussions/categories/q-a)
· [Verbesserung vorschlagen](https://github.com/etemizab/ech-schnittstellenstandard/discussions/categories/ideas)
· [Alle Diskussionen](https://github.com/etemizab/ech-schnittstellenstandard/discussions)

