# Assignment 3&4: Critique By Design

## Step 1: Find a data visualization you can improve

The below chart is from the Pew Research Center. It details climate change opinions at the national scale. At first glance, a few issues are immediately obvious to me: the title isn't informattive/narrative enough, the data does not look to be organized in any particular way, and the colors are dull. Though this visualization is not terrible, it can definitely be improved.

<p align="center">
<a href="https://www.pewresearch.org/global/2015/11/05/2-public-support-for-action-on-climate-change/climate-change-report-41/"><img src="https://www.pewresearch.org/global/wp-content/uploads/sites/2/2015/11/Climate-Change-Report-41.png?w=309"></a>
  </p>

## Step 2: Critique the Data Visualization

Using Stephen Few's [Data Visualization Effectiveness Profile](http://www.perceptualedge.com/articles/visual_business_intelligence/data_visualization_effectiveness_profile.pdf) as a guideline, the next step in this critique involves focusing on specific visualization aspects and identifying areas of improvement. The following survey demonstrates this analytical process.


<p align="center">
<img src="https://user-images.githubusercontent.com/123282392/217146077-e1cf90c3-50d5-428e-8656-8baa8801fe56.png">
  </p>

<p align="center">
<img src="https://user-images.githubusercontent.com/123282392/217146158-877e0924-a231-4679-bfea-ffa8f125596e.png">
  </p>

<p align="center">
<img src="https://user-images.githubusercontent.com/123282392/217146198-08108899-285d-4e5e-9b20-05a34a247efc.png">
  </p>

## Step 3: Sketch Out a Solution

After considering the changes that need to be prioritized (improve readability, choose visualization tool tha is not a vertical bar chart, color scheme), I then brainstormed different ways to display this data.

<p>

<p align="center">
  Sketch 1: Horizontal Bar Chart
  </p>

<p align="center">
<img width="460" height="250" src="https://user-images.githubusercontent.com/123282392/217146659-8bc34806-0142-49fa-9d14-3c67573ba62b.png">
  </p>

I first considered simply rotating the bar chart and sorting the data by size. This visualization solves the issue of the original visualization not fitting on the screen at the same time and improves readability. I also reduced the concept down to a single color to emphasize supporting climate legislation more than climate skepticism. However, this graph did not feel creative enough to me. I wanted to better emphasize the disparity between each country's percentages to make the story more impactful. I want to convey that even though people are skeptical about climate change, they still support climate legislation. The bar graph doesn't make this visually dramatic enough, so I sketched out my next idea.

<br>
</p>


<p>
<p align="center">
  Sketch 2: Scatterplot
  </p>

<p align="center">
<img width="460" height="250" src="https://user-images.githubusercontent.com/123282392/217147072-dd54d38a-f1db-47cc-a731-e82fa7b1ffb1.png">
  </p>

I next considered using a scatterplot. The visual trend in the data is more easy to see with this type of visualization, which I like. Unfortunately, I think it's inefficient to have two axes with the same units (e.g. percentage). This method also requires labeling every data point, which is too cluttered for my taste. Finally, I didn't know how to introduce color to this visualization in a way that adds significant meaning or interpretation to the data. This visualization does not look bad, but it's not as strong as I want it to be. Thus...

<br>
</p>

<p>
<p align="center">
  Sketch 3: Map (With Imaginary Data Overlaid)
  </p>

<p align="center">
<img width="460" height="250" src="https://user-images.githubusercontent.com/123282392/217147742-d6c1f2f4-151c-41b1-8c15-61d7f837cc62.png">
  </p>

After the previous two sketches, I considered using a map to tell my data story. I was excited to try this because I know Tableau has robust visualizations utilizing maps. Sadly, I could not find the dataset itself that has 37 data points, which I think would be more effective on a global map than the 15 data points I gleaned directly from the original visualization. I was also worried about how I would input the data itself onto the map - so much so that I didn't even add it to the map I traced. I considered 3D bar graphs (too complicated), ratios of one percentage to another (too hard to conceptualize for the audience), and just reporting the percentages over their gived countries (too simple, not strategic).
<br>
<br>
</p>


## Step 4A: Test the Solution

<p>
Of these 3 sketches I prefered the scatterplot concept the most. This is what I then displayed to my fellow students during an in-class discussion. From this exchange, the group consensus was:
<br>
  <br>
  1)  I need to add a date to aid context <br>
  2)  Put source in the footer (don't forget!) <br>
  3)  My Sketches 1 & 2 were easy to understand <br>
  4)  I need to narrow down who exactly my audience is - is simplicity the driving factor in my design, or telling a compelling story? Are they mutually exclusive? <br>
  5)  I need to clarify my narrative - what makes this a story worth telling? (This tells me that my title isn't narrative enough)
<br>
  <br>
This was my first round of review. Because of the feedback emphasis on improving understandability, I decided to try refining a scatterplot. This was a cleaner solution that a bar chart, and more practical than overlaying data on top of a world map.
<br>
  <br>
</p>

## Step 5A: Build the Solution

<p>
After the in-class feedback, I made a rough version of a scatterplot out of the data in Flourish.
  <br>
<p align="center">
<img width="600" height="450" src="https://user-images.githubusercontent.com/123282392/217152901-997ee132-e740-4353-bc4a-4074642d11b6.png">
  </p>
<br>
  <br>
Despite this being the very first rough draft, I was ultimately disappointed with this design. My initial hangups in the sketching stage couldn't be eliminated - using color efficiently, having the points individually labeled, etc. I couldn't stop the labels from overlapping and having the data points clustered at the top of the graphic felt more awkward than dramatic. In order to keep the axis labels readable and therefor ehorizontal, I had an awkwadly long Y-axis title as well. At this point, I decided to scrap the scatterlot altogether and try a new visualization type before getting more peer feedback.
<br>
</p>

## Steps 4B & 5B: Build a New Solution, Then Test That Instead

<p>
After being disappointed in the _drama_ that the scatterplot was lacking, I decided to click through some of the visualization templates that both Tableau and Flourish have to offer. One in particular caught my eye: the connected dot plot.
<br>
  <br>
I liked this visualization for a few reasons. I could eliminate having two axes with the same units, as I was not satisfied with this even back in the sketching phase of the scatterplot design. I liked that the template data was utilizing color to tell the story of changes over time (one color for each time period), and I figured I could use the same strategy with my changes between survey responses. I also liked that I could have the country labels easily listed along the side instead of floating next to scatterplot points, and that they were angled horizontally so they could be more readable (compared to vertical or angled labels).
<br>
  <br>
After reformatting the data in Excel to suit this visualization type, I ended up with this:
<p align="center">
  <img width="600" height="450" src="https://user-images.githubusercontent.com/123282392/217152675-884348c9-febd-4c56-b84b-dc062abcfbc2.png">
<br>
  <br>
</p>

<p>
Now that I had a digitized visualization that I was halfway happy with, I was finally able to engage in the one-on-one peer review step of this assignment.
  <br>
  <br>
I met with Maggie Harger, a student in the other section of this Spring '23 Telling Stories with Data class. I showed her my above connected dot plot. After she studied the map, given zero context she had the following to say:
  <br>
  <br>
 
_Can you understand the story the graphic is trying to tell?_
  <br>
  No, not at all.
  <br>
  <br>
_Why?_
  <br>
  The colors are too similar, it's difficult for the distinct data points to stand out for each country. I also think the title and subtitle are saying the same thing, so they're redundant.
  <br>
  <br>
_That's a good point. I'll workshop the title more since that's also what people said during the in-class feedback session._
  <br>
  Yeah, the title is confusing. I still don't really understand _why_ I'm looking at this graphic. The main takeaway should be clearer, and in the title.
  <br>
  <br>
_So the story behind this data is that even though people are skeptical about climate change, that's not enough to deter them from pursuing climate policy. So what's happening is countries are legislating more proactively instead of reactively._
  <br>
  Oh, I see... Yeah, that wasn't clear. So these data points on the far right are a good thing, and it's shocking that the lines themselves are so long?
  <br>
  <br>
_Exactly._
  <br>
  I see. Yeah, that wasn't clear. The data also isn't ordered at all, is it?
  <br>
  <br>
_...Whoops._
  <br>
  <br>
  <br>
  
After this feedback session, I knew what I had tp do. The title needed to be changed to reflect the narrative story I was trying to tell. My colors needed to support this narrative, not distract from it. I also needed to sort my data, eiher by line length, alphabetically, or by further right data point.
</p>

## Step 5C: Building Yet Another Solution

<div class="flourish-embed flourish-scatter" data-src="visualisation/12666858"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

<p>
  This is my new and improved design, which will go through one more round of peer review.
  <br>
  <br>
  I changed the color scheme to show a more dramatic contrast. I initially used green in my color scheme because the topic is environmental, but using a contrasting color with green means using red. I was concerned about this graphic looking too confusing for colorblind audiences, so instead I leaned into using blue in the graphic, and then yellow to contrast with that. I think the look is more polished and professional. I kept blue as the more dominant color (for both dots and the lines themselves) because it's less straining/distracting than having too much yellow. I tried to make the lines yelow and it caused my physical pain.
  <br>
  <br>
  I also increased the X-axis range to 0-100%, since I think this will reduce confusion for the average viewer, who is used to percentages having a maximum of 100. 

  

