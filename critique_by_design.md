# Critique By Design

<img
  src="bill-dollar-disaster.jpg"
  alt="Alt text"
  title="Optional title"
  style="display: inline-block; margin: 0 auto; max-width: 700px">


This graph was taken from CNN's website and is headlined "US hits 10th billion-dollar weather disaster of the year - at a record pace." The graph was obtained from the website of the National Centers for Environmental Information (embedded).

## Critique

### First Impression
When I initially looked at the graph, I noticed a lot of colors represented in small forms. The bright bar charts superimposed with colorful lines irritate me. Furthermore, the grid line makes it difficult for me to understand what the graph means. In a nutshell, it's really packed!

### Not a very helpful title
The graph already has a title, but reading it doesn't immediately assist me comprehend the context of the data being displayed. After more inspection, I discovered that this title is the default of the graphic included from the National Centers for Environmental Information website. Because the title is broad and impartial, it is understandable that it does not lead to a story. However, in the context of this news, the headline is not a reader's best buddy.

### What exactly is this legend about?
The legend underneath the title is made up of ten colors/components. I'm a little concerned based on the numbers; it appears that there are too many components for readers to keep track of. Something felt incorrect after I examined each of the components in the legend. The elements in the legend are not comparable variables. What I understand is that there are seven different types of disasters, one component is a composite of the seven different types of disasters, and the remaining two are statistical variables like confidence interval and a five-year average. These legends are then linked to the shapes used in the main section of the visualization, which is a separate issue that I'll go into in more detail later.

At first glance, this legend leads the reader to assume that there are ten different types of disasters to compare, which is not the case because there are only seven. Maybe it's best to separate the location, or if it must stay there at least alter the emblem to something other than square. This emphasizes the discrepancy, because the three additional components are not represented by a bar chart in the visualization section. So, a quick adjustment could be to convert the symbols "combined disaster cost," "cost 95% CI," and "5-year average cost" to lines. However, this is only if the component is to be retained in this graph.

### Overcrowded
Let me recap the major component of the visualization: there are 10 colors represented by 7 color grid diagrams and 3 color lines that are stacked on top of each other. It is also worth noting that the total line is four since the variable confidence interval is divided into two lines, which I discovered after examining more attentively while frowning, indicating how difficult it is to see the components in this graph. The usage of vertical grid lines exacerbates the high number of colors and shapes used. There doesn't seem to be any empty space there, and there seems to be so much going on in that one box that it's difficult to focus on just on or a few.

The number of data points on this graph alone is 'astounding', around 40s. That number is not the main reason I believe this graph is overcrowded, but the 40 plus 7 colors on the bar chart have given me a yellow signal. The good news is that the placement of the seven colors on the bar chart is fairly consistent, with purple (Winter Storm Count) at the top and dark yellow (Drought Count) at the bottom. The yellow signal then become a red alert when determining why there should be a line over the bar charts. There are also four lines of three distinct hues. There are simply too many!

### Context Analysis
What I understand is that the graph contains at least two main contexts, as shown by the presence of two y axes (number of events and cost in billions). In general, the article would like to point out that at the time of writing (mid-2020), the number of billion-dollar disaster events had reached an all-time high. Other graphics in the article can effectively support the narrative, as follows:
<img
  src="1st graph.jpg"
  alt="Alt text"
  title="Optional title"
  style="display: inline-block; margin: 0 auto; max-width: 700px">
  
However, in the following explanation, the article addresses disaster incidents in specific places and shows a graph that I criticize on this occasion. To recapitulate, this graph is meant to detail disaster events by year. If such is the case, the information "number of events" appears to be more essential, whereas "cost in billions" appears to be unnecessary in this visualization. In my upcoming redesign attempts, I will apply that context assumptions.

## Solution Sketch

<div class='tableauPlaceholder' id='viz1663609628770' style='position: relative'><noscript><a href='#'><img alt='The number of severe storms in 2020 is alarming ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Di&#47;Disasater&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Disasater&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Di&#47;Disasater&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1663609628770');                    var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>

Here are the adjustments I'm trying to apply to the previous graph:
> I changed the title, which was previously very general and open to more segmentation, so that readers have an initial idea before looking at the graph.
> Assuming that the relevant context is the alarming number of events in 2020, I omitted the cost information previously represented by the y axis that at the resulted in the use of lines for the statistics (lines) variables.
> For color, I opted to emphasize severe storms, which, based on the trend, are becoming more frequent; even in 2020 data, there are only severe storms. I accent it with a red color that provides the appearance of being alarming. Furthermore, I give the other variables a very soft tint variation so that they do not distract the variables I select to highlight, but still can be identified from one another because I choose to keep the 7 disaster variables on this graph.
> I'm annotating the 2020 data because the CNN article was written in the middle of the year (July), so the author's perspective that I'm attempting to approximate is that while the 2020 total is not greater than 2019, it is only the first half of 2020 and there is a possibility that the numbers will continue to grow in the second half of 2020. The annotation supports this, also for the readers of this graph for the purposes of my current assignment so as not to mistake it for one year 2020 data.
