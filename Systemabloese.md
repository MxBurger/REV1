# Systemablöse :skull:
## Lernziele
### Sie kennen den Lebenszyklus von Software, insbesondere die Möglichkeiten am Lebensende.
- Software wird im Initialprojekt geschaffen (entwickelt) und geboren (Release).
    - Die meisten Vorgehensmodelle betrachten nur diese erste Phase.
    - In der Ausbildung wird darauf das meiste Augenmerk gelegt.
- Die längste Zeit ist allerdings die Erhaltung (Maintenance).
    - Hier entstehen auch die meisten Aufwände für Änderungen und Fehlerkorrekturen.
    - Viele Software-Entwickler*innen verbringen die meiste Zeit ihrer Karriere mit Software-Wartung.
- Was sehr wenig beachtet wird ist die letzte Phase, die Zerstörung (End-of-Life).
    - Auch Software, wie alles andere, erreicht diese Phase irgendwann einmal.
- Ursachen für den Tod von Software:
    - Angehäufte technische Schuld
    - Komplexität des Systems wächst
    - Immer mehr muss getestet werden
    - Immer mehr Side-Effect-Fehler
    - Technologische Gründe (z.B. Technologie wird von der*dem Hersteller*in nicht mehr weiterentwickelt)
    - Kosten für ein Re-Engineering zu groß
    - Zu große Änderungen an Anforderungen und Kontext
    - Wartungs- und Weiterentwicklungskosten werden zu hoch
- Nach dem Tod der Software gibt es 3 Möglichkeiten:
    - Altes System ersatzlos streichen
    - Altes System durch ein neues System ablösen und ersetzen
    - Im alten System umgesetzte Anforderungen in ein anderes bestehendes System integrieren

### Sie kennen Herausforderungen im Requirements Engineering von Systemablöseprojekten.
- Überhaupt mal erkennen, dass Software abgelöst werden sollte.
- Keine\*r kennt mehr die ursprünglichen fachlichen Anforderungen
- Keine\*r kennt mehr das ganze System in der Tiefe im Detail
- Fachbereich und Entwicklung sprechen nicht dieselbe Sprache
- Systemablöse ist Operation am offenen Herzen
### Sie kennen Requirements Reverse Engineering als Vorgehensweise für Systemablösen.
- Entwickler\*innen analysieren das bestehende System und erstellen eine Beschreibung.
- Zu den Funktionen und Schnittstellen werden je nach Bedarf tiefgehende Analysen durchgeführt und genau herausgearbeitet, was wann wie von wem berechnet und getan wird.
- Ergebnisse des Reverse Engineerings
    - Schriftliche System-Spezifikation
    - Feature Tree mit Funktionsübersicht
    - Schnittstellenmodell mit Datenflüssen
    - UI-Screenshots + Beschreibungen
- Reverse Enginnering hat aber auch Schwächen
    - Reverse Engineering liefert das WIE, teilweise auch das WAS und WER, nicht aber das WOZU.
    - Liefert auch alle im Code vorhandenen Fehler, Kompromisse, Unsauberkeiten mit (nicht erkennbar).
    - Übergreifende Zusammenhänge sind oft nicht erkennbar. Gerade bei lose gekoppelten Service-Architekturen.
    - Oft zu granular und extrem teuer


### Sie kennen die Methode der Fit-Gap-Analyse bei der Einführung von Standardsoftware.
- Bei der Fit-Gap-Analyse werden:
    1. die fachlichen Anforderungen bereits vorhandenen Systemfunktionen und Eigenschaften gegenübergestellt
    2. passende Funktionen identifiziert („Fit“)
    3. Lücken identifiziert („Gaps“)
    4. definiert, wie die Lücken geschlossen werden sollen („Bridge“)
- ACHTUNG: Die Fit-Gap-Analyse verleitet dazu, dass die Stakeholder*innen nicht mehr intensiv überlegen, was sie brauchen, sondern sofort mit der Funktionsliste des Zielsystems starten und schauen, was da alles Schönes da ist.

