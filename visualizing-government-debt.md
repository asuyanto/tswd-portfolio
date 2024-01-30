| [home page](https://asuyanto.github.io/tswd-portfolio/) | [visualizing debt](visualizing-government-debt) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |


# Part-1: Web-based Visualization Tools & Data
In this part, I learned to visualize the General Government Debt in 2022 from a web page of The Organization for Economic Co-operation and Development (OECD). I embeded the chart to this page, as follow:

<iframe src="https://data.oecd.org/chart/7khC" width="860" height="645" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/7khC" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 2022</a></iframe>

# Part-2: General Government Debt-to-GDP Ratio using Tableau
In this part, I learned to visualize using Tableau by downloading the same source of the first part. Then, I adjusted the graph into heatmap using Tableau. The color is orange-blue gradient with the center value is 100, so that above 100 ratio of Debt-to-GDP get a variant of orange, else blue. It will give the audience warning feeling while finding countries with >100 ratio. I also did a data cleansing which is deleting Columbia since it has no data. Here is the data viz:

<div class='tableauPlaceholder' id='viz1706382315273' style='position: relative'><noscript><a href='#'><img alt='General Government Debt-to-GDP Ratio(Source: OECD) ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ge&#47;GeneralGovernmentDebt-to-GDPRatio&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='GeneralGovernmentDebt-to-GDPRatio&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ge&#47;GeneralGovernmentDebt-to-GDPRatio&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div> 
<script type='text/javascript'>                    
	var divElement = document.getElementById('viz1706382315273');                    
	var vizElement = divElement.getElementsByTagName('object')[0];                    	vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                 
	var scriptElement = document.createElement('script');                    
	scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    	vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

# Part-3: Another Visualization of Debt-to-GDP Ratio using Tableau
This part is about another visualization with the same data sources of part-2. This graph shows how Debt-to-GDP ratios changed in the top 5 countries over the past 20 years. I omitted periods into 20 to provide a more relevant and complete dataset. Something interesting popped up: Israel's (ISL) numbers behaved quite differently compared to the other four. To make this stand out, Israel is in a different color (red), while the others are in gray. The graph can be utilized for telling another story about historical events in Israel during the specific years, especially when experiencing notable fluctuations. The graph also uses a contextual title which consist of the main idea without redundancy.

<div class='tableauPlaceholder' id='viz1706420323902' style='position: relative'><noscript><a href='#'><img alt='Over the past 20 years, Israel&#39;s Debt-to-GDP ratio exhibited the greatest fluctuation among the top 5 countries with the highest Debt-to-GDP ratios. ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ge&#47;GeneralGovernmentDebt-to-GDPRatio&#47;Sheet2&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='GeneralGovernmentDebt-to-GDPRatio&#47;Sheet2' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ge&#47;GeneralGovernmentDebt-to-GDPRatio&#47;Sheet2&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
	var divElement = document.getElementById('viz1706420323902');                    
	var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                   
	var scriptElement = document.createElement('script');                    
	scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

# Methods of Visualization
## 1. Bar Chart
<img src="https://github.com/asuyanto/tswd-portfolio/blob/main/Bar%20Graph%20Example.png" alt="BarChart">
Purpose: Visualizes and compares discrete categories with their corresponding measured values.
Use Cases: Suitable for displaying and comparing individual values or trends within distinct categories.
Importance of Knowing:
Helps in presenting straightforward comparisons.
User-friendly for simple data sets.
Limitations in handling complex datasets and numerous categories.
## 2. Histogram
<img src="https://github.com/asuyanto/tswd-portfolio/blob/main/Histogram%20Example.png" alt="Histogram">
Purpose: Illustrates the distribution of data across a continuous interval or defined period.
Use Cases: Ideal for identifying concentration, gaps, or unusual values within a dataset.
Importance of Knowing:
Provides insights into data distribution and frequency.
Valuable for detecting patterns and outliers.
For example: Highlights peak and off-peak days by showcasing daily website clicks over a week.

Knowing when to use each visualization method is essential for effectively conveying insights from the data. Bar charts are suitable for categorical comparisons, while histograms are in revealing patterns and distributions within continuous datasets. We need to choose the appropriate visualization methods according to specific data analysis needs.

(Source: https://online.hbs.edu/blog/post/data-visualization-techniques)
