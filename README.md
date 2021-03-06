# SchoolDangers-MapBox      VERSION:*BETA*
This repository is intended to help developers visualize School Dangers Org's school incident and school location data using the MapBox.com service.  This work will also be used by School Dangers Org's public website.

The current version is *BETA*, meaning we have a framework and some reasonably accurate data, but it is not *copy-and-paste* ready for production and public dissemination.  

## Copyright and License
![Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png)
Data, analysis, compiled work, and published work by [School Dangers Organization](https://schooldangers.org/copyright) is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc-sa/4.0/ "Attribution-NonCommercial-ShareAlike 4.0 International ") by the School Dangers Organization (SDO).  

You are free to copy, distribute, transmit and adapt our data for noncommercial purposes, as long as you credit the School Dangers Organization and its contributors. If you alter or build upon our data, you may distribute the result only under the same license. The full legal code explains your rights and responsibilities.

## Warranty
This software is provided by the copyright holders and contributors "as is" and any express or implied warranties, including, but not limited to, the implied warranties of merchantability and fitness for a particular purpose are disclaimed. In no event shall the copyright owner or contributors be liable for any direct, indirect, incidental, special, exemplary, or consequential damages (including, but not limited to, procurement of substitute goods or services; loss of use, data, or profits; or business interruption) however caused and on any theory of liability, whether in contract, strict liability, or tort (including negligence or otherwise) arising in any way out of the use of this software, even if advised of the possibility of such damage. 

## School Dangers Baselayers
School Dangers baselayers (custom styled map backgrounds aka tiles) will be listed here in the future.  For now we are using *mapbox.streets*, but plan to release a less cluttered background map to help viewers focus on schools and school incidents.

## School Dangers Incident Marker Data
*BETA* map marker data is stored in /beta/data as geoJSON files.

Several *BETA* geoJSON files are provided as examples of data structure and size for incidents and school locations.  These files are not intended for production. For example, our geoJSON file of 100,000+ schools is 42MB and early testing has shown people fall asleep or speak crudely to their computers as the file downloads and javascript draws the markers. 

The primary geoJSON file is incidents.geojson.  
As we get closer to version 1.0, it is our intention that the live version of the file be published from our online database nightly and accessed using an api key so we can build some awesome statistics.
