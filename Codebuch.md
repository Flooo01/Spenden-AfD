CODEBUCH	
	
Quelle: Drucksache 19/28000  https://dserver.bundestag.de/btd/19/280/1928000.pdf	
	
Wert	Kommentar
	
edgelist	Grundregel: Die Edgelist darf pro Spalte immer nur einen Wert enthalten
from	definiert den Sender der Spende
to 	definiert den Empfänger der Spende 
donation	Höhe der Spende, gerundet und geteilt durch 10000
weight	Kleinspende=1, Großspende=2, Erbnachlass=3, Gesamtspenden Jahr XX=4
year	Jahr der Spende
	
nodelist	Grundregel: die IDs der Nodelist müssen mit den IDs der Edgelist komplett übereinstimmen
id	eindeutige Identifikation jedes einzelnen Knotens, der erfasst wird
name	Name oder Bezeichnung des Knotens
state	Bundesland des Spenders
zip code	Registrierte Postleitzahl des Spenders
town	Registrierter Wohnort des Spenders
type	Art des Spenders, also natürliche Person (n) oder juristische Person (j); ggf. Spendenjahr (y)
member	Mitglied der AfD zur Zeit der Spende: ja (j) oder nein (n)?
mandate	Mandatsträger der AfD zur Zeit der Spende: ja (j) oder nein (n)?
gender	Geschlecht des Spenders (Mann=m, Frau=f, Divers=d)
alter	Alter des Spenders zum Zeitpunkt der Spende: 20-39 Jahre= y(oung), 40-59 Jahre=m(iddle), 60+=o(ld)
doctorade	Promotion: ja (j) oder nein (n)
	
NA	definiert fehlende Werte
