My JSC370 Final Project Website

This is my JSC370 Final Project website home. The website is online at [https://jenz313.github.io/JSC370-Project/](https://jenz313.github.io/JSC370-Project/).


Welcome to the TTC Delay Explorer, a data storytelling project created for JSC370 at the University of Toronto.  
 This site explores how delays affect Toronto’s public transit system using ten years of TTC delay data from 2014 to 2024.  
 Through a mix of analysis and interactive visualizations, the project reveals when, where, and why delays occur—and what patterns emerge across time and modes.

 This site contains 3 main sections:
 
 - **Overview**: Project introduction, background, interative plots and data summary 
 - **Midterm EDA**: Initial exploratory data analysis and visual insights  
 - **Final Report**: Modeling results, key findings, and conclusions  

 Use the navigation bar at the top to explore the sections.

# Data

 - The dataset used in this project was sourced from Toronto’s Open Data Portal, covering delay events for buses, streetcars, and subways. To simplify and standardize the data, raw files were cleaned and processed using custom R scripts available in the `data` folder of this project. These scripts handle issues such as inconsistent date formats, missing values, and delay type mappings. While this site uses a cleaned CSV for faster access, the full pipeline is reproducible and can be rerun using the original TTC data and the provided scripts.

#  Key Questions Explored

 - When do delays most often happen?  
 - Are there patterns across weekdays, hours, or seasons?  
 - Which transit modes are most affected?  
 - What are the most common delay causes?  
 - Can we predict future delays using past records or external events?
