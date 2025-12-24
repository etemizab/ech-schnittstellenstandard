{\rtf1\ansi\ansicpg1252\cocoartf2822
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\paperw11900\paperh16840\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\pard\tx566\tx1133\tx1700\tx2267\tx2834\tx3401\tx3968\tx4535\tx5102\tx5669\tx6236\tx6803\pardirnatural\partightenfactor0

\f0\fs24 \cf0 # \uc0\u55357 \u56550  Building Block: BB-05 \'96 Geburtsangaben (birthData)\
\
> **Standard:** eCH-0011 \'96 Datenstandard Personendaten  \
> **Block-Version:** 0.1.0  \
> **Status:** Draft  \
> **Quelle im Standard:** Kapitel 3.3.3 \'96 birthData\
\
## 1. Zweck & fachliche Bedeutung\
Der Building Block *Geburtsangaben* beschreibt grundlegende Informationen zur Geburt einer Person.  \
Er stellt einen stabilen und unver\'e4nderlichen Bestandteil der Personenidentit\'e4t dar.\
\
## 2. Abgrenzung & Granularit\'e4t\
- **Granularit\'e4t:** Meso\
- **Rolle:** Beschreibung eines historischen Ereignisses\
- **Keine Prozesslogik:** rein beschreibend\
\
## 3. Struktur & Attribute\
| Attribut | Pflicht | Beschreibung |\
|---|---|---|\
| dateOfBirth | ja | Geburtsdatum |\
| placeOfBirth | nein | Geburtsort |\
| sex | nein | Geschlecht |\
\
## 4. Abh\'e4ngigkeiten\
- keine internen Abh\'e4ngigkeiten\
- optionale externe Referenzen (z. B. Orte)\
\
## 5. Verwendungskontext\
- Bestandteil von BB-02 \'96 Person\
- Basisinformation f\'fcr Register und Identifikation\
\
## 6. Versionierung\
| Version | Datum | Beschreibung |\
|---|---|---|\
| 0.1.0 | YYYY-MM-DD | Initiale \'dcberf\'fchrung aus eCH-0011 v9.0.0 |\
\
## 7. Quellen\
- Verein eCH, eCH-0011 Datenstandard Personendaten, Version 9.0.0\
- Kapitel 3.3.3}