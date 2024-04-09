<a href="https://www.juncture-digital.org"><img src="https://juncture-digital.github.io/juncture/static/images/ve-button.png"></a>

<param ve-config 
       title="Indigo Plant Narrative"
       author="Jordan, Hayley, & Gianna"
       banner="https://iiif.juncture-digital.org/banner/?url=https://upload.wikimedia.org/wikipedia/commons/4/47/Bartholomeus_Johannes_van_Hove%2C_Het_Mauritshuis_te_Den_Haag.jpg" 
       layout="vertical">

<!-- Entities discussed throughout the essay are typically defined before the essay text and
     are thus available in all text.  Entity identifiers (QIDs) can be found in either
     Wikipedia or Wikidata (https://www.wikidata.org)> -->
<param ve-entity eid="Q185372"> <!-- Girl with a Pearl Earring painting -->
<param ve-entity eid="Q41264"> <!-- Johannes Vermeer -->
<param ve-entity eid="Q221092"> <!-- Mauritshuis -->
<param ve-entity eid="Q36600"> <!-- The Hague -->

# Indigo Plant Narrative

Vermeer's Girl With a Pearl Earring features faded indigo in the <span data-mouseover-image-zoomto="2301,3670,1536,1242">background</span>. We can just keep this image in here This is a sample visual essay demonstrating a few key features of a Visual Essay. 
<param ve-image 
       manifest="https://iiif.juncture-digital.org/manifest/6dd738aed85597cac540ad31dd5818e86ef7f2918c7b43a9eb3123d5538e6e4c"
       label="Vermeer's Girl With a Pearl Earring" 
       description="the painting."
       license="Public domain">

# Basic usage

## Sample Image 3/11 (jordan)
This early modern illustration comes from the _Revue Horticole_. It features an indigo plant and its <span data-mouseover-image-zoomto="506,1726,963,778
">flowers.</span>
<param ve-image 
       label="Early Modern Indigofera Dosua" 
       description="from the Revue horticole. Paris :Librairie agricole de la maison rustique,1829-1974."
       license="Public domain"
       url="https://biodiversitylibrary.org/pageImage/54768315">


## Image

 This illustration, which is included in _L'art de l'indigotier_ (1770) as a supplement to writings about indigo production, depicts indigo workers <span data-mouseover-image-zoomto="1671,3280,1122,1012">churning indigo leaves.</span>
<param ve-image 
       label="L'art de l'indigotier" 
       description="by Paul de Beauvais-Raseau, illustrations by L.F. Delatour" 
       license="public domain" 
       url="https://www.biodiversitylibrary.org/pageImage/40474136">

## Timeline


<param ve-knightlab-timeline
       source="1Rswjl0FEfisfsg9Mb8gmv0zWzJWwCDc74wSVhYjD_PA"
       timenav-position="bottom"
       hash-bookmark="false”
       initial-zoom=1
       height="750">

## Map

By the 17th century, the British, Spanish, and French established indigo plantations in the Caribbean (or West Indies). <span data-mouseover-map-flyto="19.084327, -73.076567, 8">Haiti (Saint-Domingue)</span> saw particularly prolific indigo production, and networks of knowledge exchange were eventually established between these colonies and others in West Africa, especially <span data-mouseover-map-flyto="14.593509, -14.521971, 7">Senegal</span>.
<param ve-map center="17.620068, -71.562101" zoom="5" Title="The Caribbean" prefer-geojson>
<param ve-map-marker
       url="https://si.regeneratedidentities.org/project/DataFiles/SI-OB-388/388-4.jpg"
       coords="19.057147, -72.527066"
       size="727, 464"
       circle="true">

## India Map
The <span data-mouseover-map-flyto="26.6156, 84.8409, 11">Champaran district of Bihar</span> is where Gandhi began his first efforts of peaceful resistance in India protesting the poor treatment and low pay of indigo workers in 1917.
<param ve-map
       center="26.5833, 84.8333"
       zoom=5
       title="Champaran"
       prefer-geojson>
<param ve-map-layer geojson
       url="https://raw.githubusercontent.com/IndigoGirlH/IndigoNarrative/main/IndiaMap.json"
       show-labels
       stroke-width="0">
<param ve-map-marker
       url="https://upload.wikimedia.org/wikipedia/commons/e/ed/Buddhist_Stupa_at_Kesariya_at_Champaran_%28east%29_district_of_Bihar%2C_India._12.jpg"
       coords="26.5833, 84.8333"
       size="400, 200"
       circle="true">
       
## SC Map
Indigo was a major cash crop in colonial South Carolina, and most of its production was done in the port city of Charleston. Eliza Lucas Pinckney first planted Indigo seed at her Wappoo Hall Plantation in 1741. While Eliza preferred Wappoo Hall, the Pinckney family also owned and cultivated indigo at <span data-mouseover-map-flyto="32.846122, -79.824657, 11">Snee Farm in Charleston, which is now the Charles Pinckney National Historic Site.</span>
<param ve-map
       center="32.818369, -79.929117"
       zoom="11"
       Title="Charleston, South Carolina"
       prefer-geojson>
<param ve-map-layer geojson
       url="https://raw.githubusercontent.com/IndigoGirlH/IndigoNarrative/main/SCgeo.json"
       show-labels
       show-titles
       stroke-width="0">
<param ve-map-marker
       coords="32.846074, -79.824693"
       url="https://upload.wikimedia.org/wikipedia/commons/1/11/Charles_Pinckney_National_Historic_Site_%28de0d374d-090d-46eb-b83a-a106effa97c4%29.jpg"
       size="800, 533"
       circle="true">


## Image
This is a commemorative stamp of the Champaran Satyagraha, the first satyagraha movement led by <span data-mouseover-image-zoomto="256,267,351,274">Mahatma Gandhi</span> in an effort to receive fair pay for indigo farmers.
<param ve-image
       label="Commemorative Stamp"
       description="Stamp commemorating the 100th anniversary of Champaran Satyagraha"
       license="CC BY-SA 4.0"
       url="https://upload.wikimedia.org/wikipedia/commons/3/34/Stamp_of_India_-_2017_-_Colnect_696527_-_Centenary_of_the_Champaran_Indigo_Farmers_Satyagraha.jpeg">
       
## Multiple viewers

Multiple viewers may be defined for a single paragraph of text.  The first viewer defined is displayed as the default viewer.  
Others are selectable using icons displayed in the top right margin of the paragraph.
<param ve-image 
       manifest="https://iiif.juncture-digital.org/manifest/6dd738aed85597cac540ad31dd5818e86ef7f2918c7b43a9eb3123d5538e6e4c">
<param ve-map center="Q36600" zoom="11">

# References

[^1]: [Wikipedia: Girl with a Pearl Earring](https://en.wikipedia.org/wiki/Girl_with_a_Pearl_Earring)
[^2]: [We'll need to convert these to formatted citations later](https://www.biodiversitylibrary.org/pageImage/40474136)
