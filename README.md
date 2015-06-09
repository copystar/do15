# OLITA Digital Odyssey 2015: Consuming and Transforming Open Data - a hands-on tutorial
  
## Who are you?
I'm Mita Williams. I'm the UX librarian from the University of Windsor.  

## Where am I?
Good question. If I gave you directions here, I would tell you we are at 51 Dockside Dr, Toronto, ON M5A 1B6.  
  
But if I wanted to describe the location for a map, I might describe the same location using latitude and longitude:  
43° 38' 39.2706", -79° 21' 55.4508"  
You would read the above as "43 degrees, 38 minutes and 39.2706 seconds".
  
Its confusing to describe a place using minutes and seconds so let's describe the same place using longitude and longitude but using decimal degrees instead of minutes and seconds.  
43.644242, -79.365403  
  
## What if I wanted to tell people where the 100 library branches the TPL are in the city? 
You could make a map using Google Maps of all the TPL Library branches: http://www.torontopubliclibrary.ca/hours-locations/  

## How could I make this map?
First you will need the locations of all the branches of the Toronto Public Library. These are provided by the City of Toronto from their Open Data Catalogue at: http://www1.toronto.ca/wps/portal/contentonly?vgnextoid=a7ae0ea14b661310VgnVCM1000003dd60f89RCRD&vgnextchannel=1a66e03bb8d1e310VgnVCM10000071d60f89RCRD  
  
Please note that the data in the catalogue is out of date. The site provides the location of Library Branch Locations (http://www.torontopubliclibrary.ca/data/library-data.kml) and Future Library Branch Locations (http://www.torontopubliclibrary.ca/data/new-library-data.kml) but all the future branches have now opened.  

I have already combined these files together into a new file called:  
https://github.com/copystar/do15/blob/master/combined-library-data.kml 
  
It's also available on drive at: 
https://drive.google.com/open?id=0B5RDRo0uB7m5SWFEbkVWSmdvdHc&authuser=0  

These location files are in .kml which is a notation for XML that first made popular by Google Earth before becoming standardized. Google Mapping Products happily use kml files.  

## Task 1: Make a Google Map using the kml file provided
If you get stuck, please put a post-it note on your laptop
  
