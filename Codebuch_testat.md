# Datensatz Semesterverbund CRPR2 #
Codebuch Testat 
erstellt von Berenice Fengler

## Inhalt
- Edges.csv (Edgelist)
- Nodes.csv (Nodelist)
- Codebuch.md (Codierung der Datensätze)

## Ursprung und Datenerhebung
Ich habe den Datensatz über die Wikipediaeinträge, die Abgeordnetenwatch- und die Bundestagsseiten der Politiker*innen erhoben. 

Das Netzwerk ist ein *gerichtetes two-mode Netzwerk*. 


# EDGE-Attribute

**id**  
eindeutige Identifikation jedes einzelnen Knotens (vertex), der erfasst wird, selbst ernannte Abkürzungen

**from**  
definiert den Sender in gerichteten Netzwerken. Entspricht ID in der Nodelist. 

**to**
definiert den Empfänger in ungerichteten Netzwerken. Entspricht ID in der Nodelist. 

**relationship**  
definiert Verbindungen zwischen Politiker*innen und dem Organisationen, codiert nach:   
1 = Ministerium 
2 = politische Funktion (in Gremien, der Partei)
3 = Mitgliedschaften in NGOs, Stiftungen, Gedenkstätten
4 = Beteiligung an Unternehmen
5 = Stipendien
6 = Berufstätigkeiten
7 = Studien- und längere Aufenthalte im In- und Ausland

**year**  
das Jahr der Verbindung

# NODE-Attribute  
  
**id**  
eindeutige Identifikation jedes einzelnen Knotens (vertex), der erfasst wird - identisch mit den IDs der Edge-List

**short_name**
Nachname des_der Politiker_in 

**name** 
Vollständiger Name  des_der Politiker_in 

**sex**    
Geschlecht, numerische Ausprägung/Codierung: 
1 = female
2 = male
  
**education***    
höchster Bildungsabschluss, numerische Ausprägung/Codierung: 
1 = Diplom
2 = Promotion
3 = Staatsexamen
4 = Magister

**position**   
jetzige Position, Codierung: 
1 = Staatssekretär_in
2 = Minister_in

**subject**    
Fachrichtung bei Studium/Promotion, Codierung: 
1= Politik
2 = Rechtswissenschaften
3 = Soziales
4 = Wirtschaft
  
**party**    
Parteizugehörigkeit, Codierung: 
gruene = Bündnis 90/Grüne
fdp = FDP
spd = SPD 
  
**religion**    
Religion, Codierung:
1 = evangelisch
2 = römisch-katholisch   

**kids**  
Anzahl der Kinder  

**twitter**  
Anzahl der Twitter-Follower

**facebook**  
Anzahl der Facebook-Follower

**youtube**  
Anzahl der Youtube-Abonnenten

**instagram**  
Anzahl der Instagram-Follower

**type**  
Art des Knoten, Codierung: 
0 = Person
1 = Organisation

##
