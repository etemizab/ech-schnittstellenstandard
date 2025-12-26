> **Standard:** eCH-0011 \'96 Datenstandard Personendaten  \
> **Block-Version:** 0.1.0  \
> **Status:** Draft  \
> **Quelle im Standard:** Kapitel 3.3.11 \'96 residencePermitData\

## 1. Zweck & fachliche Bedeutung\
Der Building Block *Ausl\'e4nderkategorie* beschreibt den ausl\'e4nderrechtlichen Status einer Person ohne Schweizer Staatsangeh\'f6rigkeit.  \
Er enth\'e4lt Informationen zur Art der Aufenthaltsbewilligung sowie zu deren zeitlicher G\'fcltigkeit.\
\
## 2. Abgrenzung & Granularit\'e4t\
- **Granularit\'e4t:** Meso\
- **Rolle:** Rechtlicher Aufenthaltsstatus\
- **Nicht gleich Wohnsitz:** Der Block beschreibt keine Adresse oder Meldeverh\'e4ltnisse\
\
## 3. Struktur & Attribute\
| Attribut | Pflicht | Beschreibung |\
|---|---|---|\
| residencePermit | ja | Art der Aufenthaltsbewilligung |\
| validFrom | nein | G\'fcltig ab |\
| validTo | nein | G\'fcltig bis |\
| entryDate | nein | Datum der Einreise |\
\
## 4. Abh\'e4ngigkeiten\
**Externe Abh\'e4ngigkeiten**\
- eCH-0006 \'96 Aufenthaltsbewilligungen\
\
## 5. Verwendungskontext\
- Bestandteil von BB-02 \'96 Person\
- Migrations- und ausl\'e4nderrechtliche Verfahren\
\
## 6. Versionierung\
| Version | Datum | Beschreibung |\
|---|---|---|\
| 0.1.0 | YYYY-MM-DD | Initiale \'dcberf\'fchrung aus eCH-0011 v9.0.0 |\
\
## 7. Quellen\
- Verein eCH, eCH-0011 Datenstandard Personendaten, Version 9.0.0  \
- Kapitel 3.3.11}
