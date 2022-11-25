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
In der vorliegenden Projektarbeit soll evaluiert werden, ob die DISER Methodologie [Tau001] geeignet ist, um bei der COMPRA GmbH ein neues Erfahrungsmanagement
System zu entwickeln. Dieses System soll im Bereich der Softwareentwicklung des ERP Systems eEvolution und anderer Projekte der COMPRA GmbH
Entscheidungsunterstützung bieten.
Es wird behandelt werden, wie die DISER Methodologie auf die Anforderungen der COMPRA GmbH sowie eine moderne agile Arbeitsweise angepasst werden kann.\
Das Ziel dieser und weiterführender Arbeit ist es, eine neue Experience Base bei der COMPRA GmbH aufzubauen.


# Einleitung
Warum ist Erfahrungsmanagement für Unternehmen, insbesondere im Bereich der Softwareentwicklung, so wichtig?
Reicht es aus, dass Wissen und Erfahrung im persönlichen Gespräch von Mitarbeiter zu Mitarbeiter weitergegeben oder sie sporadisch und in unterschiedlichsten Formen
in einem Netzwerk, in einer Quellcodeverwaltung oder einem DMS abgelegt werden?

Wie kann sichergestellt werden, dass das Wissen des eines langjährigen Mitarbeiters nicht gänzlich verloren geht, wenn dieser das Unternehmen verlässt?
Diese einleitenden Fragen geben einen guten ersten Eindruck, warum Erfahrungsmanagement im Bereich Softwareentwicklung eine zentrale Rolle für die Produktivität der Mitarbeiter
und die Qualität der entwickelten Produkte spielt.

[Tau001] beschreibt in der Einleitung, dass der größte Vorteil im Wettbewerb von Unternehmen in der Softwareentwicklung darin besteht, bessere Software mit mehr Features schneller und mit geringeren Kosten entwickeln zu können.
Dieses Know-How kann durch die Konkurrenz nicht imitiert werden, da es nicht von dem Softwareprodukt ableitbar ist.
Daraus lässt sich annehmen, dass Experience Management im Software Engineering eine zentrale Rolle dabei spielt, um sich von der Konkurrenz abzusetzen.



# Experience Factory
> In diesem Kapitel soll das Konzept von QIP und der Experience Factory erläutert werden.

Eine Experience Factory beschreibt eine Einheit in einem Softwareunternehmen, welche kontinuierliche und inkrementelle Verbesserung der Softwareentwicklung im Unternehmen erzeugen soll. Dies wird erreicht durch die Verarbeitung und Analyse aller Arten von Wissen und Erfahrung, welche im Kontext der Softwareentwicklung relevant sind.
Sie dient als ein Repository (Experience Base) für dieses Wissen und entspricht einer Fallbasis im Sinne von Case-Based-Reasoning.
Weiterhin ist die Experience Factory zuständig für die Administration der Experience Base.

In [Tau001 1.1] beschreibt Tautz das Konzept der Experience Factory und durch einen Vergleich des CBR Zyklus mit dem Paradigma QIP.

Quality Improvement Paradigm ist ein früher Ansatz für iterative Qualitätsverbesserung von Softwareprojekten.
QIP zielt darauf ab, schon in der Startphase eines Softwareprojektes festzulegen, welche Erfahrungen daraus gewonnen werden können und wie dies konrekt erreicht werden kann.
QIP ist eine Feedback Loop, welche durch die selbst auferlegten Ziele gesteuert wird. Im letzten Schritt von QIP wird die gewonnenen Erfahrungen in eine wiederverwendbare Form gebracht und aufbewahrt.
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
Der Fakt, dass CBR und QIP schon damals einer iterativen Funktionsweise zugrunde lagen zeigt, dass ein agiler, iterativer Entwicklungsansatz diese Arten von Prozessen noch viel besser einsetzen und mehr Wert daraus gewinnen kann.
Im Vergleich zum Gebrauch in einem Wasserfallmodell werden die Erfahrungsinkremente bei einem agilen Prozess kleiner und fokussierter sein.

Dies lässt grundsätzlich vermuten, dass der Aufbau und letztendlich auch der laufende Betrieb einer Experience Factory sich gut in den aktuellen agilen Entwicklungsprozess der COMPRA GmbH integrieren lässt.

# Ansätze Erfahrungsmanagement in der Softwareentwicklung
> In diesem Kapitel soll ein Überblick über die verschiedenen Ansätze, welche im Erfahrungsmanagement in der Softwareentwicklung genutzt werden, gegeben werden.
> Außerdem sollten hier die Technicken beschrieben werden, die bisher bei der COMPRA GmbH für das Thema Erfahrungsmanagement verwendet werden.

Bei der COMPRA GmbH werden verschiedene Systeme geführt, welche neben ihrer hauptsächlichen Funktion auch als Repository für Wissens- und Erfahrungsartefakte verwendet werden.
Darunter fallen:
* MS Team Foundation Server:

  Source Control
  Interne sowie externe Kollaborationsplattform zur Planung, Kommunikation und Dokumentation der Softwareentwiclung in allen Teams und Projekten
  Projekt- oder Teambezogene Wikis

* ELO Document Management System

  Interne Dokumente (Personalmanagement, Gehaltsabrechnungen etc.)
  Dokumentation von internen Prozessen und Vorgängen (Sprint Retrospektiven, Protokolle)

* Windows File-Server:

  Ablage von verschiedensten Dateien und Dokumenten
  Installationsdateien
  Projektbezogene Dateien und Dokumente

* ERP System eEvolution und MS SQL Server:

  eEvolution wird intern für die Erstellung von Rechnungen, Dokumentation von Arbeitszeiten, die Verwaltung von Mitarbeitern und Kunden sowie CRM verwendet.


* [eEvolution Wiki](https://wwww.wikierp.de)

* MS Teams:

  Interne und externe Kommunikation und Kollaboration (Chats, Meetings).

* MS Sharepoint:

  Kalender, Dokumentation, Verschiedenes.

* Yammer:

  Internes soziales Netzwerk

* Email und IP-Telefon (Swyxit)




Vergleichen wir die verwendeten Technicken in diesen Systemen mit den von Tautz aufgeführten vorhandenen Ansätzen für Repositories im Erfahrungsmanagement, so wird deutlich, dass eine ganze Reihe bei der COMPRA GmbH im Einsatz sind:

* Controlled / Uncontrolled Keyword System [Tautz001 5.1.4]
* Full Text Search auf vorhandene Repositories [Tautz001 5.1.5]
* Hypertext [Tautz001 5.2]
* Relational and Object-Oriented DBMS [Tautz001 5.3.1 5.3.2]

Im Grund alle vorhandenen Repositories verfügen über die Möglichkeit, über Keywords oder Full Text Search durchsucht zu werden.
Das eEvolution Wiki ist eine Website, verwendet also Hypertext.
eEvolution ist ein ERP System, welches mit einer relationalen Datenbank betrieben werden muss.

Auffallend ist hier, dass nur sehr simple Technicken welche ohne weiteren Aufwand auf den Repositories angewendet werden können. Es gibt kein System, welches Logik oder Wissensbasiert arbeitet.
Dies entspricht der gelebtem Praxis im Unternehmen.







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
[@tautz_2001](D:\Stuff\Unistuff\Bachelor und Projektarbeit\Phd-tautz.pdf)  
Mohameda, A. H., et al. “An Ontology-Based Knowledge Model for Software Experience Management.” International Journal of the Computer, vol. 14, no. 4, 2004, pp. 79–88. eprints.um.edu.my, http://www.ijcim.au.edu/past_editions/2006V14N3/pp6-An%20Ontology-Based%20Knowledge%20Model.pdf.
[An Ontology-Based Knowledge Model for Software Experience Management](https://eprints.um.edu.my/4572)  
[Scrum Guide](https://scrumguides.org/scrum-guide.html)
[The Experience Factory Approach](https://www.researchgate.net/publication/2349230_The_Experience_Factory_Approach_Realizing_Learning_From_Experience_In_Software_Development_Organizations)
[Spotify-Modell](https://agilescrumgroup.de/spotify-modell/)

# Relevante Kapitel aus [Tau001]
T32 LEARN Decomposition: record (T33, page 107), analyze SEEMS (T50, page 116), forget (T54, page 119), package (T55, page 120)
