# MAPPABLE CHEAT-SHEET
An (incomplete) checklist for making geodata visualizations in (data-driven) journalism.

**ALWAYS ASK YOURSELF FIRST: Is a map really the best way to visualize the data set?**

**DATA HANDLING**
* [x] Got all geographic elements right? (especially borders &amp; place names)
* [x] Check the correct position of geocoded and self drawn map elements
(thus preventing mistakes from misused spatial reference systems)
* [x] Have all outliers and duplicates been eliminated? Correctly dealt with incomplete data entries?
* [x] Have data entries that are not necessary for the final visualization been removed?
* [x] Have the values been normalized (e.g. by population data)?

**CARTOGRAPHIC REPRESENTATION**
* [x] Has a suitable spatial reference system been chosen?
(consider rotation, distortion, equal area)

* [x] Is the level of given context information (reference points, place names, borders) well balanced?
* [x] Is it really necessary to use a basemap or can users already orient themselves by the mapped data points?
* [x] Is there too much useless white space on the map? If yes, how about several smaller maps?

**VISUAL IMPLEMENTATION**
* [x] Do readers instantly understand the key message of the visualization?
* [x] Is the visualization readable for someone who suffers from color blindness?
* [x] Choose meaningful categorial boundaries that lead to well perceivable categories
* [x] If mapping locations: pick symbols than are more meaningful than pins (or use dots instead)
* [x] Color scales
  - Rainbow colors and red-green color schemes usually should not be the first choice. [http://colorbrewer2.org/](http://colorbrewer2.org/) is your friend!
  - Be careful with manipulating color schemes when working with continuous data. You might damage the logic of equidistant colors.
  - When working with qualitative color schemes: do all colors appear equally important or are there unintended highlights?
  - Be aware of biased colors (e.g. red and green) and what meaning is usually assigned to them
  - Choose a suitable middle point when working with diverging color schemes

**LEGEND AND ATTRIBUTION**
* [x] Include copyright and attribution for all external data sources (incl. geodata and open data!)
* [x] Does the reader need a legend to understand the visualization? If yes, is your legend complete?
* [x] If you use transparent map elements, pay attention on displaying them correctly in the map legend.
* [x] If desired: how about publishing your raw data?

**INTERACTIVITY**
* [x] Is it easily understandable how interactive elements work?
* [x] Would a static map be equally suitable? Does interactivity really lead to a surplus that&#39;s worth the external dependencies that come along with interactivity?
* [x] Is your map limited to meaningful extends and zoom levels?
* [x] How does your visualization work with your content management systems?
* [x] Is everything working fine in most common browsers and on mobile devices (at least in iOS + Android)?
* [x] If desired: how about embedding options?
