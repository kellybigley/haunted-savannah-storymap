haunted-savannah-storymap
=========================

Collecting the stories and photos was the hard part.  I wanted the story map to be the easy part.  There are several ESRI story map options that have lots of very nice features.  However, utilizing the ESRI story maps requires using ArcGIS Online webmaps which would have required making a webmap with my story data.  I was really looking for something that was much more simple to implement.  Our own <a href="https://github.com/jonahadkins">Jonah Adkins</a> came to the rescue and showed me StoryMapJS, an open source javascript library that takes a JSON file as input and presents a nice story map.  The simplicity of implementation combined with the attractive user interface on the resulting story map made this solution just what I was looking for.  

<a href="http://storymap.knightlab.com/" title="StoryMapJS">StoryMapJS</a> - http://storymap.knightlab.com/
StoryMapJS provides an authoring tool to build the JSON file in the proper syntax to define each location’s coordinates, name, description, and media (photo, video, tweet, etc).  The map is built using Leaflet, so the StoryMapJS options allows the use of any custom map tiles.  This allowed me to create a custom basemap on MapStack to use in my story map.

<a href="http://mapstack.stamen.com/" title="MapStack">Map Stack</a> - http://mapstack.stamen.com/
Map Stack leverages Open Street Map data and allows users to style datasets in a multitude of ways.  Using MapStack’s tools, I was able to generate a pretty cool looking sepia toned imagery basemap to use in my story map.  <a href="http://mapstack.stamen.com/edit.html#naip[bright=-45,tint=$c29d70@70];toner-labels[invert=1,bright=-30,sat=70,tint=$c29d70@60,alpha=60]/17/32.07733/-81.09022">http://mapstack.stamen.com/edit.html#naip[bright=-45,tint=$c29d70@70];toner-labels[invert=1,bright=-30,sat=70,tint=$c29d70@60,alpha=60]/17/32.07733/-81.09022</a>


<a href="http://www.flaticon.com" title="Flaticon">Flat Icon</a> - http://www.flaticon.com/
I really wanted the icons on the map to be something more ghostlike.  Sifting through the resulting storymap icons and styles, I found the few css classes that I could override to change the icons.  All I needed was the icons themselves.  Flat Icon is an online database of free vector icons.  I was able to search for and find a few ghost icons and add them to my cart.  The site made it easy to download the iconfont for the icons and gave me all the files I needed to include for my custom web font.  

Implementing this simple story map using these really great and easy tools was just what I needed.  Check out my code here:  https://github.com/kellybigley/haunted-savannah-storymap

-----------------------------------------------------------------------------------------------------
Story Map created using <a href="http://storymap.knightlab.com/" title="StoryMapJS">StoryMapJS</a>

Map tiles from <a href="http://mapstack.stamen.com/" title="MapStack">Map Stack</a>

Icons made by Freepik from <a href="http://www.flaticon.com" title="Flaticon">www.flaticon.com</a> is licensed by <a href="http://creativecommons.org/licenses/by/3.0/" title="Creative Commons BY 3.0">CC BY 3.0</a></div>
