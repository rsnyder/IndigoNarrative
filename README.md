<a href="https://www.juncture-digital.org"><img src="https://juncture-digital.github.io/juncture/static/images/ve-button.png"></a>

<param ve-config 
       title="Girl with a Pearl Earring"
       author="JSTOR Labs team"
       banner="https://iiif.juncture-digital.org/banner/?url=https://upload.wikimedia.org/wikipedia/commons/4/47/Bartholomeus_Johannes_van_Hove%2C_Het_Mauritshuis_te_Den_Haag.jpg" 
       layout="vertical">

<!-- Entities discussed throughout the essay are typically defined before the essay text and
     are thus available in all text.  Entity identifiers (QIDs) can be found in either
     Wikipedia or Wikidata (https://www.wikidata.org)> -->
<param ve-entity eid="Q185372"> <!-- Girl with a Pearl Earring painting -->
<param ve-entity eid="Q41264"> <!-- Johannes Vermeer -->
<param ve-entity eid="Q221092"> <!-- Mauritshuis -->
<param ve-entity eid="Q36600"> <!-- The Hague -->

# Sample visual essay

This is a sample visual essay demonstrating a few key features of a Visual Essay. Additional [Documentation](https://github.com/JSTOR-Labs/juncture/wiki) and [examples](https://jstor-labs.github.io/juncture-examples) are available for reference.
<param ve-image 
       manifest="https://iiif.juncture-digital.org/manifest/6dd738aed85597cac540ad31dd5818e86ef7f2918c7b43a9eb3123d5538e6e4c">

# Basic usage

## Sample Image 3/11 (jordan)
This early modern illustration is a sample coded image from BHL. It features an indigo plant.
<param ve-image 
url="[https://www.flickr.com/photos/biodivlibrary/50506426638/in/photolist-2jX5D2h-2m8jMsj-JhxwRq-2jQWuqk-2jASucw-2imknMR-2jQWu9J-2kEEgHv-2j12Qav-H4PPa7-bAJzui-2jHPGkD-2jiN56L-ae7cxT-2jp8FV2-czRoQb-2kEEhdD-2kEEgR1-bUXJXF-2m3uqyY-2m5Szvf-2krjaF9-2m8zEAP-2jiHCVK-2kEAak4-2kEDGV5-2kEEhg4-2kEEhax-2kEEh1z-2kEDGPU-2kEAao5-2kEEgL1-2k7jxXR-XZrxcd-guTyom-aABpxQ-pz2Uvk-ab9YUz-e3nHza-VVVGkX-2m2WbDp-dP5xkd-Vy5Qyq-aFqrtZ-WJvSuM-eUykAA-dCRbDg-e2q3kU-axbCup-qea9mw/]"
label="Early Modern Indigofera Dosua" 
description="from the Revue horticole. Paris :Librairie agricole de la maison rustique,1829-1974."
license="CC BY-SA 4.0"
fit="contain">

## Image

 This illustration, which is included in _L'art de l'indigotier_ as a supplement to writings about indigo production, depicts indigo workers churning indigo leaves.[^1]
<param ve-image 
       label="L'art de l'indigotier" 
       description="painting by Johannes Vermeer" 
       license="public domain" 
       url="https://www.biodiversitylibrary.org/pageImage/40474136#page/135/mode/1up">

## Map

The work has been in the collection of the Mauritshuis in The Hague since 1902 and has been the subject of various 
literary treatments. In 2006, the Dutch public selected it as the most beautiful painting in the Netherlands.
<param ve-map center="Q36600" zoom="11" prefer-geojson>

## Image
This is a commemorative stamp of the Champaran Satyagraha, the first satyagraha movement led by <span data-mouseover-image-zoomto="824,800,1152,938">Mahatma Gandhi</span> in an effort to receive fair pay for indigo farmers.
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
