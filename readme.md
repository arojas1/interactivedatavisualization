# Interactive Data Visualization Portfolio

## Table of Contents
### [Projects and Tutorials](#Projects-and-Tutorials)
#### &emsp;[1.1 Getting Started](#11-Getting-Started-1)
#### &emsp;[1.2 Basic HTML](#12-Basic-HTML-1)
#### &emsp;[1.3 Intro to JS](#13-Intro-to-JS-1)
#### &emsp;[2.1 Quantities and Amounts](#21-Quantities-and-Amounts-1)
#### &emsp;[2.2 Distributions](#22-Distributions-1)
#### &emsp;[2.3 Time Series](#23-Time-Series-1)
#### &emsp;[2.4 Geographic](#24-Geographic-1)
### [Final Project](#Final-Project)
### [Reflection](#Reflection)

<hr>

## Projects and Tutorials

### 1.1 Getting Started

Project Link: [https://arojas1.github.io/Interactive-Data-Vis-Fall2021/1_1_getting_started/](https://arojas1.github.io/Interactive-Data-Vis-Fall2021/1_1_getting_started/)<br>
Tutorial Link: [https://github.com/InteractiveDataVis/Interactive-Data-Vis-Fall2021/tree/main/1_1_getting_started](https://github.com/InteractiveDataVis/Interactive-Data-Vis-Fall2021/tree/main/1_1_getting_started)

### 1.2 Basic HTML

Project Link: [https://arojas1.github.io/Interactive-Data-Vis-Fall2021/1_2_basic_html/](https://arojas1.github.io/Interactive-Data-Vis-Fall2021/1_2_basic_html/)<br>
Tutorial Link: [https://github.com/InteractiveDataVis/Interactive-Data-Vis-Fall2021/tree/main/1_2_basic_html](https://github.com/InteractiveDataVis/Interactive-Data-Vis-Fall2021/tree/main/1_2_basic_html)

### 1.3 Intro to JS

Project Link: [https://arojas1.github.io/Interactive-Data-Vis-Fall2021/1_3_intro_to_js/](https://arojas1.github.io/Interactive-Data-Vis-Fall2021/1_3_intro_to_js/)<br>
Tutorial Link: [https://github.com/InteractiveDataVis/Interactive-Data-Vis-Fall2021/tree/main/1_3_intro_to_js](https://github.com/InteractiveDataVis/Interactive-Data-Vis-Fall2021/tree/main/1_3_intro_to_js)

### 2.1 Quantities and Amounts

Project Link: [https://arojas1.github.io/Interactive-Data-Vis-Fall2021/2_1_quantities_and_amounts/](https://arojas1.github.io/Interactive-Data-Vis-Fall2021/2_1_quantities_and_amounts/)<br>
Tutorial Link: [https://github.com/InteractiveDataVis/Interactive-Data-Vis-Fall2021/tree/main/2_1_quantities_and_amounts](https://github.com/InteractiveDataVis/Interactive-Data-Vis-Fall2021/tree/main/2_1_quantities_and_amounts)

### 2.2 Distributions

Project Link: [https://arojas1.github.io/Interactive-Data-Vis-Fall2021/2_2_distributions/](https://arojas1.github.io/Interactive-Data-Vis-Fall2021/2_2_distributions/)<br>
Tutorial Link: [https://github.com/InteractiveDataVis/Interactive-Data-Vis-Fall2021/tree/main/2_2_distributions](https://github.com/InteractiveDataVis/Interactive-Data-Vis-Fall2021/tree/main/2_2_distributions)

### 2.3 Time Series

Project Link: [https://arojas1.github.io/Interactive-Data-Vis-Fall2021/2_2_distributions/](https://arojas1.github.io/Interactive-Data-Vis-Fall2021/2_2_distributions/)<br>
Tutorial Link: [https://github.com/InteractiveDataVis/Interactive-Data-Vis-Fall2021/tree/main/2_3_time_series](https://arojas1.github.io/Interactive-Data-Vis-Fall2021/2_3_time_series/)

### 2.4 Geographic

Project Link: [https://arojas1.github.io/Interactive-Data-Vis-Fall2021/2_4_geographic/](https://arojas1.github.io/Interactive-Data-Vis-Fall2021/2_4_geographic/)<br>
Tutorial Link: [https://github.com/InteractiveDataVis/Interactive-Data-Vis-Fall2021/tree/main/2_4_geographic](https://github.com/InteractiveDataVis/Interactive-Data-Vis-Fall2021/tree/main/2_4_geographic)

## Final Project

![Mapping Flood Myths Site Image](/FinalProject/MappingFloodMyths.png)

Project Link: [https://mappingfloodmyths.github.io](https://mappingfloodmyths.github.io)<br>
GitHub Repository Link: [https://github.com/mappingfloodmyths/mappingfloodmyths.github.io](https://github.com/mappingfloodmyths/mappingfloodmyths.github.io)

### Abstract
The power of water transcends time and connects all of humankind. Present day examples including hurricanes here in the US (Katrina, Maria, Irene to just name a few) and tsunamis like at Fukushima. Mapping Flood Myths will look at flood myths and legends and map the locations of these myths on an interactive web map.

A majority of the current flood myth analyses have been targeting Euro-centric civilizations (Ex: Noah’s Ark/Christianity, Gilgamesh’s flood/Babylon, and Deucalion’s flood/Greek). With this project as a starting point, flood myths from other civilizations can be discovered and further researched. Aside from expanding upon disfavored flood myths, this project can be a starting point for further analysis of the importance of flood myths and how they shaped civilizations. 

The target audience for this project will be anyone interested in flood myths in general or Geomythology (“the study of etiological oral traditions created by pre-scientific cultures to explain—in poetic metaphor and mythological imagery—geological phenomena such as volcanoes, earthquakes, floods, fossils, and other natural features of the landscape” (Mayor)). This project can be a starting point for many new analyses to be made in the fields of geomythology, archaeology, meteorology and many more.

### Technical Specifications
The data that I used for the website was collected from a website created by Mark Isaak called [The Flood in World Myth and Folklore](https://www.curioustaxonomy.net/home/FloodMyths/). The data was gathered using the Google Chrome extension, [WebScraper](https://webscraper.io/). Starting on the home page, I had WebScraper take the name of each region link which, once clicked, led to a page of origins. On the origin pages, WebScraper took the name of each origin link which, once clicked, then led to the page of their stories. On the story pages, I had WebScraper take the text of all paragraphs on the page. For almost all the story pages, the reference paragraph has the class HTML element of “ref”. This is how I distinguished the references for WebScraper to collect from the other paragraphs that contained the stories.

Once collected, I had to clean the data by combining some rows of data since there were duplicates created based on the paragraph and reference elements on the different pages. For example, there were some origins that had multiple stories each with their own references. When the data was scraped for this origin, WebScraper created a new line for each story multiplied by each reference that was on the page. In addition to this, there were times when a single story would be broken up into multiple paragraphs, which would also lead to a separate row in the data. To condense it, I made sure that each story, whether it was split into multiple paragraphs or not, was combined into one row with the source that went with that one story, this way there was one row per story. Once combined, I created a new column to remove any extra spaces and line breaks in the story text.

Once the text was cleaned, I started working on the locations of the stories. Many of the stories were attributed to groups of people or religions. To plot these stories on a map, I decided to look up the general area these stories were located (using Google and Wikipedia) and added the region, city and/or country name. Once all data points had a country or region, I looked up the coordinates of the centroid of each country or region and added that as latitude and longitude coordinates to the data. If there were any groups of people or religions that spanned multiple countries, I tried my best to get the central point of the region the stories spanned or to indicate within the data that this story was from multiple locations.

The data can be viewed [here](https://github.com/mappingfloodmyths/mappingfloodmyths.github.io/blob/main/Data/flood_myths_site_data_cleaned.csv).

### Sketches
Original Sketch:
![Original Sketch page 1](/FinalProject/Original_Sketches_Page_1.png)
![Original Sketch page 2](/FinalProject/Original_Sketches_Page_2.png)

Final Sketch:
![Final Sketch](/FinalProject/FinalSketches.png)

## Reflection

For my project, I originally had the idea of using Leaflet but, I ended up going with D3.js because it was easier to work with (once we had the geography class and saw that all I needed was shapefiles) and it felt like I could customize things more. I decided to go with a vintage/antique map look for my project. One way I contributed to this idea was by styling the points on the map to look like push pins. I decided to fill the space around the map with images of different works of art relating to flood myths from around the world. In the same style of vintage maps, I adjusted the colors of all the images to appear in a sepia/light brown filter using Photoshop. I also knew I wanted to do something with the imagery of a wave to match the water theme. To do this, I put the menu at the bottom of the page so that when it is clicked, a wave could rise as if flooding the page.

After each class, there was something that we ended up learning that made it into the project. Aside from most of the things that we learned for the geography and tooltip classes, I also used the class on how to make a table using D3.js for the database page and the path class helped me to understand how paths work and allowed me to make edits to the wave code that I used. For the wave code, there were some aspects of the wave that I didn’t like. For example, whenever the page would refresh or resize, the wave would be drawn again and, when it did so, it would fill in the page from the top left to the bottom right. I knew that I didn’t want the wave to disappear and redraw itself in the way it did so I went looking through the wavify.js code to see what was responsible for the redraw and to make it so that it doesn’t disappear but only changes the wave pattern. I am sure that it would have taken me three times as long to complete the wave menu had we not had the class on d3.path.

I also used what we learned in the tooltip class to help with having the different text show on the menu when a new tab is clicked as well as having the hover and click capabilities for the landmasses, pins and the popup. Since there were so many different aspects to the map, I needed a way to distinguish the pins from the landmasses when hovering and clicking. The way that I got around this was by passing HTML elements (in this case, “id” was passed) to the d3 functions. The “id” for the pins, landmass and popup list items are the same as the name of the item itself (ex: if the list item says “Guatemala”, then the “id” is also “Guatemala”). For the HTML text in the menu to change when clicked, I passed the “id” of the tab name, which was also the same name as the HTML file that had the text for that section and used d3 to load that HTML into the container for the menu.

One thing that took some time to work around was the scaling of the map to fit the screen. It was more difficult than I thought it would be to fit the map within the boundaries of the container designated for the map in the center of the webpage. To stay with the vintage map design, I wanted to add a border and background to the map so that the countries were not floating on the page. The border, however, ended up going outside of the boundaries of the container. The border was so far outside of the container that, when I tried scaling the map to fit inside, the countries ended up too small to be useful. I eventually decided on scaling the map slightly to allow the countries some space between their borders and the end of the container while keeping the countries large enough to see. This border issue is also why I decided to go with the Eckert IV geographic projection instead of the August or Vander Grinten IV geographical projections. Those projections ended up extending well past the container border. Eckert IV was the one projection that, not only fit within the vintage map style, but also did not extend so far outside of the boundaries.

Another thing that took some time to figure out was how scaling the map affected where it was shown on the page. When I was trying to make sure that the map centered perfectly on the page, I had to use calculations from the page itself to see what the x and y coordinates were for the map’s location and divide those in half to try to center it. At first it was not centering properly on the page, especially when the browser window would resize, and it took some time to realize that the scaling of the map did not relay to the x and y coordinates coming from the page data. Thus, I ended up having to calculate the coordinate locations, get them centered, and then multiply them by the scale to get the map to center properly.

With some more time, and now that I know more about D3.js than I did when I started this project, I would have reworked some of the code so that the variables that I was using flowed more easily throughout the code. When working on the popup, for example, I had quite a few issues getting the data to filter properly, without duplicates, and showing on the correct page. It took a lot of testing, and eventually, I found a solution to show the correct information. I started coding before learning some of the things in class by figuring it out as I went, looking it up, or going back after the class to append new code. Now, with foresight on what needs to be done, I am sure there are ways that the code can be a bit more concise and written in a cleaner way. Besides cleaning up the code, I wish I had more time to work on making the website more mobile friendly, accessible, and add updates to the database page. For the database, I would like to have made the page more aesthetically pleasing as well as adding features that made it feel more like a database, such as the ability to filter and search for items.