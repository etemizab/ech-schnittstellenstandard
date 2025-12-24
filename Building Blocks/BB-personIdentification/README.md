{\rtf1\ansi\ansicpg1252\cocoartf2822
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\paperw11900\paperh16840\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\pard\tx566\tx1133\tx1700\tx2267\tx2834\tx3401\tx3968\tx4535\tx5102\tx5669\tx6236\tx6803\pardirnatural\partightenfactor0

\f0\fs24 \cf0 # \uc0\u55357 \u56550  Building Block: BB-03 \'96 Personenidentifikation (personIdentificationType)\
\
> **Standard:** eCH-0011 \'96 Datenstandard Personendaten  \
> **Block-Version:** 0.1.0  \
> **Status:** Draft  \
> **Quelle im Standard:** Kapitel 3.3.1 \'96 personIdentificationType\
\
## 1. Zweck & fachliche Bedeutung\
Der Building Block *Personenidentifikation* stellt die eindeutige Identifikation einer Person sicher.  \
Er basiert auf dem externen Standard eCH-0044 und erm\'f6glicht die eindeutige Referenzierung einer Person \'fcber standardisierte Identifikatoren.\
\
## 2. Abgrenzung & Granularit\'e4t\
- **Granularit\'e4t:** Meso (referenzierter Datentyp)\
- **Rolle:** Identifikation\
- **Keine fachlichen Attribute:** ausschlie\'dflich Identifikationsmerkmale\
\
## 3. Struktur (fachliche \'dcbersicht)\
| Attribut | Pflicht | Beschreibung |\
|---|---|---|\
| identificationNumber | ja | Eindeutige Personenkennung |\
| identificationType | ja | Typ der Kennung |\
\
## 4. Abh\'e4ngigkeiten\
**Externe Abh\'e4ngigkeiten**\
- eCH-0044 \'96 Personenidentifikation\
\
## 5. Verwendungskontext\
- Bestandteil von BB-02 \'96 Person\
- Referenzierung in anderen fachlichen Kontexten\
\
## 6. Versionierung\
| Version | Datum | Beschreibung |\
|---|---|---|\
| 0.1.0 | YYYY-MM-DD | Initiale Referenz auf eCH-0044 |\
\
## 7. Quellen\
- Verein eCH, eCH-0011 Datenstandard Personendaten, Version 9.0.0\
- Kapitel 3.3.1}