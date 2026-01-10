# BB-13 – residenceData (Meldeverhältnis)

![Version](https://img.shields.io/badge/version-0.1.0-blue)
&nbsp;&nbsp;Alle Versionen: [v0.1.0](residenceData.md)

---

**Standard:** eCH-0011 – Datenstandard Personendaten  
**Block-Version:** 0.1.0  
**Status:** Draft  
**Quelle im Standard:** Kapitel 3.4 – residenceData

---

## 1. Zweck & fachliche Bedeutung

Der Building Block **Meldeverhältnis (residenceData)** beschreibt die Beziehung einer Person zu einer Gemeinde im Rahmen eines Aufenthalts oder Wohnsitzes.  
Er bildet Zuzüge, Wegzüge sowie bestehende Aufenthalte ab und ist zeitlich begrenzt.

---

## 2. Abgrenzung & Granularität

| Aspekt | Beschreibung |
|------|-------------|
| **Granularität** | Meso |
| **Rolle** | Beziehungsobjekt zwischen Person und Gemeinde |
| **Abgrenzung** | Nicht Teil der Identität – vom Personenobjekt getrennt modelliert |

---

## 3. Struktur & Attribute

| Attribut | Pflicht | Beschreibung |
|---------|---------|--------------|
| `reportingMunicipality` | ja | Meldende Gemeinde |
| `residenceType` | ja | Art des Meldeverhältnisses |
| `arrival` | nein | Zuzugsinformation |
| `departure` | nein | Wegzugsinformation |
| `dwellingAddress` | ja | Wohnadresse |

---

## 4. Abhängigkeiten

| Typ | Beschreibung |
|----|-------------|
| Intern | BB-14 – Wohnadresse |
| Intern | BB-15 – Herkunfts-/Zielort |
| Extern | eCH-0007 – Gemeinden |

---

## 5. Verwendungskontext

- Bestandteil von **BB-01 – ReportedPerson**
- Verwaltung von Wohn- und Aufenthaltsverhältnissen

---

## 6. Versionierung

| Version | Datum | Beschreibung |
|--------|-------|--------------|
| 0.1.0 | YYYY-MM-DD | Initiale Überführung aus eCH-0011 v9.0.0 |

---

## 7. Quellen

- Verein eCH  
  **eCH-0011 – Datenstandard Personendaten**, Version 9.0.0  
  Kapitel 3.4 – *residenceData*

---

### Feedback

[Ankündigungen von eCH](https://github.com/etemizab/ech-schnittstellenstandard/discussions/categories/announcements)
· [Fehler melden](https://github.com/etemizab/ech-schnittstellenstandard/discussions/categories/q-a)
· [Verbesserung vorschlagen](https://github.com/etemizab/ech-schnittstellenstandard/discussions/categories/ideas)
· [Alle Diskussionen](https://github.com/etemizab/ech-schnittstellenstandard/discussions)
