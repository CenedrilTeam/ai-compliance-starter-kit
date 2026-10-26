# KI-Anbieterrichtlinie

> **Dokumentenkontrolle**  
> Eigentümer: [RICHTLINIEN_EIGENTÜMER_ROLLE, z. B. KI-beauftragte Person]  
> Genehmigt von: [GENEHMIGER_NAME_UND_ROLLE]  
> Version: [VERSION]  
> Gültig ab: [GÜLTIGKEITSDATUM]  
> Nächste Überprüfung: [NÄCHSTES_ÜBERPRÜFUNGSDATUM]

> **KI-Compliance-Starter-Kit.** Diese Richtlinie ist das Qualitätsmanagementsystem nach Art. 17 der Verordnung (EU) 2024/1689 und folgt EN 18286:2026. Sie gilt nur für Organisationen, die KI-Systeme als Anbieter in Verkehr bringen oder in Betrieb nehmen; reine Betreiber brauchen sie nicht. Abschnitte, die nur für bestimmte Rollen gelten, tragen einen kursiven Hinweis und entfallen, wenn die Rolle nicht zutrifft.

## 1. Rechtliche und normative Grundlage

Diese Richtlinie stützt sich auf:

- Verordnung (EU) 2024/1689, Art. 17 (Qualitätsmanagementsystem)
- Verordnung (EU) 2024/1689, Art. 16 (Pflichten der Anbieter von Hochrisiko-KI-Systemen)
- Verordnung (EU) 2024/1689, Art. 8 bis 15 (Anforderungen an Hochrisiko-KI-Systeme)
- Verordnung (EU) 2024/1689, Art. 43 mit Anhang VI und VII (Konformitätsbewertung)
- Verordnung (EU) 2024/1689, Art. 6 Abs. 1 und Art. 43 Abs. 3 mit Anhang I (Produktsicherheits-Konformitätsweg)
- EN 18286:2026, Qualitätsmanagementsystem für Zwecke der KI-Verordnung (harmonisierte Norm, Fundstelle im Amtsblatt der Union seit dem 14. Oktober 2026, Durchführungsbeschluss (EU) 2026/2274)
- ISO/IEC 42001:2023, Anhang A, insbesondere A.6 (Lebenszyklus) und A.7 (Daten)

Ziel des Qualitätsmanagementsystems ist der Schutz von Gesundheit, Sicherheit und Grundrechten. Das KI-Managementsystem nach ISO/IEC 42001 bildet seinen Rahmen; für die Anforderungen des Artikels 17 Absatz 1 richtet es sich zusätzlich nach EN 18286:2026. Die Anwendung dieser harmonisierten Norm begründet nach Artikel 40 der Verordnung die Vermutung der Konformität mit Artikel 17 Absatz 1, für Buchstabe g nur zusammen mit einem Risikomanagementsystem nach Artikel 9; für Artikel 11 Absatz 1 gilt sie, soweit die technische Dokumentation alle Angaben des Anhangs IV enthält. ISO/IEC 42001 ordnet die Nachweisführung; eine Konformitätsvermutung begründen allein harmonisierte Normen, deren Fundstelle im Amtsblatt der Union veröffentlicht ist. Neben Artikel 40 kennt die Verordnung drei weitere Vermutungswege nach Artikel 42: die Übereinstimmung mit Artikel 10 Absatz 4, soweit das System auf Daten trainiert wurde, die den geografischen, verhaltensbezogenen, kontextuellen oder funktionalen Rahmen der Zweckbestimmung widerspiegeln (Absatz 1); die Erfüllung der Cybersicherheitsanforderungen des Artikels 15 durch eine Cybersicherheitszertifizierung nach der Verordnung (EU) 2019/881 (Absatz 2); und, seit der Verordnung (EU) 2026/1744, die Erfüllung derselben Anforderungen für Systeme, die in den Anwendungsbereich der Verordnung (EU) 2024/2847 fallen und die Voraussetzungen ihres Artikels 12 Absatz 1 erfüllen (Absatz 3).

Die Rechtsgrundlagen werden systematisch überprüft. Neue und geänderte Rechtsvorschriften werden laufend beobachtet; jede Änderung, die ein Anbietersystem berührt, wird bewertet und löst bei Bedarf die Überprüfung dieser Richtlinie aus. Die Pflichten aus der KI-Verordnung führt das KI-Rechtsregister. Weitere Rechtsakte, die ein Anbietersystem berühren, etwa die Datenschutz-Grundverordnung oder die Verordnung (EU) 2024/2847 über Cyberresilienz, führt das Rechtsregister der Organisation. Welches Harmonisierungsrecht des Anhangs I für ein System gilt, wird je System mit seinem Bewertungsverfahren festgehalten. Der Stand der Rechtsgrundlagen geht als Eingangsgröße in die Managementbewertung ein.

## 2. Zweck und Geltungsbereich

Diese Richtlinie ist die schriftliche Version des Qualitätsmanagementsystems, das Artikel 17 der Verordnung (EU) 2024/1689 von Anbietern eines Hochrisiko-KI-Systems verlangt. Sie führt jeden der dreizehn Aspekte des Artikels 17 Absatz 1 (Buchstaben a bis m) in einem eigenen Kapitel dieser Richtlinie aus und hält fest, welche Regel bei **[IHR_ORGANISATIONSNAME]** gilt und welches Dokument sie im Einzelnen ausführt.

Ein zweites Managementsystem entsteht dadurch nicht. Die Vorgaben des KI-Managementsystems gelten unverändert weiter; diese Richtlinie ordnet sie den Anforderungen des Artikels 17 zu und ergänzt die Regeln, die allein die Anbieterrolle betreffen.

Der Umfang der einzelnen Aspekte richtet sich nach der Größe der Organisation (Artikel 17 Absatz 2). Ein Aspekt fällt schlank aus, wo die Verhältnisse es zulassen; keiner entfällt.

*Nur für Finanzinstitute nach Artikel 17 Absatz 4; sonst entfällt dieser Absatz.*

Als Finanzinstitut, das nach dem Finanzdienstleistungsrecht der Union Anforderungen an seine interne Unternehmensführung, an seine Regelungen oder an seine Verfahren unterliegt, erfüllt **[IHR_ORGANISATIONSNAME]** die Pflicht zur Einrichtung eines Qualitätsmanagementsystems durch die Einhaltung dieser Vorschriften (Artikel 17 Absatz 4). Ausgenommen bleiben das Risikomanagement, die Beobachtung nach dem Inverkehrbringen und die Meldung schwerwiegender Vorfälle (Artikel 17 Absatz 1 Buchstaben g, h und i); diese führt **[IHR_ORGANISATIONSNAME]** nach den betreffenden Kapiteln dieser Richtlinie.

Die Richtlinie gilt für jedes KI-System, bei dem **[IHR_ORGANISATIONSNAME]** die Anbieterrolle einnimmt. Die Anbieterrolle entsteht, wenn ein System selbst entwickelt und in Verkehr gebracht oder in Betrieb genommen wird, und ebenso in den Fällen des Artikels 25 Absatz 1: wenn der eigene Name oder die eigene Handelsmarke an einem fremden System angebracht wird, wenn ein bereits in Verkehr gebrachtes System wesentlich verändert wird oder wenn seine Zweckbestimmung so geändert wird, dass es als Hochrisiko-System gilt.

Welche Systeme das im Einzelnen sind, führt das KI-Verzeichnis mit ihrer Einstufung und ihrer Rolle. Systeme, die ausschließlich betrieben und nicht angeboten werden, fallen nicht unter diese Richtlinie.

Die Grenzen des Qualitätsmanagementsystems folgen aus dem Rechtsrahmen und der Zweckbestimmung. Erfasst sind die Anforderungen der Verordnung (EU) 2024/1689 an Anbieter, für Hochrisiko-Systeme in vollem Umfang, für die übrigen Anbietersysteme die Pflichten, die ihre Einstufung auslöst, etwa die Transparenzpflichten nach Artikel 50. Fällt ein System unter das Harmonisierungsrecht des Anhangs I, gelten dessen Anforderungen daneben, und die Konformitätsbewertung folgt dem Verfahren des Produkts. Je System bildet die Zweckbestimmung, wie sie in der technischen Dokumentation festgelegt ist, die Grenze: erfasst sind die Verwendung innerhalb der Zweckbestimmung und die vernünftigerweise vorhersehbare Fehlanwendung. Eine Änderung der Zweckbestimmung wird als wesentliche Änderung behandelt.

## 3. Prozesse des Qualitätsmanagementsystems

Das Qualitätsmanagementsystem besteht aus den folgenden Prozessen. Jeder liefert Ergebnisse, die andere Prozesse aufnehmen; die Tabelle zeigt, welche Prozesse unmittelbar zusammenwirken.

| Prozess | Ergebnisse | Überwachung | Interagiert mit |
|---|---|---|---|
| **Risikomanagement** (Art. 9) | Risikoregister und Behandlungsplan je System, bewertete Restrisiken, Hinweise für die Betreiber | Neubewertung im Turnus und bei Anlass als Aufgabe; Szenarien über der Akzeptanzschwelle in der Managementbewertung | Konzeption, Entwurf, Entwicklung und Validierung, Technische Dokumentation, Beobachtung nach dem Inverkehrbringen, Meldung schwerwiegender Vorfälle |
| **Konzeption, Entwurf, Entwicklung und Validierung** (Art. 17 Abs. 1 b–d) | Zweckbestimmung, Systemanforderungen, geprüfter Entwurf, Prüf- und Validierungsergebnisse, Freigabeentscheidung | Abgeschlossene Freigabevorgänge je Entwicklungsstand; Ergebnisse gegen die Abnahmeschwellen | Risikomanagement, Datenverwaltung, Technische Dokumentation, Konformitätsbewertung und Marktzugang |
| **Datenverwaltung** (Art. 10, Art. 17 Abs. 1 f) | Datensätze mit Herkunft, Version und Qualitätszielen im Datenressourcen-Register | Qualitätsdatum und Befund je Datensatz im Datenressourcen-Register | Konzeption, Entwurf, Entwicklung und Validierung, Technische Dokumentation |
| **Technische Dokumentation** (Art. 11, Anhang IV) | Technische Dokumentation je System mit dem Nachweisansatz je Anforderung | Freigabestand je System, Vollständigkeit nach Anhang IV, Freigabe vor dem Inverkehrbringen | Risikomanagement, Konzeption, Entwurf, Entwicklung und Validierung, Datenverwaltung, Konformitätsbewertung und Marktzugang |
| **Konformitätsbewertung und Marktzugang** (Art. 43, 47 bis 49) | Bewertungsverfahren je System, EU-Konformitätserklärung, CE-Kennzeichnung, Registrierung | Stand von Erklärung, Bescheinigung und Registrierung je System in den Konformitätsunterlagen | Technische Dokumentation, Beobachtung nach dem Inverkehrbringen, Korrekturmaßnahmen und Änderungen |
| **Beobachtung nach dem Inverkehrbringen** (Art. 72) | Beobachtungsplan je System, Auswertungen im festgelegten Turnus, risikorelevante Beobachtungen | Auswertungen im Turnus mit Urteil zur fortdauernden Einhaltung; Kennzahlen in der Managementbewertung | Konformitätsbewertung und Marktzugang, Risikomanagement, Meldung schwerwiegender Vorfälle, Korrekturmaßnahmen und Änderungen |
| **Meldung schwerwiegender Vorfälle** (Art. 73) | KI-Vorfälle mit Bewertung der Meldepflicht, Meldung und Untersuchung | Fristgerechte und verspätete Meldungen in der Managementbewertung | Beobachtung nach dem Inverkehrbringen, Risikomanagement, Korrekturmaßnahmen und Änderungen |
| **Korrekturmaßnahmen und Änderungen** (Art. 20, ISO/IEC 42001 6.3 und 10.2) | Korrekturmaßnahmen, geplante Änderungen am KI-Managementsystem, Beurteilung der Wesentlichkeit | Offene und überfällige Korrekturmaßnahmen; Wirksamkeitsprüfung je Vorgang | Meldung schwerwiegender Vorfälle, Beobachtung nach dem Inverkehrbringen, Konformitätsbewertung und Marktzugang, Internes Audit und Managementbewertung |
| **Internes Audit und Managementbewertung** (ISO/IEC 42001 9.2, 9.3) | Auditberichte, Entscheidungen und Maßnahmen der Leitung, Ressourcen | Erfüllung des Auditprogramms; Umsetzung der Maßnahmen aus der letzten Bewertung | Korrekturmaßnahmen und Änderungen, Risikomanagement, Beobachtung nach dem Inverkehrbringen, Meldung schwerwiegender Vorfälle |
| **Lenkung dokumentierter Information** (Art. 18, EN 18286 4.5) | Freigegebene Versionen der Richtlinien und Dokumente, Aufzeichnungen mit Aufbewahrungsfrist | Geltungsdauer und Freigabestand der Dokumente; Aufbewahrungsfristen | Alle Prozesse dieser Tabelle |

Die Kette beginnt mit der Konzeption eines Systems und schließt sich über die Beobachtung: Beobachtungen und Vorfälle speisen die Risikobeurteilung, Korrekturmaßnahmen und Änderungen gehen in die Entwicklung zurück und lösen bei einer wesentlichen Änderung eine neue Konformitätsbewertung aus. Die Managementbewertung prüft, ob das Zusammenspiel wirkt.

## 4. Strategie zur Einhaltung der Regulierungsvorschriften

Vor dem Inverkehrbringen wird je System das Konformitätsbewertungsverfahren bestimmt. Für Hochrisiko-Systeme nach Anhang III Nummern 2 bis 8 gilt die interne Kontrolle nach Anhang VI, solange das System nicht zugleich unter einen Harmonisierungsrechtsakt des Anhangs I Abschnitt A fällt; dann geht dessen Verfahren vor (Artikel 43 Absatz 3). Für Systeme nach Anhang III Nummer 1 gilt die interne Kontrolle nur, wenn die harmonisierten Normen oder gemeinsamen Spezifikationen vollständig angewandt werden; andernfalls wird eine notifizierte Stelle nach Anhang VII beauftragt.

Die interne Kontrolle nach Anhang VI schließt vor dem Inverkehrbringen die Überprüfung ein, ob der Entwurfs- und Entwicklungsprozess des Systems und seine Beobachtung nach Artikel 72 mit der technischen Dokumentation im Einklang stehen (Anhang VI Nummer 4). Eine erkannte Abweichung wird vor der Freigabe bereinigt, entweder im Prozess oder in der Dokumentation.

*Die folgenden vier Absätze gelten nur für Systeme, die unter das Harmonisierungsrecht des Anhangs I fallen; sonst entfallen sie.*

Ist ein System Bestandteil oder Sicherheitsbauteil eines Produkts oder selbst ein Produkt, das unter das Unionsharmonisierungsrecht des Anhangs I fällt, wird die Konformitätsbewertung nach dieser Verordnung im Rahmen des Konformitätsbewertungsverfahrens dieses Produkts durchgeführt (Artikel 43 Absatz 3). Je System wird festgehalten, welches Bewertungsverfahren der sektorale Rechtsakt verlangt. Es wird eine einheitliche EU-Konformitätserklärung erstellt, die diese Verordnung und die einschlägigen sektoralen Rechtsvorschriften abdeckt (Artikel 47), und die CE-Kennzeichnung richtet sich nach diesen Rechtsvorschriften (Artikel 48).

Sieht das sektorale Verfahren die Beteiligung einer notifizierten Stelle vor, prüft diese auch die Anforderungen der Artikel 8 bis 15 und das Qualitätsmanagementsystem nach Artikel 17; die Nummern 3, 4.3, 4.4, 4.5 und 5 sowie Nummer 4.6 Absatz 5 des Anhangs VII finden dabei Anwendung.

Lässt der Rechtsakt nach Anhang I Abschnitt A den Verzicht auf eine Konformitätsbewertung durch Dritte zu, wird davon nur Gebrauch gemacht, wenn harmonisierte Normen oder gemeinsame Spezifikationen nach Artikel 41 angewandt sind, die alle Anforderungen des Kapitels III Abschnitt 2 abdecken (Artikel 43 Absatz 3 Unterabsatz 3). Die Abdeckung wird je System festgehalten, bevor auf die Drittbewertung verzichtet wird.

Die Einstufung als Hochrisiko-KI-System nach Artikel 6 Absatz 1 ändert die Wahl des Verfahrens nicht. Ebenso wenig macht der Umstand, dass ein Hochrisiko-KI-System als Sicherheitsbauteil in einem Produkt enthalten ist, für sich genommen eine Konformitätsbewertung durch Dritte erforderlich (Artikel 43 Absatz 3 Unterabsatz 3). Maßgeblich bleibt das Verfahren, das der Rechtsakt nach Anhang I Abschnitt A für das Produkt vorsieht.

Änderungen am System werden vor ihrer Übernahme daraufhin beurteilt, ob sie wesentlich sind. Als wesentlich gilt eine Änderung der Zweckbestimmung, eine Änderung der Systemgrenzen, ein Wechsel des zugrunde liegenden Modells oder des Trainingsdatenbestands, eine Änderung der Aufsichtsarchitektur sowie eine Änderung der zugesagten Leistungsgrenzen. Eine wesentliche Änderung löst eine erneute Konformitätsbewertung aus.

Systeme, die nach der Bereitstellung weiterlernen, werden gesondert behandelt: Ihre Ausgaben werden nicht ungeprüft in den Trainings- oder Eingabedatenbestand zurückgeführt, damit sich verzerrte oder fehlerhafte Ergebnisse nicht über Rückkopplungsschleifen verstärken (Artikel 15 Absatz 4). Ihre Leistung wird in festgelegten Abständen gegen die Entwurfsziele ausgewertet, und Auffälligkeiten lösen eine Überprüfung aus.

Die vorbestimmten Änderungen eines weiterlernenden Systems werden im Entwurf festgelegt und in der technischen Dokumentation beschrieben, mit ihrer Wirkung auf die Leistung und den Daten, aus denen das System lernt. Sie werden vor der Freigabe gegen die Anforderungen der Artikel 8 bis 15 geprüft, im Risikomanagement berücksichtigt und in jeder Lebenszyklusphase beachtet. Jede Ausführung einer vorbestimmten Änderung wird verifiziert und validiert und wie jede andere Änderung protokolliert. Vorbestimmte Änderungen, die bei der ersten Konformitätsbewertung festgelegt und in der technischen Dokumentation beschrieben sind, gelten nicht als wesentliche Änderung (Artikel 43 Absatz 4); eine Änderung außerhalb dieses Rahmens wird auf ihre Wesentlichkeit beurteilt.

*Die folgenden acht Absätze gelten nur, wenn eine notifizierte Stelle an der Konformitätsbewertung beteiligt ist; sonst entfallen sie.*

Die Gültigkeitsdauer jeder Bescheinigung wird je System geführt, und ihre Erneuerung wird so rechtzeitig eingeleitet, dass eine verlängerte Bescheinigung vor Ablauf vorliegt (Artikel 44).

Stellt die notifizierte Stelle Mängel fest oder verbindet sie ihre Bescheinigung mit Auflagen, werden diese als Korrekturmaßnahme mit der von ihr gesetzten Frist geführt und ihre Erledigung wird vor Fristablauf nachgewiesen. Eine Aussetzung, Einschränkung oder ein Widerruf der Bescheinigung beendet den Marktzugang des betroffenen Systems, bis seine Konformität wiederhergestellt ist.

Die notifizierte Stelle unterrichtet die betroffenen Anbieter binnen zehn Tagen über eine Aussetzung, Einschränkung oder einen Widerruf ihrer Benennung (Artikel 36 Absatz 5). Ab dieser Unterrichtung wird der Vorgang je betroffener Bescheinigung geführt.

Stellt die notifizierende Behörde bei einer Aussetzung oder Einschränkung fest, dass die beauftragte Stelle bestehende Bescheinigungen nicht weiterführen kann, bestätigt die Organisation den zuständigen nationalen Behörden des Mitgliedstaats ihrer eingetragenen Niederlassung binnen drei Monaten nach der Aussetzung oder Einschränkung schriftlich, dass eine andere qualifizierte notifizierte Stelle die Aufgaben zur Überwachung der Bescheinigung vorübergehend übernimmt und während der Dauer der Aussetzung oder Einschränkung dafür verantwortlich bleibt (Artikel 36 Absatz 8 Buchstabe b).

Wird die Benennung widerrufen, bleiben die Bescheinigungen neun Monate gültig, sofern die zuständige nationale Behörde bestätigt hat, dass von den betroffenen Systemen kein Risiko für Gesundheit, Sicherheit oder Grundrechte ausgeht, und eine andere notifizierte Stelle schriftlich bestätigt hat, dass sie die unmittelbare Verantwortung übernimmt und ihre Bewertung binnen zwölf Monaten ab dem Widerruf abschließt (Artikel 36 Absatz 9). Die schriftliche Bestätigung gegenüber der Behörde und die Bestätigung der übernehmenden Stelle werden zu den Konformitätsunterlagen des betroffenen Systems genommen.

Ist eine notifizierte Stelle nach Anhang VII beauftragt, wird sie über jede beabsichtigte Änderung des genehmigten Qualitätsmanagementsystems und über jede Änderung der von diesem System erfassten Liste der KI-Systeme vor deren Wirksamwerden unterrichtet (Anhang VII Nummer 3.4).

Ist der Zugang zu den Trainingsmodellen und den trainierten Modellen einschließlich ihrer relevanten Parameter für die Bewertung der Konformität mit den Anforderungen des Kapitels III Abschnitt 2 notwendig und sind alle anderen sinnvollen Möglichkeiten der Überprüfung ausgeschöpft oder haben sie sich als unzureichend erwiesen, wird er der notifizierten Stelle auf begründeten Antrag gewährt (Anhang VII Nummer 4.5). Der Zugang unterliegt dem bestehenden Unionsrecht zum Schutz von geistigem Eigentum und Geschäftsgeheimnissen.

Die fortlaufende Überwachung des Qualitätsmanagementsystems durch die notifizierte Stelle wird unterstützt: Zugang zu den einschlägigen Räumlichkeiten, zu den Unterlagen und zu den benötigten Informationen wird gewährt, und die von ihr durchgeführten regelmäßigen Audits werden ermöglicht.

Die Ergebnisse dieser Strategie werden je System an einer Stelle geführt: Einstufung und Rolle im KI-Verzeichnis, das gewählte Konformitätsbewertungsverfahren und die EU-Konformitätserklärung in den Konformitätsunterlagen, der Nachweisansatz je Anforderung in Kapitel 7 der technischen Dokumentation und die Beobachtung im Beobachtungsplan. Diese Richtlinie legt die Regeln fest; die Stände je System stehen dort.

Die KI-beauftragte Person verantwortet diese Beurteilung und hält ihr Ergebnis mit Datum fest.

## 5. Kennzeichnung, Registrierung und Marktzugang

Vor dem Inverkehrbringen trägt jedes System die Anbieterangaben: Name, eingetragener Handelsname oder eingetragene Handelsmarke und die Postanschrift von **[IHR_ORGANISATIONSNAME]**. Sie stehen am System selbst, hilfsweise auf der Verpackung oder in den Begleitunterlagen. Eine Website ersetzt die Postanschrift nicht.

Die CE-Kennzeichnung wird nach Artikel 48 angebracht, sichtbar, lesbar und dauerhaft. Bei digital bereitgestellten Systemen wird sie über die Benutzeroberfläche oder einen maschinenlesbaren Zugang zugänglich gemacht. Ist eine notifizierte Stelle am Verfahren beteiligt, folgt ihre Kennnummer auf das Zeichen.

Das System und die Organisation werden nach Artikel 49 Absatz 1 in der EU-Datenbank eingetragen, bevor das System in Verkehr gebracht oder in Betrieb genommen wird. Der Eintrag wird bei jeder Änderung fortgeschrieben.

Ist ein System des Anhangs III nach Artikel 6 Absatz 3 als nicht hochriskant eingestuft, wird es nach Artikel 49 Absatz 2 dennoch vor dem Inverkehrbringen oder der Inbetriebnahme in der EU-Datenbank registriert. Die Bewertung nach Artikel 6 Absatz 3 und ihre Begründung liegen dem Eintrag zugrunde.

Der Wortlaut der Anbieterangaben stimmt in Kennzeichnung, EU-Konformitätserklärung und Datenbankeintrag überein. Registrierungsnummer, Eintragungsdatum, die Vermarktungsländer und der Stand der CE-Kennzeichnung werden je System geführt.

Jedes in Verkehr gebrachte oder in Betrieb genommene System trägt eine eindeutige Kennung; jede ausgelieferte Einheit und jede bereitgestellte Instanz ist darüber hinaus einzeln gekennzeichnet, etwa durch eine Seriennummer, eine Versionskennung oder eine Mandantenkennung. Die Zuordnung von Einheit oder Instanz zu Version und Abnehmer wird in den Vertriebs- und Bereitstellungssystemen der Organisation geführt, damit sich jede Einheit in der Vertriebskette zurückverfolgen lässt, etwa für einen Rückruf oder die Unterrichtung der Betreiber.

## 6. Gebrauchsanweisung

Jedem Hochrisiko-System liegt eine Gebrauchsanweisung nach Artikel 13 bei. Sie ist knapp, vollständig und für den Betreiber verständlich in leicht verständlicher Sprache abgefasst.

Nach Artikel 13 Absatz 3 enthält die Gebrauchsanweisung mindestens die folgenden Angaben, gegliedert nach den Buchstaben a bis f:

- Buchstabe a: die Identität und die Kontaktdaten des Anbieters sowie, gegebenenfalls, seines Bevollmächtigten;
- Buchstabe b Ziffer i: die Zweckbestimmung des Systems;
- Buchstabe b Ziffer ii: das Maß an Genauigkeit einschließlich der Metriken, Robustheit und Cybersicherheit (Artikel 15);
- Buchstabe b Ziffer iii: die bekannten und vorhersehbaren Umstände, die zu Risiken für Gesundheit, Sicherheit oder Grundrechte führen können (Artikel 9 Absatz 2);
- Buchstabe b Ziffer iv bis vii: gegebenenfalls die Fähigkeiten zur Erläuterung der Ausgaben, die Leistung gegenüber bestimmten Personen oder Gruppen, die Spezifikationen für die Eingabedaten und die Informationen zur Auslegung der Ausgaben;
- Buchstabe c: die vorab bestimmten Änderungen des Systems und seiner Leistung;
- Buchstabe d: die Maßnahmen der menschlichen Aufsicht (Artikel 14) einschließlich der technischen Vorkehrungen zur Auslegung der Ausgaben;
- Buchstabe e: die benötigten Rechen- und Hardwareressourcen, die erwartete Lebensdauer und die Wartungs- und Pflegemaßnahmen;
- Buchstabe f: gegebenenfalls die Beschreibung der Mechanismen zum Erfassen, Speichern und Auslegen der Protokolle (Artikel 12).

Darüber hinaus enthält die Gebrauchsanweisung die Referenz des Systems mit Bezeichnung, Version und Kennung, den Meldeweg an den Anbieter mit der Beschreibung, wie der Betreiber die Nutzung aussetzt, und die Maßnahmen des Betreibers bei der Außerbetriebnahme. Lernt ein System im Betrieb weiter, erklärt sie das, die Wirkung auf das System und was bei Einsatz, Betrieb und Wartung zu beachten ist. Ist die Beobachtung nach dem Inverkehrbringen auf den Betreiber angewiesen, nennt sie die technischen Anforderungen an diese Überwachung nach dem Beobachtungsplan, empfohlene Werkzeuge und die dafür nötige Kompetenz.

Die Gebrauchsanweisung wird aktuell gehalten und dem System in digitaler oder gedruckter Form beigegeben. Jede gemeldete Änderung an einem System löst eine Prüfung der Gebrauchsanweisung aus.

Mit der Gebrauchsanweisung oder der Nutzungsvereinbarung erhält der Kunde die Grenzen des validierten Einsatzgebiets, die gemessene Genauigkeit je Einsatzgebiet und die Aufteilung der Verantwortung zwischen Anbieter und Kunde. Die Übergabe erfolgt vor der Inbetriebnahme und erneut bei jeder wesentlichen Änderung. Die Werte stehen in der technischen Dokumentation; Zielgruppe, Kanal und Zeitpunkt führt der KI-Kommunikationsplan.

## 7. Modelle mit allgemeinem Verwendungszweck

*Nur für Anbieter von KI-Modellen mit allgemeinem Verwendungszweck; sonst entfällt dieser Abschnitt. Für Modelle unter freier und quelloffener Lizenz mit öffentlichen Gewichten und ohne systemisches Risiko entfallen die technische Dokumentation nach Anhang XI und die Angaben nach Anhang XII (Artikel 53 Absatz 2).*

Als Anbieter eines KI-Modells mit allgemeinem Verwendungszweck erfüllt **[IHR_ORGANISATIONSNAME]** zusätzlich zu den übrigen Kapiteln dieser Richtlinie die Pflichten des Artikels 53 Absatz 1. Sie knüpfen an das Modell an, nicht an das einzelne System, in das es eingebettet ist.

Für jedes angebotene Modell besteht eine technische Dokumentation nach Anhang XI. Sie beschreibt die Trainings- und Testverfahren sowie die Ergebnisse der Bewertung und wird mit jeder wesentlichen Änderung des Modells fortgeschrieben. Sie wird für das Büro für Künstliche Intelligenz und die zuständigen nationalen Behörden bereitgehalten.

Anbietern, die das Modell in ein eigenes KI-System einbetten, werden die Angaben nach Anhang XII bereitgestellt: die Fähigkeiten und Grenzen des Modells, die technischen Voraussetzungen der Einbettung und die Angaben, die diese Anbieter für die Erfüllung ihrer eigenen Pflichten benötigen. Wird das Modell geändert, werden die Angaben nachgezogen und die betroffenen Anbieter unterrichtet.

Für die Einhaltung des Urheberrechts besteht eine schriftliche Strategie. Sie umfasst die Ermittlung und Beachtung der Nutzungsvorbehalte nach Artikel 4 Absatz 3 der Richtlinie (EU) 2019/790, einschließlich maschinenlesbarer Vorbehalte. Ausgeschlossene Quellen werden mit ihrer Begründung geführt.

Eine hinreichend detaillierte Zusammenfassung der für das Training verwendeten Inhalte wird nach der Vorlage des Büros für Künstliche Intelligenz erstellt und öffentlich zugänglich gemacht. Fundstelle und Veröffentlichungsdatum werden je Modell festgehalten.

## 8. Lebenszyklusprozesse

Jedes Anbietersystem durchläuft die folgenden Phasen in dieser Reihenfolge. Eine Phase beginnt, wenn ihr Eingangskriterium erfüllt ist, und endet mit ihrem Ausgangskriterium. Betrieb, Wartung und Beobachtung laufen danach nebeneinander, bis das System außer Betrieb genommen wird.

| Phase | Eingangskriterium | Ausgangskriterium | Verantwortlich |
|---|---|---|---|
| **1. Konzeption** | Das Vorhaben ist im KI-Verzeichnis angelegt. | Zweckbestimmung, Einstufung, Rolle, vorgesehener Konformitätsweg und eine erste Risikobetrachtung sind festgehalten; die KI-beauftragte Person hat sie freigegeben. | KI-beauftragte Person |
| **2. Entwurf und Entwicklung** | Zweckbestimmung und Systemanforderungen sind freigegeben. | Der Entwurf ist von einer zweiten fachkundigen Person geprüft, die Datensätze sind mit Version erfasst, der Stand ist versioniert. | Betrieb des KI-Managementsystems |
| **3. Verifizierung und Validierung** | Ein versionierter Stand liegt vor. | Die Ergebnisse liegen innerhalb der festgelegten Annahmeschwellen, die Restrisiken sind bewertet und angenommen. | Betrieb des KI-Managementsystems |
| **4. Inverkehrbringen oder Inbetriebnahme** | Verifizierung und Validierung sind bestanden. | Technische Dokumentation und Gebrauchsanweisung sind vollständig, die Konformitätsbewertung ist abgeschlossen, die Erklärung unterzeichnet, Kennzeichnung und Registrierung sind erfolgt. | KI-beauftragte Person |
| **5. Betrieb und Überwachung im Einsatz** | Das System ist in Verkehr gebracht oder in Betrieb genommen. | Laufend: Auswertungen nach dem Beobachtungsplan, Vorfälle sind bewertet und gemeldet. | Betrieb des KI-Managementsystems |
| **6. Wartung und Aktualisierung** | Ein Änderungswunsch, ein Beobachtungsergebnis oder eine Korrekturmaßnahme liegt vor. | Die Änderung ist auf ihre Wesentlichkeit beurteilt; eine wesentliche Änderung führt zurück in die Verifizierung und eine erneute Konformitätsbewertung. | KI-beauftragte Person |
| **7. Außerbetriebnahme** | Rücknahme, Rückruf oder das Ende der Bereitstellung ist entschieden. | Betreiber sind unterrichtet, der Eintrag in der EU-Datenbank ist fortgeschrieben, die Unterlagen bleiben bis zum Fristende erhalten. | KI-beauftragte Person |

Je Phase werden die benötigten internen und externen Ressourcen bestimmt: Personen mit ihrer Fachkunde, Rechenleistung, Werkzeuge und Modelle sowie Daten. Art, Dauer und Umfang der Tätigkeiten richten sich nach dem System und seiner Einstufung; die Rechenressourcen je Phase hält die technische Dokumentation fest.

Betreiber werden in Konzeption und Validierung einbezogen, damit ihre Anforderungen an Einsatz, Aufsicht und Wartung in die Systemanforderungen eingehen. Wie die Personen, die ein System betrifft, zu seinen Risiken gehört werden, regelt das Kapitel „Konsultation betroffener Personen“.

Planung und Durchführung werden je System im KI-Verzeichnis und in der technischen Dokumentation fortgeschrieben; dort liegen die Nachweise, dass eine Phase planmäßig durchlaufen wurde. Verfehlt ein Prozess seine Kriterien, wird das als Korrekturmaßnahme geführt.

Jeder Entwicklungsstand, der in Verkehr gebracht oder in Betrieb genommen werden soll, durchläuft einen festgelegten Entwicklungs- und Freigabeablauf: Anforderungen und ihr Review, Design und Spezifikation, Verifizierung gegen die Abnahmeschwellen, Validierung unter Einsatzbedingungen und Freigabe durch die Leitung. Verifizierung und Freigabe liegen bei verschiedenen Rollen. Der abgeschlossene Vorgang belegt die Durchführung und wird als Aufzeichnung des Qualitätsmanagementsystems aufbewahrt.

## 9. Konzeption

Am Anfang jedes Systems steht die Konzeption. Festgelegt werden:

- **Zweckbestimmung:** wofür das System bestimmt ist, in welchem Einsatzkontext und für welche Nutzergruppen, welche Personen es betrifft und welche Fehlanwendung vernünftigerweise vorhersehbar ist. Die Zweckbestimmung wird in der technischen Dokumentation geführt und bildet die Grenze des Systems.
- **Regulatorische Anforderungen:** die Einstufung nach der Verordnung, die Rolle der Organisation, weitere berührte Rechtsakte und der vorgesehene Konformitätsweg.
- **Systemanforderungen:** die Anforderungen an Leistung, Genauigkeit, Robustheit, Cybersicherheit, menschliche Aufsicht, Protokollierung und Transparenz, abgeleitet aus der Zweckbestimmung und einer ersten Risikobetrachtung.
- **Machbarkeit und Ressourcen:** ob Daten, Modelle, Rechenleistung und Fachkunde für das System zur Verfügung stehen.

Die Systemanforderungen werden aus den Pflichten hergeleitet, die sich je System aus Einstufung und Rolle ergeben, und aus den Maßnahmen der Risikobeurteilung. Jede Anforderung ist vollständig, eindeutig, verifizierbar und validierbar formuliert. Sie wird vor der Spezifikation geprüft und in dem Werkzeug geführt, mit dem die Entwicklung arbeitet; die technische Dokumentation nennt diese Fundstelle. Das Review der Anforderungen wird wiederholt, wenn Entwurf, Verifizierung oder Validierung eine Anforderung ändern.

Die Ergebnisse der Konzeption werden vor dem Entwurf geprüft und von der KI-beauftragten Person freigegeben.

## 10. Konsultation betroffener Personen

Zu den Risiken eines Systems für Gesundheit, Sicherheit und Grundrechte werden die Personen gehört, die es voraussichtlich betrifft, oder ihre Vertreter. Ist eine unmittelbare Anhörung nicht möglich, treten unabhängige Fachstellen an ihre Stelle, etwa Organisationen der Zivilgesellschaft. Die Konsultation beginnt in der Konzeption, vor Entwurf und Entwicklung, und begleitet Prüfung, Test und Validierung.

Sie läuft je System in fünf Schritten:

1. **Planen:** Die Mittel und Personen werden bereitgestellt, damit die Betroffenen angemessen gehört werden.
2. **Betroffene bestimmen:** Erfasst werden die Personen und Gruppen, die nachteilig betroffen sein können, mit besonderem Blick auf benachteiligte, unterrepräsentierte und schutzbedürftige Gruppen. Grundlage sind die betroffenen Personengruppen der Folgenabschätzung.
3. **Ziele festlegen:** Festgehalten wird, wofür die Konsultation dient, etwa für die Ermittlung und Bewertung von Risiken, die Annahmekriterien, die Maßnahmen, die Untersuchung schwerwiegender Vorfälle oder die Beobachtung nach dem Inverkehrbringen.
4. **Methode wählen und informieren:** Die Form ist altersgerecht und barrierefrei und gibt den Beteiligten die Informationen über das System, die sie für eine Rückmeldung brauchen.
5. **Durchführen und zurückmelden:** Die Ergebnisse werden festgehalten, und die Beteiligten erfahren, was aus ihren Hinweisen folgt.

Ob und in welchem Umfang konsultiert wird, richtet sich nach der Einstufung des Systems und nach den betroffenen Personengruppen; die Entscheidung und die Ergebnisse werden mit der Risikobeurteilung des Systems festgehalten. Die Ergebnisse fließen in die Risikobeurteilung ein und können die Zweckbestimmung ändern oder zusätzliche Schutzmaßnahmen im Entwurf auslösen.

## 11. Entwurf und Entwurfsprüfung

Der Entwurf eines Systems folgt den Phasen des Lebenszyklusmodells mit ihren Eingangs- und Ausgangskriterien. Die Anforderungen werden vor dem Entwurf geprüft, Entwurfsentscheidungen werden mit ihrer Begründung festgehalten, und der Entwurf wird von einer zweiten fachkundigen Person geprüft, bevor die Entwicklung beginnt.

Zwei Anforderungen werden bereits im Entwurf berücksichtigt und nicht nachträglich ergänzt. Die Maßnahmen der menschlichen Aufsicht nach Artikel 14 Absatz 4 werden konstruktiv vorgesehen: die Möglichkeit, den Betrieb anzuhalten, die Anzeige der Grenzen und der Genauigkeit des Systems sowie Vorkehrungen gegen ein übermäßiges Vertrauen in die Ausgabe. Und die Barrierefreiheit nach den Richtlinien (EU) 2016/2102 und (EU) 2019/882 gilt als Entwurfs- und Abnahmeanforderung.

Die Transparenzhinweise nach Artikel 50 werden barrierefrei ausgespielt. Sie sind über assistive Technik erreichbar, für sich verständlich und ohne Farbe allein erkennbar; für digitale Oberflächen gilt dafür EN 301 549. Der Zeitpunkt der Ausspielung liegt bei der ersten Interaktion, bei erzeugten Inhalten an der Stelle der Wahrnehmung.

Welche Verfahren im Einzelnen angewandt werden, hält die technische Dokumentation des jeweiligen Systems fest.

## 12. Entwicklung und Qualitätssicherung

Code, Modelle und Konfiguration werden versioniert abgelegt. Änderungen werden vor ihrer Übernahme freigegeben. Entwicklung, Test und Betrieb laufen in getrennten Umgebungen. Vor jeder Auslieferung wird gegen festgelegte Freigabekriterien geprüft.

Die Qualitätssicherung erstreckt sich auf das Zusammenwirken der Bestandteile: wo ein zugekauftes Modell eingebunden ist, werden Modellversion und Bezugsquelle getrennt von der Anwendungsversion geführt, damit ein Wechsel des Modells nachvollziehbar bleibt.

Die Entwicklung wird an Zielen für die verantwortungsvolle Entwicklung ausgerichtet, etwa zur Wartbarkeit, zur Datenqualität, zur Robustheit und zur Sicherheit der Systeme. Diese Ziele werden den Phasen des Entwicklungslebenszyklus zugeordnet, die zugehörigen Maßnahmen je Phase eingebaut und gemeinsam mit den übrigen KI-Zielen geführt und überprüft (ISO/IEC 42001, Anhang A.6.1.2).

Änderungen an einem System nach dem Inverkehrbringen durchlaufen einen festgelegten Änderungsablauf: Erfassung, Bewertung der betroffenen Risiken, begründete Entscheidung über die Wesentlichkeit, Freigabe, Verifizierung und das Nachziehen von technischer Dokumentation und Gebrauchsanweisung. Eine ausgeführte vorbestimmte Änderung läuft über denselben Weg. Berührt eine Änderung die Prozesse des Qualitätsmanagementsystems, wird sie zusätzlich als Änderung des Managementsystems geführt.

Änderungen am Qualitätsmanagementsystem werden als Änderung des Managementsystems geführt und vor ihrer Freigabe auf ihre Auswirkung auf das Qualitätsmanagementsystem und auf jedes Anbietersystem bewertet. Wird ein System dadurch geändert, läuft diese Änderung als Änderung am System. Kommt ein neues KI-System unter das Qualitätsmanagementsystem oder wird eines wesentlich geändert, wird anhand seiner Eigenschaften geprüft, ob die Prozesse des Qualitätsmanagementsystems zu überarbeiten sind; ist das der Fall, werden sie über eine Änderung des Managementsystems überarbeitet (EN 18286, 10.2).

## 13. Prüfung, Test und Validierung

Geprüft wird vor, während und nach der Entwicklung. Vor der Entwicklung werden die Anforderungen und die vorgesehenen Daten auf ihre Eignung geprüft. Während der Entwicklung wird bei jedem Phasenübergang und bei jeder Modellversion geprüft. Vor der Freigabe läuft ein vollständiger Testdurchgang gegen die festgelegten Annahmeschwellen. Nach der Freigabe wird bei jeder wesentlichen Änderung und bei Abweichungen aus der Beobachtung erneut geprüft.

Je System werden die Testarten, die Auswahl der Testdaten, die Kennzahlen und die Annahmeschwellen festgehalten, ebenso der Rhythmus der wiederkehrenden Prüfungen. Diese Angaben stehen in der technischen Dokumentation und werden mit jeder Modellversion fortgeschrieben. Die Testpläne decken die bestimmungsgemäße Verwendung und die vernünftigerweise vorhersehbare Fehlanwendung ab.

## 14. Technische Spezifikationen und Normen

Je System wird festgehalten, welche technischen Spezifikationen und Normen angewandt werden. Für jede Anforderung des Kapitels III Abschnitt 2, die eine harmonisierte Norm mit Fundstelle im Amtsblatt abdeckt, greift bei vollständiger Anwendung die Vermutungswirkung nach Artikel 40.

Dieselbe Vermutungswirkung erfasst die Pflichten des Kapitels III Abschnitt 3 sowie die Anforderungen, die ein Rechtsakt des Anhangs I an das Produkt stellt, soweit eine harmonisierte Norm sie abdeckt. Sie reicht in jedem Fall nur so weit, wie die Norm die betroffene Anforderung abdeckt und ihre Fundstelle im Amtsblatt der Union veröffentlicht ist.

Wird eine harmonisierte Norm nicht oder nicht vollständig angewandt, tritt an ihre Stelle die Beschreibung der gewählten Lösung: womit die Anforderung stattdessen erfüllt wird, aus welchem Grund dieser Weg gewählt wurde und woran die Erfüllung nachvollziehbar ist. Diese Beschreibung ist Bestandteil der technischen Dokumentation und Voraussetzung der Freigabe.

## 15. Datenverwaltung

Die Verfahren der Datenverwaltung erstrecken sich auf den gesamten Vorgang vor dem Inverkehrbringen: Beschaffung und Erhebung, Analyse, Kennzeichnung, Speicherung, Filterung, Auswertung, Zusammenführung und Aufbewahrung.

Für jeden Datenbestand werden Herkunft, Rechtsgrundlage und Nutzungsbeschränkungen bestimmt, bevor er verwendet wird. Trainings-, Validierungs- und Testdaten werden auf ihre Eignung für die Zweckbestimmung geprüft, auf Repräsentativität und auf mögliche Verzerrungen. Erkannte Verzerrungen werden behandelt und die Behandlung festgehalten.

Die eingesetzten Datenbestände, die Aufbereitungsschritte und die Ausschlüsse führt die technische Dokumentation je System.

Die Herkunft der Daten wird je Datensatz aufgezeichnet: die Quellenart, die Ereignisse der Verwahrkette (Erstellung, Aktualisierung, Transkription, Abstraktion, Validierung, Übergang der Kontrolle, Weitergabe ohne Übergang der Kontrolle, Transformation) sowie die abgebende Stelle bei extern bezogenen Daten. Die Angaben werden über den gesamten Lebenszyklus der Daten und des KI-Systems fortgeschrieben, also bei jeder neuen Datenquelle und bei jeder neuen Version des Datensatzes ergänzt, von der Beschaffung über Aufbereitung und Training bis zur Ausmusterung (ISO/IEC 42001, Anhang A.7.5). Geführt werden sie am Datensatz im Datenressourcen-Register.

## 16. Risikomanagement

Für jedes Anbietersystem läuft ein Risikomanagement nach Artikel 9 über den gesamten Lebenszyklus. Es ermittelt die bekannten und vernünftigerweise vorhersehbaren Risiken bei bestimmungsgemäßer Verwendung und bei vorhersehbarer Fehlanwendung, bewertet sie, führt zu Maßnahmen und prüft deren Wirkung.

Dieses produktbezogene Risikomanagement ist von der Betrachtung der Risiken und Chancen des Managementsystems zu unterscheiden: es richtet sich auf das einzelne System und seine Wirkung auf Personen. Die Durchführung und die Ergebnisse werden im KI-Risikoregister des Systems geführt; die verbleibenden Risiken und die Hinweise für den Betreiber fließen in die technische Dokumentation und in die Gebrauchsanweisung ein.

Auch das Qualitätsmanagementsystem selbst trägt Risiken: dass es seine Ergebnisse verfehlt oder unerwünschte Wirkungen hat. Sie werden mit den Risiken und Chancen des KI-Managementsystems bestimmt, im KI-Risikoregister unter der Kategorie „Qualitätsmanagementsystem“ geführt und berücksichtigen mindestens die Compliance-Strategie, die eingesetzten KI-Technologien, den Bedarf an Informationen und Unterstützung Dritter sowie die verfügbaren Ressourcen und Kompetenzen. Ein Beispiel ist der Ausfall einer externen Software, in der Unterlagen des Qualitätsmanagementsystems geführt werden; dem wird mit einer regelmäßigen Sicherung der Unterlagen und einem beschriebenen Ausweichweg begegnet. Maßnahmen gegen solche Risiken werden als Korrekturmaßnahme oder als geplante Änderung am KI-Managementsystem (ISO 6.3) geführt, in die Abläufe des Qualitätsmanagementsystems eingebunden und in der Managementbewertung auf ihre Wirksamkeit bewertet.

Der Prozess läuft in fünf Phasen und beginnt nach der fünften wieder von vorn:

1. **Ermitteln und analysieren:** Die bekannten und vernünftigerweise vorhersehbaren Risiken für Gesundheit, Sicherheit und Grundrechte werden bei bestimmungsgemäßer Verwendung ermittelt und analysiert (Buchstabe a).
2. **Fehlanwendung abschätzen:** Die Risiken, die bei vernünftigerweise vorhersehbarer Fehlanwendung entstehen können, werden abgeschätzt und bewertet (Buchstabe b).
3. **Weitere Risiken bewerten:** Aus der Auswertung der Daten aus der Beobachtung nach dem Inverkehrbringen werden weitere Risiken bewertet, die in den ersten beiden Phasen nicht sichtbar waren (Buchstabe c).
4. **Maßnahmen ergreifen:** Für die bewerteten Risiken werden geeignete und gezielte Maßnahmen ergriffen; sie werden umgesetzt und ihre Wirkung wird geprüft (Buchstabe d).
5. **Überprüfen und aktualisieren:** Das Risikomanagementsystem wird regelmäßig systematisch überprüft und aktualisiert. Der Turnus ist jährlich; außerplanmäßig wird neu bewertet, sobald eine wesentliche Änderung gemeldet wird, ein System erneut trainiert oder seine Version gewechselt wird oder eine Beobachtung im Betrieb eine festgelegte Betriebsgrenze überschreitet.

Eine Beobachtung im Betrieb, die ein bislang unbekanntes Risiko zeigt, wird als risikorelevant vermerkt und löst die Neubewertung des betroffenen Systems aus. Der Kreislauf schließt damit: die Beobachtung nach dem Inverkehrbringen speist die Risikobeurteilung, und deren Ergebnis wirkt auf die Maßnahmen zurück.

Bei der Umsetzung berücksichtigt das Risikomanagement, ob ein System nach seiner Zweckbestimmung nachteilige Auswirkungen auf Personen unter 18 Jahren oder auf andere schutzbedürftige Gruppen hat (Artikel 9 Absatz 9). Die betroffenen Personengruppen sind je System in der Folgenabschätzung erfasst; welche von ihnen als schutzbedürftig gelten, ergibt sich aus dem Gruppenkatalog. Berührt ein System eine solche Gruppe, weist das Risikoregister sie je Risikoszenario aus, und das Schadensausmaß wird unter diesem Gesichtspunkt bewertet.

## 17. Beobachtung nach dem Inverkehrbringen

Für jedes in Verkehr gebrachte System besteht ein Beobachtungsplan nach Artikel 72. Er benennt den Umfang der Beobachtung, die genutzten Datenquellen, den Auswertungsturnus, die verantwortliche Person und das Kriterium, ab dem ein Beobachtungsergebnis eine Reaktion auslöst.

Der Beobachtungsplan wird als eigenes Dokument geführt und ist Bestandteil der technischen Dokumentation. Die Auswertung findet im festgelegten Turnus statt und wird festgehalten.

Für Reparaturen und Aktualisierungen bestehen festgelegte Abläufe. Eine erkannte Fehlfunktion oder ein Beobachtungsergebnis, das eine Reaktion auslöst, führt zu einer Korrektur; deren Dringlichkeit richtet sich nach dem Schadensausmaß. Für die Aufnahme einer Meldung und die Behebung sind Reaktionszeiten zugesagt, die je System festgehalten sind. Ändert eine Aktualisierung das Verhalten eines Systems in sicherheitsrelevanter Weise, werden die Betreiber vor oder mit der Bereitstellung unterrichtet, und die Änderung wird in der technischen Dokumentation vermerkt.

Die Beobachtung beginnt für jedes System mit dem Inverkehrbringen oder der Inbetriebnahme und endet mit seiner Außerbetriebnahme. Umfang und Auswertungsturnus sind verhältnismäßig zu Technologie, Risikoklasse, Zweckbestimmung und vorhersehbarer Fehlanwendung; für Hochrisiko-Systeme ist der Turnus enger als für Systeme mit geringerem Risiko. Der Beobachtungsplan berücksichtigt die Risiken und Maßnahmen aus dem Risikomanagement, die Abhängigkeit von Betreibern, Händlern, Einführern und Zulieferern sowie technische Grenzen, die eine wirksame Beobachtung erschweren; eine solche Grenze wird mit dem Ausgleich festgehalten, der stattdessen greift.

Informationen werden je Quelle auf einem festgelegten Weg gesammelt und gespeichert: Rückmeldungen und Beschwerden von Betreibern, Nutzern und weiteren interessierten Parteien über den Meldeweg für Betreiber, Protokolle und Leistungsdaten aus dem Betrieb, soweit sie der Organisation zugänglich sind, Mitteilungen von Behörden über den KI-Kommunikationsplan und schwerwiegende Vorfälle über den KI-Vorfallprozess. Personenbezogene Daten werden dabei nur im erforderlichen Umfang verarbeitet; Daten schutzbedürftiger Gruppen werden besonders geschützt und, wo möglich, pseudonymisiert. Die Ergebnisse der Beobachtung gehen in die Managementbewertung ein.

Betrifft eine Nichtkonformität mehrere KI-Systeme, führt die Korrekturmaßnahme alle betroffenen Systeme; die Untersuchung eines Vorfalls prüft dafür, welche Systeme dasselbe Modell oder denselben Lieferanten nutzen. Die Managementbewertung wertet die Korrekturmaßnahmen je System und je Auslöser aus. Tritt bei einem System wiederholt eine Nichtkonformität auf oder häufen sich Vorgänge mit demselben Auslöser, wird geprüft, ob ein systemisches Problem vorliegt, und die Maßnahme setzt an dessen Ursache an. Dabei wird auch geprüft, ob aus den Nichtkonformitäten neue Risiken folgen; solche Risiken werden im KI-Risikoregister erfasst und bewertet, und der Bedarf an Vorbeugemaßnahmen wird bestimmt.

## 18. Meldung schwerwiegender Vorfälle

Ein schwerwiegender Vorfall nach Artikel 73 wird den Marktüberwachungsbehörden der betroffenen Mitgliedstaaten gemeldet. Die Meldung erfolgt auch dann fristwahrend, wenn der Sachverhalt noch unvollständig ist; die fehlenden Angaben werden nachgereicht.

Beruht ein System auf einem KI-Modell mit allgemeinem Verwendungszweck und stammen Modell und System vom selben Anbieter oder von Anbietern desselben Unternehmens, ist für dieses System das Büro für Künstliche Intelligenz ausschließlich zuständig; dasselbe gilt für Systeme, die eine sehr große Online-Plattform oder Suchmaschine nach der Verordnung (EU) 2022/2065 sind oder in eine solche eingebettet sind (Artikel 75 Absatz 1 in der Fassung der Verordnung (EU) 2026/1744). Vier Fälle bleiben bei den Marktüberwachungsbehörden: Produkte nach Anhang I, Systeme nach Anhang III Nummer 2, Systeme der Strafverfolgungs-, Grenz- und Finanzbehörden nach Artikel 74 Absatz 6 und Systeme nach Anhang III Nummer 8. Für die erfassten Systeme geht die Meldung eines schwerwiegenden Vorfalls abweichend von Artikel 73 an das KI-Büro (Artikel 75 Absatz 1a).

Bis zur Unterrichtung der Behörden bleibt das System unverändert, soweit eine Änderung die spätere Bewertung der Ursachen beeinträchtigen würde. Protokolle, Konfiguration, Modellstand und die verwendeten Daten werden gesichert.

Unterliegt das Unternehmen für ein System bereits einem Unionsrechtsakt mit gleichwertigen Meldepflichten oder ist das System ein Produkt nach der Medizinprodukte- oder der IVD-Verordnung, beschränkt sich die Meldung nach dieser Verordnung auf Vorfälle nach Artikel 3 Nummer 49 Buchstabe c, also auf die Verletzung von Pflichten des Unionsrechts, die dem Schutz der Grundrechte dienen. Die übrigen Vorfallarten werden über den sektoralen Meldeweg gemeldet. Bei Produkten nach der Medizinprodukte- oder der IVD-Verordnung geht die Meldung an die vom Mitgliedstaat des Vorfallorts benannte Behörde. Welcher Fall für welches System gilt, wird im KI-Verzeichnis je System festgehalten.

Betreiber melden schwerwiegende Vorfälle und Beobachtungen zu Risiken für Gesundheit, Sicherheit oder Grundrechte über den Meldeweg, den die Gebrauchsanweisung nennt; der Weg steht allen Betreibern offen. Hat ein Betreiber Grund zu der Annahme, dass die Verwendung ein Risiko im Sinne des Artikels 79 Absatz 1 birgt, setzt er die Nutzung aus und unterrichtet die Organisation (Artikel 26 Absatz 5); die Gebrauchsanweisung beschreibt, wie das geschieht. Bis zur Klärung kann die Organisation den Betreibern das Aussetzen auch selbst empfehlen oder verlangen. Jede Betreibermeldung wird als KI-Beobachtung oder KI-Vorfall aufgenommen und auf ihre Meldepflicht bewertet.

Die Fristen, die Empfänger und der Meldeweg stehen im KI-Kommunikationsplan. Die Erfassung, die Untersuchung und die Abhilfe folgen dem KI-Vorfallprozess.

## 19. Kommunikation mit Behörden und Akteuren

Die Kommunikation mit zuständigen nationalen Behörden, notifizierten Stellen, weiteren Akteuren der Lieferkette, Kunden und sonstigen interessierten Parteien ist im KI-Kommunikationsplan geregelt, mit Gegenstand, Häufigkeit, Kanal, Zielgruppe und verantwortlicher Person.

Auf eine begründete Anfrage einer zuständigen Behörde nach Artikel 21 werden die technische Dokumentation, die EU-Konformitätserklärung, der Nachweis der Konformitätsbewertung, der Beobachtungsplan und die automatisch erzeugten Protokolle bereitgestellt, in einer Sprache, welche die Behörde leicht versteht. Der Zugang zu den Protokollen wird gewährt, soweit sie der Kontrolle der Organisation unterliegen.

Setzt die Behörde keine Frist, legt die KI-beauftragte Person bei Eingang eine angemessene Frist fest, hält sie im Vorgang fest und teilt sie der Behörde mit. Dasselbe Verfahren gilt für Behörden zum Schutz der Grundrechte nach Artikel 77 und für Stellen, die den Zugang zu Daten ermöglichen. Die Nachweise der anfänglichen und fortdauernden Konformität werden je System in einem Konformitätsdossier zusammengestellt; Protokolle, die der Kontrolle der Organisation unterliegen, werden an dem in der technischen Dokumentation genannten Ort geführt.

Stellt sich heraus, dass ein in Verkehr gebrachtes System der Verordnung nicht entspricht, werden nach Artikel 20 Absatz 1 unverzüglich die erforderlichen Maßnahmen ergriffen: Herstellung der Konformität, Rücknahme, Deaktivierung oder Rückruf. Händler, Betreiber, Bevollmächtigte und Einführer werden darüber unterrichtet.

Die gewählte Maßnahme wird als Korrekturmaßnahme geführt. Der Vorgang hält die Art der Maßnahme fest und die Gruppen der Lieferkette, die unterrichtet wurden; wer im Einzelfall angeschrieben wurde, steht im Vorgang selbst.

Birgt das System ein Risiko im Sinne des Artikels 79 Absatz 1, werden zusätzlich unverzüglich die Ursachen in Zusammenarbeit mit dem meldenden Betreiber untersucht und die Marktüberwachungsbehörden sowie die notifizierte Stelle, die das System nach Anhang VII bewertet hat, über die Art der Nichtkonformität und die ergriffenen Maßnahmen unterrichtet. Beide Unterrichtungen werden am KI-Vorfall mit Datum und Referenz festgehalten.

Verlangt eine Marktüberwachungsbehörde für ein KI-System eine Korrekturmaßnahme, die Rücknahme, den Rückruf oder eine Beschränkung der Bereitstellung, wird die angeordnete Maßnahme innerhalb der von der Behörde gesetzten Frist umgesetzt; diese Frist liegt in jedem Fall unter fünfzehn Arbeitstagen, soweit das Unionsharmonisierungsrecht nichts anderes bestimmt. Die Anordnung wird mit Behörde, Aktenzeichen und Frist am betroffenen System im KI-Verzeichnis erfasst, die Umsetzung als Korrekturmaßnahme geführt und ihre Erledigung dort nachgewiesen. Betrifft die Anordnung ein System, das auch andernorts in der Union bereitgestellt wird, erstreckt sich die Maßnahme auf alle betroffenen Systeme.

Übernimmt ein Dritter für ein bereits in Verkehr gebrachtes System die Anbieterrolle, stellt **[IHR_ORGANISATIONSNAME]** ihm die technische Dokumentation bereit, die zur Beurteilung der Konformität nach Artikel 16 ausreicht, unterrichtet ihn über die bekannten Grenzen und Fehlermodi des Systems und gewährt ihm gezielten technischen Zugang, auch für Erprobung und Validierung (Artikel 25 Absatz 2). Umfang und Zeitpunkt der Übergabe werden am betroffenen System im KI-Verzeichnis festgehalten, die Vereinbarung mit dem übernehmenden Anbieter wird schriftlich geschlossen. Ist für ein System ausdrücklich erklärt, dass es nicht in ein Hochrisiko-System umgewandelt werden darf, entfällt diese Mitwirkung; die Erklärung wird am System vermerkt.

Für die Betreiber besteht ein Support. Er richtet sich an die Betreiber und ihre Nutzer; erwartete Anliegen sind Fragen zur Verwendung, Störungen, Leistungsabweichungen und Hinweise auf Risiken, die je nach Art beantwortet, behoben oder als KI-Beobachtung aufgenommen werden. Kanäle und Erreichbarkeit stehen je System in der Gebrauchsanweisung; Diagnosewerkzeuge werden bereitgestellt, wo sie für die Behebung nötig sind.

## 20. Außerbetriebnahme

Die Außerbetriebnahme eines Systems wird geplant, bevor sie wirksam wird. Festgelegt werden:

- **Risikomaßnahmen:** wie Risiken aus dem Ende des Betriebs beherrscht werden, etwa der Wegfall einer Funktion, auf die sich Betreiber oder betroffene Personen stützen, und der Übergang auf eine Ersatzlösung.
- **Datenmaßnahmen:** wie Modelle sowie Trainings-, Eingabe- und Protokolldaten zurückgegeben, gelöscht oder archiviert werden. Personenbezogene Daten werden nach dem Datenschutzrecht gelöscht, soweit keine Aufbewahrungspflicht entgegensteht.
- **Archivierung:** Die Unterlagen nach Artikel 18 bleiben bis zum Ende ihrer Frist erhalten, auch wenn das System nicht mehr bereitgestellt wird; die Protokolle nach Artikel 19 für die Dauer ihrer Frist.
- **Information der Betreiber:** Die Betreiber erfahren rechtzeitig, ab wann das System nicht mehr bereitgestellt oder unterstützt wird und welche Maßnahmen sie selbst durchführen, etwa das Beenden der Nutzung, die Sicherung eigener Daten und die Unterrichtung ihrer Nutzer.

Mit der Außerbetriebnahme endet die Beobachtung nach dem Inverkehrbringen, und der Eintrag in der EU-Datenbank wird fortgeschrieben.

## 21. Aufzeichnungen und Aufbewahrung

Fünf Arten von Unterlagen werden ab dem Inverkehrbringen oder der Inbetriebnahme zehn Jahre bereitgehalten (Artikel 18): die technische Dokumentation, die Dokumentation des Qualitätsmanagementsystems, die von notifizierten Stellen genehmigten Änderungen, deren Entscheidungen und Dokumente sowie die EU-Konformitätserklärung.

Die automatisch erzeugten Protokolle werden über einen Zeitraum aufbewahrt, der der Zweckbestimmung des Systems angemessen ist, mindestens jedoch sechs Monate (Artikel 19). Verlangt das Datenschutzrecht eine frühere Löschung, hat die Löschpflicht Vorrang; dieser Fall wird mit seiner Begründung festgehalten.

Speicherort, Zugriffsrechte und die jährliche Prüfung auf Vollständigkeit werden je System festgelegt.

## 22. Lenkung dokumentierter Information

Diese Richtlinie, die mitgeltenden Dokumente und die Aufzeichnungen des Qualitätsmanagementsystems werden in [DOKUMENTENSYSTEM, z. B. Dokumentenmanagementsystem oder Intranet] geführt. Vor der Herausgabe wird ein Dokument geprüft und freigegeben; jede Freigabe erzeugt eine neue Version mit Datum und freigebender Person, und die Änderungen gegenüber der zuletzt freigegebenen Version sind nachvollziehbar. Ein geändertes Dokument wird erneut geprüft und freigegeben, von einer Person mit der Kompetenz für den betroffenen Aspekt. Frühere Versionen bleiben erhalten und lesbar, auch nachdem sie als obsolet gekennzeichnet sind. Sie lassen sich auch außerhalb des Dokumentensystems lesen, etwa als PDF.

Eine freigegebene Version dieser Richtlinie gilt für [GELTUNGSDAUER, z. B. ein Jahr] ab Freigabe. Die Person der letzten Freigabe wird rechtzeitig vor dem Ablauf erinnert; nach Ablauf wird die Version als obsolet gekennzeichnet, sofern sie nicht vorher erneut freigegeben oder durch eine neue Version ersetzt wurde. Aufzeichnungen halten einen Stand fest und haben keine Geltungsdauer.

Die Unterlagen nach Artikel 18 rechnen ihre Aufbewahrungsfrist ab dem Inverkehrbringen: technische Dokumentation, EU-Konformitätserklärung und Beobachtungsplan ab dem Inverkehrbringen ihres Systems, diese Richtlinie und die Aufzeichnungen des Qualitätsmanagementsystems ab dem spätesten Inverkehrbringen eines Anbietersystems und nie vor ihrer Erstellung. Die Frist beträgt mindestens zehn Jahre. Nach dem Fristende wird eine Version zur Löschung vorgelegt; gelöscht wird nur auf ausdrückliche Entscheidung, und jede Löschung wird im Löschprotokoll festgehalten.

Unterlagen externer Herkunft, die für Planung und Betrieb des Qualitätsmanagementsystems nötig sind, werden mit ihrer Fundstelle geführt: Bezeichnung, Ausgabe oder Datum und Ort. Angewandte Normen stehen mit ihrer Ausgabe in Kapitel 7 der technischen Dokumentation, Rechtsakte im KI-Rechtsregister und im Rechtsregister der Organisation, Unterlagen von Lieferanten und notifizierten Stellen bei dem System, das sie betreffen.

## 23. Ressourcen und Versorgungssicherheit

Für die Anbietertätigkeit hält **[IHR_ORGANISATIONSNAME]** die erforderlichen Ressourcen vor: Personen mit der nötigen Fachkunde, Rechenleistung für Training und Betrieb, Werkzeuge und Modelle sowie die Datenbestände, auf denen die Systeme beruhen.

Zur Versorgungssicherheit gehört, dass die Abhängigkeit von einzelnen Zulieferern bekannt ist. Für Modelle, Rechenleistung und Werkzeuge, die von Dritten bezogen werden, sind die Bezugsquelle, die vertraglichen Fristen und die Folgen eines Ausfalls oder einer Abkündigung festgehalten. Wo ein Ausfall den Betrieb eines in Verkehr gebrachten Systems gefährden würde, besteht eine Ausweichmöglichkeit oder ein beschriebener Weg, das System geordnet außer Betrieb zu nehmen.

Werden ein zugekauftes KI-System, ein KI-Modell, ein Instrument, ein Dienst, eine Komponente oder ein Verfahren in ein Hochrisiko-System eingebaut, schließt **[IHR_ORGANISATIONSNAME]** mit dem jeweiligen Lieferanten eine schriftliche Vereinbarung über die Informationen, Fähigkeiten und den technischen Zugang, die zur Erfüllung der Anbieterpflichten erforderlich sind (Artikel 25 Absatz 4). Die Vereinbarungen werden je System in der technischen Dokumentation geführt, mit Lieferant, Art des Bestandteils, Bezeichnung, Vertragsstand und Wiedervorlage. Für frei und quelloffen bereitgestellte Bestandteile gilt diese Vereinbarungspflicht nicht; ihre Verwendung wird an derselben Stelle vermerkt. Modelle mit allgemeinem Verwendungszweck sind von dieser Ausnahme ausgenommen (Artikel 25 Absatz 4 Satz 2), für sie bleibt die Vereinbarung erforderlich.

Lieferanten von Modellen, Daten, Komponenten, Diensten und Leistungen im Lebenszyklus werden nach dokumentierten Kriterien ausgewählt und beurteilt: ihrer Fähigkeit, die regulatorischen und vertraglichen Anforderungen zu erfüllen, der Qualität und Herkunft der gelieferten Elemente, ihrer Informationssicherheit und ihrer Verfügbarkeit. Die Strenge richtet sich nach dem Risiko, das aus dem belieferten System folgt, und berücksichtigt, wie wirksam die Kontrollen des Lieferanten selbst sind, etwa belegt durch Zertifikate, Auditergebnisse oder seine Auskunft. Getrennt festgelegt sind die Kontrollen am Lieferanten, also die Beurteilung vor der Beauftragung, die Neubeurteilung im Turnus seines Risikourteils und die Anlassprüfung nach Vorfällen oder Änderungen, und die Kontrollen an den gelieferten Elementen, also Abnahme, Verifizierung und Validierung zugelieferter Modelle, Daten und Komponenten vor ihrer Verwendung und die Prüfung jeder neuen Version. Den Lieferanten werden die Anforderungen mitgeteilt, die ihren Beitrag betreffen. Beurteilungen, Ergebnisse und Maßnahmen stehen im KI-Lieferantenverzeichnis.

Die Ressourcen werden bei der Aufnahme eines neuen Anbietersystems und bei der jährlichen Überprüfung dieser Richtlinie beurteilt.

Jede Beurteilung eines KI-Lieferanten läuft als festgelegter Vorgang: Anlass, Prüfung gegen die genannten Kriterien, Ergebnis mit Befund und Maßnahme. Das Datum der letzten Beurteilung wird im KI-Lieferantenverzeichnis festgehalten; ein ungeeigneter Lieferant führt zu einer Korrekturmaßnahme.

## 24. Rollen und Verantwortlichkeiten

Für die Aspekte dieser Richtlinie gilt die folgende Verteilung:

- **Oberste Leitung:** Trägt die Verantwortung dafür, dass das Qualitätsmanagementsystem besteht und wirkt. Genehmigt diese Richtlinie, stellt die Mittel bereit und zeichnet die EU-Konformitätserklärung oder benennt die zeichnungsberechtigte Person.
- **KI-beauftragte Person:** Führt das Qualitätsmanagementsystem, beurteilt Änderungen auf ihre Wesentlichkeit, verantwortet die Konformitätsbewertung und die technische Dokumentation.
- **Betrieb des KI-Managementsystems:** Führt Entwicklung, Qualitätssicherung, Datenverwaltung und Beobachtung im Tagesgeschäft.
- **Vorfallmeldung:** Bewertet Vorfälle auf ihre Meldepflicht und setzt die Meldung fristgerecht ab.
- **Menschliche Aufsicht:** Nimmt die Aufsicht über den Betrieb wahr, soweit sie einem System zugewiesen ist.
- **Aufsicht über das Risikomanagement:** Überwacht das Risikomanagementsystem, gibt die Maßnahmen zur Risikobeherrschung frei und nimmt die Restrisiken an.
- **Regulatorische Anforderungen und Stand der Technik:** Ermittelt und prüft für alle Anbietersysteme die regulatorischen Anforderungen und den Stand der Technik, einschließlich Normen und Leitlinien, und meldet Änderungen an die KI-beauftragte Person.

Neben der verantwortlichen Rolle werden je Prozess weitere Rollen beteiligt:

- **Risikomanagement:** Konsultiert werden der Betrieb des KI-Managementsystems und die menschliche Aufsicht; informiert wird die KI-beauftragte Person über jede freigegebene Maßnahme und jedes angenommene Restrisiko.
- **Konformitätsbewertung und Änderungen:** Konsultiert werden die Aufsicht über das Risikomanagement und die Rolle für regulatorische Anforderungen; informiert wird die oberste Leitung vor der Unterzeichnung der EU-Konformitätserklärung.
- **Beobachtung und Vorfälle:** Konsultiert werden der Betrieb und die menschliche Aufsicht; informiert werden die KI-beauftragte Person und bei einem schwerwiegenden Vorfall die oberste Leitung.
- **Lieferkette:** Konsultiert wird die Lieferantensteuerung bei jedem Bestandteil eines Dritten; informiert wird der Betrieb über Vertragsstand und Wiedervorlage.
- **Konzeption, Entwicklung und Validierung:** Konsultiert werden die Aufsicht über das Risikomanagement, die Datenqualität und die menschliche Aufsicht; informiert wird die KI-beauftragte Person über jede Freigabe zum Inverkehrbringen.
- **Datenverwaltung:** Konsultiert werden der Datenschutz und die Entwicklung; informiert wird die KI-beauftragte Person über Datensätze mit Befund.
- **Technische Dokumentation:** Konsultiert werden die Entwicklung und die Rolle für regulatorische Anforderungen; informiert wird die oberste Leitung vor der Freigabe einer neuen Version.
- **Lenkung dokumentierter Information:** Konsultiert werden die Verantwortlichen des jeweiligen Dokuments; informiert werden die Personen, die ein Dokument zur Kenntnis nehmen.
- **Kompetenz:** Konsultiert werden die Führungskräfte der betroffenen Bereiche; informiert wird die KI-beauftragte Person über offene Schulungen.
- **Internes Audit und Managementbewertung:** Konsultiert werden die Verantwortlichen der geprüften Prozesse; informiert werden alle Rollen über die Entscheidungen der Leitung.

Die Rollen tragen die Qualitätspolitik und die KI-Ziele; jedes KI-Ziel ist einer verantwortlichen Person zugeordnet. Wer qualitätsrelevante Arbeit leitet, ausführt oder prüft, ist befugt, sie anzuhalten, wenn eine Anforderung verfehlt wird oder ein Risiko für Gesundheit, Sicherheit oder Grundrechte erkennbar ist. Ein angehaltener Schritt wird fortgesetzt, sobald die Ursache geklärt und die Freigabe erneut erteilt ist. Prüfende Personen prüfen keine eigene Arbeit.

Wechselt eine Zuweisung, wird die Änderung mit Datum festgehalten. Die namentliche Zuordnung führt die KI-RACI.

## 25. Mitgeltende Dokumente

Diese Richtlinie wird durch die folgenden Dokumente ausgeführt:

- **KI-Politik:** Der Rahmen des KI-Managementsystems, aus dem diese Richtlinie hervorgeht.
- **Technische Dokumentation je System:** Die Angaben nach Anhang IV, einschließlich Entwicklungsweg, Daten, Prüfverfahren, Normen und Protokollierung.
- **EU-Konformitätserklärung:** Die Erklärung nach Anhang V je System.
- **Beobachtungsplan:** Der Plan nach Artikel 72 Absatz 3 je System.
- **KI-Kommunikationsplan:** Gegenstand, Häufigkeit, Kanäle und Zielgruppen der Kommunikation, einschließlich der Meldung schwerwiegender Vorfälle.
- **KI-Rollen und Verantwortlichkeiten:** Die namentliche Zuordnung der Verantwortung.
- **KI-Verzeichnis:** Die eingesetzten und angebotenen Systeme mit ihrer Einstufung und Rolle.

## 26. Überprüfung und Pflege

Diese Richtlinie wird mindestens jährlich überprüft. Eine zusätzliche Überprüfung findet statt, wenn ein neues System die Anbieterrolle auslöst, wenn eine wesentliche Änderung an einem bestehenden System vorgenommen wird, wenn sich die Rechtsgrundlagen ändern oder nach einem schwerwiegenden Vorfall.

Die KI-beauftragte Person bereitet die Überprüfung vor und legt Änderungen vor; die oberste Leitung genehmigt sie. Jede Version wird mit Datum geführt.
