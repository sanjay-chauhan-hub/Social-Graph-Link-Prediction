# Social Graph Link Prediction
## Problem statement:
Given a directed social graph, we have to predict missing links to recommend friends/connnections/followers (Link Prediction in graph).
## Data Overview
Dataset from facebook's recruting challenge on kaggle: https://www.kaggle.com/c/FacebookRecruiting<br>
Data contains two columns: source and destination edge pairs in the directed graph.
- Data columns (total 2 columns):  
- source_node         int64  
- destination_node    int64
## Business objectives and constraints:
- No low-latency requirements.
- Predciting the probability of a link is useful so as to recommend the highest probability links to a user.
- We got to suggest connnections which are most likley to be correct and we should try and not miss out any connnections.

