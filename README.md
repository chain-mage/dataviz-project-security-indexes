# Data Visualization Project

## Data

The data I propose to visualize for my project is from Kaggle and is called Cyber Security Indexes. It consists of various cybersecurity and digital development indices that measure different aspects of a country’s cybersecurity posture. This dataset includes attributes from sources like the International Telecommunication Union (ITU) and the e-Governance Academy Foundation, among others. It contains the following attributes for each country:

* Cybersecurity Exposure Index (CEI): Measures a country's exposure to cybersecurity risks.
* Global Cyber Security Index (GCI): Ranks countries based on their cybersecurity commitment on a global scale.
* National Cyber Security Index (NCSI): Reflects national capacity to handle cyber threats.
* Digital Development Level (DDL): Indicates the level of digital development and technology penetration.
* Country: The name or code of the country.
* Region: The geographical region the country belongs to.

This visualization project will be valuable valuable for cybersecurity professionals, policy makers, and researchers. For cybersecurity professionals, it helps identify high-risk areas and countries with strong or weak cybersecurity preparedness. Policy makers can use the data to assess their country’s performance and allocate resources to areas that need improvement. Researchers can analyze global trends and the relationship between digital development and cybersecurity preparedness. I plan to focus on visualizing the comparison of all four indexes across two different countries. So far, I planned to use a radar chart to allow comparisons between the two countries. However, I would like to do multiple visualizations to be able to show case trends among all countries, not just two.  I will likely move away from the idea of a radar chart entirely to better showcase the trends between the indexes on a much more global scale and across multiple regions. It's important to visually see as many different trends using many channels.


## Questions & Tasks

The following tasks and questions will drive the visualization and interaction decisions for this project:

* How do different regions compare in terms of their Cybersecurity Exposure Index (CEI), Global Cyber Security Index (GCI), and National Cyber Security Index (NCSI)?

* What is the relationship between a region’s Digital Development Level (DDL) and its cybersecurity indices?

* Are there any regions where high cybersecurity risks (CEI) are accompanied by strong national policies (NCSI)?

* Are the different regional correlations among the indexes?

* Can we identify outlier regions where the cybersecurity indices (CEI, GCI, NCSI) do not follow global trends?

* Which regions have a particularly high National Cyber Security Index (NCSI) compared to the Global Cyber Security Index (GCI)?

## Sketches

(insert one or more hand-drawn sketches of interactive visualizations that you imagine)
(describe each sketch - how is the data visualized, what are the interactions, and how do these relate to the questions/tasks)

I've created and modified two different sketches. The first a radar chart as an example allowing users to compare two different countries indexes. The two quadrilaterals would be overlayed one another and be two different colors. This would allow us to make direct comparisons between countries.

#image

The second is a scaterplot using marker, x position, and y position to show comparissons and correlations between two attributes among all of the regions. Color could also possibly be added to this using gradients, but that may not convey very well.

#image

Thirdly, I have a bubble chart using size, color, x, and y position likely to indicate 3 different attributes along with region using the color.

#image


## Prototypes

I’ve created a proof of concept visualization of this data. It's what a radar chart might look like with a single country on it. It did reveal to me some concerns about this methodology when trying to accomplish the tasks that I set out to.

Another proof of concept that I made was this scatterplot comparing two of the indexes across all 193 countries. It also showed me some issues I amy run into with the missing data.

[![image](https://user-images.githubusercontent.com/68416/65240758-9ef6c980-daff-11e9-9ffa-e35fc62683d2.png)](https://vizhub.com/curran/eab039ad1765433cb51aad167d9deae4)

(please put a screenshot of one or more visualizations of this dataset you already made, for previous assignments, and link to them)

You can put images into here by pasting them into issues.

You can make images into links like this:

```
[![image](https://user-images.githubusercontent.com/68416/65240758-9ef6c980-daff-11e9-9ffa-e35fc62683d2.png)](https://vizhub.com/curran/eab039ad1765433cb51aad167d9deae4)
```


Also, you can study the [source](https://raw.githubusercontent.com/curran/dataviz-project-template-proposal/master/README.md) to figure out Markdown formatting. You can use the GitHub built-in editor to edit the document.

## Open Questions

I have many concerns when it comes to this project, but I'm up to the challenge:

* There is a bit of missing data in the dataset and I hope to address while still leaving the information useful.
* If the project is only for one major visualization, I will likely move away the radar chart idea.
* My goal is showcase trends and among the indexes across regions and my plan for that is to make a scatter plot using different marks and channels to convey multiple attributes at once. If I allow people to hover over each mark on the scatterplot, they should be able to see all info, possible viewing all four indexes at once. I also want to show correlation information for each region between the indexes.

## Milestones

(for each week, estimate what would be accomplised)

* Week 8: I want to have the dataset completely display on a scatterplot to see how bad the missing data is to decide which indexes I should focus on, as I may have to drop one since I can only think of 3 channels to convey them.
* Week 9: I would like to address my missing data, make a decision on my marks and channels, and creat a legend from there. The also come up with default values for missing data as I would like to avoid dropping rows.
* Week 10: Having addressed the issue of missing information, I would like to either aggregate averages among the indexes within regions to create a bubble chart to using the regions or find a way to implement all countries at once, but that in unlikely since we have 193 to work with. 
* Week 11: I would like to implement a mouse followe that would show all indexes when hovering over a country. If the bubble charted is aggregated by regions, then I would have a search bar for a user to input a country, and it's information would show up.
* Week 12: Have the bare bones elements and functionality completed, documenting how it address tasks and ensuring feedback is implemented.
* Week 13: Polish visual elements, ensuring clarity in color, size, and marks for the indices, Refine interactions like the mouse follower or search bar for smooth functionality.
* Week 14: Finalize all project features, ensuring everything works smoothly.
