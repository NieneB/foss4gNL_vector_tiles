
# Titel
Working with Vector Tiles - baking, making, styling. 

# Docent
Niene Boeijen

# Organisatie
Webmapper

#Beschrijving
Vector Tiles maken web maps snel en het design flexibel! Een nieuw alternatief op de traditionele raster image tiles voor web maps. 

Hoe werken Vector Tiles en hoe kom je er aan? In deze workshop gaan we van begin tot eind kijken naar vector tiles en zelf werken aan het genereren, serveren en stylen. Gebruik de PDOK vector tiles, OSM vector tiles van OpenMapTiles of genereer je eigen tiles van eigen geo-data (PostGIS/GeoPackage). Er zullen voorbeelden zijn voor beginners en gevorderde.

Voor beginners ligt de focus aan de front-end ontwikkeling. We beginnen met een kaart te maken in [Mapbox Studio](https://www.mapbox.com/studio/). Daarna breken we los van de Mapbox access token door zelf een simpele web pagina op te zetten met [MapboxGL.js](https://www.mapbox.com/mapbox-gl-js/api). We gebruiken de [Mapbox Style Specification](https://www.mapbox.com/mapbox-gl-js/style-spec/) om een eigen style.json te bouwen. Enige voor kennis van HTML, CSS en JavaScript is hierbij handig. 

Voor gevorderde zijn er voorbeelden hoe je vanuit PostGIS Vector Tiles kan serveren met [Tegola](https://github.com/go-spatial/tegola). Of OSM Vector Tiles kan serveren met [OpenMapTiles Server](https://openmaptiles.com/server/). Als extra kan je zelf je sprites maken met Inkscape en  [Spritezero](https://github.com/mapbox/spritezero) of je eigen Glyphs met [node-fontnik](https://github.com/mapbox/node-fontnik). De voorbeelden gebruiken Docker of nodejs/npm om de tools te installeren en draaien. 

# Kennis nodig:
Beginners : HTML & JS
Gevorderden: Docker, npm, PostGIS

# Na afloop kan je:
Een eigen kaart creeren in Mapbox studio. 
Een eigen kaart opzetten met MapboxGL.js 
Een style.json bestand maken met de MapboxGL.js style spec. 
Na afloop weet je waar en hoe je vector tiles kan verkrijgen en serveren met bijvoorbeeld Openmaptiles of Tegola.



