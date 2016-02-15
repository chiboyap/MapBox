# SchoolDangers School Incident Data      VERSION:*BETA*
# Files contained in the beta folders are non-production components or example data sets.

WARNING !!!!
Example datasets are static examples of the data structure for our data. 
This means they are NOT current, have not been recently updated, and the data contained is wholly inaccurate.

## Copyright and License
![Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png)
Data, analysis, compiled work, and published work by [School Dangers Organization](https://schooldangers.org/copyright) is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc-sa/4.0/ "Attribution-NonCommercial-ShareAlike 4.0 International ") by the School Dangers Organization (SDO).  

You are free to copy, distribute, transmit and adapt our data for noncommercial purposes, as long as you credit the School Dangers Organization and its contributors. If you alter or build upon our data, you may distribute the result only under the same license. The full legal code explains your rights and responsibilities.

## School Dangers Incident Marker Data
*BETA* map marker data is stored in /beta/data as geoJSON files.

Several *BETA* geoJSON files are provided as examples of data structure and size for incidents and school locations.  These files are not intended for production. For example, our geoJSON file of 100,000+ schools is 42MB and early testing has shown people fall asleep or speak crudely to their computers as the file downloads and javascript draws the markers. 

The primary geoJSON file is incidents.geojson.  
As we get closer to version 1.0, it is our intention that the live version of the file be published from our online database nightly and accessed using an api key so we can build some awesome statistics.


### GeoJSON structure for School Dangers Map Features (Incidents): ###
----------
	Incident Markers
		var geojson = [
		  {
		    "type": "Feature",
		    "geometry": {
		      "type": "Point",
		      "coordinates": [-77.03238901390978,38.913188059745586]
		    },
		    "properties": {
		      "title": "Name of School Incident Occurred",
		      "description": "Summary of the incident",
		      "marker-color": "#fc4353",
		      "marker-size": "small",
		      "marker-symbol": "marker",
		      "incident-date": "5\/18\/1978 0:00", 
		      "Year": 1978, 
		      "incident-type": "Shooting", 
		      "casualties": 1, 
		      "injuries": 0,
		      “city”: “City”,
		      “state”: “ST”,
		      “facility-type”: “K-12”,
		      "facility-subtype": "Secondary", 
		      "perpetrator": "persons name",
		      "perpetrator-fate": "Arrested",
		      "foiled": "Yes", 
		      "included-in-2002-report": “true/false”
		    }
		  }
		];

## Warranty
This software is provided by the copyright holders and contributors "as is" and any express or implied warranties, including, but not limited to, the implied warranties of merchantability and fitness for a particular purpose are disclaimed. In no event shall the copyright owner or contributors be liable for any direct, indirect, incidental, special, exemplary, or consequential damages (including, but not limited to, procurement of substitute goods or services; loss of use, data, or profits; or business interruption) however caused and on any theory of liability, whether in contract, strict liability, or tort (including negligence or otherwise) arising in any way out of the use of this software, even if advised of the possibility of such damage. 
