# Anforderungs- und Entwurfsspezifikation ("Pflichtenheft")

Health Ledger: Die digitale Patientenakte

Autoren: ...

# 1 Einführung

## 1.1 Beschreibung (Mario)
Als besonders schutzbedürftige Informationssammlung ist die Krankenakte tief in die persönliche Privatsphäre eingebettet. Die Kontrolle, wer wann in welchem Umfang Zugriff auf Krankendaten erhält, ist im aktuellen Gesundheitssystem für den Patienten nicht nur mangelhaft nachvollziehbar, sondern auch erheblich durch die segmentierte Vorhaltung in verteilten Heilanstalten und Versicherungsdienststellen erschwert. Auch wenn eine zentralisierte Patientenkartei diesen Problemen eine Lösung zu sein scheint, ergeben sich im Rahmen einer institutionalisierten Form der Datenhaltung neue Hürden der administrativen Intransparenz. Medizinische Informationsüberlassungen wären lediglich ein gewährter Dienst einer Körperschaft anstatt sich in echter Kontrolle durch den Informationseigner zu konkretisieren.

HealthLedger ist die innovative Antwort auf das Verlangen nach dezentraler und sicherer Speicherung der Gesundheitshistorie bei gleichzeitig höchstpersönlicher Zugriffskontrolle.
Mit Hilfe der verteilten Blockchain-Technologie und modernster Kryptoverfahren wird sichergestellt, dass keine Institution einer Informationsauskunft nachkommen kann ohne Einbezug und Einwilligung des Patienten.

Als Grundbedingung des Heilerfolges ist die Unterstützung der bestmöglichen Zusammenarbeit von Patient, Arzt und Versicherer das höchste Ziel von HealthLedger. Der Mechanismus vereint deshalb die Bedürfnisse aller am Genesungsprozess beteiligten Weggefährten. Dank der Garantie informationeller Selbstbestimmung wird dabei erstmalig eine echte Verantwortungsbalance geschaffen.


## 1.2 Ziele
Features von HealthLedger

* Die unkontrollierbare, nicht nachvollziehbar verteilte Patienteninformation wird durch Digitalisierung in eine elektronische, konzeptionell zentrale Akte überführt.

* Vollständige Kontrolle über die Freigabe der Patientendaten liegt mit variabel wählbarer Transparenzgranularität beim Informationseigner selbst.

* Dank der elektronischen Persistierung kann die Krankenakte global abgerufen und eingesehen werden. Auf Reisen übliche medizinische Sonderdokumente sind somit vollständig ersetzbar. Behandlungsrisiken können zu jeder Zeit an jedem Ort der Welt korrekt von medizinischem Fachpersonal evaluiert werden um den Behandlungserfolg auch in Notfällen sicherstellen zu können.

* Therapiegenehmigungsverfahren werden mittels smarter Vernetzung aller Beteiligten massiv beschleunigt. Die Reduktion von Verzögerungen in der Genesung ist das immanente Resultat.

* Durch Chaincode-Verschreibungen wird die papierlose Medikation ermöglicht. Nicht nur ist die Wahrscheinlichkeit einer Falschverabreichung rigoros eingedämmt, die Transparenz der Wechselseitigkeit von Eigen- und Versicherungsleistung nimmt auch deutlich zu. So sind bereits vor Ankunft in der Apotheke alle Fragen zur Finanzierung der Therapie geklärt.

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
* Normen, Standards, Protokolle, Hardware, externe Vorgaben

### 2.2.2 Betriebsbedingungen
* Vorgaben des Kunden (z.B. Web Browser / Betriebssystem Versionen, Programmiersprache)
* Hyperledger
* Webapp

### 2.2.3 Qualitätsmerkmale (Fynn/Patrick)

Qualitätsmerkmal | sehr gut | gut | normal | nicht relevant
---|---|---|---|---
**Zuverlässigkeit** | | | | |
Fehlertoleranz |X|-|-|-|
Wiederherstellbarkeit |X|-|-|-|
Ordnungsmäßigkeit |X|-|-|-|
Richtigkeit |X|-|-|-|
Konformität |-|X|-|-|
**Benutzerfreundlichkeit** | | | | |
Installierbarkeit |-|-|X|-|
Verständlichkeit |X|-|-|-|
Erlernbarkeit |-|X|-|-|
Bedienbarkeit |-|X|-|-|
**Performance** | | | | |
Zeitverhalten |-|-|X|-|
Effizienz|-|-|-|X|
**Sicherheit** | | | | |
Analysierbarkeit |X|-|-|-|
Modifizierbarkeit |-|-|-|X|
Stabilität |X|-|-|-|
Prüfbarkeit |X|-|-|-|


## 2.3 Graphische Benutzerschnittstelle (Fynn/Patrick)

![Loginscreen](images/login.png "Loginscreen")

Apotheker: Offene Rezepte - Übersicht

![Rezeptübersicht](images/apotheker_offene_rezeptbersicht.png "Offene Rezepte - Übersicht")

Apotheker: Rezeptdetails

![Rezeptdetails](images/apotheker_rezeptdetails.png "Rezeptdetails")

Arbeitgeber: Mitarbeiterübersicht

![Mitarbeiterübersicht](images/arbeitgeber_mitarbeiterbersicht.png "Mitarbeiterübersicht")

Arbeitgeber: Mitarbeiterakte

![Mitarbeiterakte](images/arbeitgeber_mitarbeiterakte.png "Mitarbeiterakte")

Arzt: Smart-Rezept ausstellen:

![Rezeptscreen](images/arzt_arztrezept_ausstellen.png "Rezeptscreen")

Arzt: Behandlung festhalten:

![Behandlungscreen](images/arzt_behandlung_festhalten.png "Behandlungsscreen")

Arzt: Krankschreibung ausstellen:

![Attestscreen](images/arzt_krankschreibung_ausstellen.png "Attestscreen")

Arzt/Patient/Versicherung: Behandlung einsehen:

![Krankenakte](images/arztpatientversicherung_behandlung_einsehen.png "Behandlung einsehen")

Arzt/Patient/Versicherung: Krankenakte:

![Krankenakte](images/arztpatientversicherung_krankenakte_.png "Krankenakte")

Arzt/Versicherung: Patientenübersicht

![Patientenübersicht](images/arztversicherung_patientenbersicht.png "Patientenübersicht")

Arzt/Versicherung/Apotheker/Arbeitgeber: QR Code scannen

![QR-Code scannen](images/arztversicherungapothekerarbeitgeber_qr_code_scannen.png "QR Code scannen")

Patient: Einsichtsanfragen einsehen:

![Anfragen einsehen](images/patient_anfragen_einsehen_.png "Einsichtsanfragen einsehen")

Zustandsdiagramm des Gesamtsystems:

![Komplettes Zustandsdiagramm](images/diagram_mockup_state.png "Komplettes Zustandsdiagramm")

Detailliertes Zustandsdiagramm der Patientenansicht:

![Zustandsdiagramm Patientenansicht](images/diagram_patient.png "Zustandsdiagramm Patientenansicht")

Detailliertes Zustandsdiagramm der Arztansicht:

![Zustandsdiagramm Arztansicht](images/diagram_arzt.png "Zustandsdiagramm Arztansicht")

Detailliertes Zustandsdiagramm der Versichereransicht:

![Zustandsdiagramm Versichereransicht](images/diagram_versicherer.png "Zustandsdiagramm Versichereransicht")

Detailliertes Zustandsdiagramm der Apothekeransicht:

![Zustandsdiagramm Apothekeransicht](images/diagram_apotheker.png "Zustandsdiagramm Apothekeransicht")

Detailliertes Zustandsdiagramm der Arbeitgeberansicht:

![Zustandsdiagramm Arbeitgeberansicht](images/diagram_arbeitgeber.png "Zustandsdiagramm Arbeitgeberansicht")

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
![Systemarchitekturdiagramm](images/Systemarchitektur.png "Systemarchitekturdiagramm")

### Schnittstellenbeschreibung
Das Hyperledger Fabric Framework stellt bereits eine gRPC-Schnittstelle zu den
Peers bereit. Diese Schnittstelle wird von der Applikation verwendet, um Daten
aus dem Distributed Ledger abzufragen bzw. zu aktualisieren. Mittels Protocol
Buffers werden die Daten in ein Binäres Datenformat serialisiert und an den Peer
übertragen.

## 3.2 Softwarearchitektur
![Softwarearchitektur](images/Softwarearchitektur.png "Softwarearchitektur")

## 3.3 Datenmodell

![Datenmodell](images/Benutzermodel_Krankenakte.png "Datenmodell der Krankenakte")

![Chaincode Modell](images/Benutzermodel_Chaincode.png "Chaincode Modell")

## 3.4 Abläufe
Dieses Aktivitätsdiagramm soll zeigen, wie der Arzt bei der Erstellung einer Behandelung mit
der Blockchain interagiert.

![Behandelung erstellen](images/Aktivitätsdiagram_Behandelung_erstellt.png "Behandelung erstellen")

Im folgenden Usecase wird dargestellt, wie ein User wie beispielsweise die Krankenkasse an die
benötigten Informationen gelangt. Dabei kann der Patient selbst entscheiden, ob er die benötigten
Informationen herrausgeben möchte.

![Informationen abfragen](images/Aktivitätsdiagram_Einsicht_erhalten.png "Informationen abfragen")
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
