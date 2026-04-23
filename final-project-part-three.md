| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# The final data story

[Why Your SD Card Got So Expensive](https://carnegiemellon.shorthandstories.com/why-your-sd-card-got-so-expensive/index.html)

# Changes made since Part II

Since completing Part II, I made several significant changes to the story based on user research feedback and in-class critique. 
The most substantial addition was a new section titled "What you can do about it," which provides three practical tips for everyday consumers navigating elevated storage prices. This directly addressed feedback from both my user interviews and my instructor, who noted that the story needed to give the audience something actionable rather than simply explaining the problem.

I also added three full-screen "Text Over Media" sections as visual transitions between the main narrative sections. These include a section highlighting that NAND flash prices rose by over 100% in six months, a section noting that major tech companies spent over $400 billion on AI infrastructure in a single year, and a transition into the consumer advice section. These additions gave the story a stronger visual rhythm and made the key data points more memorable.

I replaced the original cover image with a close-up photograph of a circuit board, which better communicates the technical subject matter at first glance. I also added a navigation bar so readers can jump between sections easily, and added a References section at the end of the story.

## The audience

The intended audience for this project is everyday consumers aged 18 to 35 who buy electronic devices and storage products and have noticed price increases without understanding the underlying reasons. This includes students, casual gamers, photographers, and general tech users.

Insights from my three user interviews helped sharpen this focus. The non-tech major interviewee found the "Price Index" label abstract and suggested using a concrete product example instead. The STEM major wanted clearer sourcing on the capacity allocation figures. The business/policy major suggested adding key event annotations to the charts. These insights confirmed that the primary audience needed more relatable entry points 
into the data, which led to the addition of the consumer advice section and the large-format callout statistics.

I deliberately kept the technical language minimal throughout the story. Terms like "NAND flash memory" and "fab capacity" 
are introduced with plain-language explanations so that readers without a hardware background can follow along. The story is 
structured to move from a personal observation anyone can relate to — noticing that something got more expensive — through the supply chain explanation, and finally to practical advice the reader can act on.

## Final design decisions

The most important design decision was choosing to use alternating Text Over Media and Text sections throughout the story. The full-screen image sections create visual impact and serve as chapter markers, while the plain text sections provide space for the charts and detailed explanation. This structure was inspired by examples shared in class and helped avoid the problem of the story feeling like a wall of text.

For the data visualizations, I used Tableau Public for both charts. The price index chart uses a bar chart rather than a line chart because Tableau required a date-formatted field for continuous line charts, and the quarterly labels I used were recognized as text. While a line chart would have been ideal for showing a continuous trend, the bar chart still clearly communicates the directional story: prices fell, then surged.

The capacity allocation chart ended up as a stacked area chart, which I found more visually effective than a grouped bar chart for showing how the proportions shifted over time. The two colors — blue for consumer, teal for AI enterprise — contrast clearly without being distracting.

One thing I learned through this process is that finding reliable, publicly downloadable data for niche industry topics is genuinely difficult. Most memory market data sits behind paywalls. Reconstructing data from published reports is a legitimate approach, but it requires careful documentation of methodology, which I included in the References section of the Shorthand story.

## References

All references are included in the References section of the final Shorthand story. No additional sources were used specifically for this writeup.

## AI acknowledgements

Claude (Anthropic) was used throughout this project to help identify publicly accessible data sources, reconstruct data tables from industry reports,and structure the Shorthand story. 
All final content decisions, design choices, and the overall story direction were my own.

# Final thoughts
This project started from a personal frustration: noticing that my Switch SD card had gotten significantly more expensive. I was not sure at first whether that observation could carry an entire data story, but working through the research convinced me it could. What I am most proud of is the overall narrative arc, moving from something relatable through an unexpected explanation and ending with practical advice for the reader.

If I had more time, I would have focused on finding better data. The reconstructed figures tell the right story directionally, but I would have liked to track a specific product's actual retail price over time to make the story feel more concrete. I also wish I had more time to refine the Tableau charts, particularly resolving the line chart formatting issue I ran into with date recognition.


