Codebuch

Erhoben wurden die Transfere der Spieler der VFB und deren Nationalität als auch wie viel Geld sie der VFB gekostet haben.

Daten Quelle:https://www.transfermarkt.de/vfb-stuttgart/startseite/verein/79 

#Edgelist

from,to,weight,season

from= Verein aus dem Spieler kommen
to= Spieler (mit Rückennummer angegeben)
weight= Transfersummer/Geld das für Spieler ausgegeben wurde (in 100.000er Schritten)
season= Jahr in dem Transfer stattgefunden hat

um Nationalität anzuzeigen:
from= Spieler (mit Rückennummer angegeben)
to= Nationalität/ erste Nationalität
weight= zweite Nationalität

Nodelist

Type 1: id,name,country,type

id=Spieler (mit Rückennummer angegeben)
name= Name des Spielers
country=Nationalität/ erste Nationalität
type= 1 --> bedeutet, dass es um die Spieler geht

um zweite Nationalität anzuzeigen 

id= zweite Nationalität 

Type 2: id,name,country,type

id= Verein
name= Vereinsname
country= Land des Vereins
type= 2--> bedeutet, dass es um den Verein geht
