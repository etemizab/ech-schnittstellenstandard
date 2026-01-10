# BB-XX – destinationType (Herkunfts-/Zielort)

![Version](https://img.shields.io/badge/version-0.1.0-blue)
&nbsp;&nbsp;Alle Versionen: [v0.1.0](destinationType.md)

---

**Standard:** eCH-0011 – Datenstandard Personendaten  
**Block-Version:** 0.1.0  
**Status:** Draft  
**Quelle im Standard:** Kapitel 3.9 – destinationType

---

## 1. Zweck & fachliche Bedeutung

Der Building Block **Herkunfts-/Zielort (destinationType)** beschreibt den geografischen Ursprung oder das Ziel eines Zu- oder Wegzugs.  
Er kann sowohl Schweizer Gemeinden als auch ausländische Staaten oder unbekannte Orte abbilden.

---

## 2. Abgrenzung & Granularität

| Aspekt | Beschreibung |
|------|-------------|
| **Granularität** | Meso |
| **Rolle** | Ortsangabe in Bewegungsinformationen |
| **Abgrenzung** | Keine Adresspflicht – optional kann eine Postadresse angegeben werden |

---

## 3. Struktur & Attribute

| Attribut | Pflicht | Beschreibung |
|---------|---------|--------------|
| `destinationType` | ja | Typ des Ortes (Schweiz, Ausland, unbekannt) |
| `swissTown` | nein | Schweizer Gemeinde |
| `foreignCountry` | nein | Ausländischer Staat |
| `mailAddress` | nein | Postadresse |

---

## 4. Abhängigkeiten

| Typ | Beschreibung |
|----|-------------|
| Extern | eCH-0007 – Gemeinden |
| Extern | eCH-0008 – Staaten |
| Extern | eCH-0010 – Adressen (optional) |

---

## 5. Verwendungskontext

- Bestandteil von **BB-13 – Meldeverhältnis**
- Angabe von Herkunft und Ziel bei Zu- und Wegzügen

---

## 6. Versionierung

| Version | Datum | Beschreibung |
|--------|-------|--------------|
| 0.1.0 | YYYY-MM-DD | Initiale Überführung aus eCH-0011 v9.0.0 |

---

## 7. Quellen

- Verein eCH  
  **eCH-0011 – Datenstandard Personendaten**, Version 9.0.0  
  Kapitel 3.9 – *destinationType*

---

### Feedback

[Ankündigungen von eCH](https://github.com/etemizab/ech-schnittstellenstandard/discussions/categories/announcements)
· [Fehler melden](https://github.com/etemizab/ech-schnittstellenstandard/discussions/categories/q-a)
· [Verbesserung vorschlagen](https://github.com/etemizab/ech-schnittstellenstandard/discussions/categories/ideas)
· [Alle Diskussionen](https://github.com/etemizab/ech-schnittstellenstandard/discussions)

