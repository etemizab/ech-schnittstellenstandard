{\rtf1\ansi\ansicpg1252\cocoartf2822
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\paperw11900\paperh16840\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\pard\tx566\tx1133\tx1700\tx2267\tx2834\tx3401\tx3968\tx4535\tx5102\tx5669\tx6236\tx6803\pardirnatural\partightenfactor0

\f0\fs24 \cf0 # \uc0\u55357 \u56550  Building Block: BB-01 \'96 ReportedPerson (reportedPersonType)\
\
> **Standard:** eCH-0011 \'96 Datenstandard Personendaten  \
> **Block-Version:** 0.1.0  \
> **Status:** Draft  \
> **Quelle im Standard:** Kapitel 3.2 \'96 reportedPersonType\
\
## 1. Zweck & fachliche Bedeutung\
Der Building Block *ReportedPerson* dient als oberstes Austauschobjekt im Standard eCH-0011.  \
Er fasst die fachlichen Informationen zu einer Person sowie zu einem oder mehreren Meldeverh\'e4ltnissen zusammen und bildet damit die vollst\'e4ndige Meldung im Kontext des Einwohnerwesens ab.\
\
Der Block selbst enth\'e4lt keine fachlichen Detailinformationen, sondern fungiert als strukturierender Container f\'fcr andere Building Blocks.\
\
## 2. Abgrenzung & Granularit\'e4t\
- **Granularit\'e4t:** Container (oberhalb der Meso-Ebene)\
- **Rolle:** Aggregation und Austausch\
- **Kein eigenst\'e4ndiger Fachblock:** Keine eigenen Attribute mit fachlicher Bedeutung\
\
Der Block wird bewusst nicht als eigenst\'e4ndiger Meso-Building-Block betrachtet, da er keinen eigenen fachlichen Lebenszyklus besitzt.\
\
## 3. Struktur & enthaltene Building Blocks\
| Enthaltener Block | Kardinalit\'e4t | Beschreibung |\
|---|---|---|\
| BB-02 \'96 Person | 1 | Zentrale Personeninformationen |\
| BB-13 \'96 Meldeverh\'e4ltnis | 1..n | Wohn- und Aufenthaltsverh\'e4ltnisse |\
\
## 4. Abh\'e4ngigkeiten\
**Interne Abh\'e4ngigkeiten**\
- BB-02 \'96 Person (contains)\
- BB-13 \'96 Meldeverh\'e4ltnis (contains)\
\
**Externe Abh\'e4ngigkeiten**\
- keine direkten externen Referenzen\
\
## 5. Verwendungskontext\
- Root-Element beim Austausch von Personendaten\
- Einstiegspunkt f\'fcr API-basierte Schnittstellen\
- \'dcbermittlung vollst\'e4ndiger Personenmeldungen\
\
## 6. Versionierung\
| Version | Datum | Beschreibung |\
|---|---|---|\
| 0.1.0 | YYYY-MM-DD | Initiale \'dcberf\'fchrung aus eCH-0011 v9.0.0 |\
\
## 7. Quellen\
- Verein eCH, eCH-0011 Datenstandard Personendaten, Version 9.0.0\
- Kapitel 3.2}