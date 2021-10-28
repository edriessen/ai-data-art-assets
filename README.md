# Creating assets for data art using AI

## Summary

Applying various AI methodologies to generate abstract visuals. These visuals can be used to create small art pieces. 

## Background

I’ve been working on an open data art project. In the project, I use the sentiment analysis in Google’s Natural Language API to turn music lyrics into data. After that, I use data visualisation to turn the data into abstract shapes. Here’s an example of a visual generated from the data of Avicii’s TIM (his death was the starting point of my project back in 2018):

![image of base project](/building%20ai%20image.png)

[Building AI](https://buildingai.elementsofai.com/) showed me some easy-to-understand examples of how I can apply AI. Besides improving my AI knowledge, which I think improves my skills as a business analyst, it also inspired me to apply some new techniques to my open data art project. 
 
## Data and AI techniques

The project depends on sentiment data. This data should at least have three values: an index, a sentiment score, and a magnitude score (for details, read [the google docs](https://cloud.google.com/natural-language/docs/basics#interpreting_sentiment_analysis_values)). I have three updates I’d like to incorporate into the project that are based on the course:

1.	Generate a line starting at the first data point and that continues to its nearest neighbour until it has crossed all data points.
2.	Draw a shape (e.g. a triangle) from the data points that are the nearest neighbours to a given data point. Do this for all the data points.
3.	Create my own algorithm to turn music lyrics into data. 

I plan to add the first two ideas in the near future. I’ll take a bit more time to look into the third idea.

## How it is used 

My project uses AI methods in the context of art. It uses techniques that are often associated with big data and business applications to transform relatively small collections of texts into a small data set. Visualising that data results in something I like to call small data art. I see my project as a buddy that helps me generate creative assets. 

The project can be used by anyone who is interested in the creative possibilities of AI and code. It also offers fans of music a way to visualise a full album in various unique ways; it gives people a direct visual representation of an album that is generated by a machine. People may like or dislike this. 

> _**A brief side story**: I read ‘The Mind’s I’ because the course referred to it. It has a section where Tortoise and Achilles discuss how they use a record.  Achilles, like me, listens to a record. Tortoise hangs it on the wall and views it ‘as a whole’. It takes some time for Achilles to understand how this could work. And it took some time for me to see that I sort of made a visual representation that mimics what Tortoise was talking about._

## Challenges

My project is focused on using AI to generate creative and abstract visualisations of (relatively) small collections of text. It does not aim to capture the true meaning of music, the sounds, or the lyrics in any way. 

## What's next
The project currently depends on Googles Natural Language API to generate the data. That’s a dependency I’d like to remove at some point (although I appreciate how big tech companies are democratizing their technology). Besides that, I’ll keep my eyes & ears open for other ways of transforming text into data and visualising the results. Building AI gave inspiration for both.

## Acknowledgments 

This ideas described here are new additions to my [open data art project](https://github.com/edriessen/avicii-project). That project uses [Google Natural Language API](https://cloud.google.com/natural-language/) for sentiment analysis, is built in [Python](https://www.python.org/) and depends on these packages: [Pandas](https://pandas.pydata.org/), [Matplotlib](https://matplotlib.org/), googleapiclient and google-cloud-langauge. Besides that, I use [Inkscape](https://inkscape.org/) (an open-source graphics editor) to apply minor tweaks to the graphs I generate with Matplotlib. 

And of course, I need to mention Avicii here. His music is _the_ inspiration for all of the above.



