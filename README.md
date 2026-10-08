# Terra Incognita

A browser game about sailing into the unknown, inspired by Columbus's 1492 voyage.

You leave Palos de la Frontera on 3 August 1492. Your starting chart shows part of the eastern Atlantic: Castile, Africa, the Canaries, Madeira and the Azores. Beyond it is blank parchment, hiding recognizable Earth coastlines until you sight them. Watch for signs of land, name the coasts you chart, go ashore for water, and bring word home before the crew mutinies.

The parchment is a flat projection of a spherical world. Sailing, course setting, distance and visibility use spherical coordinates. East–west travel continues across the longitude seam, and passing a pole continues on the opposite meridian. The chart repeats horizontally as you sail; latitude runs from 90°N to 90°S. Land can still block your course. Starting a new voyage resets exploration and weather on the same Earth.

## Run it

Open `index.html` in any modern browser. There is no build step, no server and no dependencies.

The page loads its fonts from Google Fonts. Offline, it falls back to Georgia.

## Play

| Action | Keys | Touch / mouse |
| --- | --- | --- |
| Set a course | | Click or tap the chart |
| Steer | `A` / `D` or `←` / `→` | Hold **Port** / **Starboard** |
| Heave to / make sail | `Space` | **Heave to** |
| Go ashore / dock at Palos | `E` | **Go ashore** |
| Whole chart | `M` | **Chart** |
| Zoom | `+` / `-`, mouse wheel | **+** / **−** |
| Faster time (1×, 2×, 4×) | `F` | **1×** |
| Pause / resume | `P` | **Pause** / **Resume** |

**Tip:** Caravels sail poorly into the wind. Near Palos the westerlies blow toward Europe. Sail south to the Canaries first and the trade winds will carry you west, as they did Columbus. To get home, go north and ride the westerlies back.

## Historical accuracy

The departure setting, fleet names, westward search for Asia and use of Atlantic wind belts are drawn from history. This is a fictional exploration game, not a reconstruction of the first voyage. Stores, sailing performance, sighting distances, morale, encounters, gold and royal rewards are simplified or invented; the three ships behave as one, and later voyages are blended into the naming options. The starting chart is a gameplay restriction, not a complete picture of European knowledge in 1492.

The captain's language about naming and claiming land reflects a colonial viewpoint. The Americas already had inhabitants, names and complex societies. The game does not simulate the coercion, enslavement, disease and other consequences of colonization. See the Library of Congress's [Columbus and the Taíno](https://www.loc.gov/exhibits/exploring-the-early-americas/columbus-and-the-taino.html) and [Christopher Columbus: Man and Myth](https://www.loc.gov/exhibits/1492/columbus.html), and NOAA's explanation of [trade winds](https://oceanservice.noaa.gov/facts/tradewinds.html).

## Map data

Coastlines use public-domain [Natural Earth 1:110m land polygons](https://www.naturalearthdata.com/downloads/110m-physical-vectors/110m-land/), embedded in `index.html` so no map download is needed at runtime. The map is generalized to a 0.25° grid; several small Atlantic islands omitted by that dataset are represented by slightly enlarged symbols. This is approximate modern geography, not a survey of 1492 shorelines. The flat projection stretches east–west shapes near the poles, although sailing distances account for latitude. Weather uses simplified global wind belts rather than reconstructed historical weather.
