## Seattle Health Resources Map


### Project Description
The Seattle Health Resources Map is an interactive, web-based mapping application that we developed to help people, more specifically individuals in need, explore the distribution of health-related and humanitarian resources across the city of Seattle. The site is built with HTML, CSS, and JavaScript and functions entirely as a static website hosted on GitHub Pages.
Our goal in creating this web application was to take publicly available data and translate it into a clear, accessible visual format. By presenting health resources within a geospatial context, our map helps individuals recognize geospatial patterns that may influence access to care. Throughout the design process, we focused on clarity, simplicity, and ease of navigation to ensure the tool was understandable to a wide range of users, including community members, researchers, and anyone seeking a better understanding of the various health-related and food services in Seattle.
### Favicon
The favicon used in this project is stored in the following directory:
/assets/favicon.png
It is referenced within the HTML header section so that it appears automatically in the browser tab when the application is loaded.


### Project Goal
The main purpose of this project is to make information about Seattle’s health resources more accessible and easier to interpret by taking various datasets and placing them within an interactive map. Visualizing health resources spatially allows users to see the broader patterns that shape health equity across the city. The project’s broader objectives include the following:
- Increasing public awareness of healthcare services and facilities located within Seattle.
- Supporting informed decision-making through a visual, map-based representation of health resources.
- Encouraging equitable access by clearly displaying locations where services are concentrated or lacking.
- Providing a platform that can be expanded upon or used for educational and community-based initiatives.


Underlying this project is the message that the spatial distribution of services has a direct impact on community outcomes. By using maps to to provide a proper visualization of these patterns, it becomes easier to understand where access gaps may exist for those services.


### Application URL
The application is publicly accessible at the following link:
https://ricoxta.github.io/Seattle_health_resources_map/


This site is hosted through GitHub Pages and does not require any additional installation in order to be viewed.
Screenshot:

#### **Full view of the map**
![Web App Screenshot](assets/mapInFullView.png)
#### **Buffer zone showing resources in the area**
![Zoomed In Shot of Seattle Map](assets/mapWithAllCategories.png)
#### **Same buffer zone with filtered categories**
![Filtered and Zoomed in Shot of Seattle](assets/mapWithFilteredCategories.png)


### Main Functions
Our Seattle Health Resources Map includes several core functions that make the site accessible and informative:


#### Interactive Map
The primary feature of the application is an interactive map that allows users to pan, zoom, and focus on different parts of Seattle. Health resource data is displayed through point symbols so that users can explore where services are located relative to neighborhoods, major roads, and other city features.
A key component of the map is the buffering tool, which allows users to input a distance (in miles) and generate a circular buffer around any area within Seattle. The map then displays how many health resources fall within that radius. This helps users understand local accessibility, estimate service reach, and visually compare resource availability between different areas of the city. The buffering feature adds a practical, analytical dimension to the map by connecting spatial proximity with real-world implications for community access.
#### About and Introductory Pages
The pages titled *about.html* and *intro.html* offer important contextual information regarding the goals of the project, the importance of mapping health resources, and background information on the development of the site.


#### Resource Display
Health resources, when included as data layers, are represented on the map as individual colored points relative to the resource category they belong to to help users visualize their spatial distribution. 


#### Simple Interface Navigation
The website includes clear and direct navigation elements so that users can move between pages without confusion.


#### Data Sources
The information used to support this project is derived from publicly available listings and datasets relevant to health resources in Seattle. Our sources include:
* __Washington State Department of Health__
* __Seattle-area public health organizations & Seattle open data portal__
    - https://www.seattle.gov/opcd/population-and-demographics/geographic-files-and-maps#2010census:~:text=Census%20Bureau%20Tract%20Map
    - https://data.seattle.gov/Community-and-Culture/Emergency-Food-and-Meals-Seattle-and-King-County/kkzf-ntnu/about_data

* __King County open data__
    - https://gis-kingcounty.opendata.arcgis.com/datasets/health-care-for-the-homeless-health-care-for-the-homeless-point/explore?location=47.611190%2C-122.315689%2C13.00&showTable=true
* __Community and nonprofit directories providing health service information__


Though the dataset included may be limited for demonstration, the overall structure is designed to accommodate future data expansion.


### Applied Libraries and Web Services
The project incorporates several web technologies and services, including:
#### Mapping Libraries
- Mapbox GL JS, supporting vector-tile visualization to implement our data as well as adding popups. 
- Turf.js, which was used for the spatial analysis of the number of resources within a certain buffer zone as well as filtering out unnecessary data points located outside the Seattle area .


#### Web Services
- GitHub Pages to host the live version of our web application.
- Basemap tile providers such as Mapbox or OpenStreetMap supply the underlying geographic layers.


These tools together allow the site to function as an interactive mapping application that is easy to deploy and maintain.


### Acknowledgments
This project was developed from the framework of the repository titled *Finalproject_groupAD* as well as our team consisting of **Jack Rainlyn**, **Ricardo Torres Arevalo**, **Reed Bayless**, **David Mwangi**, and **Stephen Saade**. We acknowledge the contributions of instructors, peers, and the broader open-source community. Public data providers and mapping library maintainers also play an essential role in making this type of work possible.


### AI Use Disclosure
The use of AI was limited to Copilot which was used to assist with coding and debugging our *index.html,* *intro.html,* and *about.html* files. It allowed us to implement some complex features which kept breaking as well as clean up our code.


### Additional Notes
- The website is fully static and does not rely on a server-side backend.
- The codebase is structured to support future additions, including new data layers, additional pages, and expanded functionality.
- The application is optimized for use on modern web browsers.
- File paths referenced in this document reflect the standard repository organization.


### Conclusion
The Seattle Health Resources Map provides an accessible method for visualizing and understanding the distribution of health-related resources across Seattle. Through a combination of clear design, spatial visualization, and publicly sourced data, the project allows users to engage with information that has direct relevance to community health. The application underscores the role of mapping in promoting awareness, facilitating decision-making, and supporting equity in access to essential health services.
