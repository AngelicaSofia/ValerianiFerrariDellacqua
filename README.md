# SafeStreets - Project Assignment for Software Engineering 2
*Project for the Software Engineering 2 course at Politecnico di Milano (Computer Science Master).*

###### The problem
SafeStreets is a crowd-sourced application that intends to provide users with the possibility to notify authorities when traffic violations occur, and in particular parking violations. The application allows users to send pictures of violations, including their date, time, and position, to authorities. Examples of violations are vehicles parked in the middle of bike lanes or in places reserved for people with disabilities, double parking, and so on.

###### Basic Service:
SafeStreets Stores the information provided by users, completing it with suitable meta-data. In particular, when it receives a picture, it runs an algorithm to read the license plate (one can also think of mechanisms with which the user can help with the recognition), and stores the retreived information with the violation, including also the type of the violation (input by the user) and the name of the street where the violation occurred (which can be retrieved from the geographical position of the violation). In addition, the application allows both end users and authorities to mine the information that has been received, for example by highlighting the streets (or the areas) with the highest frequency of violations, or the vehicles that commit the most violations. Of course, different levels of visibility could be offered to different roles.

###### Advanced function 1:
If the municipality offers a service that allows users to retrieve the information about the accidents that occur on the territory of the municipality, SafeStreets can cross this information with its own data to identify potentially unsafe areas, and suggest possible interventions (e.g. add a barrier between the bike lane and the part of the road for motorized vehicles to prevent unsafe parking).

###### Advanced function 2:
In addition, the municipality (and, in particular, the local police) could offer a service that takes the information about the violations coming from SafeStreets, and generates traffic tickets from it. In this case, mechanism should be put in place to ensure that the chain of custody of the information coming from the users is never broken, and the information is never altered (e.g., if a manipluation occurs at any point of the image showing the violation, for example to alter hte license plate, the application should discard the information). In addition, the information about issued tickets can be used by SafeStreets to build statistics, for example about the most egregious offenders, or the effectiveness of the SafeStreets initiative (e.g., by looking for trends in the issuing of tickets).

###### The documents to be created
1. Requirements Analysis and Specification Document
The Requirement analysis and specification document (RASD) contains the description of the scenarios, the use cases that describe them, and the models describing requirements and specification for the problem under consideration. You are to use a suitable mix of natural language, UML, and Alloy. Any Alloy model should be validated through the tool, by reporting the models obtained by using it and/or by showing the results of assertion checks. Of course, the initial written problem statement we provide suffers from the typical drawbacks of natural language descriptions: it is informal, incomplete, uses different terms for the same concepts, and the like. You may choose to solve the incompleteness and ambiguity as you wish, but be careful to clearly document the choices you make and the corresponding rationale.

2. Design Document
The Design document (DD) must contain a functional description of the system, and any other view you find useful to provide. You should use all the UML diagrams you need to provide and full description of the system. Alloy may also be useful, but not mandatory.

###### The solution
The RASD can be found in the RASD folder. This folder contains a latex folder that has the source files of the RASD.
The DD can be found in the DD folder. This folder contains a latex folder that has the source files of the DD.
DeliveryFolder contains the final version of each document.

###### Evaluation
The project has been evaluated with 29/30. Professor of the course: Matteo Giovanni Rossi and Elisabetta Di Nitto
