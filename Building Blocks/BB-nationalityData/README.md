{\rtf1\ansi\ansicpg1252\cocoartf2822
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\paperw11900\paperh16840\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\pard\tx566\tx1133\tx1700\tx2267\tx2834\tx3401\tx3968\tx4535\tx5102\tx5669\tx6236\tx6803\pardirnatural\partightenfactor0

\f0\fs24 \cf0 # \uc0\u55357 \u56550  Building Block: BB-08 \'96 Staatsangeh\'f6rigkeit (nationalityData)\
\
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