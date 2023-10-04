# hw4AnimePCA

## Sai Varadharajan

## 5/6/

## Files:

Box Folder: https://uwmadison.box.com/s/8oq354ju8hspa2rtql9l9ly1tzvq06r

Dataset CSV File: https://uwmadison.box.com/shared/static/fxzjs879p27h2h3pqdmeht0f7w1foe4p.csv

Rmd File: https://uwmadison.box.com/shared/static/lm538a0we3lefem96ezgf91fb2injvqu.rmd

## Introduction

The dataset I will be performing PCA on to identify underlying patterns and relationships is a dataset on anime. It includes columns for names,
genres, ratings, type, id, number of members in the fanbase, and number of episodes. I will be trying to identify clusters of similar anime shows
based on their genre, type, and rating data, and try to reduce the dimensionality of the dataset to identify the most important features that
contribute to user preferences for anime shows. Each of my two visualizations will answer an essential question (mentioned later) that contributes
to this overall goal.

## Preprocessing the data, Pros and Cons

In order to perform PCA on this dataset, I had to choose to make some modifications to the dataset. Firstly, I got rid of unnecessary columns like
the Anime_id, and then I mutated the episodes column to make sure it was a numeric type. I also got rid of rows with missing values.

A decision I made was to mutate the Genre column to only include one genre per row. For example, an anime could have the Genre value
“Mystery, Adventure,Sci-fi”. I decided to edit the values so that it would only contain the first Genre, in this case “Mystery”. I decided to do this to
make the number of genres decrease from a few hundred to forty for simplicity’s sake in my visualizations. I ran into a problem rendering the plots
because there were so many genres that it was difficult to coherently visualize because the plot would try to make a specific color for each
combination of genres, which ended up causing the plot not being able to be rendered by my computer at all.

A disadvantage of this decision could be that the resulting genres an anime is classified under might not be as accurate, and two different anime
within the same genre could be very different, which would make it difficult to make out distinct clusters in my visualization.


## Refer to https://github.com/SaiVarad1/Anime_PCA/blob/main/hw4AnimePCA%20(1).pdf for project report
