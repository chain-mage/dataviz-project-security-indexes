# Cyber Index Data Visualization Project

## Data

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

This visualization project will be valuable for cybersecurity professionals, policymakers, and researchers. For cybersecurity professionals, it helps identify where they would make more money or have more room to negotiate slaries. Policymakers can use the data to assess their country’s investment in cyber security within the private sector. I plan to focus on visualizing the average salaries of cyber positions across the globe for various size companies.

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

[![World Map Viz](https://github.com/user-attachments/assets/8d06447e-08ae-4861-bb00-3a796ded3d07)](https://vizhub.com/chain-mage/radar)

Another proof of concept that I made was this scatterplot comparing salary and the remote ratio.

[![Scatter Viz](https://github.com/user-attachments/assets/0beb762b-be9b-49e8-aedc-18e884d23f0d)](https://vizhub.com/chain-mage/gciandcei)



## Milestones
* Week 10: Having switched to a new data set. I would like to continue using the global map for a heat map of different salaries and create another kind of chart to show the relationship between salaries, job titles, and remote ratios.
* Week 11: I would like to implement a mouse follower that would show specific maps based on salary averages of different size companies and possibly even job titles.
* Week 12: Have the bare bones elements and functionality completed, documenting how it addresses tasks.
* Week 13: Polish visual elements, ensuring clarity in color, size, and possibly as a zoom peature for each country, and refine interactions like the mouse follower or search bar for smooth functionality.
* Week 14: Finalize all project features, ensuring everything works smoothly.
