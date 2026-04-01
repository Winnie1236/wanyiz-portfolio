| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Critique by Design: Natural Disaster Deaths

## Step one: the visualization

Original visualization: [Decadal average: Number of deaths from natural disasters, World(https://ourworldindata.org/natural-disasters)  
Source: Our World in Data, EM-DAT, CRED / UCLouvain (2025)
I selected this chart because it covers a topic that is globally relevant and visually striking. The original chart uses a stacked bar chart with 11 different colors to show annual average disaster deaths by type from 1900 to 2020. I was immediately drawn to it because while the overall downward trend in deaths is clear, the excessive number of colors made it very difficult to understand which types of disasters were driving the changes. I wanted to redesign it to tell a clearer and more specific story about how the nature of disaster deaths has shifted over the past century.

## Step two: the critique
I completed the Stephen Few Data Visualization Effectiveness Profile for this chart. The chart scored well on truthfulness and usefulness, the data is from a reliable source and the overall downward trend is clear. However, 
it scored poorly on perceptibility and intuitiveness. The use of 11 different colors, many of which are visually similar shades of grey and brown, makes it nearly impossible to distinguish individual disaster types within the stacked bars. The chart communicates the total trend effectively but fails to clearly show how the composition of disaster deaths has changed over time. This insight led me to think about redesigning the chart to focus 
on proportions rather than absolute numbers.

## Step three: Sketch a solution
Based on my critique, I decided to move away from showing absolute death numbers and instead focus on the share of deaths by disaster type. I sketched a 100% stacked bar chart that would group minor disaster categories into a single "Other" category, leaving only four groups: Droughts, Floods, Earthquakes, and Other. This would reduce the color count from 11 to 4, making the chart much easier to read. I built an early draft in Tableau to test this approach before finalizing the design.

## Step four: Test the solution

| Question | Interview 1 | Interview 2 |
|----------|-------------|-------------|
|  Is there anything surprising or confusing?        |      The stacking order is confusing, colored categories should be at the bottom       |     The title could more explicitly highlight the decline of droughts and floods        |
|    Is there anything you would change?      |     Move colored categories to the bottom for easier comparison        |    Focus more explicitly on the positive story of progress         |
|          |             |             |

Synthesis: 
Both interviewees understood the main message of the chart. A common pattern was that the stacking order could be improved to make comparisons easier across decades. The second interviewee's suggestion to more explicitly 
highlight the decline of droughts and floods was particularly valuable, as this is the most striking finding in the data. Based on this feedback, I considered reordering the stacked categories and refining the title to more 
clearly communicate the story of human progress in disaster resilience.
## Step five: build the solution
My final redesign is a 100% stacked bar chart built in Tableau Public. Compared to the original, it uses only four color categories, making the composition of disaster deaths easy to read at a glance. The chart clearly 
shows that in the early 20th century, Droughts and Floods dominated disaster deaths, while in recent decades their share has dropped dramatically. This tells a story of human progress in disaster resilience that the original 
chart obscures behind too many colors and categories.
<div class='tableauPlaceholder' id='viz1774931606699' style='position: relative'><noscript><a href='#'><img alt='The Composition of Disaster Deaths Has Shifted Over the Past Century ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Th&#47;TheCompositionofDisasterDeathsHasShiftedOverthePastCentury&#47;Sheet2&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='TheCompositionofDisasterDeathsHasShiftedOverthePastCentury&#47;Sheet2' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Th&#47;TheCompositionofDisasterDeathsHasShiftedOverthePastCentury&#47;Sheet2&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1774931606699');                    
  var vizElement = divElement.getElementsByTagName('object')[0]; 
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>
## References
Our World in Data. "Natural Disasters." 
https://ourworldindata.org/natural-disasters
EM-DAT, CRED / UCLouvain (2025). International Disaster Database.

## AI acknowledgements
No AI tools were used in completing this assignment.

