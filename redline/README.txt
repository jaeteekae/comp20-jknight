Implementation:
The Google Maps API was correctly used to render a map centered around Boston.
The parsing and displaying of the location of red line trains has not been implemented correctly. The console displayed an error and the XMLHttpRequest was not able to load the train information, so there was no data available to show.
It is not possible to load data from the page http://developer.mbta.com/lib/rthr/red.json using XMLHttpRequest because of Javascript's Same Origin Policy. The origin of the train data is http://www.mbta.com. Since my page does not have the same origin, my page cannot retrieve the data.

Time spent: ~1 hour