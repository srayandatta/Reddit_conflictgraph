# Reddit_conflictgraph
This dataset contains subreddit conflict and co-conflict graphs described in the paper:
Srayan Datta and Eytan Adar. Extracting inter-community conflicts in reddit. International AAAI Conference on Web and Social Media, 2019.

The subreddit conflict graph is a weighted directed graph with the following node attributes: id, name (subreddit name) and the edge attribute weight (the weight varies from 0 to 100, and denotes the percentage of controversial authors among common authors between the source and target subreddits).

The co-conflict graph is an unweighted graph with the node attributed: id, name and multilevel (deontes which community this node belongs to) and edge attribute weight (varies from 0 to 1).

If you make use of this dataset, please cite the aforementioned paper.
