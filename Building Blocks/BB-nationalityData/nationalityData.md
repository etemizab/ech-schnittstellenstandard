> **Standard:** eCH-0011 \'96 Datenstandard Personendaten  \
> **Block-Version:** 0.1.0  \
> **Status:** Draft  \
> **Quelle im Standard:** Kapitel 3.3.6 \'96 nationalityData\
\
## 1. Zweck & fachliche Bedeutung\
Der Building Block *Staatsangeh\'f6rigkeit* beschreibt die rechtliche Zugeh\'f6rigkeit einer Person zu einem oder mehreren Staaten.  \
Er ber\'fccksichtigt sowohl den aktuellen Status als auch zus\'e4tzliche Informationen zu einzelnen Staatsangeh\'f6rigkeiten.\
\
## 2. Abgrenzung & Granularit\'e4t\
- **Granularit\'e4t:** Meso\
- **Rolle:** Rechtlicher Identit\'e4tsaspekt\
- **Mehrfachzugeh\'f6rigkeit:** Mehrere Staatsangeh\'f6rigkeiten m\'f6glich\
\
## 3. Struktur & Attribute\
| Attribut | Pflicht | Beschreibung |\
|---|---|---|\
| nationalityStatus | ja | Status der Staatsangeh\'f6rigkeit |\
| countryInfo | nein | Informationen zu einzelnen Staaten |\
\
## 4. Abh\'e4ngigkeiten\
**Externe Abh\'e4ngigkeiten**\
- eCH-0008 \'96 Staaten / L\'e4ndercodes\
\
## 5. Verwendungskontext\
- Bestandteil von BB-02 \'96 Person\
- Migrations- und Registerprozesse\
\
## 6. Versionierung\
| Version | Datum | Beschreibung |\
|---|---|---|\
| 0.1.0 | YYYY-MM-DD | Initiale \'dcberf\'fchrung aus eCH-0011 v9.0.0 |\
\
## 7. Quellen\
- Verein eCH, eCH-0011 Datenstandard Personendaten, Version 9.0.0  \
- Kapitel 3.3.6}
