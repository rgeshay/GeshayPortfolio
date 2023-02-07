# Assignment 3&4: Critique By Design

## Summary

This assignment focuses on evaluating and improving an existing data visualization from the Pew Research Center. The overall redesign process includes analyzing the current data visualization, evaluating what is and is not successful, brainstorming different graphical representations, and then alternating between redesign and peer review. The final visualization represents the culmination of this process. The original Pew Research Center visualization was chosen because it lacked sophisticated design, the trends in the data was not clear, and because its story was compelling despite its visual appearance. Understanding that despite climate skepticism, climate policy is desired across the globe is very interesting and almost counterintuitive. By having the data reflect this surprising finding in a more polished, dramatic way, the story can be more clearly understood. The data is composed of response metrics from national surveys, one topic of which was climate change.

## Step 1: Find a data visualization you can improve

<p>
The below chart is from the Pew Research Center. It details climate change opinions at the national scale. At first glance, a few issues are immediately obvious to me:
  <br>
  <br>
  1) the title isn't informative/narrative enough
  <br>
  <br>
  2) the data does not look to be organized in any particular way
  <br>
  <br>
  3) The design is not visually engaging (color, too long, etc.)
  <br>
  <br>
  Though this visualization is not terrible, it can definitely be improved.
  <br>
  </p>

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

After considering the changes that need to be prioritized (improve readability, choose visualization type that is not a vertical bar chart, color scheme, etc.), I then brainstormed different ways to display this data.

<p>

<p align="center">
  Sketch 1: Horizontal Bar Chart
  </p>

<p align="center">
<img width="460" height="250" src="https://user-images.githubusercontent.com/123282392/217146659-8bc34806-0142-49fa-9d14-3c67573ba62b.png">
  </p>

I first considered simply rotating the bar chart and sorting the data by size. This visualization solves the issue of the original work not fitting on the screen at the same time and improves readability. I also reduced the concept down to a single color to emphasize supporting climate legislation more than climate skepticism. However, this graph did not feel creative enough to me. I wanted to better emphasize the disparity between each country's percentages to make the story more impactful. I want to convey that even though people are skeptical about climate change, they still support climate legislation. The bar graph doesn't make this visually dramatic enough, so I sketched out my next idea.

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

After the previous two sketches, I considered using a map to tell my data story. I was excited to try this because I know Tableau has robust visualizations utilizing maps. Sadly, I could not find the dataset itself that has 37 data points, which I think would be more effective on a global map than the 15 data points I gleaned directly from the original visualization. I was also worried about how I would input the data itself onto the map - so much so that I didn't even add it to the map I traced. I considered 3D bar graphs (too complicated), ratios of one percentage to another (too hard to conceptualize for the audience), and just reporting the percentages over their given countries (too simple, not strategic).
<br>
<br>
Of these 3 sketches I prefered the scatterplot concept the most. This is what I then displayed to my fellow students during an in-class discussion.
</p>


## Step 4A: Test the Solution

<p>
During an in-class discussion, my peers gave me the following feedback on the scatterplot visualization sketch:
<br>
  <br>
  1)  I need to add a date to aid context <br>
  2)  Put source in the footer (don't forget!) <br>
  3)  My Sketches 1 & 2 were easy to understand <br>
  4)  I need to narrow down who exactly my audience is - is simplicity the driving factor in my design, or telling a compelling story? Are they mutually exclusive? <br>
  5)  I need to clarify my narrative - what makes this a story worth telling? (This tells me that my title isn't narrative enough)
<br>
  <br>
This was my first round of review. Because of the feedback emphasis on improving understandability, I decided to commit to refining a scatterplot as a visualization technique. This was a cleaner solution that a bar chart, and more practical than overlaying data on top of a world map.
<br>
  <br>
</p>

## Step 5A: Build the Solution

After the in-class feedback, I made a rough version of a scatterplot out of the data in Flourish.

<p align="center">
<img width="600" height="450" src="https://user-images.githubusercontent.com/123282392/217152901-997ee132-e740-4353-bc4a-4074642d11b6.png">
  </p>
<p>
  <br>
  <br>
Despite this being the very first rough draft, I was ultimately disappointed with this design. My initial hangups in the sketching stage couldn't be eliminated - using color efficiently, having the points individually labeled, etc. I couldn't stop the labels from overlapping and having the data points clustered at the top of the graphic felt more awkward than dramatic. In order to keep the axis labels readable and therefore horizontal, I had an awkwadly long Y-axis title as well. At this point, I decided to scrap the scatterplot altogether and try a new visualization type before getting more peer feedback.
<br>
</p>

## Steps 4B & 5B: Build a New Solution, Then Test That Instead (featuring Maggie)

<p>
After being disappointed in the drama that the scatterplot was lacking, I decided to click through some of the visualization templates that both Tableau and Flourish have to offer. One in particular caught my eye: Flourish's the connected dot plot.
  <br>
  <br>
I liked this visualization for a few reasons. I could eliminate having two axes with the same units, as I was not satisfied with this even back in the sketching phase of the scatterplot design. I liked that the template data was utilizing color to tell the story of changes over time (one color for each time period), and I figured I could use the same strategy with my changes between survey responses. I liked that the line element allows the difference in the two data points per country to be emphasized, rather than their base values. I also liked that I could have the country labels easily listed along the side instead of floating next to scatterplot points, and that they were angled horizontally so they could be more readable (compared to vertical or angled labels).
  <br>
  <br>
After reformatting the data in Excel to suit this visualization type, I ended up with this:
  </p>
  
<p align="center">
  <img width="600" height="450" src="https://user-images.githubusercontent.com/123282392/217152675-884348c9-febd-4c56-b84b-dc062abcfbc2.png">
  <br>
  <br>
</p>

<p>
Now that I had a digitized visualization that I was halfway happy with, I was finally able to engage in the one-on-one peer review step of this assignment.
  <br>
  <br>
I met with Maggie Harger, a student in the other section of this Spring '23 Telling Stories with Data class. I showed her my above connected dot plot. After I gave no context and let her study the map, our subsequent conversation went something like this:
  <br>
  <br>
  </p>
 
 <p>
  
  Me: Can you understand the story the graphic is trying to tell?
  <br>
  <br>
  Maggie: No, not at all.
  <br>
  <br>
  Me: Why?
  <br>
  <br>
  Maggie: The colors are too similar, it's difficult for the distinct data points to stand out for each country. I also think the title and subtitle are saying the same thing, so they're redundant.
  <br>
  <br>
  Me: That's a good point. I'll workshop the title more since that's also what people said during the in-class feedback session.
  <br>
  <br>
  Maggie: Yeah, the title is confusing. I still don't really understand _why_ I'm looking at this graphic. The main takeaway should be clearer, and in the title.
  <br>
  <br>
  Me: So the story behind this data is that even though people are skeptical about climate change, that's not enough to deter them from pursuing climate policy. So what's happening is countries are legislating more proactively instead of reactively.
  <br>
  <br>
  Maggie: Oh, I see... Yeah, that wasn't clear. So these data points on the far right are a good thing, and it's shocking that the lines themselves are so long?
  <br>
  <br>
  Me: Exactly.
  <br>
  <br>
  Maggie: I see. Yeah, that wasn't clear. The data also isn't ordered at all, is it?
  <br>
  <br>
  </p>
  ...Whoops.
  
<p>
  <br>
  <br>
  <br>
  
After this feedback session, I knew what I had to do. The title needed to be changed to reflect the narrative story I was trying to tell. My colors needed to support this narrative, not distract from it. I also needed to sort my data somehow.
<br>
</p>

## Step 5C: Building Yet Another Solution

<p>
  For my new and improved design, I made several big changes.
  <br>
  <br>
  I changed the color scheme to show a more dramatic contrast. I initially used green in my color scheme because the data is thematically environmental, but I have two data points for each country which necessitate color distinctions. Using a contrasting color with green means using red. I was concerned about this graphic looking too confusing for colorblind audiences, so instead I leaned into using blue in the graphic, and then yellow to contrast with that. I think the look is more polished and professional. I kept blue as the more dominant color (for both dots and the lines themselves) because it's less straining/distracting than having too much yellow. I tried to make the lines yellow and it caused me physical pain.
  <br>
  <br>
  I also increased the X-axis range to 0-100%, since I think this will reduce confusion for the average viewer, who is used to percentages having a maximum of 100. This might be creating too much negative space, so I'll ask my next peer reviewer about that. Regarding the Y-axis, I removed the redundant label "Country" that Maggie and I both missed on our initial reviews. I then edited all the text to make it darker and thus more readable, and increased the Y-axis font size.
  <br>
  <br>
  I also changed the title, but kept the subtitle. I feel conflicted about removing the subtitle, since I want to add in the context of the percentages corresponding to survey metrics within individual countries. This information might not be necessary for the audience though, so perhaps I am holding onto this for no reason. I also forgot to add a source link at the bottom, so I'll have to amend that for my final version.
  <br>
  </p>


## Step 4D: Test the Solution (featuring Aishwarya)


<p>
For my next peer level review, I was much more excited to showcase my data visualization. For this review level, I prepared some questions beforehand that I knew I wanted answered:
<br>
  <br>
  
  Me: When you looked at this visualization, what elements did you look at first?
  <br>
  <br>
  Aishwarya: My eyes first went to the lines in the visualization themselves since they're clustered in the middle and look a bit messy. [Oops, I forgot to order the data...] I then looked at the X-axis to see what the dots represented, and then finally looked at the title for context
  <br>
  <br>
  Me: What do you think is the purpose of this graphic?
  <br>
  <br>
  Aishwarya: I actually wasn't really sure about that at first. I think the most meaning is in the legend, but the title and subtitle are a little... confusing? [When I gave her more context, she said] Oh, that makes a lot more sense. Ok, now I understand this graph. I like the style with the dots and the lines, so I don't think that's why I was confused. I think the title can frame the issue better or give more context for the data. 
  <br>
  <br>
  Me: What do you like about the visualization?
  <br>
  <br>
  Aishwarya: I like the colors, they're very clear. I also like that this isn't some boring bar chart or something. [I then showed her the original visualization, and she said] Yeah, yours is *much* better.
  <br>
  <br>
  When asked about the combination of title and subtitle, Aishwarya recommended altering the X-axis label from "Percentage" to "Percent of Respondents", then adding more detail to the title itself. This would nullify the need for a subtitle and be a quick fix!
  <br>
  </p>

## Step 5D: Build Last Solution

<p>
After this conversation, I realized I really needed to rework my title so that it was clearer. I think some of the context was muddied by relying on the subtitle as well, so I removed it per Aishwarya's advice while also making the title more specific/informative. I also followed Aishwarya's recommendation to edit the X-axis to reflect what the percentages are refering to, so it is now "Percent of Respondents". After incorporating Aishwarya's specific recommendations, I then edited the spacing a bit between the legend items and  added padding to the edges of the graphic. It took a long time to ensure my Y-axis labels were all visible (not overlapping) and the graphic's text colors were matching.
  <br>
  <br>
  At the very end of this process, I remembered that both Maggie and Aishwarya had said that the line arrangement was distracting, so I went into Excel to reorganize my data. I had to manually move the data points because the Y-axis is categorical, not continuous. I arranged the countries from least to greatest X-axis value of "Believe Climate Change is a Serious Problem". I then reordered the legend so that the yellow symbology is on the same side of the graphic as the yellow data points. This made a huge difference in how busy the graphic looked. It is now much more polished, and the trend is in the data is much clearer. I hope this supports the narrative that the new title is framing for the audience.
  <br>
  <br>
  After all of this, my final product is below.
  <br>
  </p>

<p align="center">
<iframe src='https://flo.uri.sh/visualisation/12666858/embed' title='Interactive or visual content' class='flourish-embed-iframe' frameborder='0' scrolling='no' style='width:90%;height:600px;' sandbox='allow-same-origin allow-forms allow-scripts allow-downloads allow-popups allow-popups-to-escape-sandbox allow-top-navigation-by-user-activation'></iframe><div style='width:100%!;margin-top:4px!important;text-align:right!important;'><a class='flourish-credit' href='https://public.flourish.studio/visualisation/12666858/?utm_source=embed&utm_campaign=visualisation/12666858' target='_top' style='text-decoration:none!important'><img alt='Made with Flourish' src='https://public.flourish.studio/resources/made_with_flourish.svg' style='width:105px!important;height:16px!important;border:none!important;margin:0!important;'> </a></div>

<br>
<br>
Thank you for following this stream-of-consciousness journey to refine a data visualization. I am excited to convey more interesting stroeis that are supported by visually pleasing data, especially in the climate sphere. So many stories are worth telling!
</p> 

