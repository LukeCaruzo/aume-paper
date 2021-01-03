---
title: Rollen im Scrum Team
subtitle: Welche Entwicklungspraktiken sind für ein Scrum Team aktuell besonders relevant?
author: Lucas Schmidt
date: 2021-01-11
fontsize: 11pt
numbersections: true
listings: true
bibliography: [bibliography.bib]
csl: chicago-author-date.csl
---

# Abstract

Die Zukunft der Software-Entwicklung liegt heutzutage im agilen und mobilen Bereich. Durch immer weiter verteilte Teams an verschiedensten Standorten, mit verschiedensten Kulturen und verschiedensten Vorkenntnissen, muss man sich im Bereich der Software-Entwicklung auf immer mehr Problemstellungen einstellen. Dafür benötigt man eine agile Strategie und ein mobiles Vorgehen. Eine der Herangehensweisen dafür, ist die Nutzung des Vorgehensmodell der Scrum Methodik. Diese Arbeit soll daher die verschiedenen Rollen im Scrum Team aufgreifen, analysieren und erörtern. Dazu werden die drei Entwicklungspraktiken die testgetriebene Entwicklung, die modellgetriebene Entwicklung und die verteilte Entwicklung genauer betrachtet und im Zusammenhang mit dem Scrum Team gebracht. Im Bezug dazu werden Grundlagen über das Refactoring, die Continuous Integration, das Pair Programming und die Collective Ownership erläutert. Dabei werden drei Leitfragen eingebunden und beantwortet. Anhand dieser Erörterung können tiefgreifendere Untersuchungen der Scrum Methodik fortgeführt werden.

# Einleitung

## Motivation

Die Aktualität, Mobilität und Flexibilität des Scrum Prinzips machen dies zu einem sehr effektiven Werkzeug in der Projektdurchführung. Dazu ist dies ein sehr einfaches Prinzip, welches dadurch eine hohe Effektivität bietet. Des weiteren bietet Scrum viel Bewegungsraum für die Entwickler, jedoch wird das Hauptziel des Projektes nicht aus den Augen verloren. Dadurch fördert man die Anregung individueller kreativer Prozesse des Entwicklerteams. Durch diese Herangehensweise lassen sich viele Vorteile ausnutzen.
Um diese Prinzipien vollständig auszunutzen, wird sich in dieser Arbeit mit der Frage beschäftigt, welche Entwicklungspraktiken aktuell besonders relevant für ein Scrum Entwicklerteam sind.

## Aufgabenstellung

Zuerst werden die allgemeinen Werte und Grundlagen von Scrum erörtert um grundlegende Verständnisse von Scrum zu erlangen. Unter diesen befinden sich die Werte und der Ansatz von Scrum. Darunter werden die drei Säulen der empirischen Verbesserung angeschnitten. Daneben wird noch auf die Scrum Events eingegangen.
Danach wird ein grundlegendes Verständnis der Rollen von Scrum zu geschaffen, um die Vorteile der verschiedensten Entwicklungspraktiken im bezug zu diesen besser verstehen zu können.
In dieser Arbeit beschäftigen wir uns insbesondere mit der beantwortung der Hauptleitfrage, welche Entwicklungspraktiken für ein Scrum Team aktuell besonders relevant sind. Dabei wird speziell auf die drei Entwicklungspraktiken, nämlich der testgetriebenen Entwicklung, der modellgetriebenen Entwicklung und der verteilten Entwicklung eingegangen. Im Bezug dazu werden Grundlagen über das Refactoring, die Continuous Integration, das Pair Programming und die Collective Ownership erörtert. Es wird sich dabei auf den aktuellsten Stand von 2020 bezogen.
Daneben wird sich mit weiteren Leitfragen beschäftigt, wie was überhaupt eine erfolgreiche Praktik in der Entwicklung ist, welche Praktiken aus aktueller Sicht häufig angewandt wird und wieso, sowie welche Kosten mit den einzelnen Praktiken verbunden sind. 
Im Abschluss dazu wird das Thema noch einmal zusammengefasst und ein Fazit gezogen.

# Grundlagen

Die Scrum Methodik lässt sich als Gegenstück zur Befehls-und-Kontroll-Organisation verstehen, bei der die Mitarbeiter genaueste Anweisungen erhalten. Im Bezug dazu baut Scrum auf die Vorgabe einer klaren Zieldefinition auf, wozu ein hochqualifiziertes, interdisziplinäres Entwicklerteam benötigt wird. Diese Entwickler sind für die Umsetzung des Ziels dann individuell verantwortlich und bekommen dadurch genügend Freiraum um ihr Wissens- und Kreativitätspotential völlig auszuschöpfen.

## Werte der agilen Software-Entwicklung

Durch Scrum werden im Grunde nur die Werte der agilen Software-Entwicklung aufgegriffen, welche von Ken Schwaber, Jeff Sutherland und anderen im Jahre 2001 definiert wurden.

1. Individuen und Interaktionen sind wichtiger als Prozesse und Werkzeuge.
2. Funktionierende Software ist wichtiger als umfassende Dokumentation.
3. Zusammenarbeit mit dem Kunden ist wichtiger als Vertragsverhandlungen.
4. Reagieren auf Veränderung ist wichtiger als das Befolgen eines Plans.

Dort werden die Werte auf der rechten Seite für wichtig empfunden, es werden jedoch die Werte auf der linken Seite höher eingeschätzt. [@2001agilemanifesto]
Daher besteht Scrum nur aus einem minimalen Regelsatz. Dort werden die vier Ereignisse, drei Artefakte und drei Rollen, welche den Kern von Scrum ausmachen, beschrieben. Dieser Regelsatz wird im Scrum Guide, oder auch in Kurzversion im Agile Atlas, beschrieben. Jedoch muss das Scrum-Framework durch Techniken erweitert werden. In dieser Arbeit werden wir uns besonders auf die Techniken und Kernaussagen für die Scrum-Rollen beschäftigen. Dieser Kern wurde von den Techniken getrennt, da man klar die zentralen Wirkungsmechanismen definieren möchte und dabei auch eine große Freiheit bei der individuellen Ausgestaltung ermöglichen möchte. [@2020scrumwiki] In dieser Arbeit werden wir uns besonders mit den Techniken und Kernaussagen für die Scrum-Rollen beschäftigen.

## Ansatz von Scrum

Scrum wurde mit einem empirischen, inkrementellen und iterativen Ansatz entwickelt. Durch die Erfahrungswerte, dass die meisten Entwicklungsprojekte zu komplex sind, um für diese einen vollständigen Plan zu entwickeln, konnte sich Scrum dort daher durchsetzen. Zu Anfangs ist bei diesen Projekten ein wesentlicher Teil der Anforderungen und dessen Lösungsansätze unklar. Scrum zielt daher eher auf die Erzielung von Zwischenergebnissen ab. Dies umfasst sowie den Entwicklungsablauf des Produkts sowie die Planung an sich. Der Product Backlog, wird im kontinuierlichen Entwicklungsprozess nach und nach verbessert. Der dazu gehörende Detailplan, auch Sprint Backlog genannt, wird nur für den kommenden Zyklus, auch Sprint genannt, erarbeitet. Durch diese Herangehensweise, wird sich im Konkreten nur auf die Projektplanung fokussiert. [@2020scrumwiki]

### Die drei Säulen der empirischen Verbesserung

1. Transparenz: Fortschritt im Projekt wird für alle sichtbar und in regelmässigen Intervallen festgehalten.
2. Überprüfung: Es gibt eine kontinuierliche Abgabe von Projektergebnissen und Funktionalitäten, welche dann auch bewertet werden.
3. Anpassung: Die Projektanforderungen sind nicht in Stein gemeisselt. Sie können kontinuierlich verbessert und detailliert erweitert werden. Dadurch reduziert Scrum die Komplexität der Aufgabe nicht, sondern strukturiert sie in weniger komplexe Einzelteile (auch Inkremente genannt).

Durch diese drei Säulen kann man das Ziel, nämlich die schnelle und kostengünstige Entwicklung von hochwertigen Produkten, welches in einer Vision formuliert ist, gut umsetzen. Die definierten Anforderungen, welche im Product Backlog niedergeschrieben werden, werden in Sprints, welche Intervalle zwischen ein bis vier Wochen sind, nach und nach umgesetzt. Für das Sprintende ist vorgesehen ein Teilprodukt vorzustellen, auch das Product Increment genannt. Danach wird das Produkt und die Anforderungen, sowie das Vorgehen überprüft und für den nächsten Sprint weiterentwickelt. Dabei ist vorgesehen Scrum in einem Team bestehend aus minimal drei und maximal neun Entwicklern zu betreiben. Für größere Projekte benötigt man daher weitergehende Frameworks, welche jedoch auch auf Scrum aufbauen können. [@2020scrumguide]

## Scrum Events

Durch die Gliederung aller Scrum Events als Sprint, werden dadurch alle Angelegenheiten die nötig sind, um Scrum-Artefakte zu überprüfen und anzupassen vereint. Durch diese Zusammenfassung bieten die Events die erforderliche Transparenz. Ebenfalls entsteht durch diese Events eine gewisse Regelmässigkeit und ermöglicht das vermeiden von Meetings, welche nicht in Scrum definiert sind.
Zu den Scrum Events zählt der Sprint an sich, das Sprint Planning, das Daily Scrum, die Sprint Review und die Sprint Retrospektive. 
Im Sprint läuft das eigentliche Projekt ab, wobei Ideen in Werte umgesetzt werden. Diese haben eine feste Länge um mehr Konsistenz zu schaffen. Wenn ein Sprint endet, beginnt unmittelbar ein neuer. 
Alle oben genannten Scrum Events finden innerhalb des Sprints statt. 
Dazu gehört das Sprint Planning, welches den Sprint initiiert, wobei ein Plan für das gemeinschaftliche Arbeiten des gesamten Scrum Teams erstellt wird. 
Im mittleren Teil des Sprints gibt es die Daily Scrum Meetings. Diese sind nötig um den Verlauf des Fortschritts des Sprint-Ziels zu überprüfen. Dabei wird wenn nötig die bevorstehende geplante Arbeit und der Backlog angepasst. Jedoch können sich die Entwickler/innen auch außerhalb des Daily Scrum Meetings treffen. 
Um den Sprint abzuschließen findet am Ende dieses die Sprint Review statt. Dabei wird das Ergebnis des Sprints überprüft und für die künftigen Sprints anpassungen vorgenommen. Dabei werden die Ergebnisse des Sprints durch das Entwicklerteam präsentiert. 
Daraufhin folgt die Sprint Retrospektive, diese ist dazu da, den Verlauf zur Steigerung der Qualität und Effektivität zu planen. Dazu wird überprüft, wie der Sprint im Bezug auf Interaktionen, Individuen, Prozesse und Werkzeuge verlief. Probleme dabei werden identifiziert und die Ursachen dafür erforscht, um diese im kommenden Sprint zu verbessern. Nach der Sprint Retrospektive ist der Sprint endgültig abgeschlossen. [@2020scrumguide]

# Rollen in Scrum
Für das Scrum Framework gibt es drei Rollen, den/die Product Owner/in, den/die Scrum Master/in und den/die Entwickler/in, beziehungsweise das Entwicklerteam. Dieses Scrum Team ist selbstorganisierend und interdisziplinär. Außerdem hat das Scrum Team die Fähigkeit sich selbstständig zu managen. Es teilt ein gemeinsames Ziel, das Produkt-Ziel. 
Dieses Scrum Team ist klein genug, dass es flexibel bleibt und groß genug, damit innerhalb eines Sprintsabschnittes ein bedeutsames Zwischenziel zu erreichen. Üblicherweise besteht es aus maximal 10, beziehungsweise weniger personen. Es wurde festgestellt, dass kleinere Teams besser kommunizieren und auch produktiver sind. Bei einem zu großen Scrum Team, sollte man sich in Erwägung ziehen dieses in mehrere kleinere zusammengehörende Scrum Teams zu reorganisieren. Dabei sollte die Produktvision nicht aus den Augen verloren werden, das heisst, dass sie sich das Produkt-Ziel, den Product Backlog und der/die Product Owner/in teilen.
Es besteht eine ergebnisverantwortlichkeit zwischen dem Scrum Team und den produktbezogenen Aktivitäten. Darunter befinden sich die Verifikation, die Wartung, der Betrieb, die Experimente, die Forschung und die Entwicklung. Durch den geschickten organisatorischen Aufbau ist es einfach möglich seine Arbeit selbst zu steuern. Durch die Struktur des Projekts in Sprintabläufe mit nachhaltiger Geschwindigkeit wird der Fokus und die Kontinuität des Teams stetig verbessert.
Das Scrum Team ist außerdem eigenverantwortlich in jedem Sprint ein wertvolles Inkrement zu schaffen. Dafür gibt es innerhalb des Scrum Teams die drei spezifischen Rollen, den/die Product Owner/in, den/die Scrum Master/in und den/die Entwickler/in. [@2020scrumguide]

## Product Owner/in

Der/die Product Owner/in sind die Eigentlichen verantwortlichen innerhalb des Scrum Teams. Dabei steht die Maximierung des Wertes des Produkts im Vordergrund. 
Das Product-Backlog-Management gehört zu den Hauptaufgaben des/der Product Owner/in. Dies umfasst das Produkt-Ziel zu entwickeln und klar zu kommunizieren. Dazu gehört das Erstellen der Product-Backlog-Einträge und genau zu kommunizieren. Dabei muss er auch die Reihenfolge dieser Product-Backlog-Einträge festlegen, um sicherzustellen, dass dieser sichtbar, transparent und verständlich ist. Ob der/die Product Owner/in die oben genannten Aufgaben selbst erfüllt oder sie delegiert, bleibt ihm überlassen. Jedoch bleibt die Verantwortlichkeit dessen bei ihm. 
Um erfolgreich zu sein, muss die gesamte Organisation des/der Product Owners/in respektiert werden. Dies lässt sich durch das Überprüfen des Inkrements bei der Sprint Review nachverfolgen.
Bei dem/der Product Owner/in handelt es sich um eine Einzelperson, kein gremium. Dieser ist Ansprechpartner für die Stakeholder/innen, welcher ihre Bedürfnisse im Product Backlog berücksichtigt. Um Änderungen am Product Backlog zu erzeugen, müssen sich diese mit dem/der Product Owner/in besprechen und ihn/sie überzeugen. [@2020scrumguide]

## Scrum Master/in

Der/die Scrum Master/in muss die Durchführung des Scrum Guide betreuen. Dabei hilft er den Teilnehmer/innen die Scrum-Theorie, sowie -Praxis umzusetzen und zu verstehen. Dies betrifft die Organisation, sowie das Scrum Team an sich. Dies dient der Steigerung der Effektivität des Scrum Teams. Daher sind sie echte Führungskräfte, welche dem Scrum Team und der Gesamtorganisation dienen. [@2020scrumguide]

### Bedeutung für den/die Product Owner/in

Der/die Scrum Master/in unterstützt den/die Product Owner/in auf verschiedenste Weisen. Darunter befindet sich die Suche nach Techniken für die effektivste Definition des Produkt-Ziels und die Hilfe beim Product-Backlog-Management. Unter anderem hilft er dem Scrum Team die Einträge im Product-Backlog zu verstehen und dessen Notwendigkeit zu präzisieren. Er hilft außerdem bei der Etablierung einer empirischen Produktplanung. Die Zusammenarbeit zwischen dem/der Product Owner/in und den Stakeholdern wird ebenfalls nach Wunsch oder Bedarf gesteigert. [@2020scrumguide]

### Bedeutung für das Entwicklerteam

Die Unterstützung des/der Product Owners/in für das Entwicklerteam wird durch verschiedenste Techniken umgesetzt. Dabei hilft er den Entwicklern sich in Selbstmanagement und interdisziplinärer Zusammenarbeit zu verbessern. Den Fokus auf die Schaffung von einem Inkrement zu unterstützen, welche sich auf die Definition of Done stützen. Er beseitigt ebenfalls Hindernisse des Teams, die den Fortschritt behindern. Das Zeitmanagement wird von ihm überwacht, damit die Scrum Events stattfinden und diese innerhalb der vorgegebenen Timeboxen bleiben. [@2020scrumguide]

### Bedeutung für das Organisieren

Die Organisation im Scrum Team wird auf verschiedenen Wegen durch den/die Scrum Master/in gestützt. Der/die Scrum Master/in leitet die Organisation bei der Einführung von Scrum, um die Teilnehmer zu schulen. Er ist ebenfalls dafür verantwortlich die Einführung von Scrum in der Organisation zu planen und zu empfehlen. Die Stakeholder/innen werden beim Verständnis und bei der Umsetzung für komplexe Arbeit von dem/der Scrum Master/in unterstützt. Ebenfalls wird durch ihn die Barriere zwischen Stakeholder/innen und dem Entwicklerteam aufgelöst. [@2020scrumguide]

## Entwickler/in

Die Hauptaufgabe der Entwickler/innen ist, in jedem Sprint einen nutzbaren Inkrement zu schaffen. Je nach Arbeitsumfeld sind die spezifischen Fähigkeiten der Entwickler breit gefächert. Dabei sind sie verantwortlich den Plan des Sprints zu erstellen, nämlich den Sprint Backlog. Sie müssen ebenfalls die Qualität sichern, welches sie durch die Einhaltung der Definition of Done machen. Des weiteren wird von ihnen täglich der Plan zur Erreichung des Sprint-Ziels angepasst. Durch ihr Wissen, können sie sich wechselseitig als Expert/innen zur Verantwortung gezogen werden. [@2020scrumguide]

### Grösse des Teams

Die Größe eines Scrum teams ist von hoher Bedeutung. Es sollte aus minimal drei und maximal neun Mitgliedern bestehen. Man muss dabei beachten, dass durch steigende Teamgröße sich der Koordinationsaufwand erheblich steigert. Jedoch muss es groß genug sein, um alle Kompetenzen in sich zu vereinigen. Bei grösseren Teams muss zu erweiternden Frameworks gegriffen werden. [@2020scrumwiki]

## Stakeholder/innen

Eigentlich sind die Stakeholder/innen Rollen außerhalb von Scrum, jedoch werden sie hier des Verständnisses halber aufgelistet. Unter ihnen befinden sich die Kunden, die Anwender/innen und das Management. Die Kommunikation zwischen dem Scrum Team und den Stakeholder/innen wird durch den/die Product Owner/in gestärkt und geleitet. [@2020scrumwiki]

# Die aktuell wichtigsten Entwicklungspraktiken für ein Scrum Team

[@2011agile]

## Das Refactoring

## Die Continuous Integration

## Das Pair Programming

## Die Collective Ownership

## Die testgetriebene Entwicklung

## Die modellgetriebene Entwicklung

## Die verteilte Entwicklung

## Erfolgreiche Praktiken in der Entwicklung

Was ist überhaupt eine erfolgreiche Praktik in der Entwicklung?

## Aktuell häufig angewandte Praktiken

Welche Praktiken werden aus aktueller Sicht häufig angewandt und warum?

## Kosten der Praktiken

Welche Kosten sind mit den Praktiken verbunden?

# Zusammenfassung

## Fazit

# Quellen