# Anforderungs- und Entwurfsspezifikation ("Pflichtenheft")

Health Ledger: Die digitale Patientenakte

Autoren: ...

# 1 Einführung

## 1.1 Beschreibung (Mario)
* Projektname: Hea(L)th Ledger. Endorsed by Heath Ledger.
* Darstellung der Produktvision in Prosa (5-10 Sätze) (Mario)

## 1.2 Ziele
* Anwendungsbereiche, Motivation, Umfang, Marktanforderungen, Alleinstellungsmerkmale (Mario)
* Krankenakte in der Blockchain
* Vollständige Kontrolle über Freigabe der Patientendaten liegt mit variabler Transparenzgranularität beim Nutzer selbst
* Einsehbar von Ärzten auf der ganzen Welt
* Smartes Therapiegenehmigungsverfahren
* Rezeptfreie Medikation über Chaincode-Verschreibungen
* Informationen zu Zielbenutzergruppen und deren Merkmale (Bildung, Erfahrung, Sachkenntnis)
* Abgrenzung (Was ist das Softwaresystem _nicht_)
* Abrechnung / Zahlung

# 2 Anforderungen

## 2.1 Funktionale Anforderungen
* Use-Case Diagramme (Matthias/Mario)

  Vorerst Draw.io XML geshared per GoogleDrive:

  https://drive.google.com/file/d/1pAMpS3cQI8lluesfpWAqOeUHeMnuNVrb/view?usp=sharing

* Akteure
 * Versicherungen
   * “Behandlungen validieren”
 * Apotheker
   * “Smart-Rezept einsehen.”
 * Ärzte
   * “Behandlungen festhalten.”
 * Patienten
   * “Transparenz kontrollieren.”
 * Arbeitgeber
   * “Krankschreibungen einsehen.”

* Strukturierung der Diagramme in funktionale Gruppen (Matthias/Mario)

## 2.2 Nicht-funktionale Anforderungen

### 2.2.1 Rahmenbedingungen
* Normen, Standards, Protokolle, Hardware, externe Vorgaben

### 2.2.2 Betriebsbedingungen
* Vorgaben des Kunden (z.B. Web Browser / Betriebssystem Versionen, Programmiersprache)
* Hyperledger
* Webapp

### 2.2.3 Qualitätsmerkmale (Fynn/Patrick)
* Externe Qualitätsanforderungen: Performance, Sicherheit, Zuverlässigkeit, Benutzerfreundlichkeit

## 2.3 Graphische Benutzerschnittstelle (Fynn/Patrick)
* GUI-Mockups passend zu User Stories
* Modellierung der Navigation zwischen den Screens der GUI-Mockups als Zustandsdiagramm

## 2.4 Anforderungen im Detail (Alle)
* User Stories mit Akzeptanzkritierien
* Optional: Name (oder ID) und Priorität ("Must", "Should", "Could", "Won't")
* Strukturierung der User Stories in funktionale Gruppen

### Schablone für User Stories

| **Als** | **möchte ich** | **so dass** | **Akzeptanz** |
| :------ | :----- | :------ | :-------- |
| Wer | Was | Warum | Wann akzeptiert |

Vorerst geshared per Google Tables:

https://docs.google.com/spreadsheets/d/1EZi6x1SPVpHn4N_kmLJ6R4SVIBvgqvcm2nRK712TtfE/edit?usp=sharing

# 3 Technische Beschreibung (Nils/Kevin/Cem)

## 3.1 Systemübersicht
* Systemarchitekturdiagramm ("Box-And-Arrow" Diagramm)
* Schnittstellenbeschreibung
* Kommunikationsprotokolle, Datenformate

## 3.2 Softwarearchitektur
* Darstellung von Softwarebausteinen (Module, Schichten, Komponenten)

## 3.3 Datenmodell
* Konzeptionelles Analyseklassendiagramm

## 3.4 Abläufe
* Aktivitätsdiagramme für relevante Use Cases
* Aktivitätsdiagramm für den Ablauf sämtlicher Use Cases

## 3.5 Entwurf
* Detaillierte UML-Diagramme für relevante Softwarebausteine

# 4 Projektorganisation

## 4.1 Annahmen
* Nicht durch den Kunden definierte spezifische Annahmen, Anforderungen und Abhängigkeiten
* Verwendete Technologien (Programmiersprache, Frameworks, etc.)
* Einschränkungen, Betriebsbedingungen und Faktoren, die die Entwicklung beeinflussen (Betriebssysteme, Entwicklungsumgebung)
* Interne Qualitätsanforderungen (z.B. Softwarequalitätsmerkmale wie z.B. Erweiterbarkeit)

## 4.2 Verantwortlichkeiten
* Zuordnung von Personen zu Softwarebausteinen aus Kapitel 3.1 und 3.2
* Rollendefinition und Zuordnung

## 4.3 Grober Projektplan
* Meilensteine

# 5 Anhänge

## 5.1 Glossar
* Definitionen, Abkürzungen, Begriffe

## 5.2 Referenzen
* Handbücher, Gesetze

## 5.3 Index
