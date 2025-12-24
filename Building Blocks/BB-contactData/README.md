{\rtf1\ansi\ansicpg1252\cocoartf2822
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\paperw11900\paperh16840\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\pard\tx566\tx1133\tx1700\tx2267\tx2834\tx3401\tx3968\tx4535\tx5102\tx5669\tx6236\tx6803\pardirnatural\partightenfactor0

\f0\fs24 \cf0 # \uc0\u55357 \u56550  Building Block: BB-10 \'96 Kontaktangaben (contactData)\
\
> **Standard:** eCH-0011 \'96 Datenstandard Personendaten  \
> **Block-Version:** 0.1.0  \
> **Status:** Draft  \
> **Quelle im Standard:** Kapitel 3.3.8 \'96 contactData\
\
## 1. Zweck & fachliche Bedeutung\
Der Building Block *Kontaktangaben* beschreibt die postalischen und optionalen elektronischen Kontaktinformationen einer Person.  \
Er dient prim\'e4r der Zustellung von amtlicher Korrespondenz.\
\
## 2. Abgrenzung & Granularit\'e4t\
- **Granularit\'e4t:** Meso\
- **Rolle:** Kommunikations- und Zustellinformation\
- **Keine Wohnsitzdefinition:** Wohnadressen werden im Meldeverh\'e4ltnis gef\'fchrt\
\
## 3. Struktur & Attribute\
| Attribut | Pflicht | Beschreibung |\
|---|---|---|\
| contactAddress | ja | Zustelladresse |\
| identification | nein | Referenzierte Identifikatoren |\
\
## 4. Abh\'e4ngigkeiten\
**Externe Abh\'e4ngigkeiten**\
- eCH-0010 \'96 Adressstandard\
- eCH-0044 \'96 Personenidentifikation (optional)\
\
## 5. Verwendungskontext\
- Bestandteil von BB-02 \'96 Person\
- Zustellung von amtlichen Dokumenten\
\
## 6. Versionierung\
| Version | Datum | Beschreibung |\
|---|---|---|\
| 0.1.0 | YYYY-MM-DD | Initiale \'dcberf\'fchrung aus eCH-0011 v9.0.0 |\
\
## 7. Quellen\
- Verein eCH, eCH-0011 Datenstandard Personendaten, Version 9.0.0  \
- Kapitel 3.3.8}