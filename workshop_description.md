
# Titel
Vector Tiles - making, baking, styling

# Docent
Niene Boeijen

# Organisatie
Webmapper

# Beschrijving

Vector tile technologie is een nieuw alternatief op de traditionele raster image tiles voor web maps. Zij maken web maps sneller te publiceren en flexibeler vorm te geven. 

Hoe werken vector tiles en hoe kom je er aan? In deze workshop maken we zelf een web map op basis van vector tiles. We gebruiken vector tiles van PDOK en OpenMapTiles en maken vector tiles van eigen geo-data (PostGIS/GeoPackage). Er zijn voorbeelden voor beginners en gevorderden.

Voor beginners ligt de focus op de front-end ontwikkeling. We maken een kaart te maken met [Mapbox Studio](https://www.mapbox.com/studio/). Daarna zetten we zelf een eenvoudige web-pagina met een kaart-viewer op te zetten met [MapboxGL.js](https://www.mapbox.com/mapbox-gl-js/api). We gebruiken de [Mapbox Style Specification](https://www.mapbox.com/mapbox-gl-js/style-spec/) om een eigen cartografische vormgeving te specificeren. De vector tiles komen van [PDOK](https://github.com/PDOK/vectortiles-bgt-brt). Enige voorkennis van HTML, CSS en JavaScript is hierbij handig.

Voor gevorderden zijn er voorbeelden om vanuit PostGIS je eigen data te serveren als vector tiles met [Tegola](https://github.com/go-spatial/tegola) of [T-rex](https://github.com/t-rex-tileserver/t-rex) en om OpenStreetMap data te serveren met [OpenMapTiles Server](https://openmaptiles.com/server/). Als extra kan je de cartografische vormgeving verder uitwerken door zelf iconen te maken en eigen lettertypes te gebruiken. Deze voorbeelden gebruiken Docker of NodeJS/NPM om de tools te installeren en draaien.

# Kennis nodig:

* Beginners : HTML, CSS & JS
* Gevorderden: Docker, NodeJS/NPM, PostGIS

# Na afloop kan je:

* Een vector tile web map vormgeven
* Een kaart-viewer voor vector tiles opzetten
* Openbare vector tiles vormgeven en tonen
* Eigen vector tiles maken en publiseren
