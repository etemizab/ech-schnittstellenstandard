> **Standard:** eCH-0011 \'96 Datenstandard Personendaten  \
> **Block-Version:** 0.1.0  \
> **Status:** Draft  \
> **Quelle im Standard:** Kapitel 3.4 \'96 residenceData\
> 
## 1. Zweck & fachliche Bedeutung\
Der Building Block *Meldeverh\'e4ltnis* beschreibt die Beziehung einer Person zu einer Gemeinde im Rahmen eines Aufenthalts oder Wohnsitzes.  \
Er bildet Zuz\'fcge, Wegz\'fcge sowie bestehende Aufenthalte ab und ist zeitlich begrenzt.\

## 2. Abgrenzung & Granularit\'e4t\
- **Granularit\'e4t:** Meso\
- **Rolle:** Beziehungsobjekt zwischen Person und Gemeinde\
- **Nicht Teil der Identit\'e4t:** Das Meldeverh\'e4ltnis ist vom Personenobjekt getrennt modelliert\
\
## 3. Struktur & Attribute\
| Attribut | Pflicht | Beschreibung |\
|---|---|---|\
| reportingMunicipality | ja | Meldende Gemeinde |\
| residenceType | ja | Art des Meldeverh\'e4ltnisses |\
| arrival | nein | Zuzugsinformation |\
| departure | nein | Wegzugsinformation |\
| dwellingAddress | ja | Wohnadresse |\
\
## 4. Abh\'e4ngigkeiten\
**Interne Abh\'e4ngigkeiten**\
- BB-14 \'96 Wohnadresse\
- BB-15 \'96 Herkunfts-/Zielort\
\
**Externe Abh\'e4ngigkeiten**\
- eCH-0007 \'96 Gemeinden\
\
## 5. Verwendungskontext\
- Bestandteil von BB-01 \'96 ReportedPerson\
- Verwaltung von Wohn- und Aufenthaltsverh\'e4ltnissen\
\
## 6. Versionierung\
| Version | Datum | Beschreibung |\
|---|---|---|\
| 0.1.0 | YYYY-MM-DD | Initiale \'dcberf\'fchrung aus eCH-0011 v9.0.0 |\
\
## 7. Quellen\
- Verein eCH, eCH-0011 Datenstandard Personendaten, Version 9.0.0  \
- Kapitel 3.4}
