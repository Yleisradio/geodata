# Finland

All maps are saved in WGS-84 projection and topojson format. Scale is 1:4.5m.

## finland-regions-2020.topo.json

field | Example value | description
----- | ------------- | -----------
id    |	01            | Official region number (00 format)
name	| Uusimaa       | Name in English
nimi	| Uusimaa       | Name in Finnish
namn	| Nyland        | Name in Swedish

## finland-munis-2020.topo.json

field | Example value | description
----- | ------------- | -----------
id    |	934           | Official municipality number (000 format)
nimi	| Vimpeli       | Name in Finnish
namn	| Vindala       | Name in Swedish, corrected to follow the Institute for the Languages of Finland's recommendations
population  | 2827    | Population in end of 2019
district    |	EP      | ID of hospital district to which the municipality belongs
specialdistrict | TAYS  | ID of the special hospital district


## finland-hospital_districts-2020.topo.json

Combined map with one layer identical to finland-munis, and one layer containing the hospital districts. `districts` layer properties:

field | Example value | description
----- | ------------- | -----------
id	  | L             | Official id
nimi  | Lappi         | Shortened name in Finnish
nimi_long	| Lapin SHP | Full name in Finnish
namn  | Lappland      | Shortened name in Swedish
namn_long	| Lapplands sjukvårdsdistrikt | Full name in Swedish
specialdistrict | OYS | ID of the special district to where the district belongs
population  | 117171  | Total population of the district

## finland-hva-2021.topo.json

Combined map with two layers: `munis` and `hva` (hyvinvointialueet = "wellbeing services counties").

field | Example value | description
----- | ------------- | -----------
id	  | L             | Official municipality id
name_fi  | Vaasa         | Full name in Finnish
name_sv  | Vasa      | Full name in Swedish
hva_id | PO | ID of the HVA to where the municipality belongs
population  | 67551  | Population in december 2020

The `hva` layer also contains the fields `short_name_fi` and `short_name_sv`.