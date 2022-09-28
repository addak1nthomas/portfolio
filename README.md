# portfolio
Portfolio of academic materials from Telling Stories with Data at Carnegie Mellon University

# About Me
I am a second year graduate student in the MS in Healthcare Policy and Management at Heinz College within Carnegie Mellon University. I originally come from Houston, TX, but consider Pittsburgh to be my home now. In my free time, I enjoy travelling, exercise, and music.

# What I Hope to Learn
In this course, I hope the learn more about the effective methods of communicating data via visualization to one who may be unfamiliar with the topics being depicted. I am hoping to persue a career in management consulting, so it is important I am able to communicate insights effectively.

# Portfolio

## Assignment 1

## Assignment 2 - Visualizing Government Debt
### Organization for Economic Co-operation and Development (OECD)
<iframe src="https://data.oecd.org/chart/6Ogp" width="860" height="645" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/6Ogp" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 2021</a></iframe>
#### OECD (2022), General government debt (indicator). doi: 10.1787/a0528cc2-en (Accessed on 11 September 2022)
### Flourish Pt. 1
<div class="flourish-embed flourish-chart" data-src="visualisation/11161279"><script src="https://public.flourish.studio/resources/embed.js"></script></div>
#### OECD (2022), General government debt (indicator). doi: 10.1787/a0528cc2-en (Accessed on 11 September 2022)
### Flourish Pt. 2
<div class="flourish-embed flourish-chart" data-src="visualisation/11154504"><script src="https://public.flourish.studio/resources/embed.js"></script></div>
#### OECD (2022), General government debt (indicator). doi: 10.1787/a0528cc2-en (Accessed on 11 September 2022)
The chart above was is a subset of the data from part 1. I decided to remove the other countries that were not highlighted in the initial data from the OECD chart. I noticed that the first visualization was attempting to show the debt to GDP ratio of the member countries of G7. Because of this, I decided to remove the other countries not being highlighted to avoid distracting information. 
Because we are in the United States and I am most interested in conveying the ratios of the United States, I decided to go ahead and grey out the other 6 member countries of G7. This is an effective strategy as it really allows for the United States to stand out and the viewers eyes are immediately drawn to the trends that are occuring in the United States.
### Tableau
<iframe src="https://public.tableau.com/views/Debt_GDP_Ratio/DebttoGDPRatio?:showVizHome=no&:embed=true" width="100%" height="1000" seamless frameborder="0" scrolling="no"></iframe>
#### OECD (2022), General government debt (indicator). doi: 10.1787/a0528cc2-en (Accessed on 11 September 2022)
## In-Class Exercise (September 13th)
<div class='tableauPlaceholder' id='viz1663097964645' style='position: relative'><noscript><a href='#'><img alt='% of Americans Trusting Media Sources ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ne&#47;News_Media_Trust&#47;ofAmericansTrustingMediaSources&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='News_Media_Trust&#47;ofAmericansTrustingMediaSources' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ne&#47;News_Media_Trust&#47;ofAmericansTrustingMediaSources&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1663097964645');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>
## Assignment 3 & 4: Critique by Design
### Step 1 & 2: Finding a Data Visualization and Initial Critique
The orginal data visualization and data associated with it comes from https://fathom.info/salaryper/ . Specifically, I will be focusing on the year 2010. It can be seen on this page that the visualization is quite disorganized and very distracting from the message. First of all, we can see that visualization uses MLB logos to depict each baseball team along with their repsective data. While this is very innovative and cool, not everyone looking at this visualization is going to be a fan of the MLB. It is important that the visualization is going to appeal to a variety of different audiences and the logos do not make it clear which team is which. 

Next, the center of the visualization is quite messy. There are so many colors and lengths of lines, but no clear indicator as to what exactly the lines and colors mean. It would maybe be more effective to find a way to depict the relationship without having a bunch of crossing lines. 
### Step 3: Sketch a Solution 
<iframe style="border: 1px solid rgba(0, 0, 0, 0.1);" width="800" height="450" src="https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Fproto%2FE144REXHe1ZF6btEt6Jvv5%2FUntitled%3Fnode-id%3D1%253A29%26scaling%3Dcontain%26page-id%3D0%253A1" allowfullscreen></iframe>
In my sketch, I envision a list that is sorted by the performance of each MLB team. I believe that the colors are very distracting so I think it would be most effective to stick with a more standard color scheme that is not going to distract the viewer from the story being told. Instead of whatever kind of visualization was seen in the orginial one, I believe that a standard bar graph would be just as effective to communuicate the message being told. Finally, I believe that the title definitley needs to be more distinct so that it does not take long for the viewer to identify what story is being told with the visualization.
### Step 4: Test your solution
The first person I had test my solution to the orginial visualization was a young male. I asked some generic questions to find out if he could identiy what story is being told, the confusing portions of the graph, and any reccomendations he had for me. He was able to identify the story being told and stated specifically that the visualization was examining the relationship with total MLB salaries to team performance. He stated that nothing in the graph was confusing, but instead provided reccomendations that he wish he would see the dollar amount that each team was spending so that it would be easier to grasp onto the number. This combined with the number of wins would effectively allow for the viewer to examine the relationship between the two.

The next person I spoke with was a middle-aged woman. She stated that the graph was depicting MLB team performance and the salaries associated with each team. She stated that she found it confusing to conceptualize the amount of money each team was spending on their players. She stated that this graph could be improved by finding a way for the reader to grasp onto the total amount of money being spent by each team. 
### Step 5: Build the Solution
<div class='tableauPlaceholder' id='viz1663710573513' style='position: relative'><noscript><a href='#'><img alt='MLB Team&#39;s Performance and Total Player Salaries (2010) ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;ML&#47;MLB_Performance_Salary&#47;MLBTeamsPerformanceandTotalPlayerSalaries2010&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='MLB_Performance_Salary&#47;MLBTeamsPerformanceandTotalPlayerSalaries2010' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;ML&#47;MLB_Performance_Salary&#47;MLBTeamsPerformanceandTotalPlayerSalaries2010&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1663710573513');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>
For the final solution, I incorporated the feedback given during my research and the in-class feedback seesion. I went ahead and added the dollar amount of each team's salary as well as combined the 2 variables of team name and total number of wins to allow for the data to be sorted correctly in Tableau.
[## Final Project Part 1](Final_Project_AddakinThomas.md)
