# about

drag the marker or use the geocoder to reveal which hawker stores are within 30 min walking distance to the marker location.

* Used mapbox Isochrone API to generate the isochrone polygone, then used [turf.intersect()](https://turfjs.org/docs/) to find the hawker stores which reside in the polygon

* Data is from [@datascapesg/help-our-hawkers](https://github.com/datascapesg/help-our-hawkers)

for a similar map check out [iso-hawker-nearby](https://github.com/weirdyang/iso-hawker-nearby)