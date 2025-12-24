{\rtf1\ansi\ansicpg1252\cocoartf2822
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\paperw11900\paperh16840\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\pard\tx566\tx1133\tx1700\tx2267\tx2834\tx3401\tx3968\tx4535\tx5102\tx5669\tx6236\tx6803\pardirnatural\partightenfactor0

\f0\fs24 \cf0 # \uc0\u55357 \u56550  Building Block: BB-14 \'96 Wohnadresse (dwellingAddressType)\
\
> **Standard:** eCH-0011 \'96 Datenstandard Personendaten  \
> **Block-Version:** 0.1.0  \
> **Status:** Draft  \
> **Quelle im Standard:** Kapitel 3.4.5 \'96 dwellingAddressType\
\
## 1. Zweck & fachliche Bedeutung\
Der Building Block *Wohnadresse* beschreibt die konkrete Wohnsituation einer Person innerhalb eines Meldeverh\'e4ltnisses.  \
Er enth\'e4lt sowohl adressbezogene Informationen als auch wohnungs- und haushaltsbezogene Identifikatoren.\
\
## 2. Abgrenzung & Granularit\'e4t\
- **Granularit\'e4t:** Meso\
- **Rolle:** Physischer Aufenthaltsort\
- **Nicht f\'fcr Zustellung:** Zustelladressen sind separat modelliert\
\
## 3. Struktur & Attribute\
| Attribut | Pflicht | Beschreibung |\
|---|---|---|\
| address | ja | Physische Adresse |\
| EGID | nein | Geb\'e4udeidentifikator |\
| EWID | nein | Wohnungsidentifikator |\
| householdId | nein | Haushalt |\
| movingDate | nein | Einzugsdatum |\
\
## 4. Abh\'e4ngigkeiten\
**Externe Abh\'e4ngigkeiten**\
- eCH-0010 \'96 Adressstandard\
\
## 5. Verwendungskontext\
- Bestandteil von BB-13 \'96 Meldeverh\'e4ltnis\
- Wohnsitzverwaltung und Statistik\
\
## 6. Versionierung\
| Version | Datum | Beschreibung |\
|---|---|---|\
| 0.1.0 | YYYY-MM-DD | Initiale \'dcberf\'fchrung aus eCH-0011 v9.0.0 |\
\
## 7. Quellen\
- Verein eCH, eCH-0011 Datenstandard Personendaten, Version 9.0.0  \
- Kapitel 3.4.5}