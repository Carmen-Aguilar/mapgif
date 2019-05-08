# How to make a gif of a map

Prior to the UK local elections in May 2019, Sky News was shared a database with historic local results since 1973.

The data shows that the two main parties control three-quarters of the councils, one of the highest rate of two-party dominance of the last 46 years. It also told us that the rise of the LD explains the fall of the two-party dominance and the increase of councils without overall control, and that the LD was not favoured by joining the government coalition in 2010.

We [published these findings in our story](https://news.sky.com/story/local-elections-see-how-your-area-has-voted-over-the-past-40-years-11707933), where people can also search for a particular local authority and see how each area has voted over the past 40 years (scroll down in the previous link).

To promote the story, I played with `ggplot` and `gganimate` to produce a gif map, although it is particular tricky this kind of visualisations in the UK due to boundary changes. 

Here is [my "how I did it" R Notebook](http://rpubs.com/Carmen_Aguilar/gif_map_localelections).
