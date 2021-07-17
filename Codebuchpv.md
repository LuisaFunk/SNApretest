# Codebuch Pretest lf067 #

Inhalt: Edgelist, Nodelist, Codierung Attribute

    
## Egde-Attribute
**id**
bei Spielerinnen: Nachnamen,
bei Vereinen: Name der Stadt, aus der der Verein kommt; bei Doppelungen zwei weitere Buchstaben hinzufügen (Abkürzung der weiteren Vereinsbezeichnung),
bei Ländern: offizielle Ländercodes (die z.B. von FIFA genutzt werden).

## Node-Attribute

**id**
Identische ID wie aus der edgelist zur Identifikation der Knoten.

**name** vollständiger Name

**type**
1 = person (Spielerin),
2 = organisation (Verein, Land).

folgende Node-Attribute betreffen nur type=1, also die Spielerinnen:

**birth**
Geburtsjahr

**age**
1 = 18 Jahre und jünger,
2 = 19 bis 21 Jahre,
3 = 22 bis 25 Jahre,
4 = 26 bis 28 Jahre,
5 = 29 Jahre und älter.

**position**
Position auf dem Spielfeld
1 = Mittelblock,
2 = Zuspiel,
3 = Außenangriff,
4 = Diagonal,
5 = Libera.

**country**
Heimatland, bzw. Land in dem die Spielerin geboren wurde

##
