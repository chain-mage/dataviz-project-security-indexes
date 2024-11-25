# Cyber Index Data Visualization Project

## Data

The data I propose to visualize for my project is from [Kaggle](https://www.kaggle.com/datasets/katerynameleshenko/cyber-security-indexes?resource=download) and is called Cyber Security Indexes. It consists of various cybersecurity and digital development indices that measure different aspects of a country’s cybersecurity posture. It contains the following attributes for each country:

* Cybersecurity Exposure Index (CEI): Measures a country's exposure to cybersecurity risks.
* Global Cyber Security Index (GCI): Ranks countries based on their cybersecurity commitment on a global scale.
* National Cyber Security Index (NCSI): Reflects national capacity to handle cyber threats.
* Digital Development Level (DDL): Indicates the level of digital development and technology penetration.
* Country: The name or code of the country.
* Region: The geographical region the country belongs to.

This visualization project will be valuable for cybersecurity professionals, policymakers, and researchers. For cybersecurity professionals, it helps identify high-risk areas and countries with strong or weak cybersecurity preparedness. Policymakers can use the data to assess their country’s performance and allocate resources to areas that need improvement. Researchers can analyze global trends and the relationship between digital development and cybersecurity preparedness. I plan to focus on visualizing the comparison of all four indexes across countries and regions. So far, I have planned to use a radar chart to allow comparisons between the two countries. However, I would like to do multiple visualizations to showcase trends among all countries, not just two.  I will likely move away from the idea of a radar chart entirely to better showcase the trends between the indexes on a much more global scale and across multiple regions. It's important to visually see as many different trends as possible using many channels.


## Questions & Tasks

The following tasks and questions will drive the visualization and interaction decisions for this project:

* How do different regions compare in terms of their Cybersecurity Exposure Index (CEI), Global Cyber Security Index (GCI), and National Cyber Security Index (NCSI)?

* What is the relationship between a region’s Digital Development Level (DDL) and its cybersecurity indices?

* Are there any regions where high cybersecurity risks (CEI) are accompanied by strong national policies (NCSI)?

* Are the different regional correlations among the indexes?

* Can we identify outlier regions where the cybersecurity indices (CEI, GCI, NCSI) do not follow global trends?

* Which regions have a particularly high National Cyber Security Index (NCSI) compared to the Global Cyber Security Index (GCI)?

## Sketches

I've created and modified two different sketches. The first a radar chart as an example allowing users to compare two different countries indexes. The two quadrilaterals would be overlayed one another and be two different colors. This would allow us to make direct comparisons between countries.

![Radar Sketch](https://github.com/user-attachments/assets/dbd36f86-1eae-4454-bb65-fb675148283b)

The second is a scaterplot using marker, x position, and y position to show comparissons and correlations between two attributes among all of the regions. Color could also possibly be added to this using gradients, but that may not convey very well.

![Scatter Sketch](https://github.com/user-attachments/assets/e5a05714-0780-455f-aede-ccc0e8034917)

Thirdly, I have a bubble chart using size, color, x, and y position likely to indicate 3 different attributes along with region using the color.

![Bubble Sketch](https://github.com/user-attachments/assets/52723e2e-5dcc-4edb-a758-60022fc8d796)

## Prototypes

I’ve created a proof of concept visualization of this data. It's what a radar chart might look like with a single country on it. It did reveal to me some concerns about this methodology when trying to accomplish the tasks that I set out to.

[![Radar Viz](https://github.com/user-attachments/assets/8d06447e-08ae-4861-bb00-3a796ded3d07)](https://vizhub.com/chain-mage/radar)

Another proof of concept that I made was this scatterplot comparing two of the indexes across all 193 countries. It also showed me some issues I amy run into with the missing data.

[![Scatter Viz](https://github.com/user-attachments/assets/0beb762b-be9b-49e8-aedc-18e884d23f0d)](https://vizhub.com/chain-mage/gciandcei)


## Open Questions

I have many concerns when it comes to this project, but I'm up to the challenge:

* There is a bit of missing data in the dataset, and I hope to address it while still leaving the information useful.
* If the project is only for one major visualization, I will likely move away from the radar chart idea.
* My goal is to showcase trends among the indexes across regions, and my plan for that is to make a scatter plot using different marks and channels to convey multiple attributes at once. If I allow people to hover over each mark on the scatterplot, they should be able to see all the info, viewing all four indexes at once. I also want to show correlation information for each region between the indexes.

## Milestones

* Week 8: I want to have the dataset completely display on a scatterplot to see how bad the missing data is to decide which indexes I should focus on, as I may have to drop one since I can only think of 3 channels to convey them.
* Week 9: I would like to address my missing data, decide on my marks and channels, and create a legend from there. I would also like to come up with default values for missing data to avoid dropping rows.
* Week 10: Having addressed the issue of missing information, I would like to either aggregate averages among the indexes within regions to create a bubble chart to use the regions or find a way to implement all countries at once, but that is unlikely since we have 193 to work with. 
* Week 11: I would like to implement a mouse follower that would show all indexes when hovering over a country. If the bubble chart is aggregated by regions, then I would have a search bar for a user to input a country, and its information would show up.
* Week 12: Have the bare bones elements and functionality completed, documenting how it address tasks and ensuring feedback is implemented.
* Week 13: Polish visual elements, ensuring clarity in color, size, and marks for the indices, and refine interactions like the mouse follower or search bar for smooth functionality.
* Week 14: Finalize all project features, ensuring everything works smoothly.

# Cyber Index Data Visualization Project

## Updates

For week 10, I have successfully pivoted to a project revolving around salaries regarding the world map. The project now consists of a world map with concentric circles representing the salaries of companies of varying sizes. Currently, you can hover over each bubble to find exact numbers and labels. In the future, for clarity, I would like the map to be able to zoom in by continent to allow for better viewing by also having the bubbles dynamically shrink as it zooms; for example, Europe is very difficult to view and hover over exact countries right now. The countries currently with no data have stripes across them. I also want to add borders around countries while that perspective country's bubble is being hovered over. The plan, for now, is to add a legend in week eleven that will fade out other company sizes while hovering over one size's color and adding more color to the globe. Then for interactivity on week 12, I would like to add the zoom feature per continent. Week 13 will ensure the smoothness of the features and possible messing with font sizes and colors for clarity. I also want to make it so that every bubble being hovered over lists all 3 company sizes and averages per country.

## Week 9 update
[![Week 9](https://github.com/user-attachments/assets/c5ee7758-ead4-45bf-91e7-d5dc5458f711)](https://vizhub.com/chain-mage/week10)
Click on Picture to go to VizHub.



## Milestones
* Week 11: Add interact legend and coloring to globe.
* Week 12: Add a zoom in by continent feature.
* Week 13: Polish visual elements, ensuring clarity in color, size, and zoom per continent.
* Week 14: Finalize all project features, ensuring everything works smoothly.

# Cyber Salaries Data Visualization Project

## Week 10 Updates

For week 10, I have successfully pivoted to a project revolving around salaries regarding the world map. The project now consists of a world map with concentric circles representing the salaries of companies of varying sizes. Currently, you can hover over each bubble to find exact numbers and labels. In the future, for clarity, I would like the map to be able to zoom in by continent to allow for better viewing by also having the bubbles dynamically shrink as it zooms; for example, Europe is very difficult to view and hover over exact countries right now. The countries currently with no data have stripes across them. I also want to add borders around countries while that perspective country's bubble is being hovered over. The plan, for now, is to add a legend in week eleven that will fade out other company sizes while hovering over one size's color and adding more color to the globe. Then for interactivity on week 12, I would like to add the zoom feature per continent. Week 13 will ensure the smoothness of the features and possible messing with font sizes and colors for clarity. I also want to make it so that every bubble being hovered over lists all 3 company sizes and averages per country.

## Current State
[![Week 9](https://github.com/user-attachments/assets/c5ee7758-ead4-45bf-91e7-d5dc5458f711)](https://vizhub.com/chain-mage/week10)
Click on Picture to go to VizHub.



## Milestones
* Week 11: Add interact legend and coloring to globe.
* Week 12: Add a zoom in by continent feature.
* Week 13: Polish visual elements, ensuring clarity in color, size, and zoom per continent.
* Week 14: Finalize all project features, ensuring everything works smoothly.
