# TaboolaClicks
Taboola challenge displays clicks per minute

1.Just for now use this beta Json data that I created for testing, (all the data is meaningless, therefore you may see clicks from the sea)
http://beta.json-generator.com/api/json/get/VytKrxQK

2.The guideline is attached below:

1) Drop the flat map and stay only with the 3d globe.

2) left to the globe:
a. Taboola's logo above the text "today's clicks" - small letters, cool font.
b. the sum of today's clicks, aggregation of all the clicks up until this second. what is "today"? great question! today starts at midnight. 
which midnight? great question! the timezone should be configurable to whoever puts your product on the monitor. EST and Jerusalem timezones are enough.
(btw, if you want to be real pros you can add to the text "today's clicks" " - from 00:00 Israel Time" / "from 00:00 EST". according to the chosen timezone.

The sum will be updated evey second (same as the clicks on the globe), preferable with a nice animation that replaces (only the changed digits!) from top to bottom. hope you know what i mean.

3) right to the globe:
a. state #1: 
  - top 3 items with thumbnails, titles and number of clicks gained from midnight.
  - trending topic (top 5 words, using text indexing). this is a nice learnign task to experience, but very complicated. it will probably look bad. in this case, you can expand the "top items" section to 5 items.

b. state #2: 
- top 3 sourse publishers
- top 3 target publishers
each section will include the pub name, its % of total clicks and the % visualization (using bars).

4) On the globe:
a. clicks by coordinates (try to add an animation that will make the clicks flash on the screen)
b. heat map for all countries.

5) The initial display will be a worldwide globe.
It will be shown for 14 seconds:
7 with state #1 and 7 with state #2.

Then the globe will zoom in the first country.
all the stats will be changed accordingly (2b, 3a, 3b) and a photo of the country's flag will be displayed below the clicks sun (2b).
This country will be zoomed in for 16 seconds (including the zoom in anumation). The rest of the time (16s minus zoom) will be split between state #1 and state #2.

Then 16 secs for the second country and 14 secs for the thied country - exactly as described for the first.

After the 3 zoomed countries, the globe returns to a worldwide display and hozer halila.

6) US should be divided into states for the heat map!

7) don't forget that ecery second X reflects what really happened at X-1 minute. it refers both to the sum (2b) and the flashing clicks on the globe.

please find the attached video, showing an example of the two states (only for the worldwide display! but it's the same for the zoomed countries, except fot the flags addition).
