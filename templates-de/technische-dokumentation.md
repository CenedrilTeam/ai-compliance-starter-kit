# Technische Dokumentation nach Anhang IV

> **Dokumentenkontrolle**  
> Eigentümer: [RICHTLINIEN_EIGENTÜMER_ROLLE, z. B. KI-beauftragte Person]  
> Genehmigt von: [GENEHMIGER_NAME_UND_ROLLE]  
> Version: [VERSION]  
> Gültig ab: [GÜLTIGKEITSDATUM]  
> Nächste Überprüfung: [NÄCHSTES_ÜBERPRÜFUNGSDATUM]

> **KI-Compliance-Starter-Kit.** Vorlage für die technische Dokumentation eines Hochrisiko-KI-Systems nach Art. 11 und Anhang IV der Verordnung (EU) 2024/1689. Die Gliederung folgt den Nummern 1 bis 9 des Anhangs IV; jeder Abschnitt nennt die Buchstaben, die er abdeckt. Die Dokumentation wird vor dem Inverkehrbringen oder der Inbetriebnahme erstellt, aktuell gehalten und zehn Jahre aufbewahrt (Art. 18). Kleine und mittlere Unternehmen dürfen die Angaben in vereinfachter Form vorlegen (Art. 11 Abs. 1).

| Angabe | Eintrag |
|---|---|
| KI-System | [SYSTEM] |
| Eindeutige Kennung | [KENNUNG] |
| Version | [VERSION_DES_SYSTEMS] |
| Anbieter | [IHR_ORGANISATIONSNAME], [ANSCHRIFT] |
| Stand der Dokumentation | [DATUM] |

## 1. Allgemeine Beschreibung des KI-Systems

### 1.1 Zweckbestimmung und Funktionsweise

Anhang IV Nr. 1 Buchst. a.

- **Zweckbestimmung:** [wofür das System bestimmt ist, in welchem Einsatzkontext, für welche Nutzergruppen]
- **Betroffene Personen:** [wen die Ergebnisse betreffen]
- **Funktionsweise:** [was das System mit den Eingaben tut, z. B. ordnet Eingaben Kategorien zu und gibt einen Konfidenzwert aus]
- **Vorhersehbare Fehlanwendung:** [welche Nutzung außerhalb der Zweckbestimmung vernünftigerweise vorhersehbar ist]

### 1.2 Einstufungsgrundlage

- **Risikoklasse:** [z. B. hohes Risiko]
- **Grundlage:** [z. B. Anhang III Nr. 5 Buchst. c oder Sicherheitsbauteil eines Produkts nach Anhang I]
- **Rolle der Organisation:** [Anbieter, Anbieter und Betreiber]

### 1.3 Anbieter, Versionen und Wertschöpfungskette

Anhang IV Nr. 1 Buchst. a bis c.

- **Versionen:** [Versionsstand des Systems und Bezug zu früheren Versionen]
- **Zusammenwirken mit anderer Hard- und Software und anderen KI-Systemen:** [Schnittstellen, eingebundene Modelle]
- **Bestandteile Dritter:** [zugekaufte Modelle, Werkzeuge, Dienste und Komponenten]

| Lieferant | Art des Bestandteils | Bezeichnung | Vereinbarung nach Art. 25 Abs. 4 | Wiedervorlage |
|---|---|---|---|---|
| [LIEFERANT] | [z. B. KI-Modell mit allgemeinem Verwendungszweck] | [BEZEICHNUNG] | [z. B. vereinbart, in Verhandlung, frei und quelloffen ausgenommen] | [DATUM] |

### 1.4 Bereitstellung, Aktualisierung und Zielhardware

Anhang IV Nr. 1 Buchst. c bis e.

- **Formen des Inverkehrbringens:** [z. B. Software als Dienst, Programmierschnittstelle, herunterladbares Paket]
- **Aktualisierungen:** [Anforderungen an Software- und Firmware-Aktualisierungen]
- **Zielhardware:** [Hardware, auf der das System laufen soll, oder „serverseitig beim Anbieter“]

### 1.5 Benutzeroberfläche und Gebrauchsanweisung

Anhang IV Nr. 1 Buchst. f bis h.

- **Benutzeroberfläche:** [Beschreibung der Oberfläche für den Betreiber]
- **Abbildungen:** [bei Produktbestandteilen: Fotos oder Abbildungen der äußeren Merkmale, Kennzeichnung, innerer Aufbau]
- **Gebrauchsanweisung:** [Fundstelle und Version der Gebrauchsanweisung nach Art. 13]

## 2. Detaillierte Beschreibung der Bestandteile und des Entwicklungsprozesses

### 2.1 Methoden und Entwicklungsschritte

Anhang IV Nr. 2 Buchst. a und b.

- **Entwicklungsweg:** [Methoden und Schritte, einschließlich vortrainierter Systeme und Werkzeuge Dritter und wie sie verwendet, integriert oder verändert wurden]
- **Entwurfsspezifikationen:** [allgemeine Logik, Algorithmen, wesentliche Entwurfsentscheidungen mit Begründung und Annahmen, auch zu den Personen, für die das System bestimmt ist]
- **Optimierungsziel und Abwägungen:** [was das System optimieren soll, erwartete Ausgabequalität, technische Abwägungen zur Erfüllung von Kapitel III Abschnitt 2]

### 2.2 Systemarchitektur

Anhang IV Nr. 2 Buchst. c.

[Aufbau der Softwarebestandteile, ihr Zusammenwirken und ihre Einbindung in die Gesamtverarbeitung; Rechenressourcen für Entwicklung, Training, Test und Validierung.]

### 2.3 Daten und Datengovernance (Art. 10)

Anhang IV Nr. 2 Buchst. d.

| Datensatz | Zweck (Training, Validierung, Test) | Herkunft | Umfang und Merkmale | Aufbereitung (Kennzeichnung, Bereinigung) | Prüfung auf Verzerrung |
|---|---|---|---|---|---|
| [DATENSATZ] | [ZWECK] | [HERKUNFT] | [UMFANG] | [AUFBEREITUNG] | [ERGEBNIS] |

### 2.4 Menschliche Aufsicht und Automation Bias

Anhang IV Nr. 2 Buchst. e.

[Bewertung der Maßnahmen der menschlichen Aufsicht nach Art. 14, einschließlich der technischen Vorkehrungen, die den Betreibern die Auslegung der Ausgaben erleichtern, und der Vorkehrungen gegen übermäßiges Vertrauen in die Ausgabe.]

### 2.5 Validierungs- und Testverfahren

Anhang IV Nr. 2 Buchst. g.

| Testart | Testdaten | Kennzahl | Abnahmeschwelle | Ergebnis | Protokoll (Datum, unterzeichnet von) |
|---|---|---|---|---|---|
| [z. B. Genauigkeit je Altersgruppe] | [TESTDATEN] | [KENNZAHL] | [SCHWELLE] | [ERGEBNIS] | [PROTOKOLL] |

Geprüft werden Genauigkeit, Robustheit und mögliche diskriminierende Auswirkungen, auch in Bezug auf Personen und Gruppen, für die das System bestimmt ist.

### 2.6 Cybersicherheitsmaßnahmen

Anhang IV Nr. 2 Buchst. h.

[Maßnahmen gegen Datenvergiftung, Modellvergiftung, gezielte Umgehung, Angriffe auf Vertraulichkeit und Modellfehler; Verweis auf eine Cybersicherheitszertifizierung, falls vorhanden (Art. 42 Abs. 2 und 3).]

## 3. Überwachung, Funktionsweise und Kontrolle

Anhang IV Nr. 3.

### 3.1 Fähigkeiten, Grenzen und Genauigkeit

- **Fähigkeiten und Leistungsgrenzen:** [was das System kann und wo seine Grenzen liegen]
- **Genauigkeit:** [Genauigkeit für bestimmte Personen oder Gruppen und insgesamt erwartete Genauigkeit für die Zweckbestimmung]
- **Validiertes Einsatzgebiet:** [Einsatzgebiete, für die die Werte gelten]

### 3.2 Vorhersehbare unbeabsichtigte Ergebnisse und Risikoquellen

[Vorhersehbare unbeabsichtigte Ergebnisse und Quellen von Risiken für Gesundheit, Sicherheit, Grundrechte und Diskriminierung im Hinblick auf die Zweckbestimmung.]

### 3.3 Menschliche Aufsichtsmaßnahmen

[Maßnahmen der menschlichen Aufsicht nach Art. 14 aus Sicht des Betriebs: wer beaufsichtigt, welche Werkzeuge zur Auslegung bereitstehen, wie das System angehalten wird.]

### 3.4 Spezifikationen der Eingabedaten

[Anforderungen an die Eingabedaten: Formate, Wertebereiche, Qualität, Repräsentativität für den Einsatzkontext.]

### 3.5 Protokollierung (Art. 12)

[Welche Ereignisse automatisch protokolliert werden, wo die Protokolle liegen, wer Zugriff hat und wie lange sie aufbewahrt werden.]

## 4. Eignung der Leistungskennzahlen

Anhang IV Nr. 4.

[Begründung, warum die gewählten Leistungskennzahlen für das konkrete System geeignet sind.]

## 5. Risikomanagementsystem (Art. 9)

Anhang IV Nr. 5.

[Beschreibung des Risikomanagementsystems nach Art. 9 für dieses System, mit Verweis auf das KI-Risikoregister und den KI-Risikobehandlungsplan (Anlage B).]

## 6. Relevante Änderungen über den Lebenszyklus

Anhang IV Nr. 6 und Nr. 2 Buchst. f.

| Datum | Version | Änderung | Wesentlich (Art. 43 Abs. 4) | Vorab bestimmt | Folge (z. B. erneute Konformitätsbewertung) |
|---|---|---|---|---|---|
| [DATUM] | [VERSION] | [ÄNDERUNG] | [JA_ODER_NEIN] | [JA_ODER_NEIN] | [FOLGE] |

## 7. Angewandte harmonisierte Normen

Anhang IV Nr. 7.

| Norm oder gemeinsame Spezifikation | Ausgabe | Angewandt (vollständig, teilweise) | Abgedeckte Anforderungen |
|---|---|---|---|
| [z. B. EN 18286:2026] | [AUSGABE] | [UMFANG] | [z. B. Art. 17 Abs. 1] |

Wo keine harmonisierte Norm angewandt wird: [gewählte Lösung je Anforderung des Kapitels III Abschnitt 2, Grund und Nachweis, einschließlich anderer Normen und technischer Spezifikationen].

## 8. Kopie der EU-Konformitätserklärung

Anhang IV Nr. 8.

[Kopie der EU-Konformitätserklärung nach Art. 47 oder Verweis auf ihre Fundstelle.]

## 9. Beobachtung nach dem Inverkehrbringen (Art. 72)

Anhang IV Nr. 9.

[Beschreibung des Systems zur Bewertung der Leistung nach dem Inverkehrbringen, einschließlich des Beobachtungsplans nach Art. 72 Abs. 3: Datenquellen, Auswertungsturnus, Auslösekriterium, verantwortliche Person.]

## Anlagen

| Anlage | Inhalt | Fundstelle |
|---|---|---|
| A | Gebrauchsanweisung | [FUNDSTELLE] |
| B | KI-Risikoregister und KI-Risikobehandlungsplan | [FUNDSTELLE] |
| C | Test- und Validierungsprotokolle | [FUNDSTELLE] |
| D | Beobachtungsplan | [FUNDSTELLE] |
