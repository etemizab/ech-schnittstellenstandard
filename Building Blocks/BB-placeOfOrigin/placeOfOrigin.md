> **Standard:** eCH-0011 \'96 Datenstandard Personendaten  \
> **Block-Version:** 0.1.0  \
> **Status:** Draft  \
> **Quelle im Standard:** Kapitel 3.3.10 \'96 placeOfOrigin\

## 1. Zweck & fachliche Bedeutung\
Der Building Block *Heimatort* beschreibt den rechtlich definierten Heimatort einer Person.  \
Er ist insbesondere f\'fcr Personen mit Schweizer Staatsangeh\'f6rigkeit relevant und stellt eine dauerhafte rechtliche Zuordnung dar, unabh\'e4ngig vom aktuellen Wohnort.\
\
## 2. Abgrenzung & Granularit\'e4t\
- **Granularit\'e4t:** Meso\
- **Rolle:** Rechtliche Herkunftsangabe\
- **Nicht gleich Wohnort:** Der Heimatort ist keine Aufenthalts- oder Adressinformation\
\
## 3. Struktur & Attribute\
| Attribut | Pflicht | Beschreibung |\
|---|---|---|\
| originName | ja | Name des Heimatorts |\
| canton | ja | Kanton des Heimatorts |\
| originId | nein | Eindeutige Identifikation des Heimatorts |\
\
## 4. Abh\'e4ngigkeiten\
**Externe Abh\'e4ngigkeiten**\
- eCH-0135 \'96 Heimatort-Identifikationen\
- eCH-0007 \'96 Gemeinden und Kantone\
\
## 5. Verwendungskontext\
- Bestandteil von BB-02 \'96 Person\
- Rechtliche und registerbezogene Auswertungen\
\
## 6. Versionierung\
| Version | Datum | Beschreibung |\
|---|---|---|\
| 0.1.0 | YYYY-MM-DD | Initiale \'dcberf\'fchrung aus eCH-0011 v9.0.0 |\
\
## 7. Quellen\
- Verein eCH, eCH-0011 Datenstandard Personendaten, Version 9.0.0  \
- Kapitel 3.3.10}
