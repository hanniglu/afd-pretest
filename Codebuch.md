# Codebuch: Verbindungen der AFD zu rechten Vereinigungen #


## Ursprung und Erhebung

Unser Datensatz beinhaltet die AfD-Abgeordneten des Landtags Baden-Württemberg. Die weiteren Informationen stammen aus Web-Recherchen und sind meist aus Zeitungen, Blogs oder Berichten des Verfassungsschutzes, sowie den Social-Media-Profilen und Websites der Abgeordneten. Da die Quellen teilweise nicht zu 100% überprüfbar sind, versuchen wir möglichst mehrere Quellen für einen Fakt zu suchen, sodenn die erste Quelle nicht ein eigener Kanal der Person oder ein Qualitätsmedium ist.

Das Netzwerk ist ein *ungerichtetes two-mode Netzwerk*.

Dabei untersuchen wir die als rechtsextremistisch eingestuften Vereinigungen Junge Alternative, Flügel (und die Erfurter Resolution), Querdenken und Christen in der AfD und ihre Verbindung zur Partei Alternative für Deutschland und ihren Kandidat*innen für die Landtagswahl 2021 in Baden-Württemberg.

Wir unterscheiden zwischen drei Arten von Akteuren (Vereinigung, Partei, Privatperson) und drei verschiedenen Beziehungsarten zwischen den Akteuren (Mitglied, Sympathisant, Anhänger).


## EDGE-Attribute ##


**id**

(eindeutige Kodierung des Knoten)

Codiert von 1 bis …, jede ID entspricht einem Akteur 


**relation**

Beziehungsart zwischen den Akteuren

1= Mitglied 

2= Anhänger (meist bei aufgelösten Vereinigungen wie dem Flügel)

3= Sympathisant (Akteur äußert sich positiv über Vereinigung)


**years** 

Dauer der Beziehung bis 2021



## NODE-Attribute ##


**id**

Identische ID wie aus der edgelist zur Identifikation der Knoten. 


**vorname**

Vorname des Akteurs (bei realer Person)


**name**

Nachname oder Name der Vereinigung


**type** 

Art des Akteurs


1= Vereinigung

2= Privatperson


**sex**

1= männlich

2= weiblich

3= divers


**year**

Geburts-/ Gründungsjahr


**region**

Nach Wahlkreisen 1-70, genaue Benennung folgt später


**statement** 

Rechte Äußerungen in sozialen Medien oder bei Reden

1= ja

2= nein


**protest** 

Teilnahme an als rechts eingestuften Demonstrationen

1=ja

2=nein
