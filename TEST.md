Final group project instructions:

You will do the final group project in groups of 3–4. The final product will be a flexdashboard (html created from RMarkdown file) that presents interesting facets of a dataset to viewers and allows them to interact in at least some of the panes. There is more information about flexdashboards available at https://rmarkdown.rstudio.com/flexdashboard/examples.html.

Your group’s dashboard should include a text block somewhere on the dashboard that explains the data (including the data source) as well as what the dashboard can be used to explore and how to navigate it (for example, see the left-most pane in this dashboard: https://walkerke.shinyapps.io/neighborhood_diversity/). Besides this text block, your dashboard show have at least three panes with output (figures or tables). At least one should be interactive (using htmlwidgets). You may include everything in a single page (like https://beta.rstudioconnect.com/jjallaire/htmlwidgets-waste-sites/htmlwidgets-waste-sites.html) or you can spread results and text across several tabs of a dashboard (like https://walkerke.shinyapps.io/neighborhood_diversity/#explore-metros and https://beta.rstudioconnect.com/jjallaire/htmlwidgets-showcase-storyboard/htmlwidgets-showcase-storyboard.html).

There is extensive documentation about building flexdashboards here: https://rmarkdown.rstudio.com/flexdashboard/using.html. To divide group work, you may find it helpful to have some group members work on designing and setting up the framework for the dashboard, and then other members focus on writing the code for the figures and tables that will go in specific panes of the dashboard. Everything can then be put together by moving the code for those figures and tables into the flexdashboard Rmarkdown file.

You will have in-class group work time to work on this during the in-person sessions. This project will also require some work with your group outside of class. I will provide feedback and help during the in-class group work time.

The final group project will be graded with A through F, with the following point values (out of 30 possible):

30 points for an A
25 points for a B
20 points for a C
15 points for a D
10 points for an F
If you turn nothing in, you will get 0 points.

0.5.0.1 Final presentation
In total, the group’s presentation should last 15 minutes. There will then be 5 minutes for questions.
Split the presentation up into two parts: (1) an overview of your flexdashboard (about 7 minutes) and (2) a tutorial-style discussion of how you used R to do the project (about 8 minutes).
The overview of your flexdashboard should:
Explain the data sources for your dashboard
Explain what a user should be able to explore or understand by using your dashboard
Walk viewers through each pane in the flexdashboard and how any interactive elements can be used
The tutorial part should include the following sections:
Interesting packages / techniques: Spend a bit more time on any parts that you found particularly interesting or exciting. Were there packages you used that were helpful that we haven’t talked about in class? Did you find out how to do anything that you think other students could use in the future? Did you end up writing a lot of functions to use? Did you have an interesting way of sharing code and data among your group members?
Lessons learned: If you were to do this project again from scratch, what would you do differently? Were there any big wrong turns along the way? Did you find out how to do something late in the project that would have saved you time if you’d started using it earlier?
0.5.0.2 Flexdashboard
The grade for the flexdashboard will be based on the following criteria:

It should work.
It should include text that is clearly written, without grammatical errors or typos. Any graphics are easily to interpret and follow some of the principles of good graphics covered in class.
It includes at least three rendered outputs (e.g., plots, tables). At least one should be interactive.
It is self-contained—in other words, a user shouldn’t need to hear you explain the dashboard to understand it. It should include enough information on the app for a user to figure out how to use the app and interpret the output.