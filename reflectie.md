# Status 
### Waar staan we globaal?
- We zijn klaar met het maken van dimensies tabellen en waren bezig met het verbinden van de dimensies met het feit tabel
- De dimtabellen werden gemaakt in spark-warehouse folder
- De verbinding luktte voor 3 dimensies "DimCustomer,DimSlot, DimDate" maar voor de DimWeer nog niet!

### Wat loopt goed en minder goed ?
* Het maken van dimensies was goed gegaan 
* We hadden het moeilijk om DimWeer te maken en verbinden met de fact tabel wegens het lezen van JSON file en Zo soort ding hebben we nog nooit gezien!
* 

### Hoe verloop de samenwerking 
* De samenwerking was goed gegaan in het algemeen. We hebben goed met elkaar kunnen communiceren en elkaar helpen. 

### Progress per deel
* 65% 

### Vragen 
* Hoe kunnen we de JSON file van de DimWeer lezen?
* Hoe kunnen we de data halen van een JSON file?
* Moeten we incremantal maken voor de Fact tabel Als de Customer tabel?
****************************
# Na het eerste gesprek "07/10/2024"
### Feedback 
* Het maken van een refelctie.md file. 
* Taal aanpassen van de weer.csv file "Taal moet in een taal zijn Zowel Engels of Nederlands"
* Verwerk de namen van Spark-wearhouse folders om de dimensies tabels en fact tabel duidelijker te maken.
* SCD start en end maken voor de customer dimensie. 
* Incremental maken voor dimCustomer.
* De Incremantal moet ook geladen worden in het feit tabel.
* monotonically_increasing_id() toepassen ipv uuid() in dimCustomer
* De fact tabel moet alleen maar meetwaarden, sleutel en FK'S die verwijzen naar dimensies 