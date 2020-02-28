Road Infrastructure Asset Management

I got idea from OpenStreetCam.org, however I want to make it simple by using only JQuery, Leafletjs, Python Django, PostGIS, and Bootstrap.

Task List:
- [x] Upload survey data file
  - [x] Upload project file
  - [x] Upload GPS data
  - [ ] Upload photos (front, left, right, back, birdeye)
  - [ ] Upload depth file for road roughness
  - [ ] Upload depth file for road geometry
- [ ] Postprocessing
  - [x] Stitch photos to get panoramic view
  - [x] Capture Depth data (using Terabee 3D Camera)
  - [ ] Asset identification using road object detection and recognition
  - [ ] Calculate IRI
- [ ] Map
  - [x] create base map using leafletjs, Python Django, Bootstrap, JQuery, and Postgis
  - [x] load survey data and overlaid into map
  - [ ] display survey data on the survey window (slightly similar like openstreetcam)
  - [ ] make slider for sliding survey data based on timestamp
