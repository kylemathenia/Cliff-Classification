The best tool for finding cliffs in the United States.
# [Go to app.](https://relativeradness.users.earthengine.app/view/cliffs)

![Cliffs](https://media.giphy.com/media/97k0I9lZmvf5xzQK2L/giphy-downsized.gif)

![Cliffs](https://media.giphy.com/media/elRmM3PfsE1s7BKTrk/giphy.gif?cid=790b76117335d14ed91d21fe88bc0ce3ae8cf7da88c66335&rid=giphy.gif&ct=g)

# Layers:

**Slope:** Pure slope visualized with colors to highlight dramatic terrain. Yellow and above is pretty seriously steep. 

**Fuzzy Cliff Classification (Zoom: 14-16):** The best cliff map at zoom levels 14-16. "Fuzzy" just means there is a range of color for how confident the map is that the feature is a cliff. 

**Fuzzy Cliff Classification (Zoom: 10-13):** This allows you to see the cliffs even when zoomed out really far. It may take a moment to render because there is a lot to compute. 

**Cliff Classification 10m Res:** Just the fuzzy classification converted to binary true/false cliff tiles. The fuzzy maps are better. 

**Cliff Classification 30m Res:** A lower resolution version of cliffs classified so you can compare with the NED Landforms cliff classification map. 

**NED Cliff Classification:** The previous best available cliff classification map I could find. Data provided by The Conservation Science Partners. This only shows the tiles classified as cliffs in the NED Landforms map. 

# Go to [the site](https://sites.google.com/view/relativelyrad/cliff-classification/app-video) and [Google Earth Engine](https://developers.google.com/earth-engine/guides/playground) for more info. 


The code can be pasted directly into the Google Earth Engine code editor. Alternatively, it can be modified and used with the earth engine API. 


"App Layers" is the code implemented in the app. "All Layers" includes additional layers that might be interesting to see. 
