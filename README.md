# Cyber Index Data Visualization Project

## Data

For week 9, I have taken a hard pivot from my previous data set, due to incomplete data. I've shifted to a new data set on global Cyber Security salaries, which can also be found on[Kaggle](https://www.kaggle.com/datasets/deepcontractor/cyber-security-salaries). It contains the following attributes for each country:

* Cybersecurity Exposure Index (CEI): Measures a country's exposure to cybersecurity risks.
* Global Cyber Security Index (GCI): Ranks countries based on their cybersecurity commitment on a global scale.
* National Cyber Security Index (NCSI): Reflects national capacity to handle cyber threats.
* Digital Development Level (DDL): Indicates the level of digital development and technology penetration.
* Country: The name or code of the country.
* Region: The geographical region the country belongs to.

This visualization project will be valuable for cybersecurity professionals, policymakers, and researchers. For cybersecurity professionals, it helps identify where they would make more money or have more room to negotiate slaries. Policymakers can use the data to assess their country’s investment in cyber security within the private sector. I plan to focus on visualizing the average salaries of cyber positions across the globe for various size companies.

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

I’ve created a proof of concept visualization of this data. It's a global heatmap to showcase the average salary in each nation where we have data.

[![World Map Viz](https://github.com/user-attachments/assets/8d06447e-08ae-4861-bb00-3a796ded3d07)](https://vizhub.com/chain-mage/radar)

Another proof of concept that I made was this scatterplot comparing salary and the remote ratio.

[![Scatter Viz](https://github.com/user-attachments/assets/0beb762b-be9b-49e8-aedc-18e884d23f0d)](https://vizhub.com/chain-mage/gciandcei)



## Milestones

* Week 8: I want to have the dataset completely display on a scatterplot to see how bad the missing data is to decide which indexes I should focus on, as I may have to drop one since I can only think of 3 channels to convey them.
* Week 9: I would like to address my missing data, decide on my marks and channels, and create a legend from there. I would also like to come up with default values for missing data to avoid dropping rows.
* Week 10: Having addressed the issue of missing information, I would like to either aggregate averages among the indexes within regions to create a bubble chart to use the regions or find a way to implement all countries at once, but that is unlikely since we have 193 to work with. 
* Week 11: I would like to implement a mouse follower that would show all indexes when hovering over a country. If the bubble chart is aggregated by regions, then I would have a search bar for a user to input a country, and its information would show up.
* Week 12: Have the bare bones elements and functionality completed, documenting how it address tasks and ensuring feedback is implemented.
* Week 13: Polish visual elements, ensuring clarity in color, size, and marks for the indices, and refine interactions like the mouse follower or search bar for smooth functionality.
* Week 14: Finalize all project features, ensuring everything works smoothly.
