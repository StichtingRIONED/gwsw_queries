# gwsw_queries

**SPARQL queries op het GWSW Endpoint**

Dit repository bevat de SPARQL-queries voor algemene toepassingen van het GWSW. 
Grotendeels worden deze queries gebruikt door GWSW Apps, de standaard-applicaties op de GWSW Server.
Zie ook https://apps.gwsw.nl 

De queries leveren gegevenstabellen voor allerlei toepassingen. Ze zijn onderverdeeld in de volgende mappen:
* **Apps** Diverse toepassingen van GWSW Apps (Status, Nulmeting, HydX-export)
* **Geo** Geografische uitwisseling (WFS/GML, GeoPackage, CityGML)
* **Model** Overzichten met de inhoud van het GWSW Datamodel

De queries zijn direct bruikbaar op het SPARQL endpoint https://sparql.gwsw.nl .
Vaak dienen dan nog wel variabelen ingevuld te worden:
* **{{&version}}** De URL van het betreffende GWSW Datamodel, bijvoorbeeld: http://data.gwsw.nl/1.5/totaal/

