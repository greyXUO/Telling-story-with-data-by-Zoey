## Assignment 1: Visualizeing Government Debt
# OECD data
<iframe src="https://data.oecd.org/chart/7eXB" width="860" height="645" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/7eXB" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 2018</a></iframe>


This visualization is easy to read and interact with. When you move the cursor over a bar, it displays the corresponding country and the debt-to-GDP value as a percentage. The bars are sorted by the percentage value, allowing the audience to quickly identify which country has the highest or lowest debt compared to its GDP. The use of highlighted colors makes it easier to locate the country names, which are positioned at the bottom of the graph. 

However, it contains limited information as it only represents the debt rate in 2018.

# Heat map version
<div class='tableauPlaceholder' id='viz1699239475009' style='position: relative'><noscript><a href='#'><img alt='General Government Debt   (Total, % of GDP, 1995-2022)source: https:&#47;&#47;www.oecd.org&#47; ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;oe&#47;oecd_16992394629770&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='oecd_16992394629770&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;oe&#47;oecd_16992394629770&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-GB' /><param name='filter' value='publish=yes' /></object></div>
<script type='text/javascript'>
  var divElement = document.getElementById('viz1699239475009');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>


The heat map contains a much larger dataset than the bar chart, spanning from 1995 to 2022. Different background colors are employed to represent various values within the blocks. We've also implemented sorting, using the average value for each country. For instance, Japan and Greece exhibit the highest debt ratios, indicated by deep orange colors, signifying significantly higher ratios compared to other data points. 

When scrolling down, we can easily scan and compare countries by their colors. Additionally, we can examine the data for each year. To observe trends in the ratio changes, we can scroll to the right and observe shifts in colors. 

In a word, I appreciate this visualization as it functions effectively in both macro and micro perspectives, accommodating a vast amount of data.

# Boxplot version

<div class='tableauPlaceholder' id='viz1699243674692' style='position: relative'><noscript><a href='#'><img alt='General Government Debt   (Total, % of GDP, 1995-2022)source: https:&#47;&#47;www.oecd.org&#47; ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;oe&#47;oecd2_16992417012690&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='oecd2_16992417012690&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;oe&#47;oecd2_16992417012690&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-GB' /><param name='filter' value='publish=yes' /></object></div>
<script type='text/javascript'>
  var divElement = document.getElementById('viz1699243674692');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

Although the heat map did a good job of facilitating comparisons among countries, it was challenging to determine the extent of the increase in the debt-to-GDP ratio. We could only discern whether it was increasing or decreasing, but not by how much.

To address this issue, I opted to use a box plot to provide a broader view of the global trend while retaining the data points for each country. A box plot can convey four values for each data group: the minimum and maximum values (excluding outliers), the first quartile, the median, and the third quartile. This allows us to gain a statistical understanding of the ratio for all countries quickly.

In the box plot, each box represents the data for all countries in a given year. It's evident that the boxes have been increasing in height since 2010, indicating a global increase in debt. The debt ratio reached its peak in 2020 and subsequently returned to previous levels. This trend was not as noticeable in the heatmap, as both light blue and deep blue are represented in shades of blue.

Regarding the choice of color, I prefer gray, as it draws less attention and works well with large datasets. We don't want the visualization to be overwhelmed with colorful boxes. Blue was selected for a calm and professional style, given that this is official data.
