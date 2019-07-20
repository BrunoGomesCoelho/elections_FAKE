# Data Analysis of the 2018 Brazilian Election

A small look at the 2018 Brazilian election, joining the electoral zones with graphical information from IBGE.
Not a currently maintained repository, but maybe the code could be usefull to somenone :)

## Data Sources
The address of the various electoral zones were manually acquired as CSV files from [the oficial tse website](http://www.tse.jus.br/eleitor/servicos/cartorios-e-zonas-eleitorais/pesquisa-a-zonas-eleitorais)

The result of the elections for each electoral zone was acquired from the "Presidente (formato ZIP) " file also in [the oficial tse website](http://www.tse.jus.br/hotsites/pesquisas-eleitorais/resultados_anos/votacao/votacao_secao_eleitoral_2018.html)

## Processing
Using [Google's Geolocation API](https://developers.google.com/maps/documentation/geolocation/intro) the numerous address were processed as latitude and longitude.


