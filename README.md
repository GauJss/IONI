# IONI Real Data Description
This folder contains the Sina Weibo dataset used in the study "Inward and Outward Network Influence Analysis" by Yujia Wu, Wei Lan, Tao Zou, and Chi-Ling Cai.

Sina_W.xlsx: A symmetric adjacency matrix representing the friendship network among users. 
Sina_Covariates.xlsx: Contains user-level covariates utilized in the analysis. Descriptions of each covariate are provided below.

Covariate Descriptions:
Posts: Total number of posts by the user over the entire study period.
Duration: Time since the user registered on the Sina Weibo platform.
Self-Introduction: Length (in characters) of the user’s self-description.
Gender: male=1 and female=0. 

The In-degree / Out-degree used in the paper, which are the number of followers (in-degree) and followees (out-degree) for each user, are calculated directly from the adjacency matrix in Sina_W.xlsx.
