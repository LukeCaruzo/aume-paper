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

Die Zukunft der Software-Entwicklung liegt heutzutage im agilen und mobilen Bereich. Durch immer weiter verteilte Teams an verschiedensten Standorten, mit verschiedensten Kulturen und verschiedensten Vorkenntnissen, muss man sich im Bereich der Software-Entwicklung auf immer neue Herausforderungen einstellen. Dafür benötigt man eine agile Strategie und ein mobiles Vorgehen. Eine der Herangehensweisen dafür, ist die Nutzung des Vorgehensmodell der Scrum Methodik. Diese Arbeit soll daher die verschiedenen Rollen im Scrum Team aufgreifen, analysieren und erörtern. Dazu werden drei Entwicklungspraktiken, nämlich die testgetriebene Entwicklung, die modellgetriebene Entwicklung und die verteilte Entwicklung,  genauer betrachtet und im Zusammenhang mit dem Scrum Team gebracht. Im Bezug dazu werden Grundlagen über das Refactoring, die Continuous Integration, das Pair Programming und die Collective Ownership erläutert. Dabei werden drei Leitfragen eingebunden und beantwortet. Anhand dieser Erörterung können tiefgreifendere Untersuchungen der Scrum Methodik fortgeführt werden.

# Einleitung

## Motivation

Die Aktualität, Mobilität und Flexibilität des Scrum Prinzips machen dies zu einem sehr effektiven Werkzeug in der Projektdurchführung. Dazu ist dies ein sehr einfaches Prinzip, welches dadurch eine hohe Effektivität bietet. Des weiteren bietet Scrum viel Spielraum für die Entwickler, ohne das Hauptziel des Projektes aus den Augen zu verlieren. Dadurch fördert man die Anregung individueller kreativer Prozesse des Entwicklerteams. Durch diese Herangehensweise lassen sich viele Vorteile ausnutzen.
Um diese Prinzipien vollständig auszunutzen, wird sich in dieser Arbeit mit der Frage beschäftigt, welche Entwicklungspraktiken aktuell besonders relevant für ein Scrum Entwicklerteam sind.

## Aufgabenstellung

Zuerst werden die allgemeinen Werte und Grundlagen von Scrum erörtert um grundlegende Verständnisse von Scrum zu erlangen. Unter diesen befinden sich die Werte und der Ansatz von Scrum. Dabei werden die drei Säulen der empirischen Verbesserung angeschnitten. Daneben wird noch auf die Scrum Events eingegangen.
Danach wird ein grundlegendes Verständnis der Rollen von Scrum zu geschaffen, um die Vorteile der verschiedensten Entwicklungspraktiken im Bezug zu diesen besser verstehen zu können.
In dieser Arbeit beschäftigen wir uns insbesondere mit der Beantwortung der Hauptleitfrage, welche Entwicklungspraktiken für ein Scrum Team aktuell besonders relevant sind. Dabei wird speziell auf die drei Entwicklungspraktiken, nämlich der testgetriebenen Entwicklung, der modellgetriebenen Entwicklung und der verteilten Entwicklung eingegangen. Im Bezug dazu werden Grundlagen über das Refactoring, die Continuous Integration, das Pair Programming und die Collective Ownership erörtert. Es wird sich dabei auf den aktuellsten Stand von 2020 bezogen.
Daneben wird sich mit weiteren Leitfragen beschäftigt, wie was überhaupt eine erfolgreiche Praktik in der Entwicklung ist, welche Praktiken aus aktueller Sicht häufig angewandt wird und wieso, sowie welche Kosten mit den einzelnen Praktiken verbunden sind. 
Im Abschluss dazu wird das Thema noch einmal zusammengefasst und ein Fazit gezogen.

# Grundlagen

Die Scrum Methodik lässt sich als Gegenstück zur Befehls-und-Kontroll-Organisation verstehen, bei der die Mitarbeiter genaueste Anweisungen erhalten. Im Bezug dazu baut Scrum auf die Vorgabe einer klaren Zieldefinition auf, wozu ein hochqualifiziertes, interdisziplinäres Entwicklerteam benötigt wird. Diese Entwickler sind für die Umsetzung des Ziels dann individuell verantwortlich und bekommen dadurch genügend Freiraum um ihr Wissens- und Kreativitätspotential optimal auszuschöpfen.

## Werte der agilen Software-Entwicklung

Durch Scrum werden im Grunde nur die Werte der agilen Software-Entwicklung aufgegriffen, welche von Ken Schwaber, Jeff Sutherland und anderen im Jahre 2001 definiert wurden.

1. Individuen und Interaktionen sind wichtiger als Prozesse und Werkzeuge.
2. Funktionierende Software ist wichtiger als umfassende Dokumentation.
3. Zusammenarbeit mit dem Kunden ist wichtiger als Vertragsverhandlungen.
4. Reagieren auf Veränderung ist wichtiger als das Befolgen eines Plans.

Dort werden die Werte auf der rechten Seite für wichtig empfunden, es werden jedoch die Werte auf der linken Seite höher eingeschätzt. [@2001agilemanifesto]
Daher besteht Scrum nur aus einem minimalen Regelsatz. Dort werden die vier Ereignisse, drei Artefakte und drei Rollen, welche den Kern von Scrum ausmachen, beschrieben. Dieser Regelsatz wird im Scrum Guide, oder auch in Kurzversion im Agile Atlas, beschrieben. Jedoch muss das Scrum-Framework durch Techniken erweitert werden. In dieser Arbeit werden wir uns besonders auf die Techniken und Kernaussagen für die Scrum-Rollen beschäftigen. Dieser Kern wurde von den Techniken getrennt, da man klar die zentralen Wirkungsmechanismen definieren möchte und dabei auch eine große Freiheit bei der individuellen Ausgestaltung ermöglichen möchte. [@2020scrumwiki] In dieser Arbeit werden wir uns besonders mit den Techniken und Kernaussagen für die Scrum-Rollen beschäftigen.

## Ansatz von Scrum

Scrum wurde mit einem empirischen, inkrementellen und iterativen Ansatz entwickelt. Durch die Erfahrungswerte, dass die meisten Entwicklungsprojekte zu komplex sind, um für diese einen vollständigen Plan zu entwickeln, konnte sich Scrum dort daher durchsetzen. Am Anfang ist bei komplexen Projekten ein wesentlicher Teil der Anforderungen und dessen Lösungsansätze unklar. Scrum zielt daher eher auf das Erreichen von Zwischenergebnissen ab. Dies umfasst sowie den Entwicklungsablauf des Produkts sowie die Planung an sich. Der Product Backlog, wird im kontinuierlichen Entwicklungsprozess nach und nach verbessert. Der dazu gehörende Detailplan, auch Sprint Backlog genannt, wird nur für den kommenden Zyklus, auch Sprint genannt, erarbeitet. Durch diese Herangehensweise, wird sich im Konkreten nur auf die Projektplanung fokussiert. [@2020scrumwiki]

### Die drei Säulen der empirischen Verbesserung

1. Transparenz: Fortschritt im Projekt wird für alle sichtbar und in regelmässigen Intervallen festgehalten.
2. Überprüfung: Es gibt eine kontinuierliche Abgabe von Projektergebnissen und Funktionalitäten, welche dann auch bewertet werden.
3. Anpassung: Die Projektanforderungen sind dynamisch. Sie können kontinuierlich verbessert und detailliert erweitert werden. Dadurch reduziert Scrum die Komplexität der Aufgabe nicht, sondern strukturiert sie in weniger komplexe Einzelteile (auch Inkremente genannt).

Durch diese drei Säulen kann man das Ziel, nämlich die schnelle und kostengünstige Entwicklung von hochwertigen Produkten, welches in einer Vision formuliert ist, gut umsetzen. Die definierten Anforderungen, welche im Product Backlog niedergeschrieben werden, werden in Sprints, welche Intervalle zwischen ein bis vier Wochen sind, nach und nach umgesetzt. Für das Sprintende ist vorgesehen ein Teilprodukt (Product Increment) vorzustellen. Danach wird das Produkt und die Anforderungen, sowie das Vorgehen überprüft und für den nächsten Sprint weiterentwickelt. Dabei ist vorgesehen, dass ein Scrum Team aus minimal drei und maximal neun Entwicklern besteht. Für größere Projekte benötigt man daher weitergehende Frameworks, welche jedoch auch auf Scrum aufbauen können. [@2020scrumguide]

## Scrum Events

Durch die Gliederung aller Scrum Events als Sprint, werden dadurch alle Angelegenheiten die nötig sind vereint, um Scrum-Artefakte zu überprüfen und anzupassen. Durch diese Zusammenfassung bieten die Events die erforderliche Transparenz. Ebenfalls entsteht durch diese Events eine gewisse Regelmässigkeit und ermöglicht das vermeiden von Meetings, welche nicht in Scrum definiert sind.
Zu den Scrum Events zählt der Sprint an sich, das Sprint Planning, das Daily Scrum, die Sprint Review und die Sprint Retrospektive. 
Im Sprint läuft das eigentliche Projekt ab, wobei Ideen in Werte umgesetzt werden. Diese haben eine feste Länge um mehr Konsistenz zu schaffen. Wenn ein Sprint endet, beginnt unmittelbar ein neuer. 
Alle oben genannten Scrum Events finden innerhalb des Sprints statt. 
Dazu gehört das Sprint Planning, welches den Sprint initiiert und ein Plan für das gemeinschaftliche Arbeiten des gesamten Scrum Teams erstellt wird. 
Im mittleren Teil des Sprints gibt es die Daily Scrum Meetings. Diese sind nötig um den Verlauf des Fortschritts des Sprint-Ziels zu überprüfen und somit die geplante Arbeit und das Backlog fortlaufend anzupassen. Den Entwickler/innen ist es möglich sich auch außerhalb des Daily Scrum Meetings zu treffen. 
Um den Sprint abzuschließen findet am Ende die Sprint Review statt. Die Entwicklerteams präsentieren die Ergebnisse des Sprints. Dabei wird das Ergebnis des Sprints überprüft und für die künftigen Sprints anpassungen vorgenommen. 
Daraufhin folgt die Sprint Retrospektive, diese ist dazu da, den Verlauf zur Steigerung der Qualität und Effektivität zu planen. Dazu wird überprüft, wie der Sprint im Bezug auf Interaktionen, Individuen, Prozesse und Werkzeuge verlief. Probleme dabei werden identifiziert und die Ursachen dafür erforscht, um diese im kommenden Sprint zu verbessern. Nach der Sprint Retrospektive ist der Sprint endgültig abgeschlossen. [@2020scrumguide]

## Rollen in Scrum
Für das Scrum Framework gibt es drei Rollen, den/die Product Owner/in, den/die Scrum Master/in und den/die Entwickler/in, beziehungsweise das Entwicklerteam. Dieses Scrum Team ist selbstorganisierend und interdisziplinär. Außerdem hat das Scrum Team die Fähigkeit sich selbstständig zu managen. Es teilt ein gemeinsames Ziel, das Produkt-Ziel. 
Dieses Scrum Team ist klein genug, dass es flexibel bleibt und groß genug, damit innerhalb eines Sprintsabschnittes ein bedeutsames Zwischenziel zu erreichen. Üblicherweise besteht es aus maximal 10, beziehungsweise weniger Personen. Es wurde festgestellt, dass kleinere Teams besser kommunizieren und auch produktiver sind. Bei einem zu großen Scrum Team, sollte man sich in Erwägung ziehen dieses in mehrere kleinere zusammengehörende Scrum Teams zu reorganisieren. Dabei sollte die Produktvision nicht aus den Augen verloren werden, das heisst, dass sie sich das Produkt-Ziel, den Product Backlog und der/die Product Owner/in teilen.
Es besteht eine ergebnisverantwortlichkeit zwischen dem Scrum Team und den produktbezogenen Aktivitäten. Darunter befinden sich die Verifikation, die Wartung, der Betrieb, die Experimente, die Forschung und die Entwicklung. Durch den geschickten organisatorischen Aufbau ist es einfach möglich seine Arbeit selbst zu steuern. Durch die Struktur des Projekts in Sprintabläufe mit nachhaltiger Geschwindigkeit wird der Fokus und die Kontinuität des Teams stetig verbessert.
Das Scrum Team ist außerdem eigenverantwortlich in jedem Sprint ein wertvolles Inkrement zu schaffen. Dafür gibt es innerhalb des Scrum Teams die drei spezifischen Rollen, den/die Product Owner/in, den/die Scrum Master/in und den/die Entwickler/in. [@2020scrumguide]

### Product Owner/in

Der/die Product Owner/in sind die Eigentlichen verantwortlichen innerhalb des Scrum Teams. Dabei steht die Maximierung des Wertes des Produkts im Vordergrund. 
Das Product-Backlog-Management gehört zu den Hauptaufgaben des/der Product Owner/in. Dies umfasst das Produkt-Ziel zu entwickeln und klar zu kommunizieren. Dazu gehört das Erstellen der Product-Backlog-Einträge und genau zu kommunizieren. Diese Rolle beinhaltet auch die Reihenfolge dieser Product-Backlog-Einträge festzulegen, um sicherzustellen, dass dieser sichtbar, transparent und verständlich ist. Ob der/die Product Owner/in die oben genannten Aufgaben selbst erfüllt oder sie delegiert, bleibt ihm überlassen. Jedoch bleibt die Verantwortlichkeit dessen bei ihm. 
Um erfolgreich zu sein, muss die gesamte Organisation des/der Product Owners/in respektiert werden. Dies lässt sich durch das Überprüfen des Inkrements bei der Sprint Review nachverfolgen.
Bei dem/der Product Owner/in handelt es sich um eine Einzelperson, kein Gremium. Diese Person ist Ansprechpartner für alle Stakeholder/innen, welcher ihre Bedürfnisse im Product Backlog berücksichtigt. Um Änderungen am Product Backlog zu erzeugen, müssen sich diese mit dem/der Product Owner/in besprechen und ihn/sie überzeugen. [@2020scrumguide]

### Scrum Master/in

Der/die Scrum Master/in muss die Durchführung des Scrum Guide betreuen. Dabei hilft er den Teilnehmer/innen die Scrum-Theorie, sowie -Praxis umzusetzen und zu verstehen. Dies betrifft die Organisation, sowie das Scrum Team an sich. Dies dient der Steigerung der Effektivität des Scrum Teams. Daher sind sie echte Führungskräfte, welche dem Scrum Team und der Gesamtorganisation dienen. [@2020scrumguide]

#### Bedeutung für den/die Product Owner/in

Der/die Scrum Master/in unterstützt den/die Product Owner/in auf verschiedenste Weisen. Darunter befindet sich die Suche nach Techniken für die effektivste Definition des Produkt-Ziels und die Hilfe beim Product-Backlog-Management. Unter anderem hilft er dem Scrum Team die Einträge im Product-Backlog zu verstehen und dessen Notwendigkeit zu präzisieren. Er hilft außerdem bei der Etablierung einer empirischen Produktplanung. Die Zusammenarbeit zwischen dem/der Product Owner/in und den Stakeholdern wird ebenfalls nach Wunsch oder Bedarf gesteigert. [@2020scrumguide]

#### Bedeutung für das Entwicklerteam

Die Unterstützung des/der Product Owners/in für das Entwicklerteam wird durch verschiedenste Techniken umgesetzt. Dabei hilft er den Entwicklern sich in Selbstmanagement und interdisziplinärer Zusammenarbeit zu verbessern. Den Fokus auf die Schaffung von einem Inkrement zu unterstützen, welche sich auf die “Definition of Done” stützen. Er beseitigt ebenfalls Hindernisse des Teams, die den Fortschritt behindern. Das Zeitmanagement wird von ihm überwacht, damit die Scrum Events stattfinden und diese innerhalb der vorgegebenen Timeboxen bleiben. [@2020scrumguide]

#### Bedeutung für das Organisieren

Die Organisation im Scrum Team wird auf verschiedenen Wegen durch den/die Scrum Master/in gestützt. Der/die Scrum Master/in leitet die Organisation bei der Einführung von Scrum, um die Teilnehmer zu schulen. Er ist ebenfalls dafür verantwortlich die Einführung von Scrum in der Organisation zu planen und zu empfehlen. Die Stakeholder/innen werden beim Verständnis und bei der Umsetzung für komplexe Arbeit von dem/der Scrum Master/in unterstützt. Ebenfalls wird durch ihn die Barriere zwischen Stakeholder/innen und dem Entwicklerteam aufgelöst. [@2020scrumguide]

### Entwickler/in

Die Hauptaufgabe der Entwickler/innen ist, in jedem Sprint einen nutzbaren Inkrement zu schaffen. Je nach Arbeitsumfeld sind die spezifischen Fähigkeiten der Entwickler breit gefächert. Dabei sind sie verantwortlich den Plan des Sprints zu erstellen, nämlich den Sprint Backlog. Sie müssen ebenfalls die Qualität sichern, welches sie durch die Einhaltung der “Definition of Done” machen. Des weiteren wird von ihnen täglich der Plan zur Erreichung des Sprint-Ziels angepasst. Durch ihr Wissen, können sie sich wechselseitig als Expert/innen zur Verantwortung gezogen werden. [@2020scrumguide]

#### Grösse des Teams

Die Größe eines Scrum Teams ist von hoher Bedeutung. Es sollte aus minimal drei und maximal neun Mitgliedern bestehen. Man muss dabei beachten, dass durch steigende Teamgröße sich der Koordinationsaufwand erheblich steigert. Jedoch muss es groß genug sein, um alle Kompetenzen in sich zu vereinigen. Bei grösseren Teams muss zu erweiternden Frameworks gegriffen werden. [@2020scrumwiki]

### Stakeholder/innen

Eigentlich befinden sich die Stakeholder/innen Rollen außerhalb von Scrum, jedoch werden sie hier des Verständnisses halber aufgelistet. Unter ihnen befinden sich die Auftraggeber, die Anwenderschaft und das Management. Die Kommunikation zwischen dem Scrum Team und der Gruppe der Stakeholder/innen wird durch den/die Product Owner/in gestärkt und geleitet. [@2020scrumwiki]

# Die aktuell wichtigsten Entwicklungspraktiken für ein Scrum Team

In dieser Arbeit beschäftigen wir uns mit der Frage, welche Entwicklungspraktiken für ein Scrum Team aktuell besonders relevant sind. Dazu legen wir unseren Fokus auf die folgenden Entwicklungspraktiken, nämlich der testgetriebenen Entwicklung, der modellgetriebenen Entwicklung und der verteilten Entwicklung. Dabei betrachten wir auch das Refactoring, die “Continuous Integration”, das “Pair Programming” und die “Collective Ownership”. Diese Praktiken sind enthalten in den vorzustellenden Entwicklungspraktiken und spielen einen großen Teil bei der Umsetzung. Daher werden diese im aktuellen Entwicklerumfeld häufig genutzt und beinahe jedes Entwicklerteam bemächtigt sich ihrer Vorteile.
Um ein genaues Verständnis der genannten Entwicklungspraktiken zu bekommen, sollten zuerst Grundlagen der aufbauenden Praktiken, nämlich dem “Refactoring”, der “Continuous Integration”, dem “Pair Programming” und der “Collective Ownership” geschaffen werden. Dazu wird im nächsten Abschnitt zuerst das Refactoring behandelt. Wenn die Grundlagen geschaffen wurden, wird sich im kommenden Verlauf der Arbeit speziell auf die drei Entwicklungspraktiken, nämlich der testgetriebene Entwicklung, der modellgetriebene Entwicklung und der verteilten Entwicklung bezogen und diese analysiert. Daraufhin wird im Bezug zu diesen die Leitfragen, die im Abschnitt Aufgabenstellung vorgestellt wurden, beantwortet. 

## Das Refactoring

In der Software Entwicklung ist das Refactoring schon längst nichts neues mehr. 
Beim Refactoring wird die  innere Struktur von Software verändert, ohne das von aussen betrachtbare Verhalten zu ändern. Dazu gehört beispielsweise das einfache Umbenennen von Instanzvariablen. Aufwändigeres Refactoring ist zum Beispiel das Vorgehen “Replace Nested Conditional with Guard Clause”. Dabei wird eine eingebettete Wenn-Dann-Abfrage verbessert, indem Variablen direkt zurückgegeben werden, anstatt einzeln gesetzt und dann erst zurückgegeben zu werden. 
Refactoring kann durch Nutzung von Tests validiert werden, denn diese Tests sollten vor dem Refactoring sowie danach gleichermaßen funktionieren, da die Funktionalität der getesteten Funktionen gleich bleibt. Dies ist wichtig, da man beim Refactoring nur die innere Struktur verändert und die Schnittstelle nach aussen unangetastet bleibt. Da man beim Testen häufig einzelne Funktionen testet, kann man daher nach einem Refactoring genau überprüfen, ob man fehlerhaftes Refactoring betrieben hat. 
Um den Code leserlich zu halten, muss man auf Refactoring wert legen. Dazu zählt auch die Wiederholungen von Code. Diese Wiederholungen werden auf dauer zu einem immer größer werdenden Problem, da diese den Refactoringaufwand mit jeder Wiederholung weiter steigern. 
Die Frage, wann man sich am besten mit Refactorings beschäftigt, sollte immer mit einem “jetzt” beantwortet werden. Denn wenn man Code entdeckt, den man Refactoring unterziehen könnte und diesen nicht bearbeitet, steigert dies das Risiko, dass dieser schlechte Code die weiterführende Arbeit behindert. Größeres Refactoring tritt nur durch ein Versäumnis oder technologische Alternativen auf. Die Behebung dessen könnte mehrere Tage oder Wochen benötigen und sollte daher nicht sofort in Angriff genommen werden. Ebenfalls ist es häufig sehr teuer größere Refactorings durchzuführen und daher ist genau abzuwägen, ob diese von Nöten sind und wie man am besten vorgeht. 
Im Bezug auf Scrum tauchen die Refactorings bei der “Definition of Done” auf. Dabei sollte eine Story nur als erledigt gelten, wenn der Code vollständig refaktorisiert worden ist. Um die Wichtigkeit des Refactorings dem/der Product Owner/in verständlich zu machen, muss das Team dieses Vorgehen in die “Definition of Done” übernehmen. Dies ist so wichtig, da durch Refactoring das Team untereinander profitiert. Bei Arbeit am Refactoring sollte dies auch untereinander im Team am Daily Scrum Meeting besprochen werden. [@2011agile]

## Die Continuous Integration

Im Scrum Kontext ist es wichtig häufig Feedback zu bekommen. Eine der dafür geeignetsten Strategien ist die Anwendung von der “Continuous Integration”. 
Der Begriff der Continuous Integration wurde vom “Extreme Programming” geprägt. Dort wird die ständige und kleinschrittige Integration von Codeänderungen beschrieben. 
Heutzutage lässt sich die Continuous Integration in den meisten Versionsverwaltungstools, wie GitHub, GitLab oder anderen (zum Beispiel Jenkins) leicht einbinden. Dabei wird ein Prozess gestartet, welcher die Korrektheit von Konsistenzkriterien überprüft. Dazu gehört die Compilierfähigkeit, die semantische Korrektheit, die funktionierende Paketierung, die Testabdeckung und eventuell die Codemetriken und Komplexitätsmaße. Diese Konsistenzkriterien werden bei jedem Commit auf den Remote überprüft. 
Die Compilierfähigkeit beschreibt dabei, dass sich alle Komponenten fehlerfrei übersetzen lassen. Die semantische Korrektheit ist gegeben, wenn alle  der automatisierten Tests fehlerfrei durchlaufen. Dabei werden auf Klassenebene die Unit Tests ausgeführt und für das Zusammenspiel verschiedener Komponenten gibt es die Integrationstests. Die funktionierende Paketierung beschreibt hierbei, das Erzeugen eines deploybaren Artefakt. Idealerweise wird dabei genau dieses auf einem Testsystem ausgerollt. Des weiteren gibt es die Testabdeckung, welche beschreibt, wie viel Prozent des Codes durch die Tests abgedeckt wird. Ebenfalls können optional die Codemetriken und Komplexitätsmaße überprüft werden. Dabei handelt es sich um Qualitätskriterien, wie Maximalwerte von Klassengrössen oder Verschachtelungstiefen. 
Durch diese Taktiken, lässt sich mit Hilfe von Continuous Integration schnellstmöglich Feedback einholen. Beim Fehlschlagen einer Integration muss das Entwicklerteam schnellstmöglich (zum Beispiel automatisch) benachrichtigt werden, um Folgeschritte einzuleiten. 
Im Bezug auf Scrum, wird die “Continuous Integration” bei der “Definition of Done”, sowie bei den Daily Scrum Meetings nützlich. Es sollte in der “Definition of Done” festgelegt sein, dass die Integration erfolgreich durchgelaufen sein muss. Im Daily Scrum Meeting kann das automatisierte Deployment hilfreich werden. Dort können die Entwickler sich gegenseitig neuste Änderungen schnell präsentieren und zeigen, dass diese lauffähig sind. 
Um Arbeitsaufwand zu minimieren, sollte die “Continuous Integration” schon bei Projektstart eingebunden werden, es ist aber jedoch auch möglich diese nachträglich in ein laufendes Projekt einzupflegen. [@2011agile]

## Das Pair Programming

Von Pair Programming ist die Rede, wenn zwei Entwickler simultan an einem Projekt arbeiten. Dies kann gemeinsam vor Ort an einem Rechner stattfinden oder von unterschiedlichen Orten unterstützt durch geeignete Kommunikationssoftware. Die Grundidee dabei ist, dass die Entwickler durch einen ständigen Dialog sich über das Detaildesign und den Code durchgehend austauschen. Diese Praktik ähnelt einer kontinuierlichen Codereview. Bei diesem Vorgehen wechseln die Rollen der Entwickler ständig, da sie sich aufteilen, welcher aktiv schreibt und welcher passiv beiträgt. 
Erfahrungsgemäß ist Pair Programming ein mächtiges Werkzeug, da es zu mehr Disziplin führt. Zusammen arbeitende Entwickler achten gegenseitig mehr auf die Einhaltung von Codekonventionen und weitere wichtige Aspekte. Durch diese Vorteile weist der paarweise entwickelte Code eine höhere Qualität auf. Daher ist die zukünftige Wartung und Erweiterung des Codes kostengünstiger.
Im Bezug zu Scrum hilft das Pair Programming vor allem mit dem Beilegen von Wissensungleichheiten im Team. Sollte im Daily Scrum Meeting festgestellt werden, dass einzelne Programmierer nicht weiter kommen sollten, kann durch Pair Programming diesem Einhalt geboten werden. Des weiteren ist das Scrum Team kollektiv für das Erreichen des Sprint-Ziels verantwortlich, was die gegenseitige Unterstützung fördert. 
Auch zu beachten ist, dass der Entwicklungspartner regelmäßig gewechselt wird, sodass sich keine festen Paare innerhalb des Scrum Teams bilden.
Pair Programming lässt sich sowohl in ein bestehendes Projekt, als auch  ein gerade erst gestartetes Projekt, leicht einpflegen. [@2011agile]

## Die Collective Ownership

Die Collective Ownership beschreibt die Verantwortlichkeit des gesamten Teams für den geschriebenen Quellcode. Dabei wird keinem Entwickler einzeln Teile des Codes zugeordnet, sondern alle Entwickler sind gleich verantwortlich für den Code. Dies macht das Projekt ein agiler, da jeder Entwickler an jeder Stelle des Codes arbeiten kann. Weil das gesamte Team für die Änderungen verantwortlich gemacht wird, ist es notwendig sich dementsprechend gut über die gemachte Arbeit austauschen. Nur durch Collective Ownership ist das Pair Programming überhaupt möglich, da dort das gesamte Team als kollektive Einheit kollaboriert. 
Im Scrum Kontext hilft die Collective Ownership bei der Aufgabenverteilung. Dabei können Aufgaben einfach nach fachlichen Kriterien geschnitten werden, ohne auf spezielle Codeabschnitte Rücksicht geben zu müssen. Das stellt sicher, dass eine fachliche und für den Kunden wertschöpfende Anforderung in sich geschlossen entwickelt werden kann. [@2011agile]

## Die testgetriebene Entwicklung

Die testgetriebene Entwicklung, auch Test Driven Development genannt, besteht im Grunde aus drei Teilen.
Im ersten Teil schreiben die Entwickler automatisierte Tests, noch bevor sie mit dem eigentlich Applikationscode beginnen. Das Design findet dabei in kleinen Abschnitten und nach und nach statt. Es liegt dabei der Fokus auf dem Schreiben der Tests vor dem eigentlichen Entwickeln. Dazu hilft es das Design in kleinen Abschnitten zu entwickeln, was ein inkrementelles Design verspricht. 
Die Entwicklung findet dabei in einem Test-Code-Refactor-Zyklus statt, welcher den Kern des Test Driven Development beschreibt. Diese Mechanik funktioniert dabei in drei Schritten, nämlich das Schreiben eines Testfalls, welcher fehlschlägt. Dabei werden auch neue Funktionen und Methoden aufgerufen, welche noch nicht existieren. Daraufhin wird der Test durch Änderungen am Anwendungscode zum Erfolg gebracht. Im letzten Schritt wird der geschriebene Code dem Refactoring unterzogen, wie im vorherigen Abschnitt erläutert wurde.
Dieses Vorgehen ist im Scrum Kontext sehr nützlich um ein stetiges Inkrement zu erzeugen, was auch auf Testabdeckung und das Testen im allgemeinen Rücksicht nimmt. Auch hilft es den Entwicklern beim Fokus auf den nächsten Schritt und fördert gleichzeitig das unabhängige Arbeiten der Entwickler. [@2011agile]

## Die modellgetriebene Entwicklung

Bei der modellgetriebenen Entwicklung handelt es sich um die Praktik, anhand von Modellen Software zu entwickeln. 
Modelle sind eine Abstraktion der komplexen Realität. Dabei richten sich die Form und der Inhalt der Modelle nach ihrem jeweiligen Einsatzzweck. Diese Modelle müssen formal sein, dass heißt sie müssen vom Computer verarbeitet werden können.  Dazu werden häufig domänenspezifische Sprachen verwendet. 
Das Ziel dabei ist, dass die erstellten Modelle automatisch in Code überführt werden können. Somit lässt sich beispielsweise ein System modellieren und dann als Quellcode darstellen. Dadurch lässt sich kostbare Entwicklungszeit einsparen und die geschaffenen Modelle sind eine gut verständliche Abbildung des zu schaffenden Systems. 
Im Rahmen von Scrum ist es von Vorteil, eine domänenspezifische Sprache inkrementell zu entwickeln. Dabei startet man wie gewohnt in den anfänglichen Sprints damit und ab einem bestimmten Zeitpunkt bildet sich dann ein wiederkehrendes Muster, auch mit Hilfe der automatische Generierung von Code. 
Beim Arbeiten mit domänenspezifischen Sprachen gilt ebenfalls im Scrum Umfeld die Collective Ownership”, daher sind alle Entwickler gleichermaßen für den entwickelten Generator verantwortlich. Wie üblich sollte Gebrauch von Refactoring gemacht werden. Der Einsatz von “Continuous Integration” ist in der modellgetriebenen Entwicklung auch sehr nützlich. Dabei kann der Codegenerator in die Continuous Integration eingebunden werden, um die einzelnen Codestücke zu generieren.
Sinnvoll eingesetzt kann die modellgetriebene Entwicklung mit Scrum die Produktivität und Qualität des Teams merkbar steigern. [@2011agile]

## Die verteilte Entwicklung

Da Scrum Teams auch verteilt agieren können, ist die verteilte Entwicklung eine Betrachtung wert. 
Bei der verteilten Entwicklung differenziert man zwischen zweierlei Arten von Teams: Dem verteilten Team und dem verstreuten Team. Beide Teams decken das benötigte Wissen und die notwendigen Rollen ab, welche sie zum erfüllen der “Definition of Done” benötigten. 
Bei den verteilten Teams sitzen die Teammitglieder an einem Standort zusammen, kooperieren aber mit Teams, welche sich an anderen Standpunkten befinden. Somit entwickeln mehrere Teams gemeinsam dasselbe Projekt. 
Beim verstreuten Team befinden sich die Teammitglieder über mehrere Standorte verstreut. 
Bei einem verteilten Team hat man den Vorteil der physischen Nähe innerhalb des Teams, jedoch den Nachteil, dass die Kommunikation mit den anderen Teams erschwert ist. Dies führt häufig dazu, dass sich an den verschiedenen Standorten, verschiedene Entwicklungskulturen und eine mangelnde konzeptionelle Integrität herausbildet. Bei verstreuten Teams hat man diese Nachteile nicht, jedoch dauert es deutlich länger bis das Team eine Teambildung vollzogen hat und anfängt performant zu arbeiten. Wichtig dabei ist, dass die Teams, egal welche Konstellation, gemeinsam an einem Projekt arbeiten. 
Das “virtuelle Pair Programming” bildet einen großen Vorteil, welcher jedoch auch Herausforderungen mit sich bringt. Dies bedeutet unter anderem, dass der fehlende physische Kontakt die Effizienz von Pair Programming mildert. Virtuelles Pair Programming funktioniert am effektivsten, wenn die Teammitglieder auch im persönlichen Kontakt stehen, dass heißt die Standorte liegen nicht zu weit auseinander. 
Um dies trotzdem effizient nutzen zu können, sollten die Entwickler über  Video- und Sprach-Kommunikationssoftware verbunden sein. 
Die Benutzung von Entwicklungstests bleibt nahezu unverändert, wohingegen die Akzeptanztests mehr Bedeutung bekommen. Diese sind wichtig, da die Spezifikation meist von  Entwicklern unterschiedlich interpretiert wird. Durch Nutzung von Akzeptanztests werden die Akzeptanzkriterien technisch dargestellt und sind selbst in anderen Kulturräumen verständlich. Der Hauptvorteil bietet sich jedoch dabei, dass durch die zeitnahe und systematische Ausführung der Akzeptanztests eine Analyse der Anforderungen schnell erstellt werden kann.
Bei verteiler Entwicklung rückt die Wichtigkeit der “Collective Ownership” noch mehr in den Vordergrund, da in manchen Ländern mit einer erhöhten Fluktuation von Entwicklern gerechnet werden muss. Daher ist es wichtig, dass alle beteiligten Entwickler jedes Detail der Software verstehen. 
Auch die “Continuous Integration” ist bei verteilter Entwicklung sehr wichtig. Heutzutage lässt sich dies auch ohne feste Standortbindung schnell und sicher einrichten und somit die Entwickler aktiv bei ihrer Arbeit unterstützen.
Es ist außerdem wichtig, dass alle Standorte die ähnliche Ausbildung erhalten. 
Im Scrum Kontext kann es sehr schnell vorkommen, dass das Team verteilt ist und daher zur verteilten Entwicklung gegriffen werden muss. [@2011agile]

## Erfolgreiche Praktiken in der Entwicklung

Eine erfolgreiche Praktik in der Entwicklung ist eine, die das Entwicklungsgeschehen, sowie das Scrum Team verbessert und unterstützt. Ohne eine  effiziente und korrekte Nutzung dieser eigentlich erfolgreichen Praktik kann eine eigentlich erfolgreiche Praktik genau im gegenteiligen wirken.
In dieser Arbeit wurden speziell drei Entwicklungspraktiken, nämlich die testgetriebene Entwicklung, die modellgetriebene Entwicklung und die verteilte Entwicklung, hervorgehoben und im Scrum Kontext erläutert. 
Dazu gehört die testgetriebene Entwicklung, welche ein stetiges Inkrement durch das vordefinieren des Codes als Tests ermöglicht. Bei einer korrekten Anwendung hat man daher den Vorteil, erstens ein stetiges Inkrement vorzuweisen und zweitens direkt eine hohe Testabdeckung für den Quellcode vorweisen zu können. Das Praktische dabei ist außerdem, dass beim Bearbeiten einer User Story durch einen Entwickler die Designentscheidungen nach und nach stattfinden und somit effektiver mit dem Product Owner kommuniziert werden können. Dabei wird außerdem bei jedem Entwickler die unabhängige Arbeit und den Fokus auf den nächsten Schritt gefördert. Diese Punkte machen diese Entwicklungspraktik bei korrekter Anwendung zu einer erfolgreichen Praktik in der Entwicklung.
Die nächste vorgestellte Praktik ist die modellgetriebene Entwicklung. Dabei wird durch die Nutzung von Modellen und Codegeneratoren, wie im Abschnitt oben erläutert, die Produktivität und Qualität des Teams merkbar gesteigert. Da man bei der Kommunikation zwischen dem Entwicklerteam und dem Product Owner die gewünschten Features für alle verständlich aufzeigen muss, helfen diese Modelle besonders dabei. Zusätzlich kann durch die Codegenerierung Entwicklungsarbeit eingespart werden.
Die dritte aufgezeigte Praktik ist die verteilte Entwicklung. Da ein Scrum Team häufig nicht vom selben Standort agiert, ist es von großem Vorteil die Prinzipien der verteilten Entwicklung zu nutzen. Dabei fördert man die standortunabhängige Zusammenarbeit eines oder mehrerer Entwicklerteams. Diese Praktik erweist sich als erfolgreiche Entwicklungspraktik, da durch sie eine reibungslose Zusammenarbeit von Teams an verschiedenen Standorten möglich gemacht wird.
Diese Praktiken können ein Entwicklungsvorgang effizient und agil unterstützen. Dabei helfen sie die Zusammenarbeit des Teams oder der Teams zu fördern und stoßen die Kreativität der einzelnen Entwickler an. [@2011agile]

## Aktuell häufig angewandte Praktiken

Es gibt viele verschiedene Entwicklungspraktiken, welche jedoch alle dasselbe Ziel verfolgen. Dieses Ziel ist, das Entwicklerteam auf dem Entwicklungsweg zu unterstützen und das erreichen dieses zu erleichtern. 
Aus aktueller Sicht werden die oben erläuterten Entwicklungspraktiken, nämlich die testgetriebene Entwicklung, die modellgetriebene Entwicklung und die verteilte Entwicklung, häufig angewandt. Diese unterstützen die Entwicklerteams bei ihrer Arbeit. In Zeiten wie der Corona Pandemie sind die Entwickler beispielsweise darauf angewiesen von zu Hause oder von entfernten Standorten zusammen zu entwickeln. Dabei kann beispielsweise die Praktik der verteilten Entwicklung sehr hilfreich werden. 
Zusätzlich können sie bei ihrer Arbeit durch das Nutzen der testgetriebenen Entwicklung unterstützt werden. Viele moderne Projekte müssen eine hohe Testabdeckung erzielen, da dies besonders in sicherheitskritischen Projekten von hoher Wichtigkeit ist (zum Beispiel in der Automobilindustrie). Größere Vernetztheit mit einhergehender größerer Komplexität, verlangt dass jede Schnittstelle ausgiebig getestet wird. [@2011agile]

## Kosten der Praktiken

Die Kosten für diese Praktiken sind unterschiedlich. Durch das korrekte Einpflegen einer Praktik an einer Stelle werden Kosten geschaffen, welche an einer anderen Stelle wieder entfallen. 
Bei der testgetriebenen Entwicklung sind die anfallenden Kosten Schulungskosten. Das heißt, dass bei der Einführung von testgetriebener Entwicklung die Entwickler geschult werden müssen, wie sie Anforderungen in atomare Funktionseinheiten zerlegen können. Zudem ist Konsequenz der Entwickler nötig. Entwicklern welche noch kaum Erfahrung besitzen müssen diese Praktik erst erlernen, um sie erfolgreich einzusetzen. Dadurch ergibt sich eine höhere Einarbeitungszeit. Zudem ist die Nutzung der testgetriebenen Entwicklung kein Ersatz für alle anderen Testarten, welche man zusätzlich einpflegen muss. [@2020tddwiki]
Bei der modellgetriebenen Entwicklung fallen Kosten bei der Initialisierung des Projektes an. Bei komplexeren Projekten ist meist schwerer eine geeignete domänenspezifische Sprache zu entwickeln. Da die Modelle meist nur Teilaspekte des Projektes abbilden, wird häufig der eigentliche Aufwand unterschätzt. Durch diese Punkte erhöht sich der Kostenfaktor der Praktik. [@2020mdsdwiki]
Die verteilte Entwicklung trägt den Hauptkostenpunkt in der gleichen Ausbildung aller Standorte. Dabei ist es wichtig, dass alle Entwickler an allen Standorten die gleiche Ausbildung erhalten und somit kann diese Praktik nicht zum Outsourcing und das damit gewünschte Minimieren der Kosten genutzt werden. Zusätzlich fallen bei notwendigen Reisen an die verschiedenen Standorte kosten an. Auch das Veranstalten von grösseren Teamtreffen von verschiedenen Standorten muss berücksichtigt werden. [@2016vd]
Auch wenn man die genauen Kosten nicht genau berechnen kann, zeigt die Erfahrung dass diese sich im späteren Verlauf des Projekts amortisieren. Denn auch bisher unberücksichtigte Herausforderung können effizient gemeistert werden. Dazu zählen unter anderem den Wechsel von Entwicklern oder das Auftreten einer Pandemie, welche viele bisherige Abläufe unmöglich macht.  Erfahrungswerte verschiedenster Teams haben gezeigt, dass das Einbinden der verschiedenen Entwicklungspraktiken in ein oder mehrere Entwicklerteams meistens die Agilität und Effektivität steigert und ein qualitativ hochwertigeres Arbeiten ermöglicht. [@2011agile]

# Auswertung

In diesem Kapitel wird sich mit der Auswertung der erlangten Kenntnissen auseinandergesetzt. Dazu wird der Inhalt dieser Arbeit noch einmal aufbereitet und zusammengefasst um die Zusammenhänge, welche erarbeitet wurden zu veranschaulichen. Die Problemstellung der Arbeit war, herauszufinden welche Entwicklungspraktiken aktuell besonders relevant sind, welche von ihnen aktuell häufig angewandt werden, was für Kosten dabei entstehen und was überhaupt eine erfolgreiche Entwicklungspraktik ist. 

## Zusammenfassung

Zuerst wurden die Grundlagen für das grobe Verständnis von Scrum und den einzelnen Scrum Rollen geschaffen. Dabei wurden die vier zentralen Scrum Rollen vorgestellt. 
Für das Verständnis der Entwicklungspraktiken ist es notwendig über das Refactoring, die Continuous Integration, das Pair Programming und die Collective Ownership zu kennen und zu verstehen.  
Daraufhin wurden die drei eigentlichen Entwicklungspraktiken, nämlich die testgetriebene Entwicklung, die modellgetriebene Entwicklung und die verteilte Entwicklung vorgestellt und in den Zusammenhang mit den zuvor beschriebenen Praktiken gesetzt. Dabei wurde der Gesamtfokus auf den Zusammenhang im Scrum Kontext gelegt. 
Abschließend wurden die drei Leitfragen, wie was überhaupt eine erfolgreiche Praktik in der Entwicklung ist, welche Praktiken aus aktueller Sicht häufig angewandt wird und wieso, sowie welche Kosten mit den einzelnen Praktiken verbunden sind, aufgegriffen und beantwortet.

## Fazit

Es gibt viele verschiedene Entwicklungspraktiken, welche in verschiedenen Konstellationen miteinander genutzt werden können. Es gibt kein Geheimrezept, womit man die perfekte Zusammenarbeit dieser Entwicklungspraktiken vorhersagen kann. In einem Scrum Team kommt es daher häufig dazu, dass mehrere Praktiken gemeinsam genutzt werden. Welche dabei eingebunden werden muss das Scrum Team für sich entscheiden. Dabei sollte darauf geachtet werden die Komplexität so klein wie möglich zuhalten und die eigentlichen Ziele nicht aus den Augen zu verlieren. Der zusätzliche Aufwand und die damit verbundenen Kosten sind von Praktik zu Praktik unterschiedlich und können schwer genau beziffert werden. Die Erfahrung zeigt allerdings, dass bestimmte Entwicklungspraktiken Vorteile bieten, welche den mitgelieferten Nachteilen überlegen sind.

# Quellen