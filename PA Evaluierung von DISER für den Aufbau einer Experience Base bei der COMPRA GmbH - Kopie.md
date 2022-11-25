---
title: "Evaluierung einer Experience Factory bei der COMPRA GmbH"
date: \today
author: "Lennard Brunke"
fontsize: 11pt
classoption: twocolumn
documentclass: article
indent: true
link-citations: true
urlcolor: "blue"
output:
  pdf_document:
    toc: true
    number_sections: true
---

# Zusammenfassung
In der vorliegenden Projektarbeit soll evaluiert werden, ob die DISER Methodologie [@tautz_2001] geeignet ist, um bei der COMPRA GmbH eine neue Experience Factory zu entwickeln. Dieses System soll im Bereich der Softwareentwicklung des ERP Systems eEvolution und anderer Projekte der COMPRA GmbH
Entscheidungsunterstützung bieten.
Es wird die aktuelle Situation des Experience-Managements bei der COMPRA GmbH analysiert und im weiteren behandelt werden, wie die DISER Methodologie grundsätzlich aufgebaut ist und wie sie auf die Anforderungen der COMPRA GmbH sowie eine moderne agile Arbeitsweise angepasst werden kann.
Das Ziel dieser und weiterführender Arbeit ist es, eine neue Experience Base bei der COMPRA GmbH aufzubauen.


# Einleitung
Warum ist Erfahrungsmanagement für Unternehmen, insbesondere im Bereich der Softwareentwicklung, so wichtig?
Reicht es aus, dass Wissen und Erfahrung im persönlichen Gespräch von Mitarbeiter zu Mitarbeiter weitergegeben oder sie sporadisch und in unterschiedlichsten Formen
in einem Netzwerk, in einer Quellcodeverwaltung oder einem DMS abgelegt werden?

Wie kann sichergestellt werden, dass das Wissen des eines langjährigen Mitarbeiters nicht gänzlich verloren geht, wenn dieser das Unternehmen verlässt?
Diese einleitenden Fragen geben einen guten ersten Eindruck, warum Erfahrungsmanagement im Bereich Softwareentwicklung eine zentrale Rolle für die Produktivität der Mitarbeiter
und die Qualität der entwickelten Produkte spielt.

[@tautz_2001] beschreibt in der Einleitung, dass der größte Vorteil im Wettbewerb von Unternehmen in der Softwareentwicklung darin besteht, bessere Software mit mehr Features schneller und mit geringeren Kosten entwickeln zu können.
Dieses Know-How kann durch die Konkurrenz nicht imitiert werden, da es nicht von dem Softwareprodukt ableitbar ist.
Daraus lässt sich annehmen, dass Experience Management im Software Engineering ein entscheidender Vorteil ist, um sich von der Konkurrenz abzusetzen.



# Experience Factory
> In diesem Kapitel soll das Konzept von QIP und der Experience Factory erläutert werden.

Eine Experience Factory beschreibt eine Einheit in einem Softwareunternehmen, welche kontinuierliche und inkrementelle Verbesserung der Softwareentwicklung im Unternehmen erzeugen soll. Dies wird erreicht durch die Verarbeitung und Analyse aller Arten von Wissen und Erfahrung, welche im Kontext der Softwareentwicklung relevant sind.
Sie dient als ein Repository (Experience Base) für dieses Wissen und entspricht einer Fallbasis im Sinne von Case-Based-Reasoning.
Weiterhin ist die Experience Factory zuständig für die Administration der Experience Base.

In [Tau001 1.1] beschreibt Tautz das Konzept der Experience Factory durch einen Vergleich des CBR Zyklus mit dem Paradigma QIP.

Quality Improvement Paradigm [Basili001] ist ein früher Ansatz für iterative Qualitätsverbesserung von Softwareprojekten.
QIP zielt darauf ab, schon in der Startphase eines Softwareprojektes festzulegen, welche Erfahrungen daraus gewonnen werden können und wie dies konkret erreicht werden kann.
QIP ist als eine Feedback Loop aufgebaut, welche durch die selbst auferlegten Ziele gesteuert wird. Im letzten Schritt von QIP wird die gewonnenen Erfahrungen in eine wieder verwendbare Form gebracht und aufbewahrt.
Im Kontrast dazu ist der CBR Zyklus mehr technischer Natur, aber grundsätzlich zielen beide Ansätze auf das Gleiche ab:
Ein Experience Model welches im Kontext der Softwareentwicklung wiederverwendet werden kann.

Beide dieser Konzepte bilden die Basis der Experience Factory:
> The experience factory is a logical and/or physical organization that
> supports project developments by analyzing and synthesizing all
> kinds of experience, acting as a repository for such experience, and
> supplying that experience to various projects on demand. It packages experience by building
> informal, formal or schematized, and
> productized models and measures of various software processes,
> products, and other forms of knowledge via people, documents,
> and automated support.

Die genannten Konzepte wurden in einer Zeit entwickelt, in welcher das übliche Vorgehen in Softwareprojekten einer Form des Wasserfallmodells entsprach. Heutzutage, und auch bei der COMPRA GmbH, wird ein agiler Entwicklungsprozess bevorzugt.
Der Fakt, dass CBR und QIP schon damals einer iterativen Funktionsweise zugrunde lagen zeigt, dass ein agiler, iterativer Entwicklungsansatz diese Arten von Prozessen noch viel besser einsetzen und einfacher Wert daraus gewinnen kann.
Im Vergleich zum Gebrauch in einem Wasserfallmodell werden die Erfahrungsinkremente bei einem agilen Prozess kleiner und fokussierter sein.

Dies lässt grundsätzlich vermuten, dass der Aufbau und letztendlich auch der laufende Betrieb einer Experience Factory sich gut in den aktuellen agilen Entwicklungsprozess der COMPRA GmbH integrieren lässt.

# Ansätze Erfahrungsmanagement in der Softwareentwicklung
> In diesem Kapitel soll ein Überblick über die verschiedenen Ansätze, welche im Erfahrungsmanagement in der Softwareentwicklung genutzt werden, gegeben werden.
> Außerdem sollten hier die Technicken beschrieben werden, die bisher bei der COMPRA GmbH für das Thema Erfahrungsmanagement verwendet werden.

Bei der COMPRA GmbH werden verschiedene Softwaresysteme geführt, welche neben ihrer hauptsächlichen Funktion auch als Repository für Wissens- und Erfahrungsartefakte verwendet werden. Dies geschieht nicht zwangsläufig mit der Intention des Erfahrungsmanagement, sondern ist häufig eine Konsequenz aus der Kommunikation und Kollaboration.
Nachfolgend werden alle Softwaresysteme genannt, welche in irgendeiner Form als Repository für Erfahrungsmanagement genutzt werden:

* MS Team Foundation Server:

  Source Control
  Interne sowie externe Kollaborationsplattform zur Planung, Kommunikation und Dokumentation der Softwareentwiclung in allen Teams und Projekten Projekt- oder Teambezogene Wikis


* ELO Document Management System

  Interne Dokumente (Personalmanagement, Gehaltsabrechnungen etc.)
  Dokumentation von internen Prozessen und Vorgängen (Sprint Retrospektiven, Protokolle)


* Windows File-Server:

  Ablage von verschiedensten Dateien und Dokumenten
  Installationsdateien
  Projektbezogene Dateien und Dokumente


* ERP System eEvolution und MS SQL Server:

  Erstellung von Rechnungen
  Dokumentation von Arbeitszeiten
  Verwaltung von Mitarbeitern und Kunden
  CRM


* [eEvolution Wiki](https://wwww.wikierp.de)

  Offizielles, zentrales Wiki für das ERP System eEvolution

* MS Teams:

  Interne und externe Kommunikation und Kollaboration (Chats, Meetings).


* MS Sharepoint:

  Teamübergreifende Kalender, Dokumentation, Verschiedenes.


* Yammer:

  Internes soziales Netzwerk


* Email und IP-Telefon



Vergleichen wir die verwendeten Technicken in diesen Systemen mit den von Tautz aufgeführten vorhandenen Ansätzen für Erfahrungs-Repositories wird deutlich, dass eine ganze Reihe bei der COMPRA GmbH im Einsatz sind:

* Controlled / Uncontrolled Keyword System [Tautz001 5.1.4]
* Full Text Search auf vorhandene Repositories [Tautz001 5.1.5]
* Hypertext [Tautz001 5.2]
* Relational and Object-Oriented DBMS [Tautz001 5.3.1 5.3.2]

Alle vorhandenen Repositories verfügen über die Möglichkeit über Full Text Search durchsucht zu werden.
Der Team Foundation Server verwendet ein unkontrolliertes Keyword System, wobei jegliche Art von Workitem mit beliebigen Keywords versehen werden kann.
Das eEvolution Wiki ist eine Website, verwendet also Hypertext.
eEvolution ist ein ERP System, welches mit einer relationalen Datenbank betrieben wird.

Auffallend ist hier, dass nur eher simple Ansätze verwendet werden, welche ohne weiteren größeren Aufwand innerhalb der genannten Softwaresysteme betrieben werden können. Es gibt kein System, welches logikbasiert, wissensbasiert oder mit irgendeiner Form von KI arbeitet.

##  Erfahrungsmanagement bei der COMPRA GmbH

Zuvor wurden Erfahrungs-Repositories bei der COMPRA GmbH genannt.
In diesem Kapitel soll im Detail behandelt werden, wie die Repositories im Prozess der Softwareentwicklung eingebunden sind, welche Vor- und Nachteile dies beinhaltet und welche Maßnahmen nötig sind, um die Softwareentwicklung durch gezieltes Erfahrungsmanagement zu verbessern.

Das am häufigsten und am erfolgreichsten verwendete System bei der COMPRA GmbH ist der MS Team Foundation Server (TFS). Er wird als Source Control, Product Backlog sowie Kommunikations- und Kollaborationsplattform (intern und extern) verwendet.
Die COMPRA GmbH arbeitet nach einem agilen Manifest mit Scrum. Im TFS wird das Product Backlog zu jedem Team bzw. Kunden oder Projekt in Form von Features, User Stories und Issues gepflegt. An diesem Product Backlog sind alle relevanten Stakeholder beteiligt.
Nehmen wir nun an, ein Team steht vor einer neuen Anforderung eines Kunden und möchte frühere Entwicklungen und Erfahrungen nutzen, welche bereits für andere Kunden in diesem Bereich gemacht wurden, um den Entwicklungsprozess in den Aspekten Kosten, Geschwindigkeit und Qualität zu verbessern.

Das bisherige übliche Vorgehen ist hierbei, zunächst den TFS über eine Full Text Search, Keywords oder gefiltert nach Attributen des Product Backlogs zu durchsuchen. Dies kann in manchen Fällen schnell relevante Product Backlog Items finden, jedoch nur, wenn der Suchende bereits Kenntnis über die Existenz der relevanten Backlog Items hat.
Ist keine Kenntnis darüber vorhanden, ist die Suche meist langwierig und ohne Erfolg.
Aus diesem Grund wird vor dem Schritt des Durchsuchens des Backlogs im persönlichen Gespräch mit anderen Mitarbeitern versucht, bereits zu filtern ob ähnliche Anforderungen in der Vergangenheit bereits existierten, für welches Projekt bzw. Kunden diese entwickelt wurden und welche Mitarbeiter darin involviert waren.
Mit diesen Informationen können die richtigen Kollegen angesprochen werden, um letztendlich die relevanten Backlog Items zu finden, sofern sie existieren.
Es ist vorgesehen, dass Backlog Items mit sämtlichen relevanten Informationen verknüpft sind. Dies beinhaltet Code Changesets, Dokumentationen jeglicher Art sowie sämtliche Kommunikation zum Backlog Item im Bezug auf Requirement-Engineering. In der Praxis ist dies leider nicht immer der Fall und auch hier sind wichtige Informationen oft nur über die involvierten Mitarbeiter zu finden.
Ein Problem dabei ist, dass wie oben beschrieben noch viele weitere Systeme als Experience-Repository verwendet werden und nicht alle Informationen im relevanten TFS Backlog Item aggregiert werden. Gibt es beispielsweise eine Installationsanleitung mit "lessons learned" aus vorherigen Projekten, welche aber in einem Projektordner auf einem File Server abgelegt ist, so muss der Suchende Mitarbeiter erst auf diese Information hingewiesen werden.

Dies führt zu einer großen Belastung von gewissen Senior Mitarbeitern, welche den größten Erfahrungsschatz besitzen. Das Problem und die Auslastung wird noch viel größer, wenn der Mitarbeiter wiederholt aus verschiedenen Quellen nach den selben Informationen gefragt wird.

Um dieses Problem zu lösen, sollte ein einheitlicher Prozess für eine Experience Factory entwickelt werden, damit Artefakte in genau einem Repository zu finden sind und Mitarbeiter wissen, wie diese Artefakte dort abgelegt werden sollen.
Weiterhin muss die Experience Factory fest in die Entwicklungsprozesse integriert werden, damit Erfahrungsartefakte nicht vergessen werden können.
Wenn ein Mitarbeiter nach einer Information sucht muss klar sein wie und wo nach dieser Information gesucht werden kann.

## Agiler Entwicklungsprozess bei der COMPRA GmbH







# DISER
> In diesem Kapitel soll die Methodologie DISER zusammgengefasst werden.

## Repräsentation von Software Engineering Erfahrungen
> In diesem Kapitel soll [@tautz_2001] Kapitel 6 zusammgengefasst werden.

Eine der elementarsten Fragen für den Aufbau einer neuen Experience Base ist, nach welchem Schema das Wissen und die Erfahrung strukturiert sein soll. Dies ist wichtig, um einerseits das Erfassen von Artefakten einfach und intuitiv zu halten, um sie in der alltäglichen Kommunikation verwenden zu können als auch um die spezifischen Anforderungen des Unternehmens abzudecken.
Weiterhin bestimmt der Repräsentationsformalismus, wie die Erfahrungsartefakte tatsächlich im Kontext der Softwareentwicklung genutzt werden können.

## REFSENO
REFSENO beschreibt wie die Informationen in einer Experience Base formuliert und strukturiert werden können um die Möglichkeiten in der Verwendung in einer Experience Factory zu maximieren. [Tautz001 6.1]
REFSENO's zentrales Element wird durch "concepts" definiert, welche Software Engineering Artefakte modellieren. Concepts setzen sich durch verschiedene Attribute zusammen, welche sich in terminal und nonterminal attributes unterscheiden.


## Technische Infrastruktur

## GOODSEE (goal-oriented ontology development for software engineering experience)




## DISER Task Framework
## DISER Anforderungen


# Anforderungen COMPRA
In diesem Kapitel soll beschrieben werden, welche Anforderungen von COMPRA kommen und ob DISER diese erfüllen kann. Hier sollten die Anforderungen von Tautz durchgegangen und evaluiert werden, welche für die COMPRA relevant sind. Weiterhin wird beschrieben, was angepasst werden muss.

## Wissensquellen

# Fazit
# Quellen
[An Ontology-Based Knowledge Model for Software Experience Management](https://eprints.um.edu.my/4572)

# Relevante Kapitel aus [Tau001]
T32 LEARN Decomposition: record (T33, page 107), analyze SEEMS (T50, page 116), forget (T54, page 119), package (T55, page 120)
