# Create a map

Map a set of languages and color them by feature or two sets of
features.

## Usage

``` r
map.feature(
  languages,
  features = "",
  label = "",
  popup = "",
  latitude = NA,
  longitude = NA,
  label.hide = TRUE,
  label.fsize = 15,
  label.font = "sans-serif",
  label.position = "right",
  label.emphasize = list(NULL, "black"),
  shape = NULL,
  shape.size = 20,
  pipe.data = NULL,
  shape.color = "black",
  stroke.features = NULL,
  point.cluster = FALSE,
  density.estimation = NULL,
  density.method = "fixed distance",
  density.estimation.color = NULL,
  density.estimation.opacity = 0.6,
  density.points = TRUE,
  density.width = NULL,
  density.legend = TRUE,
  density.legend.opacity = 1,
  density.legend.position = "bottomleft",
  density.title = "",
  density.control = FALSE,
  isogloss = NULL,
  isogloss.color = "black",
  isogloss.opacity = 0.2,
  isogloss.line.width = 3,
  isogloss.width = NULL,
  color = NULL,
  stroke.color = NULL,
  image.url = NULL,
  image.width = 100,
  image.height = 100,
  image.X.shift = 0,
  image.Y.shift = 0,
  title = NULL,
  stroke.title = NULL,
  control = "",
  legend = TRUE,
  legend.opacity = 1,
  legend.position = "topright",
  stroke.legend = TRUE,
  stroke.legend.opacity = 1,
  stroke.legend.position = "bottomleft",
  width = 5,
  stroke.radius = 9.5,
  opacity = 1,
  stroke.opacity = 1,
  scale.bar = TRUE,
  scale.bar.position = "bottomleft",
  minimap = FALSE,
  minimap.position = "bottomright",
  minimap.width = 150,
  minimap.height = 150,
  facet = NULL,
  tile = "OpenStreetMap.Mapnik",
  tile.name = NULL,
  tile.opacity = 1,
  zoom.control = FALSE,
  zoom.level = NULL,
  rectangle.lng = NULL,
  rectangle.lat = NULL,
  rectangle.color = "black",
  line.lng = NULL,
  line.lat = NULL,
  line.type = "standard",
  line.color = "black",
  line.opacity = 0.8,
  line.label = NULL,
  line.width = 3,
  graticule = NULL,
  minichart = "bar",
  minichart.data = NULL,
  minichart.time = NULL,
  minichart.labels = FALSE,
  map.orientation = "Pacific",
  radius = NULL
)
```

## Arguments

- languages:

  character vector of languages (can be written in lower case)

- features:

  character vector of features

- label:

  character vector of strings that will appear near points

- popup:

  character vector of strings that will appear in pop-up window

- latitude:

  numeric vector of latitudes

- longitude:

  numeric vector of longitudes

- label.hide:

  logical. If FALSE, labels are displayed allways. If TRUE, labels are
  displayed on mouse over. By default is TRUE.

- label.fsize:

  numeric value of the label font size. By default is 14.

- label.font:

  string with values of generic family: "serif", "sans-serif",
  "monospace", or font name e. g. "Times New Roman"

- label.position:

  the position of labels: "left", "right", "top", "bottom"

- label.emphasize:

  is the list. First argument is a vector of points in datframe that
  should be emphasized. Second argument is a string with a color for
  emphasis.

- shape:

  1.  if TRUE, creates icons (up to five categories) for values in the
      `features` variable;

  2.  it also could be a vector of any strings that represents the
      levels of the `features` variable;

  3.  it also could be a string vector that represents the number of
      observations in dataset.

- shape.size:

  size of the `shape` icons

- pipe.data:

  this variable is important, when you use map.feature with dplyr pipes.
  Expected usage: pipe.data = .

- shape.color:

  color of the `shape` icons

- stroke.features:

  additional independent stroke features

- point.cluster:

  logical. If TRUE, points will be united into clusters.

- density.estimation:

  additional independent features, used for density estimation

- density.method:

  string with one of the two methods: "kernal density estimation" or
  "fixed distance" (default)

- density.estimation.color:

  vector of density polygons' colors

- density.estimation.opacity:

  a numeric vector of density polygons opacity.

- density.points:

  logical. If FALSE, it doesn't show points in polygones.

- density.width:

  for density.method = "fixed distance" it is a numeric measure (1 is
  1km). For density.method = "kernal density estimation" it is a vector
  with two meausures (first is latitude, secong is longitude). Defaults
  are normal reference bandwidth (see
  [bandwidth.nrd](https://rdrr.io/pkg/MASS/man/bandwidth.nrd.html)).

- density.legend:

  logical. If TRUE, function show legend for density features. By
  default is FALSE.

- density.legend.opacity:

  a numeric vector of density-legend opacity.

- density.legend.position:

  the position of the legend: "topright", "bottomright",
  "bottomleft","topleft"

- density.title:

  title of a density-feature legend

- density.control:

  logical. If TRUE, function show layer control buttons for density
  plot. By default is FALSE

- isogloss:

  dataframe with corresponding features

- isogloss.color:

  vector of isoglosses' colors

- isogloss.opacity:

  a numeric vector of density polygons opacity.

- isogloss.line.width:

  a numeric value for line width

- isogloss.width:

  for density.method = "fixed distance" it is a numeric measure (1 is
  1km). For density.method = "kernal density estimation" it is a vector
  with two meausures (first is latitude, secong is longitude). Defaults
  are normal reference bandwidth (see
  [bandwidth.nrd](https://rdrr.io/pkg/MASS/man/bandwidth.nrd.html)).

- color:

  vector of colors or palette. The color argument can be (1) a character
  vector of RGM or named colors; (2) the name of an RColorBrewer
  palette; (3) the full name of a viridis palette; (4) a function that
  receives a single value between 0 and 1 and returns a color. For more
  examples see
  [`colorNumeric`](https://rstudio.github.io/leaflet/reference/colorNumeric.html)

- stroke.color:

  vector of stroke colors

- image.url:

  character vector of URLs with an images

- image.width:

  numeric vector of image widths

- image.height:

  numeric vector of image heights

- image.X.shift:

  numeric vector of image's X axis shift relative to the
  latitude-longitude point

- image.Y.shift:

  numeric vector of image's Y axis shift relative to the
  latitude-longitude point

- title:

  title of a legend.

- stroke.title:

  title of a stroke-feature legend.

- control:

  vector of grouping values that make it possible to create control
  panel that can turn off/on some points on the map.

- legend:

  logical. If TRUE, function show legend. By default is TRUE.

- legend.opacity:

  a numeric vector of legend opacity.

- legend.position:

  the position of the legend: "topright", "bottomright",
  "bottomleft","topleft"

- stroke.legend:

  logical. If TRUE, function show stroke.legend. By default is FALSE.

- stroke.legend.opacity:

  a numeric vector of stroke.legend opacity.

- stroke.legend.position:

  the position of the stroke.legend: "topright", "bottomright",
  "bottomleft","topleft"

- width:

  a numeric vector of radius for circles or width for barcharts in
  minicharts.

- stroke.radius:

  a numeric vector of stroke radii for the circles.

- opacity:

  a numeric vector of marker opacity.

- stroke.opacity:

  a numeric vector of stroke opacity.

- scale.bar:

  logical. If TRUE, function shows scale-bar. By default is TRUE.

- scale.bar.position:

  the position of the scale-bar: "topright", "bottomright",
  "bottomleft","topleft"

- minimap:

  logical. If TRUE, function shows mini map. By default is FALSE.

- minimap.position:

  the position of the minimap: "topright", "bottomright",
  "bottomleft","topleft"

- minimap.width:

  The width of the minimap in pixels.

- minimap.height:

  The height of the minimap in pixels.

- facet:

  character vector that provide a grouping variable. If it is no `NULL`,
  then as a result a list of leaflets for `sync` or `latticeView`
  functions from `mapview` package is returned.

- tile:

  a character verctor with a map tiles, popularized by Google Maps. See
  [here](https://leaflet-extras.github.io/leaflet-providers/preview/)
  for the complete set.

- tile.name:

  a character verctor with a user's map tiles' names.

- tile.opacity:

  numeric value from 0 to 1 denoting opacity of the tile.

- zoom.control:

  logical. If TRUE, function shows zoom controls. By default is FALSE.

- zoom.level:

  a numeric value of the zoom level.

- rectangle.lng:

  vector of two longitude values for rectangle.

- rectangle.lat:

  vector of two latitude values for rectangle.

- rectangle.color:

  vector of rectangle border color.

- line.lng:

  vector of two (or more) longitude values for line.

- line.lat:

  vector of two (or more) latitude values for line.

- line.type:

  a character string indicating which type of line is to be computed.
  One of "standard" (default), or "logit". The first one should be
  combined with the arguments line.lat and line.lng and provide simple
  lines. Other variant "logit" is the decision boundary of the logistic
  regression made using longitude and latitude coordinates (works only
  if feature argument have two levels).

- line.color:

  vector of line color.

- line.opacity:

  a numeric vector of line opacity.

- line.label:

  character vector that will appear near the line.

- line.width:

  a numeric vector of line width.

- graticule:

  a numeric vector for graticule spacing in map units between horizontal
  and vertical lines.

- minichart:

  citation from leaflet.minicharts package: "Possible values are "bar"
  for bar charts, "pie" for pie charts, "polar-area" and
  "polar-radius"."

- minichart.data:

  citation from leaflet.minicharts package: "A numeric matrix with
  number of rows equal to the number of elements in lng or lat and
  number of column equal to the number of variables to represent. If
  parameter time is set, the number of rows must be equal to the length
  of lng times the number of unique time steps in the data."

- minichart.time:

  citation from leaflet.minicharts package: "A vector with length equal
  to the number of rows in chartdata and containing either numbers
  representing time indices or dates or datetimes. Each unique value
  must appear as many times as the others. This parameter can be used
  when one wants to represent the evolution of some variables on a map."

- minichart.labels:

  citation from leaflet.minicharts package: "Should values be displayed
  above chart elements."

- map.orientation:

  a character verctor with values "Pacific" and "Atlantic". It
  distinguishes Pacific-centered and Atlantic-centered maps. By default
  is "Pacific".

- radius:

  deprecated argument

## Author

George Moroz \<agricolamz@gmail.com\>

## Examples

``` r
map.feature(c("Kabardian", "Russian"))

{"x":{"options":{"crs":{"crsClass":"L.CRS.EPSG3857","code":null,"proj4def":null,"projectedBounds":null,"options":{}},"zoomControl":false},"calls":[{"method":"addTiles","args":["OpenStreetMap.Mapnik",null,null,{"minZoom":0,"maxZoom":18,"tileSize":256,"subdomains":"abc","errorTileUrl":"","tms":false,"noWrap":false,"zoomOffset":0,"zoomReverse":false,"opacity":1,"zIndex":1,"detectRetina":false}]},{"method":"addProviderTiles","args":["OpenStreetMap.Mapnik",null,"OpenStreetMap.Mapnik",{"errorTileUrl":"","noWrap":false,"opacity":1,"detectRetina":false}]},{"method":"addCircleMarkers","args":[[43.5082,59],[43.3918,50],5,null,["",""],{"interactive":true,"className":"","stroke":false,"color":"#03F","weight":1,"opacity":0.5,"fill":true,"fillColor":["#3B8BC6","#3B8BC6"],"fillOpacity":1},null,null,["<a href='https://glottolog.org/resource/languoid/id/kaba1278' target='_blank'>Kabardian<\/a><br>","<a href='https://glottolog.org/resource/languoid/id/russ1263' target='_blank'>Russian<\/a><br>"],null,null,{"interactive":false,"permanent":false,"direction":"right","opacity":1,"offset":[7.5,0],"textsize":"10px","textOnly":true,"style":{"font-size":"15px","font-family":"sans-serif"},"className":"","sticky":true},null]},{"method":"addScaleBar","args":[{"maxWidth":100,"metric":true,"imperial":true,"updateWhenIdle":true,"position":"bottomleft"}]}],"limits":{"lat":[43.5082,59],"lng":[43.3918,50]}},"evals":[],"jsHooks":[]}
```
