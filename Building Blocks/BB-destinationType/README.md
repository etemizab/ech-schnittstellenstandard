{\rtf1\ansi\ansicpg1252\cocoartf2822
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fnil\fcharset0 .AppleSystemUIFontMonospaced-Regular;}
{\colortbl;\red255\green255\blue255;\red14\green14\blue14;}
{\*\expandedcolortbl;;\cssrgb\c6700\c6700\c6700;}
\paperw11900\paperh16840\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\pard\tx560\tx1120\tx1680\tx2240\tx2800\tx3360\tx3920\tx4480\tx5040\tx5600\tx6160\tx6720\sl324\slmult1\pardirnatural\partightenfactor0

\f0\fs28 \cf2 # \uc0\u55357 \u56550  Building Block: BB-15 \'96 Herkunfts-/Zielort (destinationType)\
\
> **Standard:** eCH-0011 \'96 Datenstandard Personendaten  \
> **Block-Version:** 0.1.0  \
> **Status:** Draft  \
> **Quelle im Standard:** Kapitel 3.9 \'96 destinationType\
\
## 1. Zweck & fachliche Bedeutung\
Der Building Block *Herkunfts-/Zielort* beschreibt den geografischen Ursprung oder das Ziel eines Zu- oder Wegzugs.  \
Er kann sowohl Schweizer Gemeinden als auch ausl\'e4ndische Staaten oder unbekannte Orte abbilden.\
\
## 2. Abgrenzung & Granularit\'e4t\
- **Granularit\'e4t:** Meso\
- **Rolle:** Ortsangabe in Bewegungsinformationen\
- **Keine Adresspflicht:** Optional kann eine Postadresse angegeben werden\
\
## 3. Struktur & Attribute\
| Attribut | Pflicht | Beschreibung |\
|---|---|---|\
| destinationType | ja | Typ des Ortes (Schweiz, Ausland, unbekannt) |\
| swissTown | nein | Schweizer Gemeinde |\
| foreignCountry | nein | Ausl\'e4ndischer Staat |\
| mailAddress | nein | Postadresse |\
\
## 4. Abh\'e4ngigkeiten\
**Externe Abh\'e4ngigkeiten**\
- eCH-0007 \'96 Gemeinden\
- eCH-0008 \'96 Staaten\
- eCH-0010 \'96 Adressen (optional)\
\
## 5. Verwendungskontext\
- Bestandteil von BB-13 \'96 Meldeverh\'e4ltnis\
- Angabe von Herkunft und Ziel bei Zu- und Wegz\'fcgen\
\
## 6. Versionierung\
| Version | Datum | Beschreibung |\
|---|---|---|\
| 0.1.0 | YYYY-MM-DD | Initiale \'dcberf\'fchrung aus eCH-0011 v9.0.0 |\
\
## 7. Quellen\
- Verein eCH, eCH-0011 Datenstandard Personendaten, Version 9.0.0  \
- Kapitel 3.9}