# Task 1.3 - navigating around large files

The past exercises we just did were using quite small amounts of text. In the real world we'll probably be handling files with much text in it. So lets learn how to navigate around a little quicker with large text files.

Task:
[ ] Change the first word in the text file with the very last word in there file.
[ ] Add this text to the end of line 77  "I KNOW HOW TO JUMP TO LINES NOW!"
[ ] For the line that is 10 below the first line change it say "Vim vim for meeee".

---------------------------------------
Hints:
make sure you've setup linenumbers in your .vimrc
combine combinations of movement: ie: 10 + w || 10 h
jump to line: `:` + <LINE_NUMBER>
go to start: gg
go to end: G
---------------------------------------

Hello! This is the very first line to tart counting from.

The Resource Timing interfaces enable retrieving and analyzing detailed network timing data regarding the loading of an application's resource(s). An application can use the timing metrics to determine, for example, the length of time it takes to load a specific resource, such as an XMLHttpRequest, <SVG>, image, or script.

The interface's properties create a resource loading timeline with high-resolution timestamps for network events such as redirect start and end times, DNS lookup start and end times, request start, response start and end times, etc. The interface also includes other properties that provide data about the size of the fetched resource as well as the type of resource that initiated the fetch.

This document provides an overview of the Resource Timing interfaces. For more details about the interfaces including examples see each interface's reference page, Using the Resource Timing API, and the references in the See also section. For a graphical representation of the resource timing processing model see the resource timing phases figure.

<!DOCTYPE html>
<html>
  <head>
    <title>Localizing the Map</title>
    <meta name="viewport" content="initial-scale=1.0, user-scalable=no">
    <meta charset="utf-8">
    <style>
      /* Always set the map height explicitly to define the size of the div
       * element that contains the map. */
      #map {
        height: 100%;
      }
      /* Optional: Makes the sample page fill the window. */
      html, body {
        height: 100%;
        margin: 0;
        padding: 0;
      }
    </style>
  </head>
  <body>
    <div id="map"></div>
    <script>
      // This example displays a map with the language and region set
      // to Japan. These settings are specified in the HTML script element
      // when loading the Google Maps JavaScript API.
      // Setting the language shows the map in the language of your choice.
      // Setting the region biases the geocoding results to that region.
      function initMap() {
        var map = new google.maps.Map(document.getElementById('map'), {
          zoom: 8,
          center: {lat: 35.717, lng: 139.731}
        });
      }
    </script>
    <script src="https://maps.googleapis.com/maps/api/js?key=YOUR_API_KEY&callback=initMap&language=ja&region=JP"
    async defer>
    </script>
  </body>
</html>

All this text was taken from random websites I had open and code I grabbed from anywhere.
This is the last line of text... byeeee!
