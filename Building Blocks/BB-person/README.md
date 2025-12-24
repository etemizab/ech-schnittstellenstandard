{\rtf1\ansi\ansicpg1252\cocoartf2822
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\paperw11900\paperh16840\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\pard\tx566\tx1133\tx1700\tx2267\tx2834\tx3401\tx3968\tx4535\tx5102\tx5669\tx6236\tx6803\pardirnatural\partightenfactor0

\f0\fs24 \cf0 # \uc0\u55357 \u56550  Building Block: BB-02 \'96 Person (personType)\
\
> **Standard:** eCH-0011 \'96 Datenstandard Personendaten  \
> **Block-Version:** 0.1.0  \
> **Status:** Draft  \
> **Quelle im Standard:** Kapitel 3.3 \'96 personType\
\
## 1. Zweck & fachliche Bedeutung\
Der Building Block *Person* beschreibt die grundlegende Identit\'e4t einer nat\'fcrlichen Person im Kontext des Einwohnerwesens.  \
Er fungiert als zentrales Fachobjekt und b\'fcndelt mehrere spezialisierte Building Blocks, welche unterschiedliche Aspekte der Person beschreiben.\
\
## 2. Abgrenzung & Granularit\'e4t\
- **Granularit\'e4t:** Meso (fachlich geschlossener Datentyp)\
- **Rolle:** Zentrales Kernobjekt\
- **Keine Aufenthaltsinformationen:** Wohn- und Meldeverh\'e4ltnisse sind bewusst ausgelagert\
\
Diese Trennung erlaubt eine klare Abgrenzung zwischen Identit\'e4t und Aufenthaltsbezug.\
\
## 3. Struktur & enthaltene Building Blocks\
| Enthaltener Block | Pflicht | Beschreibung |\
|---|---|---|\
| BB-03 \'96 Personenidentifikation | ja | Eindeutige Identifikation |\
| BB-04 \'96 Namensangaben | ja | Namen und Namensvarianten |\
| BB-05 \'96 Geburtsangaben | ja | Angaben zur Geburt |\
| BB-06 \'96 Konfession | ja | Religionszugeh\'f6rigkeit |\
| BB-07 \'96 Zivilstand | ja | Zivilstandsangaben |\
| BB-08 \'96 Staatsangeh\'f6rigkeit | ja | Nationalit\'e4ten |\
| BB-09 \'96 Todesangaben | nein | Angaben zum Todesfall |\
| BB-10 \'96 Kontaktangaben | nein | Zustell- und Kontaktinformationen |\
| BB-11 \'96 Heimatort | bedingt | Schweizer Personen |\
| BB-12 \'96 Ausl\'e4nderkategorie | bedingt | Personen ohne Schweizer Staatsangeh\'f6rigkeit |\
\
## 4. Abh\'e4ngigkeiten\
- interne Referenzen auf spezialisierte Person-Blocks\
- indirekte externe Referenzen \'fcber diese Blocks\
\
## 5. Verwendungskontext\
- Bestandteil von BB-01 \'96 ReportedPerson\
- Basisobjekt f\'fcr Personenabfragen und Register\
\
## 6. Versionierung\
| Version | Datum | Beschreibung |\
|---|---|---|\
| 0.1.0 | YYYY-MM-DD | Initiale \'dcberf\'fchrung aus eCH-0011 v9.0.0 |\
\
## 7. Quellen\
- Verein eCH, eCH-0011 Datenstandard Personendaten, Version 9.0.0\
- Kapitel 3.3}