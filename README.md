# GWSW_Queries

**SPARQL queries op het GWSW endpoint**

Dit repository bevat SPARQL queries die gebruikt worden door GWSW Apps, de standaardapplicaties op de GWSW Server.
Zie ook https://apps.gwsw.nl 

De queries leveren gegevenstabellen voor allerlei toepassingen. Ze zijn onderverdeeld in de volgende mappen:
* **Apps** Queries in gebruik door GWSW Apps (Status, Nulmeting, HydX-export)
* **Geo** Geografische uitwisseling (WFS/GML, GeoPackage, CityGML)
* **Model** Overzichten met de inhoud van het GWSW Datamodel

De queries zijn direct bruikbaar op het SPARQL endpoint https://sparql.gwsw.nl .
Vaak dienen dan nog wel variabelen ingevuld te worden:
* **{{&version}}** De URL van het betreffende GWSW Datamodel, bijvoorbeeld: http://data.gwsw.nl/1.5/totaal/

