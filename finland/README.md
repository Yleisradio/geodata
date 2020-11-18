# Finland

All maps are saved in WGS-84 projection and topojson format.

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