# BB-07 – maritalData (Zivilstandsangaben)

![Version](https://img.shields.io/badge/version-0.1.0-blue)
&nbsp;&nbsp;Alle Versionen: [v0.1.0](martialData.md)

---

**Standard:** eCH-0011 – Datenstandard Personendaten  
**Block-Version:** 0.1.0  
**Status:** Draft  
**Quelle im Standard:** Kapitel 3.3.5 – maritalData

---

## 1. Zweck & fachliche Bedeutung

Der Building Block **Zivilstandsangaben (maritalData)** beschreibt den aktuellen Zivilstand einer Person sowie ergänzende Informationen zu Trennung oder Auflösung einer Ehe oder Partnerschaft.

Er bildet einen wichtigen rechtlichen Status ab, der sich im Lebensverlauf ändern kann.

---

## 2. Abgrenzung & Granularität

| Aspekt | Beschreibung |
|------|-------------|
| **Granularität** | Meso |
| **Rolle** | Rechtlicher Personenstatus |
| **Abgrenzung** | Keine Ereignisabfolge – Historisierung erfolgt ausserhalb dieses Blocks |

---

## 3. Struktur & Attribute

| Attribut | Pflicht | Beschreibung |
|---------|---------|--------------|
| `maritalStatus` | ja | Aktueller Zivilstand |
| `separationDate` | nein | Datum der Trennung |
| `separationReason` | nein | Grund der Trennung |

---

## 4. Abhängigkeiten

| Typ | Beschreibung |
|----|-------------|
| Intern | Keine |
| Extern | Codesysteme gemäss eCH-Vorgaben |

---

## 5. Verwendungskontext

- Bestandteil von **BB-02 – Person**
- Rechtliche und administrative Verfahren

---

## 6. Versionierung

| Version | Datum | Beschreibung |
|--------|-------|--------------|
| 0.1.0 | YYYY-MM-DD | Initiale Überführung aus eCH-0011 v9.0.0 |

---

## 7. Quellen

- Verein eCH  
  **eCH-0011 – Datenstandard Personendaten**, Version 9.0.0  
  Kapitel 3.3.5 – *maritalData*

---

### Feedback

[Ankündigungen von eCH](https://github.com/etemizab/ech-schnittstellenstandard/discussions/categories/announcements)
· [Fehler melden](https://github.com/etemizab/ech-schnittstellenstandard/discussions/categories/q-a)
· [Verbesserung vorschlagen](https://github.com/etemizab/ech-schnittstellenstandard/discussions/categories/ideas)
· [Alle Diskussionen](https://github.com/etemizab/ech-schnittstellenstandard/discussions)
