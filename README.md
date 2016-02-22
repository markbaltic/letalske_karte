# letalske_karte
Primerjava letalskih kart (projekt pri programiranju 1)

Pri porojektu sem primerjal cene letalskih kart, ki jih ponujata Ryanair in Volotea, za let Benetke - Krf in nazaj. Predpostavil sem, da bo letenje z Ryanair-om ceneje, a izkaže se, da je najboljša opcija, če za let Benetke - Krf kupim karto pri Ryanair-u, Krf - Benetke pa pri Voloteji. Spodaj prilagam opis datotek, ki jih ta repozitorij vsebuje.

Seznam datotek:
  Datoteka letalske_karte.ipynb je predstavitev celotnega projekta. Paziti je treba, kam se shrani datoteke, saj na začetku mora   prebrati csv datoteke iz mape na računalniku (je potrebno napisat ustrezno pot).
  
  ryanair_api.py in volotea_api.py naloži podatke iz spletnih strani letalskih ponudnikov.
  
  zapis_csv.py zažene "modula" ryanair_api in volotea_api ter z njuno pomočjo zapiše podatke letov v csv datoteke, ki jih          poimenuje ryanair_datum.csv, ryanair_return_datum.csv in podobno za voloteo (datum je datum, ko program naloži podatke).
  
  ryanair_2016-02-17.csv in ostale csv datoteke vsebujejo podatke, ki sem jih naložil dne 17. februarja 2016.

