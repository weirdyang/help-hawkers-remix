# about

drag the marker or use the geocoder to reveal which hawker stores are within 30 min walking distance to the marker location.

* Used mapbox Isochrone API to generate the isochrone polygone, then used [turf.intersect()](https://turfjs.org/docs/) to find the hawker stores which reside in the polygon

* Data is from [@datascapesg/help-our-hawkers](https://github.com/datascapesg/help-our-hawkers)

* Original google map and recommendations: [Google Maps Layer to find and support the digitally disadvantaged hawkers near youO](https://www.reddit.com/r/singapore/comments/nret1k/update_google_maps_layer_to_find_and_support_the/)

* for a similar map check out [iso-hawker-nearby](https://github.com/weirdyang/iso-hawker-nearby)

# acknowledgements

* u/loneRifle for the flatjson export

* u/waffleboy92 and his fellow contributors for collecting the daa