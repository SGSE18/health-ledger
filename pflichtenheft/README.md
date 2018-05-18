# Anforderungs- und Entwurfsspezifikation ("Pflichtenheft")

Health Ledger: Die digitale Patientenakte

Autoren: ...

# 1 Einführung

## 1.1 Beschreibung (Mario)
Als besonders schutzbedürftige Informationssammlung ist die Krankenakte tief in die persönliche Privatsphäre eingebettet. Die Kontrolle, wer wann in welchem Umfang Zugriff auf Krankendaten erhält, ist im aktuellen Gesundheitssystem für den Patienten nicht nur mangelhaft nachvollziehbar, sondern auch erheblich durch die segmentierte Vorhaltung in verteilten Heilanstalten und Versicherungsdienststellen erschwert. Auch wenn eine zentralisierte Patientenkartei diesen Problemen eine Lösung zu sein scheint, ergeben sich im Rahmen einer institutionalisierten Form der Datenhaltung neue Hürden der administrativen Intransparenz. Medizinische Informationsüberlassungen wären lediglich ein gewährter Dienst einer Körperschaft anstatt sich in echter Kontrolle durch den Informationseigner zu konkretisieren.

HealthLedger ist die innovative Antwort auf das Verlangen nach dezentraler und sicherer Speicherung der Gesundheitshistorie bei gleichzeitig höchstpersönlicher Zugriffskontrolle.
Mit Hilfe der verteilten Blockchain-Technologie und modernster Kryptoverfahren wird sichergestellt, dass keine Institution einer Informationsauskunft ohne Einbezug und Einwilligung des Patienten nachkommen kann.

Als Grundbedingung des Heilerfolges ist die Unterstützung der bestmöglichen Zusammenarbeit von Patient, Arzt und Versicherer das höchste Ziel von HealthLedger. Der Mechanismus vereint deshalb die Bedürfnisse aller am Genesungsprozess beteiligten Weggefährten. Dank der Garantie informationeller Selbstbestimmung wird dabei erstmalig eine echte Verantwortungsbalance geschaffen.


## 1.2 Ziele
Features von HealthLedger

* Die unkontrollierbare, nicht nachvollziehbar verteilte Patienteninformation wird durch Digitalisierung in eine elektronische, konzeptionell zentrale Akte überführt.

* Vollständige Kontrolle über die Freigabe der Patientendaten liegt mit variabel wählbarer Transparenzgranularität beim Informationseigner selbst.

* Dank der elektronischen Persistierung kann die Krankenakte global abgerufen und eingesehen werden. Auf Reisen übliche medizinische Sonderdokumente sind somit vollständig ersetzbar. Behandlungsrisiken können zu jeder Zeit an jedem Ort der Welt korrekt von medizinischem Fachpersonal evaluiert werden um den Behandlungserfolg auch in Notfällen sicherstellen zu können.

* Therapiegenehmigungsverfahren werden mittels smarter Vernetzung aller Beteiligten massiv beschleunigt. Die Reduktion von Verzögerungen der Genesung ist das immanente Resultat.

* Durch Chaincode-Verschreibungen wird die papierlose Medikation ermöglicht. Nicht nur ist die Wahrscheinlichkeit einer Falschverabreichung rigoros eingedämmt, der Verarbeitungskomfort für Apotheker und Versicherer steigt zusätzlich deutlich.

* Gemessen an den sehr unterschiedlichen Bedürfnissen und Hintergründen der Systemnutzer liefert HealthLedger maßgeschneiderte Oberflächen für das Anwenderspektrum zwischen medizinischem Laien, Facharzt und Versicherungsdienstleister. Im gleichen Zuge kann als Zusatzvorteil eine selektive Kurzeinsicht gewährt werden, um zum Beispiel den Arbeitgeber frühzeitig und papierlos über eine Krankmeldung zu informieren.
 
HealthLedger bringt die Idee der Krankenakte nach zeitgemäßem technischen Standard in das 21. Jahrhundert. Anders als in Abrechnungs-Softwaresystemen, die gezielt für Versicherungseinrichtungen an den Markt gebracht wurden und Krankendokumente nur als bruchstückhafte Artefakte erzeugen, steht für HealthLedger die Kooperation mit dem Patienten im klaren Fokus. HealthLedger entfernt die unpersönliche Versicherungsbuchhaltung von jenem, was im Mittelpunkt stehen sollte: dem Menschen.


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
Dass die zu speichernden Daten einen besonderen Schutzfaktor aufweisen, soll ein treibender Faktor beim Entwurf des Systems darstellen. Es soll ein Verschlüsselungskonzept entworfen werden, welches den Betrieb der Hyperledger-Blockchain durch Versicherer und ähnliche Gremien erlaubt und gleichzeitig keinen Zweifel an der Sicherheit privater Informationen zulässt. Patienten soll keine Notwendigkeit der aktiven Teilnahme an der Validierung ("Mining") im Sinne des Blockchain-Protokolls aufgezwungen werden. Diese Leistung soll allein bei institutionalisierten Systemteilnehmern mit Cashflow liegen. Damit diese teilprivate Blockchain dennoch mit allen regulatorischen Ansprüchen an den Datenschutz konform ist, wird ein Komplementärkonzept zu den bereits in der Hyperledger-Technologie enthaltenen Kryptoprinzipien erarbeitet. Hyperledger-Nodes sollen durch nicht-private Nutzer betrieben werden können, ohne dass deren Position zu einer erweiterten Einflussnahme auf gespeicherte Daten bevollmächtigt.

### 2.2.2 Betriebsbedingungen
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
