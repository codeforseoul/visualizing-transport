##WHAT:
I live in Suwon (south of Seoul), it takes me 1 hour to get to Gangnam Station but only 45 minutes to get to Eujiro (North of the river and much farther geographically).  Transportation systems affect how citizens experience distance and I want to visualize this. The example below shows the geography of london reshaped to the image of the subway map. My idea is similar except I want to reshape the geography of Seoul to visualize distances between locations. 

![image](https://cloud.githubusercontent.com/assets/4232594/5704211/a5489d46-9ab2-11e4-956c-ad6d80bf1e65.png)


Here is a concept of how it may look like if done correctly (but a heatmap may be more feasible):
http://bl.ocks.org/mbostock/cfcdbd3eacd79d30b2e6

###WHY:
  - This visualization can show true distances between places (by time) and can even be used as a planning tool for the Seoul city government in planning new transportation routes
  - This can promote the use of transit instead of cars. (buses and trains are faster in the city than private automobiles)

###WHO: 
####People with skills or interests in: 
  - Data Collection: There are numerous APIs that give information about travel data. I can use google transit but I think the naver map may be more accurate. We need to build something that can call from the API and collect the data: 
   - Korean: The Naver API is in Korean. Someone who speaks Korean would be very helpful!
   - Data Visualization, Mapping and/or Browser technologies: After collecting the data we need to find a way to display it nicely and also efficiently (a browser can only take so much data) 
   - Urbanists/Designers: People that are interested in urbanization and can realize good use cases for this 

###API:
- http://developer.naver.com/wiki/pages/JavaScript#section-JavaScript-Nhn.api.map.LatLng
-  http://api.bus.go.kr/
- https://developers.google.com/maps/documentation/directions/

####Map Resrouces:
- SHP file of Korea: http://sgis.kostat.go.kr/statbd/statbd_03.vw#
- Json of Korea: http://www.station3.co.kr/korea-maps/
- Source of Current Map: https://github.com/SeoulTech/southkorea-maps

###ADDITIONAL LINKS/ INSPIRATION:
    - Shanghai Metro Flow: http://tillnagel.com/2013/12/shanghai-metro-flow/
    - Tokyo Wind Map: http://air.nullschool.net/
    - London Tube Map: http://brunoimbrizi.com/experiments/#/07
    - London Resahped: http://benedikt-gross.de/log/2012/02/metrography-london-tube-map-to-large-scale-collective-mental-map/

    - To Create Subway Map: http://kalyani.com/2010/10/subway-map-visualization-jquery-plugin/