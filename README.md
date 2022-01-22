# Tree project
Tree project for investigation of trees around Paris region. 

## Research questions
Dataset on trees contains important information about the current trees positions and types of trees. 
It also allows to go backwards in time looking at which trees actually existed before and which were planted later. 
Simple visualisation shows and highlights areas of the urban forest in Paris 
with the oldest (trees which have larger trunk diameter). 

Inspired and started by students from Master Data Science course 2020 at CRI, continued in 2021/2022. Dana started the notebook, Liubov has started to look at the data. Liubov and Marc leading the course.


# Data 
The project is based on the data https://data.iledefrance.fr/explore/dataset/les-arbres/table/?disjunctive.typeemplacement&disjunctive.arrondissement&disjunctive.libellefrancais&disjunctive.genre&disjunctive.espece&disjunctive.varieteoucultivar&disjunctive.stadedeveloppement&disjunctive.remarquable

Additional dataset can be found in https://www.data.gouv.fr/fr/datasets/arbres-en-open-data-en-france-par-namr/

Additional data collection resource at https://umap.openstreetmap.fr/en/map/open-trees-memories-map_567217 

Metadata: DOMANIALITE, ARRONDISSEMENT, COMPLEMENT ADRESSE, NUMERO, LIEU / ADRES

### Ispirational links 
Other projects working on this https://capgeo.maps.arcgis.com/apps/instant/media/index.html?appid=07f20d39ae48498dafcba7ccb86a2cca


# Methods 
We use network methods and general statistics for tree data analysis. 
The main types of algorithms applied here are: 
1. algorithm for construction of geometric graph out of N points in locations of trees 
2. algorithm for construction of happy green walks in cities


