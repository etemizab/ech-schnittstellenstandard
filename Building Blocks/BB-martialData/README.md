{\rtf1\ansi\ansicpg1252\cocoartf2822
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fnil\fcharset0 .AppleSystemUIFontMonospaced-Regular;}
{\colortbl;\red255\green255\blue255;\red14\green14\blue14;}
{\*\expandedcolortbl;;\cssrgb\c6700\c6700\c6700;}
\paperw11900\paperh16840\margl1440\margr1440\vieww19280\viewh14540\viewkind0
\pard\tx560\tx1120\tx1680\tx2240\tx2800\tx3360\tx3920\tx4480\tx5040\tx5600\tx6160\tx6720\sl324\slmult1\pardirnatural\partightenfactor0

\f0\fs28 \cf2 # \uc0\u55357 \u56550  Building Block: BB-07 \'96 Zivilstandsangaben (maritalData)\
\
> **Standard:** eCH-0011 \'96 Datenstandard Personendaten  \
> **Block-Version:** 0.1.0  \
> **Status:** Draft  \
> **Quelle im Standard:** Kapitel 3.3.5 \'96 maritalData\
\
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