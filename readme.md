### A Day in Heliopolis Markdown Document

This map is my first ever interactive web map! This map is a personal intinerary I would recommend anyone visiting Heliopolis to try. It provides a skelital framework for a suggested route but the itinerary can be flexible. Egypt is comnstantly growing and changing to fit the demands of its massive population, so there is always opportunity to explore! 

##### This is the code I used and how I collected my data:
- Leaflet library
- HTML, CSS, JavaScript
- Turf.js library
- The route I got from Google Maps. I loaded the geographic data (coordinates) into GeoJson.io and managed the data from that point on. 
- The basemap I downloaded from https://leaflet-extras.github.io/leaflet-providers/preview/ 

#### Major Functions

I added color to the start and end points to allow the viewer to easily interpret my intened route. Using Turf I calculated the distance in feet between points so that the reader will be able to estimate time for travel. I added short descriptions in JS under each stop so that the reader will have more information about each place they are visiting. I added two text boxes to provide historic and personal infomation about Heliopolis. I added a link to a helpful travel website I saw and wanted to cite. The basemap I chose feels very appropiriate to the reality of the dusty atmosphere in Heliopolis. 