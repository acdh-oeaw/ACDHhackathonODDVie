# ACDH virtual Open Data hackathon series 2019: Open Data Day Vienna hack
The repo containing your task for the second hackathon in the ACDH hackathon series 2019: Open Data Day Vienna hack. This task is open for submissions from Feb 11, 2019 (2 p.m. CET) to Feb 28, 2019 (midnight CET). 

## Your task

The second hack of the ACDH virtual hackathon series focuses on Open Government Data provided by the City of Vienna. In this hack, your task is to develop a creative mode of processing cartographical data. It is your decision what to do with the data: You could enrich it, automatically vectorize it or develop an innovative application to explore it. 

The data to be worked on in this task are cartographic data showing war damage to buildings in Vienna, obviously compiled by the City of Vienna in 1946. 

The data are described here:
https://www.data.gv.at/katalog/dataset/87282445-a02d-4f7f-9bf6-196d73d9b3a9

Actual map data are provided by a WMS service. You can access them using any GIS software by adding a WMS layer and providing a GetCapabilities URL (https://data.wien.gv.at/daten/wms?service=WMS&request=GetCapabilities&version=1.1.1). The layer providing the war damage map has an ID *BOMBENSCHADENOGD* and a label *Kriegsschäden um 1946*. Be aware that the same WMS service provides over 200 layers ranging from a historical map from 1904 to up-to-date public toilet locations. If you want to embed the data on a webpage, all major map libraries support WMS layers ([Leaflet doc](https://leafletjs.com/examples/wms/wms.html), [OpenLayers doc](https://openlayers.org/en/latest/examples/wms-tiled.html)).

## What your submission should contain

Each submission has to include code, an instruction on how to run it (readme), a short presentation of what was done (in a format of your choice: poster, video, description,...), enriched data (if applicable) and statistics on the data (if applicable).

## Judgement criteria

Your submission will be judged by the following criteria:
* Creativity, innovation  (e.g. Is the approach/idea new and unique? Does it do something that hasn’t been done before? Does it provide new insights into the data? Does the hack provide a new/faster/clearer solution to the old problem?)
* Accessibility, reusability, reproducibility (e.g. Is the code properly documented? Is the technical approach reproducible?)
* Elegance (e.g. Is the code easy to modify and reuse? Is it readable for others? Is modularity considered in the design? Is the code simple and concise?)

## Openness

Participants will work on their solutions in a dedicated (own) GitHub repository. Once you have finished your work, set your repo to public, tag it #ACDHhackathonODDVie and send the repo link to vanessa.hannesschlaeger[at]oeaw.ac.at and tanja.wissik[at]oeaw.ac.at.

All code submitted by all participants (as well as all reviews by all judges) shall be made permanently publicly available on GitHub under an MIT license (or similarly permissive license, respectively a fitting open license for submissions of enriched data and presentation material). By submitting their code to this challange, participants agree to these terms.
