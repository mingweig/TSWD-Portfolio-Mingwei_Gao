| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [visualizing debt](visualizing-government-debt) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Average holiday Spending by Americans

## Data Source: Exploding Topics

Links:[URL](https://explodingtopics.com/blog/christmas-spending-stats)


Original Graphic:

![image](https://github.com/mingweig/TSWD-Portfolio-Mingwei_Gao/assets/122922442/4f44d43c-1483-4a95-8f4b-aab732fc95e0)

## Critique the data visualization

The bar chart's strength lies in its simplicity and clarity. It effectively communicates the trend of personal Christmas gift spending over a range of years. The uniform color scheme and clear labels contribute to its readability. However, the chart could be improved by adding more context. For instance, including data on average spending per capita or relative to income would give a more comprehensive view of spending habits. Additionally, while the blue bars are visually distinct, using different colors or additional visual elements might help to make the chart more engaging and highlight specific years or trends. It would also be beneficial to include some annotations to explain significant peaks or dips in spending, which could provide insights into consumer behavior or economic conditions influencing these changes.

Moreover, using tableau we can add interactivity such as hover-over details for each bar could enhance the engagement and provide more detailed information without cluttering the initial view. This way, the visualization could cater to both a glance and a more in-depth analysis for those who are interested.

The primary audience for this visualization could be individuals or businesses interested in consumer spending habits, particularly related to personal Christmas gift spending. This could include retailers, marketers, economists, or even consumers themselves who are curious about spending trends during the holiday season.

The bar chart provides a clear, year-by-year breakdown of spending, which makes it effective for quickly conveying the overall trend of increasing or decreasing expenditure. However, the raw data table suggests a richer dataset that includes categories of spending, which the bar chart does not currently reflect.

I believe the visualization could be improved to be more effective for its audience. While it effectively shows a general trend, it lacks the specificity that could be beneficial for decision-making. For instance, retailers and marketers might benefit from understanding the proportions of spending on family, friends, coworkers, and others to tailor their marketing strategies or decisions accordingly.

To enhance its effectiveness, the visualization could incorporate a stacked bar chart to include the breakdown of spending by category, as indicated in the raw data table. This would provide a more nuanced view of spending habits. While the existing chart is a good start, I think incorporating these additional elements would create a more comprehensive tool that better serves the needs of an audience looking to understand and make decisions based on Christmas spending habits.

The method of evaluating the data visualization based on criteria like usefulness, completeness, perceptibility, truthfulness, intuitiveness, aesthetics, and engagement is quite comprehensive. 

However, there could be additional measures that might enhance the evaluation.

For example, Contextual Relevance: There could be a measure for how well the visualization provides context for the data. For instance, does it compare the personal spending on Christmas gifts to overall personal spending, or does it account for economic conditions like inflation? This could give the audience a more in-depth understanding of the data.
Data Density and Scalability: Another measure could be how well the visualization balances data density with readability. Does it manage to display a large amount of data without becoming cluttered? And is it scalable if more data points need to be added in the future?

I would change this graphic mainly in these two parts:
Color. I think utilizing a color scheme that differentiates between types of spending (family, friends, coworkers, others) would make the data more accessible and allow for quicker insights at a glance. 

In addition, Type of Visualization. Transitioning to a stacked bar chart or a multi-series line chart could provide a clearer picture of spending trends over time and by category. Moreover, an interactive component such as tooltips or a drill-down feature could enhance user engagement, allowing viewers to explore the data more deeply.

## Sketch out a Solution

I opted for this new design to streamline the visual narrative of Christmas gift spending over two decades. The original bar chart, while clear, didn't quite capture the dynamic nature of the spending trends. By transitioning to a line chart, I can illustrate the ebbs and flows of expenditures more fluidly, which paints a more nuanced picture of year-over-year changes.

Moreover, I've layered the sum of all gifts as a bold, prominent line, which stands out against the individual spending categories. This approach immediately draws the viewer's attention to the overall trend first, before diving into the specifics. 

The stacked bar chart underneath serves a complementary role. It provides a clear, segmented view of each category's contribution to the total, enhancing the understanding of how each segment has driven the total expenditure. The line chart introduces the trend, and the stacked bar chart breaks down the components. This layered approach caters to a more comprehensive analysis without overwhelming the audience.

<div class='tableauPlaceholder' id='viz1700069477245' style='position: relative'><noscript><a href='#'><img alt='Dashboard 1 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;A3&#47;A3A4&#47;Dashboard1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='A3A4&#47;Dashboard1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;A3&#47;A3A4&#47;Dashboard1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
var divElement = document.getElementById('viz1700069477245');                    
var vizElement = divElement.getElementsByTagName('object')[0];                    
if ( divElement.offsetWidth > 800 ) { vizElement.style.width='1000px';vizElement.style.height='827px';} 
else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='1000px';vizElement.style.height='827px';} 
else { vizElement.style.width='100%';vizElement.style.height='777px';}                     
var scriptElement = document.createElement('script');                    
scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

## Test the solution

### Interviewee 1: Student, early 20's

Based on our conversation, it's clear that we're looking at a detailed breakdown of Christmas gift spending over a series of years. It's quite telling that family gifts are where the majority of the money goes, while coworkers seem to receive the least – it shows where our priorities lie during the festive season.

However, there's an area that could use some tweaking. The color used to represent the total sum of all categories is a little too similar to the others. This could be misleading or at least a bit hard to discern at first glance, especially for the busy eyes of store owners and marketers who rely on such data to make quick decisions.

The intended audience, being those who are deeply involved in sales and marketing strategies, would benefit from a visualization that's more direct and less cluttered. Simplifying the chart by focusing on just one type of graph would enhance readability. Also, using a more distinctive color or perhaps even a different line style for the total spending would make the information stand out better and be instantly recognizable.

She recommends I stick to either the line chart or the stacked bar chart, not both. If we go with the line chart, let's make sure the total spending line is in a bold color like a bright blue or red, and clearly distinct from the category-specific lines. For the stacked bar chart, we could highlight the total spending as a separate bar or use a different pattern or shading to distinguish it from individual categories.

By making these changes, the graph will not only be more visually appealing but also more practical and effective for its intended audience.

### Interviewee 2: Student, mid 20's

The visual we have here is a depiction of gift expenditures over a selected timeline. It's intriguing to observe that gifts for family members significantly surpass those for friends or coworkers, underscoring the familial emphasis during the holiday season. The gradual increase in the total spending through the years is also noteworthy, suggesting a consistent upward trend in the generosity or perhaps in the commercialization of the season.

However, it's somewhat surprising to see such a dominant skew towards family gifts. This might suggest a cultural trend or a data peculiarity worth exploring further.

The visualization seems tailored for a diverse audience. Christmas gift manufacturers could use this data to forecast demand, the general public might find the spending patterns interesting, and business owners could leverage this information for inventory management of various gift categories.

Taking the suggestions into account, He advocates for a revamp of the visual to enhance its interpretability and aesthetic appeal. This could involve:

Adjusting the bar chart to display averages in ascending order, providing a more logical progression from the least to the most spent.
Modifying the color scheme for the total expenditure to a standout hue, one that isn't merely a shade different but rather a completely new color that captures immediate attention.

Clarifying the legend by distinguishing the total expenditure from the individual categories, which could mean separating it spatially or using a unique design element like a border or pattern.

## Build New Solution:

The new design trying to address some key points of feedback:

Total Expenditure Line Clarity: The sum of all gifts is now represented by a bold grey line, which i changed from the previous design where it might have blended with the other categories. 

Stacked Bar Chart Adjustments: The stacked bar chart seems unchanged at first glance. But I do make the sum in the background in light grey and rearrange the bars from minimum to maximum spending.

Color Choices: This choice to use grey is because it doesn't compete with the other colors for attention yet provides a clear demarcation of the overall trend. Removing the sum from the categories in the legend also helps to simplify the visualization, making it easier for viewers to distinguish between the total spending and the individual categories.

The new design is centered around enhancing readability and ensuring that key data points, like the total expenditure, stand out. The bold black line serves this purpose well, drawing immediate attention and making it easier for the viewer to understand the overall spending trend, ensuring that the key message is  apparent to viewers. 

<div class='tableauPlaceholder' id='viz1700080830060' style='position: relative'><noscript><a href='#'><img alt='Dashboard 1 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;A3&#47;A3A4Refine&#47;Dashboard1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='A3A4Refine&#47;Dashboard1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;A3&#47;A3A4Refine&#47;Dashboard1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>                
<script type='text/javascript'>                    
var divElement = document.getElementById('viz1700080830060');                    
var vizElement = divElement.getElementsByTagName('object')[0];                    
if ( divElement.offsetWidth > 800 ) { vizElement.style.width='1000px';vizElement.style.height='827px';} 
else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='1000px';vizElement.style.height='827px';} 
else { vizElement.style.width='100%';vizElement.style.height='877px';}                     
var scriptElement = document.createElement('script');                    
scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>
