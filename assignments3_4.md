# Assignment 3&4: Critique By Design
\
**Step 1: Find a data visualization you can improve**
\
\
The below chart is from the Pew Research Center. It details climate change opinions at the national scale. At first glance, a few issues are immediately obvious to me: the title isn't informattive/narrative enough, the data does not look to be organized in any particular way, and the colors are dull. Though this visualization is not terrible, it can definitely be improved.
\
\
<a href="https://www.pewresearch.org/global/2015/11/05/2-public-support-for-action-on-climate-change/climate-change-report-41/"><img src="https://www.pewresearch.org/global/wp-content/uploads/sites/2/2015/11/Climate-Change-Report-41.png?w=309"></a>

\
\
**Step 2: Critique the Data Visualization**
\
\
Using Stephen Few's [Data Visualization Effectiveness Profile](http://www.perceptualedge.com/articles/visual_business_intelligence/data_visualization_effectiveness_profile.pdf) as a guideline, the next step in this critique involves focusing on specific visualization aspects and identifying areas of improvement. The following survey demonstrates this analytical process.
\
\
![image](https://user-images.githubusercontent.com/123282392/217146077-e1cf90c3-50d5-428e-8656-8baa8801fe56.png)
\
![image](https://user-images.githubusercontent.com/123282392/217146158-877e0924-a231-4679-bfea-ffa8f125596e.png)
\
![image](https://user-images.githubusercontent.com/123282392/217146198-08108899-285d-4e5e-9b20-05a34a247efc.png)
\
\
**Step 3: Sketch Out a Solution**
\
\
After considering the changes that need to be prioritized (improve readability, choose visualization tool tha is not a vertical bar chart, color scheme), I then brainstormed different ways to display this data.
\
\
Sketch 1: Horizontal Bar Chart
\
![image](https://user-images.githubusercontent.com/123282392/217146659-8bc34806-0142-49fa-9d14-3c67573ba62b.png)
\
I first considered simply rotating the bar chart and sorting the data by size. This visualization solves the issue of the original visualization not fitting on the screen at the same time and improves readability. I also reduced the concept down to a single color to emphasize supporting climate legislation more than climate skepticism. However, this graph did not feel creative enough to me. I wanted to better emphasize the disparity between each country's percentages to make the story more impactful. I want to convey that even though people are skeptical about climate change, they still support climate legislation. The bar graph doesn't make this visually dramatic enough, so I sketched out my next idea.
\
\
Sketch 2: Scatterplot
\
![image](https://user-images.githubusercontent.com/123282392/217147072-dd54d38a-f1db-47cc-a731-e82fa7b1ffb1.png)
\
I next considered using a scatterplot. The visual trend in the data is more easy to see with this type of visualization, which I like. Unfortunately, I think it's inefficient to have two axes with the same units (e.g. percentage). This method also requires labeling every data point, which is too cluttered for my taste. Finally, I didn't know how to introduce color to this visualization in a way that adds significant meaning or interpretation to the data. This visualization does not look bad, but it's not as strong as I want it to be. Thus...
\
\
Sketch 3:
\
![image](https://user-images.githubusercontent.com/123282392/217147742-d6c1f2f4-151c-41b1-8c15-61d7f837cc62.png)
\
After the previous two sketches, I considered using a map to tell my data story. I was excited to try this because I know Tableau has robust visualizations utilizing maps. Sadly, I could not find the dataset itself that has 37 data points, which I think would be more effective on a global map than the 15 data points I gleaned directly from the original visualization. I was also worried about how I would input the data itself onto the map - so much so that I didn't even add it to the map I traced. I considered 3D bar graphs (too complicated), ratios of one percentage to another (too hard to conceptualize for the audience), and just reporting the percentages over their gived countries (too simple, not strategic).
\
\
**Step 4A: Test the Solution**
\
Of these 3 sketches I prefered the scatterplot concept the most. This is what I then displayed to my fellow students during an in-class discussion. From this exchange, the group consensus was:
\
  1)  I need to add a date to aid context
  2)  Put source in the footer (don't forget!)
  3)  My Sketches 1 & 2 were easy to understand
  4)  I need to narrow down who exactly my audience is - is simplicity the driving factor in my design, or telling a compelling story? Are they mutually exclusive?
  5)  I need to clarify my narrative - what makes this a story worth telling? (This tells me that my title isn't narrative enough)
\
This was my first round of review. From here, I decided to try refining a scatterplot.
\
**Step 5A: Build the Solution**
\
After the in-class feedback, I made a rough version of a scatterplot out of the data in Flourish.
\
\
I was ultimately disappointed with this design. My initial hangups in the sketching stage couldn't be eliminated - using color efficiently, having the points individually labeled, etc. At this point I decided to try a new visualization altogether before getting more peer feedback.
\
\
**Step 4B: Test the Solution (Again)**
\
After being disappointed in the _drama_ that the scatterplot was lacking, I decided to click through some of the visualization templates that both Tableau and Flourish have to offer. One in particular caught my eye: the connected dot plot.
\
I liked this visualization for a few reasons. I could eliminate having two axes with the same units, as I was not satisfied with this even back in the sketching phase of this redesign. I liked that the template data was utilizing color to tell the story of changes over time, and I figured I could do similarly with my changes between survey responses. I also liked that I could have the country labels easily listed along the side instead of floating next to scatterplot points, and that they were angled horizontally so they could be more readable (compared to vertical or angled labels).
