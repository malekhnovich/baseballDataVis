<h2>Summary</h2>

The dataset I worked is the baseball data set, it consists
of 1,157 baseball players. The baseball player's handedness,
height (in inches), batting average, home runs, and weight(in pounds)
were all aspects of each player that I focused on. I decided to make the handedness of the players
a categorical variable that I could use in comparison to the  batter's average and homeruns hit.
I also decided to use the weight of the players because my reviewers hypothesized that heavier players
would be stronger and hit more homeruns.



<h1>Key Findings</h1>

<h2>Introduction</h2>
By exploring the data, I wanted to find correlations that signify
what makes a good baseball player based on the statistics that were
provided in the dataset. The handedness of the data returns 'R','L',
and 'B'. These represent right-hand hitters, left-hand hitters, and hitters
that can hit with either hand.

<h2>What makes a Good Baseball Player at the Plate?</h2>
It is clear that baseball players who <b>weigh more</b> are overall
more likely to hit homeruns  than baseball players that are lighter. This makes
sense that heavier players would have more power and can launch the ball farther and
even out of the stadium. By showing the statistics in a bargraph, it is easy to see the levels
of each type of hitter.

<h2> How does Handedness Affect a baseball player's ability at the plate?</h2>
There is a clear trend among baseball players in the data that shows that left-hand
hitters are overall better hitters than both right-hand hitters and 'both'-hand hitters.
Right-hand hitters might not be as strong and have a lower batting average than left-hand hitters,
but they do hit more homeruns  than both-hand hitters.

<h2>Key Findings : Conclusion</h2>
Weight and handedness are two significant factors in determining whether a baseball player
is a good hitter both in terms of average and the number of homeruns that they hit.


<h2>Design</h2>

Immediately after I received the data, I knew I wanted to categorize the
data based on a specific factor. I noticed that handedness was the only variable
that could be categorized without cleaning the data. Initially, I decided to graph
handedness of the data versus the total batting average of the players in a lineplot. After
receiving feedback, I determined that this did not provide a clear visual. I then switched
to the 'HR' attribute of the data, standing for homeruns. I noticed that the correlation between
homeruns and handedness was more noticeable visually. Again, after recieving feedback I decided to
change the graph type from a scatter plot to a bargraph which would
depict the handedness of the batters and their average homerun output appropritely. At first, I wondered whether to depict
the averages or the total for the handedness of the players. For <b>chart type</b>,  I decided to use the totals after recieving feedback
because it gathered all the players together. For <b> x-axis encoding </b>, I used the categorical
variable of handedness to seperate that categorical feature into 3 distinct groups. I used a line graph with two lines
both the batting average and the number of homeruns hit, using blue and red to make the colors distinct.
For <b> y-axis encoding </b>, I decided to use  the number of <b>homerun's hit</b>.
The <b>legend </b> shows the different features that I wanted to look at along
with the axes. In addition, I also changed the abbreviations of the handedness attributes from 'R','L
, and 'B' to 'Right','Left', and 'Both'.

<h2>Feedback</h2>
I asked three of my classmates for feedback at different points in time.


1.<b> The first person I received feedback </b> from suggested the graph of handedness and average didn't really show me anything.

2.<b>The second person I received feedback</b> from suggested the graph of hr and handedness was better but still as a scatterplot
    required a person to look at it for a while to see the trend.

3.<b> The third person I received feedback </b> from suggested the graph of hr and handedness  with average equailing x2 confuses the viewer of the graph
"keep it simple"

4. Bargraph of handedness and hr shows a specific trend that
can be noticed right away.

5. Why is there a k on the y axis and why isn't average showing the number as a decimal

6. Can we get the plot of the points to connect in order to show
the trend of averages as well?

7. Wouldn't weight be a significant factor in homeruns hit?

8. The average still shows as a whole number rather than a decimal

9. I ordered the weights from least to greatest in order to better show
a story

10. adjusted the duration of the story frame in order to provide viewer more time
to see the changes in the weight.

11. Recommended that I create an additional graph and split out the weight aspect of the data




<h2>Resources</h2>
Looked at http://bl.ocks.org/tybyers/736da90eefe0c347a1d6 to see how the graph in the lesson was created.

https://stackoverflow.com/questions/23305230/how-do-you-reduce-the-number-of-y-axis-ticks-in-dimple-js