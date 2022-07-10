---
title: Application Programming Interface
status: Feedback erwünscht
category: Technologie
---

## Was es ist

Software Anwendungen nutzen APIs um miteinander zu kommunizieren.
Man kann das mit einem Gespräch zwischen zwei Personen vergleichen.
In diesem Beispiel wären die Personen zwei Software Anwendungen und die API die Sprache die zur Kommunikation genutzt wird.
Im Gegensatz zu einem Gespräch zwischen zwei Personen ist eine API jedoch beschränkt.
Informationen können nur über vorbestimmte Endpunkte ausgetauscht werden.

## Welches Problem es löst

Software Anwendungen können mit der Zeit sehr komplex werden.
Dadurch können bereits kleine Code-Änderungen zu komplexen Nebeneffekten führen.



Software Applikationen und Computer System können mit der Zeit sehr komplex werden.
Dadurch können bereits kleine Code-Änderungen in einer Applikationen zu umfangreichen Nebeneffekten führen.
Eine andere Applikation müsste daher den Kontext dieser Nebeneffekte verstehen um effektiv zu kommunizieren.
Das ist in der Praxis jedoch sehr schwer.
Es ist oft nötig Applikationen in kleinere Software Module runterzubrechen um die [Skalierbarkeit](/scalability/) von großen Software Systemen zu ermöglichen.
Das erschwert die Kommunikation zwischen Software Modulen und Applikationen erheblich.
APIs lösen dieses Kommunikationsproblem in dem sie einen festen Vertrag zwischen den kommunizierenden Parteien etablieren.

As applications become more complex, small code changes can have drastic effects on other functionality. Applications need to take a modular approach to their functionality if they can grow and maintain stability simultaneously. Without APIs, there is a lack of a framework for the interaction between applications. Without a shared framework, it is challenging for applications to [scale](/scalability/) and integrate.

## Wie es das Problem löst

APIs moderieren den Austausch von Informationen zwischen Computer Systemen in dem sie feste Kommunikationsendpunkte (Endpoints) festlegen.
Sie sind ein wichtiger Bestandteil von modernen Software Anwendungen und stellen die nötige Transparenz zur Verfügung, die bei der Interaktion zwischen unterschiedlicher Software Anwendungen benötigt wird.
 


APIs allow computer programs or applications to interact and share information in a defined and understandable manner. They are the building blocks for modern applications and they provide developers with a way to integrate applications together. Whenever you hear about [microservices](/microservices/) working together, you can infer that they interact via an API. 
