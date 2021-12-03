# Verschraling voorzieningen in Nederlandse gemeenten

De afgelopen decennia zijn er veel gemeentelijke voorzieningen verdwenen door bezuinigingen of omdat gemeenten zijn gefuseerd of gesplitst. Denk aan zwembaden, postkantoren, politiebureau's, gemeentehuizen, scholen en bibliotheken. Follow the Money wil deze verschraling van publieke voorzieningen in kaart brengen en een aantal dingen weten:

1. In hoeverre zijn voorzieningen verdwenen in Nederlandse gemeenten? Dus wanneer, wat en waar?
2. In hoeverre is de reistijd van mensen naar deze voorzieningen toe- of afgenomen? En wat zijn de verschillen tussen gebieden? 

Het grote probleem hier is het vinden van goede data. Om te bepalen welke voorzieningen er verdwenen zijn, moet je natuurlijk weten welke voorzieningen er zijn en waren. Dat blijkt haast onmogelijk om na te gaan. De politie is bijvoorbeeld zo vaak gereorganiseerd, dat archieven kwijt zijn en overzichten over waar bureau's gevestigd waren, zijn verdwenen. Eigenlijk zouden we oude telefoonboeken moeten doorzoeken, maar die zijn nog niet gedigitaliseerd.

We hebben voor dit project daarom moeten uitwijken naar een afstandentabel van het CBS. Die doet jaarlijks (2007-20219) metingen over de gemiddelde afstanden die mensen in buurten, wijken en gemeenten moeten afleggen naar een aantal basisvoorzieningen, zoals:
* huisarts
* ziekenhuis
* basisschool
* vmbo
* havo_vwo
* bibliotheek

We op basis van deze data een verhaal kunnen maken (dat kun je [hier lezen](https://www.ftm.nl/artikelen/verschraling-platteland?utm_campaign=Dimitri-Tokmetzis&utm_source=article&utm_medium=link&share=WZHhSkWk%2FaABIchwL8u5OGV9n7PLu6qgLYPhsi06euQAzSvdaCd9KuKBkYIyWWQ%3D)). We zijn nog niet tevreden op de manier waarop we de data hebben gevisualiseerd. Ook al zijn de data beperkt, we zouden hier meer mee moeten kunnen. 

Wat hebben beschikbaar?
1. Een tabel van het CBS met afstanden naar een aantal basisvoorzieningen tussen 2007-2019 per buurt, wijk en gemeente.
2. Shapefiles van wijken, buurten en gemeenten. 

De data van het CBS zijn vrij makkelijk om mee te werken. Shapefiles zijn lastiger, zeker van gemeenten. Een van de problemen is dat je met gemeentelijke herindelingen zit: ieder jaar worden er weer gemeenten gefuseerd of gesplitst. Daar moet je dus rekening mee houden. Daarnaast zijn shapefiles vrij groot en heb je gespecialiseerde software, zoals ArcGIS of het open source QGIS nodig om wat meer geavanceerde analyses te kunnen doen. Er zijn ook andere tools beschikbaar voor analyse en visualisatie, denk aan:
1. Geopandas, een Python library waarmee je makkelijk met data (pandas) en geografische files kunt werken.
2. Diensten als Mapbox, Google Earth (moet je shapefiles eerst omzetten naar KML). Voor web-applicaties heb je meestal geoJSON nodig. 

