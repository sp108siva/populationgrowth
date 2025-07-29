
Message of the Visualization:
This project aims to provide a narrative around how growth in population is impacting different countries across the world. Population growth affects both economic and environment aspects of a country. Below are the factors studied as part of this project:
•	Gross Domestic Product (GDP) is one of the factors that depicts how well a country is performing economically, but it has been seen that GDP of many low-income and lower-middle-income countries are not growing proportional to the population growth. As a result, it makes it more difficult for these countries to afford increase in expenditures that is needed to uplift the people from hardship. 
•	Carbon Dioxide (CO2) Emission acts like a layer in the air, trapping heat in the atmosphere, and warming up the Earth. CO2 Emission have increased many folds due to growth of population and increased human activities like burning of fossil fuels. Global temperature is raised, as the CO2 layer stops the Earth from cooling down.
•	Forest acts as a crucial factor for maintaining the climate balance. But forest area has been depleting as the population is growing. As a result of depletion in forest area, environment is negatively impacted like extinction of wildlife, soil erosion, floods, global warming, loss of biodiversity.

Narrative Structure:
Narrative Visualization follows the structure of an Interactive Slideshow giving the users functionality to navigate through different slides and the details if needed and understand the impact of Population Growth on different factors like Gross Domestic Product, Carbon Dioxide Emission, and Forest Area Depletion. 
User have been given a navigation option from the scene 1, if the user wants to explore some tangent information about the growth in the population across different countries, so that user can further relate to the factors that have been detailed in all the scenes.

Visual Structure:
Visual structure is based on different scenes (web pages). Each scene is portrayed using same layout and template for visual consistency. Below are visual consistencies used in the project:
•	Title for each scene is placed above the visualization and helps in establishing the context for visualization. 
•	The visualization container which displays the data (Graphs) consistent for same type of chart with similar kind of text color for each scene of the narrative visualization. 
•	Pagination is provided to let the users know which scene is been shown.
•	Background color in each visualization is consistent.
•	Transitions are used to design the scenes for consistency and keeping the viewer from getting disoriented through the order of the scenes. 
•	Graph varies per the necessity of the scene to convey the narrative of the data in an appropriate way.

Scenes and Visual Ordering:
Project contains 4 web pages which depicts 4 scenes. Below are the details for each scene:
•	First scene sets the context of the project displaying how population growth is impacting the economic aspects of different countries. Visualization is presented as a Scatterplot graph (showing population growth % vs GDP for different countries of the world). From scene 1 user have two options:
o	First option is part of the Interactive Slideshow structure, where user can tangent into exploring more information about population growth trends in different countries. For this option User needs to click on the “Click Here” link present in the scene 1, which will navigate the user to the scene 2. 
o	Second option is used by the user if the user is not interested in exploring more details about the scene and wants to continue. Then user have the option to go to scene 3, by clicking on the “Next Page” button or go to any other scenes by clicking on the page numbers present on the pagination section. 
•	Second scene is getting the user to be more exploratory usage of the project, by showing the population growth trends across different countries. Visualization is presented as a Bar graph (showing population growth % for different countries of the world). From scene 2 user have the option to go back to the scene 1 using the “Previous Page” button or to proceed to Scene 3 using the “Next Page” button. Just to mention no pagination is provided in this scene as this an investigative scene.    
•	Third scene is venturing into how population growth is impacting the environmental aspects of different countries. Visualization is presented as a Bar graph (showing population growth % vs Carbon Dioxide (CO2) emission for different countries). From scene 3 user have the below options:
o	Go to scene 4, by clicking on the “Next Page” button 
o	Go to scene 1, by clicking on the “Previous Page” button
o	Go to any other scenes by clicking on the page numbers present on the pagination section.
•	Fourth scene is taking further into how population growth is impacting environmental aspects of different countries. Visualization is presented as a Line graph (showing forest area % for different countries over a time). From scene 4 user have the below options:
o	Go to scene 1, by clicking on the “Start Again” button 
o	Go to scene 3, by clicking on the “Previous Page” button
o	Go to any other scenes by clicking on the page numbers present on the pagination section.

Annotations:
Annotations are used to highlight in the data, which will help the user to further explore the data and get more conclusive answers from the data. Annotations have a consistent template on all the scenes for font size and a bolded style. 
Annotation in Scene 1 (Scatterplot – population growth vs GDP) is the textual details situated inside the visualization meant to highlight the ‘GDP growth with respect to the population growth of the country’. When the user clicks the hyperlink (“Click Here”) to transition forward to scene 2 the annotation for scene 1 is no more visible. 
Annotation in Scene 2 (Bar graph – population growth % vs countries) is the textual details situated inside the visualization meant to highlight the ‘population growth of the country’. When the user clicks the “Previous Page” to navigate to Scene 1 or “Next Page” to forward to Scene 3 the annotations for Scene 2 are cleared. 
Annotation in Scene 3 (Bar graph – carbon emission increase % vs countries) is the textual details situated inside the visualization meant to highlight ‘carbon emission increase % with respect to the population growth’. When the user clicks the “Next” or “Previous” button to navigate back to Scene 1 or Scene 2 the annotation for Scene 3 is cleared. Also, in each scene there are annotations in the form of tool tips which appears when user mouse hovers.

Parameters:
Parameters are a means to engage the users in the narrative visualization, and make the users further explore the data and find conclusive answers. Parameters used in this visualization are in two ways: First way is through pagination, when user navigate through different scenes. Since the page number is retained, it will help in maintaining the state of the application by letting the user know which visualization user evaluates based on the previous values. Second way are the data point belonging to a specific country, when user move overs a data a pop up is displayed with data points related to that country, which similar across most of the scenes, this gives the users a reference to the state of the data present in previous scenes and benefit the user to gather more information about values detailed in the existing visualization.

Triggers: 
Triggers in this project is utilized in two approaches for this visualization. First approach is divided into two subcategories: First subcategory is to navigate from one scene to another scene through "mouse clicks" events over the embedded in the navigation buttons (namely: “Next Page”, “Previous Page”, “Start Again”). As the user navigates through different scenes these navigation buttons help the use to understand the visualizations in a better way. Second subcategory is present in the scene 1 in the form of “mouse click” events in the link (“Click Here”), which will navigate the user from scene 1 to the scene 2. Second Approach is used to show up the pop ups whenever user is doing a "mouse hover" over the bars in Bar chat or over the circles in Scatterplot. Transitions have been used in the mouse hover pop ups to give the users a seamless experience, when different data points are traversed in the visualization. These triggering points are also helpful in maintaining the state of the visualization since it provides the user information about the page number along with the country specific data points for reference.

Data Used:
Data used for the purpose of this project is derived from the World Development Indicators dataset from World Bank. Data can be accessed by anyone using the link ("https://datacatalog.worldbank.org/search/dataset/0037712”). This data is free to use. 
For this project dataset is considered from the year 2000 through 2018.
