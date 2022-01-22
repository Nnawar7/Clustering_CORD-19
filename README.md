# Clustering_CORD-19
Clustering Analysis on Open Research Dataset CORD 19
Overview:
In response to the COVID-19 pandemic, the White House and a coalition of leading research groups
have prepared the COVID-19 Open Research Dataset (CORD-19). CORD-19 is a resource of over
57,000 scholarly articles, including over 45,000 with full text, about COVID-19, SARS-CoV-2, and
related coronaviruses. This freely available dataset is provided to the global research community. As
a big data community, how can we help researchers to easily find the related research papers
easily?
You can find the dataset and the main challenge on kaggle
https://www.kaggle.com/allen-institute-for-ai/CORD-19-research-challenge

Goals:
Given the large number of literature and the rapid spread of COVID-19, it is difficult for health
professionals to keep up with new information on the virus. Can clustering similar research articles
together simplify the search for related publications? How can the content of the clusters be
qualified? And over each cluster how can we recommend the most similar papers leveraging
clustering?

Requirements:
you are required to find out the best way to cluster the research papers using the research
papers details in the JSON file with the metadata in the CSV file, then you should build a
neighborhood recommender system to receive the title of research paper and recommend
the most N similar papers to it based on its cluster. So you should find a way to represent
the papers in vectors and cluster them then build a neighbourhood recommender system
on the clusters.
