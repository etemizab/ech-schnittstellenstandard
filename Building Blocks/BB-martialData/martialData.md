> **Standard:** eCH-0011 \'96 Datenstandard Personendaten  \
> **Block-Version:** 0.1.0  \
> **Status:** Draft  \
> **Quelle im Standard:** Kapitel 3.3.5 \'96 maritalData\

## 1. Zweck & fachliche Bedeutung\
Der Building Block *Zivilstandsangaben* beschreibt den aktuellen Zivilstand einer Person sowie erg\'e4nzende Informationen zu Trennung oder Aufl\'f6sung einer Ehe oder Partnerschaft.\
\
Er bildet einen wichtigen rechtlichen Status ab, der sich im Lebensverlauf \'e4ndern kann.\
\
## 2. Abgrenzung & Granularit\'e4t\
- **Granularit\'e4t:** Meso\
- **Rolle:** Rechtlicher Personenstatus\
- **Keine Ereignisabfolge:** Historisierung erfolgt ausserhalb dieses Blocks\
\
## 3. Struktur & Attribute\
| Attribut | Pflicht | Beschreibung |\
|---|---|---|\
| maritalStatus | ja | Aktueller Zivilstand |\
| separationDate | nein | Datum der Trennung |\
| separationReason | nein | Grund der Trennung |\
\
## 4. Abh\'e4ngigkeiten\
- keine internen Abh\'e4ngigkeiten\
- Codesysteme gem\'e4ss eCH-Vorgaben\
\
## 5. Verwendungskontext\
- Bestandteil von BB-02 \'96 Person\
- Rechtliche und administrative Verfahren\
\
## 6. Versionierung\
| Version | Datum | Beschreibung |\
|---|---|---|\
| 0.1.0 | YYYY-MM-DD | Initiale \'dcberf\'fchrung aus eCH-0011 v9.0.0 |\
\
## 7. Quellen\
- Verein eCH, eCH-0011 Datenstandard Personendaten, Version 9.0.0  \
- Kapitel 3.3.5}
