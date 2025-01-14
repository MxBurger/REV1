# Ziele, Kontext, Stakeholder*innen :skull:

## Lernziele:

###  Sie können das eigentliche Problem und die Ziele hinter Anforderungen und Lösungsideen herausarbeiten.
- Bevor man mit funktionalen and anderen Anforderungen loslegt, muss das WARUM glasklar sein.
- Das WARUM sollte sich in den oberen Ebenen der Anforderungsspezifikation (Vision, Scope, Ziele) klar widerspiegeln. → "Start with the Why"
    - Warum nimmt die*der Auftraggeber\*in (viel) Geld in die Hand, um das Projekt anzugehen?
    - Was ist denn das eigentliche Problem?
    - Was wird durch das Projekt/Produkt bzw. die Funktion besser, schneller, leichter, ...?
    - Wann ist das Projekt bzw. die Umsetzung der Anforderung ein Erfolg?
- Problemlösen = Beseitigen von etwas Negativem (der Ist-Zustand ist nicht-OK)
- Ziel = Erreichen von etwas Positivem (der Ist-Zustand kann schon OK sein)
- Die Kernfrage am Beginn der meisten Projekte ist: „Wo ist der Schmerz?“
- Zur Ermittlung des WARUMs kann die "5-Why-Methode" vom Toyota-Guy verwendet werden, um den tatsächlichen Zwekc zu Ermitteln (der Zweck liegt immer außerhalb des zu realisierenden Software-Systems)
- Dokumentieren lässt sich das ganze mit einem **Problem Statement**. Es beantwortet folgende Fragen:
    - Wie ist es jetzt?
    - Was ist das Problem daran?
    - Wer hat das Problem?
    - Welcher Schaden entsteht dadurch?

- *„Momentan <Ist-Situation, Ausgangslange, Ursachen>.
Das führt zu <Problem, Schaden, Symptom> für <Betroffene (Personen, Prozesse)>.“* Mit solchen "Satzschablonen lässt sich die Dokumentation standardisieren.


###  Sie können das Big Picture für ein System skizzieren und klare und prüfbare Ziele setzen.
#### Big Picture und Vision
- Die Vision beschreibt das System auf oberster Ebene („Big Picture“). Sie beschreibt, wie das System zur Lösung des Problems beiträgt.
- Das Big Picture beschreibt auf sehr hoher Flughöhe das WAS? und beantwortet auch die Frage nach dem Sinn (WOZU?“)
- Die Vision beschreibt (auch) die high-level Anforderungen an das System auf oberster Ebene und sollte daher die wesentlichen Kernanforderungen und Stakeholder\*innen benennen. Sie ist damit eine maßgebliche Entscheidungshilfe.
- Musthaves in der Vision:
    - Wie heißt das System?
    - Für wen bauen wir es?
    - In welchem Themenfeld bewegen wir uns?
    - Welchen Nutzen soll es bringen?
    - Was sind die Kernanforderungen (Funktionen, Eigenschaften)?
- eine beliebte Methode zur Beschreibung des Big Pictures ist der Elevator Pitch

#### Klare prüfbare Ziele
- Ziele beschreiben konkrete und prüfbare Eigenschaften des Systems, Zustände und Ergebnisse, an denen wir am Ende erkennen, ob wir die Vision erreicht haben bzw. während des Projektes, ob wir ihr näherkommen.
- Gute Kriterien für Ziele sind *SMART* (fml :roll_eyes:)
    - **S**pezifisch, konkret
    - **M**essbar, prüfbar
    - **A**bgestimmt
    - **R**ealistisch, erreichbar
    - **T**erminiert
- es gibt aber auch noch zusätzliche Kriterien, die vorallem wichtig für eine gemeinsame Richtung und Sinn sind
- Es gibt harte Zielen und Strech-Goals, die zur Not auch unerreicht bleiben können
- Natürlich ist es zur Abgrenzung auch sinnvoll Nicht-Ziele zu formulieren
- Ziele kann man mit Akzeptanzkritierien und Metriken prüfbar machen (Sie sind bereits während der Umsetzung als Monitoring-Instrument nützlich)
    - Eine Metrik bildet ein Ziel auf einen zu erreichenden Zahlenwert ab. Sie beinhaltet den zu erreichenden Zielwert bzw. Wertebereich, die Maßeinheit und ggf. Angaben zum Messvorgang.
    - Akzeptanzkriterien beschreiben vollständig, welche Kriterien erfüllt sein müssen, damit ein Ziel als „erreicht“ gelten kann.
- Ziele können in verschiedenen Dimensionen existieren:
    - Projekt- bzw. Prozessziele beschreiben den Prozess der Software-Entwicklung
    - Qualitätsziele beschreiben die zu erreichende Produktqualität bzw. Eigenschaften.
    - Funktionale Ziele beschreiben Funktionen, die das System bieten muss.
    -  Nutzenziele beschreiben positive Wirkungen auf die Umwelt, die das System im Betrieb bewirken soll.

###  Sie können ein System abgrenzen.
- Was machen wir (in Scope)? Was nicht mehr (out of Scope)?
- Was werden die Kernfunktionen und –Eigenschaften (Kernanforderungen, Key-Features) sein?
- Können wir diese Fragen beantworten, ist das Ergebnis der „Scope“, der beschreibt, was wir alles ändern. Er wird im Zuge des RE immer klarer.
- In einem Projekt muss der Scope auch schon im Projektauftrag beschrieben sein.

###  Sie kennen die wesentlichen Aspekte des Systemkontexts und können diese analysieren.
#### Systemkontext
- Der Systemkontext beschreibt alles, was außerhalb des Systems liegt und die Anforderungen beeinflusst (der Sytemkontext ist sehr unterschiedlich, je nach zu realisierendem System)
- Dazu können gehören:
    - Zu lösende Probleme und zu erreichende Ziele
    - Zu unterstützende und betroffene Geschäftsprozesse
    - Relevante Ereignisse
    - Stakeholder*innen, Akteur*innen und die Organisationsstruktur
    - Die vorhandene (und geplante) IT-Infrastruktur
    - Physikalische Einsatzumwelt
    - Einzuhaltende Gesetze, Normen, Vorschriften. Auch interne.
    - Andere Systeme (Altsysteme, Konkurrenzsysteme, anzubindende Systeme)
    - Vorhandene Dokumente (Projektauftrag, Analysen, Konzepte, Fehlerberichte, ...)
- Erst wenn Ziele, Scope und Kontext festgelegt sind, kann man beginnen, die
Anforderungen zu ermitteln.

#### Kontextanalyse
- Es geht darum:
    - Die Fachdomäne der Stakeholder\*innen zu kennen und zu verstehen.
    - Alles zu kennen, was rund ums System da ist (im Real Life und in der Software/IT) und Einfluss auf das zu schaffende/zu ändernde System hat.
    - Relevante Einsatzszenarien zu erkennen
    - Bereits wesentliche Rahmenbedingungen zu erkennen
- Zur Kontextanalyse (*Umfeldanalyse* im Projekt-Engineering-Jargon) gehören z.Bsp.:
    - wichtige Personen(gruppen) (Stakeholder\*innen wie Anwender\*innen, Kund\*innen, ... und deren Kenntnisse/Skills/Ausbildung
    - Organisation (Rollen, Hierarchie, Abteilungen)
    - Kultur (Ungeschriebene Regeln, Best Practices, Beziehungen, …)
    - Fremdsysteme (technische Systeme aus Soft- u. Hardware, Konkurrenzprodukte)
    - Altsysteme (Vorgängersysteme, Vorgängerversionen des Systems)
    - Terminologie (Sprache der Domäne, Fachbegriffe, Abkürzungen)
    - Gesetzliche Rahmenbedingungen (Gesetze, Normen, Standards)
    - Übergeordnete (oder benachbarte) Projekte/Produkte (z.B. übergeordnetes SAP System)
    - Dokumente (interne Vorschriften, Systemdokumentation)





###  Sie wissen um die wesentliche Rolle der Stakeholder\*innen und können die richtigen Stakeholder\*innen auswählen.

###  Sie kennen wichtige Grundregeln im Umgang mit Stakeholder\*innen.