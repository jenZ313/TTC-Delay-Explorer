My JSC370 Final Project Website

This is my JSC370 Final Project website home. The website is online at [https://jenz313.github.io/JSC370-Project/](https://jenz313.github.io/JSC370-Project/).

### Final Presentation Video
[Download or view on GitHub](./FinalPresentation.mp4)

[Watch on Google Drive](https://drive. oogle.com/file/d/1mh-4vVDxRuStieVEqAO37nox59I6Yp9q/view?usp=sharing)


Welcome to the TTC Delay Explorer, a data storytelling project created for JSC370 at the University of Toronto.  
 This site explores how delays affect Toronto’s public transit system using ten years of TTC delay data from 2014 to 2024.  
 Through a mix of analysis and interactive visualizations, the project reveals when, where, and why delays occur—and what patterns emerge across time and modes.

 This site contains 3 main sections:
 
 - **Overview**: Project introduction, background, interative plots and data summary 
 - **Midterm EDA**: Initial exploratory data analysis and visual insights  
 - **Final Report**: Modeling results, key findings, and conclusions  

 Use the navigation bar at the top to explore the sections.

# Data

- The dataset used in this project was sourced from Toronto’s Open Data Portal and includes delay records for buses, streetcars, and subways. To simplify and standardize the data, all raw files were cleaned using the script `clean_data.Rmd` located in the `data` folder. This script addresses issues such as inconsistent date formats, missing values, and delay type codes.

- While the midterm report performs similar cleaning steps, `clean_data.Rmd` additionally saves the cleaned result as a CSV file for easy reuse in the final report. The midterm report itself can be run directly without additional setup, as it retrieves streetcar and subway data through the TTC API. The necessary code for processing bus delays and mapping delay types is also provided in the `data` folder for full reproducibility.

#  Key Questions Explored

 - When do delays most often happen?  
 - Are there patterns across weekdays, hours, or seasons?  
 - Which transit modes are most affected?  
 - What are the most common delay causes?  
 - Can we predict future delays using past records or external events?
