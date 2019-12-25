# BerlinTrafficCounts

## Übersicht aller Zählungen in Tabelle
https://vizsim.github.io/BerlinTrafficCounts/index.html  
	- filter table to get the street you are interested  
	- get raw data/"Rohdaten"  
	- view raw data in chart for cars and bikes  

	
## Beispielauswertungen Radverkehr  
### Veränderung des Radverkehrsanteil je PLZ
* mit Klick auf PLZ können einzelne Zählungen nachvollzogen werden  
https://vizsim.github.io/BerlinTrafficCounts/map_change_cycling_share_berlin_jsonChart_onClick.html


### Veränderung des Radverkehrsanteil je PLZ (inkl. Tagesgang von Radverkehr)
https://vizsim.github.io/BerlinTrafficCounts/map_change_cycling_share_berlin_jsonChart_onClick_tagesgang.html  

## Skripte  
* 1_metadata2table: erstellt die Übersichtstabelle
* 2_berlin_vzaehlung_parser: parsed die Einzelfiles (zumindest 17.000 davon) in eine große csv (Rohdaten_Berlin_1992-2019_zda.csv)
* 3_berlin_vzaehlung_plotter: erstellt die Beispielauswertungen Radverkehr
	
	
## andere Beispielauswertungen Radverkehr  

### Kottbusser Damm / Hermannplatz:  
![](https://vizsim.github.io/BerlinTrafficCounts/auswertungen/Auswertung_kottbusserDamm.PNG)  
### Oberbaumbrücke:  
![](https://vizsim.github.io/BerlinTrafficCounts/auswertungen/Auswertung_oberbaum.PNG)  
### Oranienstraße:  
![](https://vizsim.github.io/BerlinTrafficCounts/auswertungen/Auswertung_oranienstrasse.PNG)  
### Frankfurter Tor:  
![](https://vizsim.github.io/BerlinTrafficCounts/auswertungen/Auswertung_frankfurterTor.PNG)  
### Schönhauser Allee:  
![](https://vizsim.github.io/BerlinTrafficCounts/auswertungen/Auswertung_schoenhauser.PNG)  
### Am Görlitzer Bahnhof:    
![](https://vizsim.github.io/BerlinTrafficCounts/auswertungen/Auswertung_goerli.PNG)  
### Hermannstraße / Flughafenstraße:  
![](https://vizsim.github.io/BerlinTrafficCounts/auswertungen/Auswertung_hermannFlug.PNG)  
### Unter den Linden / Wilhelmstraße:  
![](https://vizsim.github.io/BerlinTrafficCounts/auswertungen/Auswertung_linden.PNG)  
### Mehringdamm:  
![](https://vizsim.github.io/BerlinTrafficCounts/auswertungen/Auswertung_mehring.PNG)  
### Späthbrücke (Neukölln/Treptow):  
![](https://vizsim.github.io/BerlinTrafficCounts/auswertungen/Auswertung_spaethbr.PNG)  
### Wildenbruchstraße:  
![](https://vizsim.github.io/BerlinTrafficCounts/auswertungen/Auswertung_wildenbruch.PNG)  



## PKW-Zählungen auf Karte (Geocode leider nicht zuverlässig genug)
https://vizsim.github.io/BerlinTrafficCounts/out_circles_col_size_hyperlink_vega_modified.html  

Vizualisation of a snippet of (~500 counts out of 20,000) from the official traffic counts data since 1980ies which is quite messy and also sometimes inaccurate. It was originally not meant to be published.

disclaimer:
- geocoding worked not for all points well




## Datenquelle:
Verkehrslenkung Berlin / Rohdaten Verkehrszählungen  
license: CC BY-SA 3.0 DE, https://creativecommons.org/licenses/by/3.0/de  

https://fragdenstaat.de/anfrage/kfz-verkehrszahldaten-aus-berlin/

