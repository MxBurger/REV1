# Anforderungen ermitteln :tired_face:
## Lernziele

### Sie wissen, welche Informationen man im Requirements Engineering ermitteln muss.
- Ermitteln heißt, alle **relevanten** Anforderungen im **geforderten Detailgrad** aus den Quellen herauszuholen und gemeinsames Verständnis bei allen relevanten Stakeholdern*innen herzustellen.
- „Relevant“ = Nicht alle Anforderungen, die die Stakeholder\*innen sich vielleicht ausgedacht haben, sondern nur diejenigen Anforderungen, die für den Bau des Produktes tatsächlich notwendig sind.
- „geforderter Detailgrad“ = Nicht immer müssen Anforderungen sofort extrem genau beschrieben werden.
- Grundsatz: Erst Anforderungen sammeln, dann analysieren
- Grundsatz: Erst Anforderungen, dann Lösung
- Funktionale Anforderungen: Was möchten die Akteur*innen mit dem System machen? Was muss das System selbst tun? 
    - Funktionen
        - Ablauf
        - Akteur\*innen
        - Entscheidungen
        - Regeln
        - ...
    - Verhalten
    - Struktur
        - Fachliche Module
        - UI
        - Schnittstellen
        - Datenstruktur(en)
        - ...
- Qualitätsanforderungen: Welches Qualitätsniveau brauchen die Stakeholder*innen?
    - Performance
    - Sicherheit
    - Wartbarkeit
    - ...
- Rahmenbedingungen: In welchem technischen, organisatorischen, zeitlichen, budgetären etc. Rahmen können wir uns bewegen?
    - Organisatorische
    - Technische
    - Regulatorische

- Zu jeder einzelnen Anforderung müssen wir am Ende wissen:
    - Wer braucht es?
    - Was wird benötigt?
    - Wozu wird es benötigt?

### Sie kennen die wesentlichen Quellen von Anforderungen in Software-Projekten. Sie kennen Grundprinzipien und wesentliche Methoden zur Ermittlung von funktionalen und Qualitätsanforderungen.

- Stakeholder\*innen
    - Auftraggeber*in
    - Nutzer*innen
    - Architekt*innen
    - Entwickler*inn
- Eigene Ideen des Entwickler*innen-Teams
- Andere Systeme
    - Alt- u. Vorgängersystem
    - Umfeldsystem
    - Third Party Komponenten
    - Konkurrenzsysteme
- Dokumente
    - Normen / Standards
    - Gesetze
    - Vorschriften
    - Prozessbeschreibung
    - Produktbeschreibungungen
- Je nach Projektkontext sind unterschiedliche Ermittlungsmethoden sinnvoll.
- Methoden, um Anforderungen von den Stakeholder*innen herauszubekommen:
    - Interview: Vorüberlegte Fragen werden einer\*einem oder mehreren Stakeholder\*innen gestellt. Antworten werden protokolliert.
    - Fragebogen: Schriftliches Interview. Geeignet für viele Stakeholder\*innen.
    - Meetings, Workshops, Feldbeobachtungen, Apprenticing, Prototyping, ...
- Methoden, um Anforderungen aus Dokumenten herauszubekommen:
- Dokumentanalyse: Dokumente identifizieren und mit dem Ziel lesen, Anforderungen abzuleiten
- Methoden, um Anforderungen aus bestehenden Systemen herauszubekommen:
    - Feldbeobachtungen, Dokumentanalyse, Systemarchäologie, Reverse Engineering, ...

### Sie können Interviews zur Anforderungsermittlung vorbereiten und durchführen.
Yes, aber
- Ein Interview ist eine Form der Befragung mit dem Ziel, persönliche Informationen, Sachverhalte oder Meinungen zu ermitteln. 
- Interviews (Gruppe oder einzeln) sollten vorbereitet sein (Leitfaden). Die\*Der Interviewer\*in führt durch das Gespräch. Bei mündlichen Interviews kann man ggf. vom Leitfaden abweichen.
- Mögliche Zwecke von Fragen:
    - Fragen zum Informationsgewinn
    - Fragen zur persönlichen Bewertung
    - Fragen zum Aufmachen der Gedanken und Entdecken von Möglichkeiten
    - Fragen zum Zumachen der Gedanken und Entscheidungen treffen
- Fragearten
    - Offene und geschlossene Fragen
    - Direkte oder indirekte Fragen
    - Vergleichsfragen
    - Mit oder ohne Begründung
- Beispiel-Ablauf
    1. Einleitung
    2. Fragen zu Person und Rolle 
    3. Ist-Situation und Probleme
    4. Kontext
    5. Anwendungsfälle
    6. Nutzen und Risiken
    7. Sonstiges
    8. Danke und ein kleiner Ausblick
- Pro-Tipps:
    - Überlegen Sie sich die Fragen vorher
    - Setzen Sie einen klaren zeitlichen Rahmen
    - Schaffen Sie ein angenehmes Setting
    - Überlegen Sie vorher, wie Sie protokollieren
    - Bleiben Sie beim Thema
    - Verbessern Sie nach jedem Interview den Interviewleitfaden

### Sie können Dokumente analysieren und Anforderungen aus ihnen gewinnen.
Yes, aber
- Dokumente als Quellen haben Vorteile und Nachteile:
- Vorteile:
    - geringer Aufwand bei der Ermittlung der Informationen
    - keine Notwendigkeit für weitere Dokumentationen wie z. B. bei einem Interview
- Nachteile:
    - Möglicherweise nicht aktuell und/oder inkonsistent
    - Oft unvollständig und schwer zu verstehen (unklare Begriffe und Abkürzungen, nur Schlagworte)
    - Daten lassen Spielraum für Interpretationen
- empfohlener Ablauf
    - vorab Informationen definieren, die benötigt werden
    - Dokument nur grob scannen, ob es das richtige ist
    - Inhaltsverzeichnis betrachten
    - Lesen und Fragen notieren
    - Zusammenfassungen und Visualisierungen erstellen

### Sie können prüfbare Qualitätsanforderungen ermitteln und beschreiben.
- Qualitätsanforderungen definieren, was für die Stakeholder*innen „Qualität“
bedeutet.
- ISO 25010 definiert:
    - Funktionalität
    - Effizienz
    - Kompatibilität
    - Benutzbarkeit
    - Zuverlässigkeit
    - Security
    - Wartbarkeit
    - Portierbarkeit
- Qualitätsanforderungen sind schwer zu greifen, da hilft: 
    - Beispiele geben
    - Standards definieren (im Unternehmen z.Bsp)
    - Testfälle spezifizieren
    - Anwendungskontext geben („Operationalisieren“) -> konkrete Einsatzszenarien, in denen eine Qualitätsanforderung relevant ist
- Risiko und Schaden bei Nicht-Erfüllung benennen
- Immer wieder fordern Stakeholder*innen völlig überzogene Qualität, daher sind Qualitätsanforderungen sehr genau zu hinterfragen
- Es gibt prüfbare und messbare Qualitätsanforderungen
    - „messbar“ -> Anforderung wird in Zahlen ausgedrückt (quantitativ), Schwellwert wird definiert
    - „prüfbar“ -> Anforderung wird als Set von möglichst eindeutigen Prüfkriterien ausgedrückt (qualitativ)

### Sie kennen wesentliche Methoden zur Analyse und Verfeinerung von Anforderungen.

- Beim Ermitteln der Detailanforderungen sollte das Entwicklungsteam unbedingt intensiv eingebunden werden
- Checklisten für die Detailspezifikation und wiederkehrende Anforderungen (bsp.: UI-Controls)
- Semantische Analyse -> Die Sätze werden Wort für Wort analysiert
    - Verb → Welcher Ablauf steckt dahinter? Welche notwendigen Schritte sind nicht extra genannt?
    - Subjekt → Wer genau/welche Rolle ist gemeint? Wer könnte sonst noch gemeint sein?
    - Adjektiv → Welche Werte oder Ausprägungen gibt es dazu?
    - Abkürzungen → Was bedeutet die Abkürzung?
    - Fachbegriffe → Was ist das?
    - Universalquantoren („alle, jede, immer, …“) → Wirklich alle, immer, jede? Wer/was gehört dazu? Gibt es Ausnahmen?
- Nicht nur an die Anforderung denken, die die Stakeholder*innen von sich aus sagen


plz kill m3

