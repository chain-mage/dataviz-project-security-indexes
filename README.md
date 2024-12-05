# Cyber Index Data Visualization Project

## Week 8

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

* Week 9: I would like to address my missing data, decide on my marks and channels, and create a legend from there. I would also like to come up with default values for missing data to avoid dropping rows.
* Week 10: Having addressed the issue of missing information, I would like to either aggregate averages among the indexes within regions to create a bubble chart to use the regions or find a way to implement all countries at once, but that is unlikely since we have 193 to work with. 
* Week 11: I would like to implement a mouse follower that would show all indexes when hovering over a country. If the bubble chart is aggregated by regions, then I would have a search bar for a user to input a country, and its information would show up.
* Week 12: Have the bare bones elements and functionality completed, documenting how it address tasks and ensuring feedback is implemented.
* Week 13: Polish visual elements, ensuring clarity in color, size, and marks for the indices, and refine interactions like the mouse follower or search bar for smooth functionality.
* Week 14: Finalize all project features, ensuring everything works smoothly.


## Week 9 Updates

For week 9, I have taken a hard pivot from my previous data set, due to incomplete data. I've shifted to a new data set on global Cyber Security salaries, which can also be found on [Kaggle](https://www.kaggle.com/datasets/deepcontractor/cyber-security-salaries). It contains the following attributes for each job and position:

* work_year: The year the salary data corresponds to.
* experience_level: The level of experience of the employee.
* employment_type: The type of employmentFull-Time, Part-Time, etc.
* job_title: The specific title of the job.
* salary: The salary amount as reported in the currency of the respective job.
* salary_currency: The currency in which the salary is reported.
* salary_in_usd: The salary amount converted to USD for standardization.
* employee_residence: The country where the employee resides.
* remote_ratio: The percentage of the job done remotely. 0% for fully on-site, 100% for fully remote.
* company_location: The country where the company is headquartered.
* company_size: The size of the company, Small (S), Medium (M), or Large (L).

This visualization project will be valuable for cybersecurity professionals, policymakers, and researchers. For cybersecurity professionals, it helps identify where they would make more money or have more room to negotiate slaries. Policymakers can use the data to assess their country’s investment in cyber security within the private sector. I plan to focus on visualizing the average salaries of cyber positions across the globe for various size companies. I will likely make a global map with bubbles to show salaries for various countries and company sizes.

## Questions & Tasks

* The following tasks and questions will drive the visualization and interaction decisions for this project:

* How do salaries compare across different employee residence countries and company locations?

* How do salaries vary across companies of different sizes (Small, Medium, Large)?

* Are there any job titles, experience levels, or geographic regions with particularly high salaries that stand out as outliers?

* Do certain job titles or sectors within the cybersecurity domain consistently pay more?

* Are there significant correlations between factors such as experience level, remote work, and salary?

## Sketches

The sketches that I created for the previous data set are still apliccable, but withe different labels of course. TFor example the radar chart would allow us to make comparisons of remote work, experience level, and salary, and employment type (eployment type ranging from contract/part-time/fulltime) between different job titles and positons.

![Radar Sketch](https://github.com/user-attachments/assets/dbd36f86-1eae-4454-bb65-fb675148283b)

This scatterplot uses marker shape, x-position, and y-position to explore the relationship between remote work percentage (remote_ratio) and salaries. Marker shapes could specify specific job title or countries.

![Scatter Sketch](https://github.com/user-attachments/assets/e5a05714-0780-455f-aede-ccc0e8034917)

The bubble chart could be modified in the following ways. This bubble chart could use x-position, y-position, bubble size, and color to compare job titles. The x-axis could represent average salaries, the y-axis the percentage of remote work, and bubble size the frequency of that job title in the dataset. Each bubble color could represent company size (Small/Medium/Large).

![Bubble Sketch](https://github.com/user-attachments/assets/52723e2e-5dcc-4edb-a758-60022fc8d796)

## Prototypes

I’ve created a proof of concept visualization of this data. It's a global heatmap to showcase the average salary in each nation where we have data.

[![Map Viz](https://github.com/user-attachments/assets/beda53d8-7bbf-404f-8b39-bc9326d543cb)](https://vizhub.com/chain-mage/map).

Another proof of concept that I made was this scatterplot comparing salary and the remote ratio.

[![Scatter Viz 2](https://github.com/user-attachments/assets/432f93e3-61a7-4d79-bd67-3b624fe1a539)](https://vizhub.com/chain-mage/remotetosalary).



## Milestones
* Week 10: Having switched to a new data set. I would like to continue using the global map for a heat map of different salaries and create another kind of chart to show the relationship between salaries, job titles, and remote ratios. I will likely make a global map with bubbles to show salaries for various countries, company sizes.
* Week 11: I would like to implement a mouse follower that would show specific maps based on salary averages of different size companies and possibly even job titles.
* Week 12: Have the bare bones elements and functionality completed, documenting how it addresses tasks.
* Week 13: Polish visual elements, ensuring clarity in color, size, and possibly as a zoom peature for each country, and refine interactions like the mouse follower or search bar for smooth functionality.
* Week 14: Finalize all project features, ensuring everything works smoothly.


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

## Week 11 Updates

For week 11, I have pivoted to a globe that can be rotated by clicking and dragging with the window. I've also added a legend that you can hover over to get rid of all bubbles except the ones that are the color that is being hovered over in the legend. Working with a globe has certainly come with some unexpected challenges. For example, when rotating the globe, the bubbles of the countries that are no longer visible remain visible. I believe I'll have to address this using the z coordinate plane and toggling their visibility that way. Additionally, I noticed that the bubbles are not all visible as some obstuct other even if representing the same country. I also need to make it so the bubbles are not present at all if the average salary is zero. My milestones have certainly changed, and I imagine there will be difficulty implenting a zoom feature later on, but I will try.

## Current State

[![Viz Globe](https://github.com/user-attachments/assets/b00c60c3-2c33-471b-a6e2-89eac1d455e4)](https://vizhub.com/chain-mage/week11) 



Click on Picture to go to VizHub.



## Milestones
* Week 12: Fix bubbles on the globe to only be visible when facing the front and to not obscure one another.
* Week 13: Polish visual elements, ensuring clarity in color, size, and zoom.
* Week 14: Finalize all project features, ensuring everything works smoothly.

## Week 12 Updates

For week 12, I made a significant amount of progress to make this a scalabe and interactive visualization. I made the visualization responve and will now adjust without be set to a specific size. This can be tested by adjusting the siz of your browser window on the VizHub page. Now we can zoom in and out for more visibility. Making the bubble sizes inversly proportional to the amount of zoom applied to the visualization, allows the to scale. Making them smaller, the more you zoom in and vice versa. Which means now we can see areas like europe much better by Zooming in. I also offset the bubbles for each country, so that they are not cocentric and we can see them all clearly. Now that we can zoom in, I also placed the legend in a white box in the top right corner of the screen. Additionally, information no longer appears on the cursor when hovering over a bubble, the information will now appear in an information box in the bottom right corner. I do plan to polish things up a bit. Definitely plan on adding a box in the legend with no-data-strips to let the viewer no, the stripes mean no data. I may also add some code so the area around the globe appears to be in space, making the SVG color black.

## Current State


[![Viz Globe 2](https://github.com/user-attachments/assets/0d6bbf3e-ba04-4be4-a11c-19eff17e3936)](https://vizhub.com/chain-mage/week12)



Click on Picture to go to VizHub.



## Next Milestones
* Week 13: Polish visual elements, ensuring clarity in color, size, and zoom.
* Week 14: Finalize all project features, report, and ensuring everything works smoothly.


## Week 13 Updates

For week 13, I really wanted to polish up the visual elements of the project. I added a a space background with stars that shift around as the globe is being rotated. I also added a title box and ensured that every thing was responsive and would still function if the window size was adjusted. I also added a colorbox to represent the no-data stripes in the legeng and made the information box in the bottom left more neat and concise when hovering over a bubble. The numbers are now clear, everything is a little more polished, and although I may make a few more adjustments in the future as I interact with the map a little more. The visualization appears to be finished.

## Current State


[![Globe Viz 3](https://github.com/user-attachments/assets/924504b9-9035-4f15-a709-fcab169d153b)](https://vizhub.com/chain-mage/week13)



Click on Picture to go to VizHub.



## Next Milestones
* Week 14: Finalize all project features, report, and ensuring everything works smoothly.

## Week 14 Updates

For Week 14, I really wanted to showcase what this kind of visualization was capable of showing. I felt like I really needed a more complete dataset. So, I took some UN information one male and female populations of earth by country catagorized by select age groups. Then I wittled down the information to strictly being years, population of women, population of men, population of children, and country. Then with a CSV to JSON converter, I created JSON data to use in this visualization and altered my code to work with this new dataset. I also added 2 sliders to the visualization to adjust the offset and the year being represented on the globe. This is really the culmination of what I set out to do with this project. I've listed the features below.

Features:

* Hover over country bubbles to display detailed values and labels.
* Rotate the globe by left-clicking and dragging.
* Zoom in and out to explore clustered areas more closely.
* An information box dynamically updates with country-specific data for country last hovered over.
* A color-coded legend represents different data categories.
* A title box for the visualization.
* The background features a space theme

## Current State


[![Final](https://github.com/user-attachments/assets/9a849772-2e3e-4593-b7cf-c410d60eb3ff)](https://vizhub.com/chain-mage/country-population)



Click on Picture to go to VizHub.

## Future Work

Over the course of this project, I had some longstanding goals that I figured I would leave for future work just due to time constraints.

* Different channels for population information (Pie charts, bar graphs, histograms) to populate information box.
* Give option for pie charts instead of bubbles on the globe.
* Create a more accurate drawing of the globe and graticules to represent every UN region.
* Provide the ability to search by country in a search bar.
* Create a method to lock in two countries to compare them and their populations.
* Add additional metrics (such as happiness index, CO2 Emissions, and GDP) and see if they correlate in anyway to populations.
