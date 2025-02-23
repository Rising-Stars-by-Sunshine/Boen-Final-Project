# Bot Detection in Social Media via Hypergraph Neural Networks: A Group-Centric Approach

## Proposal Overview
This project proposes a novel approach to bot detection in social media by utilizing Hypergraph Neural Networks (HGNNs) to capture group-centric interactions. Social bots often operate in coordinated clusters, making traditional methods based on individual user features less effective. This study aims to improve detection accuracy by analyzing the network structure, including both user-level and group-level features, using the Twibot-22 dataset.

## Background
The presence of bots on social media platforms poses significant challenges to online discourse, public trust, and platform security. Bots have been used to spread misinformation, manipulate public opinion, and influence elections at an unprecedented scale. Current detection methods, which rely on user metadata or text-based approaches, often fail to capture the higher-order group interactions that are crucial for identifying coordinated bot activities. This research seeks to address this gap by modeling group behaviors through social network analysis and Hypergraph Neural Networks.

## Research Objectives
- **Bot Detection**: Improve bot detection accuracy by incorporating group-level interactions in social media networks.
- **Engagement Analysis**: Investigate the effects of platform policies, such as subscription eligibility, on user engagement and tweet activity.
- **Methodological Contributions**: Introduce a novel group-based approach to bot detection and integrate multiple machine learning techniques for explanation, prediction, and causal inference.

## Methodology

### 1. Machine Learning for Explanation
In this phase, we conduct a social network analysis of the Twibot-22 dataset to identify differences in centrality measures (degree, betweenness, and closeness) between human and bot accounts. These measures help explain the relative importance of users in the network and reveal structural differences in how bots and humans interact.

### 2. Machine Learning for Prediction
A Hypergraph Neural Network (HGNN) is used for binary node classification to distinguish between human and bot accounts. By constructing a hypergraph based on user-follower relationships, this method captures group behaviors and higher-order interactions, which traditional pairwise graph-based methods cannot.

### 3. Causal Inference Using Machine Learning
We apply a Regression Discontinuity (RD) design to study the impact of Twitter’s subscription program on user engagement. This method leverages the follower count threshold (2000 followers) to analyze its causal effect on tweet activity, helping to understand how platform policies influence user behavior.

## Evaluation

- **Explanation**: The analysis of centrality measures (degree, betweenness, closeness) indicates that bots typically have lower centrality values, especially in degree and betweenness, suggesting that these measures can effectively differentiate between human and bot accounts.

- **Prediction**: The model achieved a test accuracy of 0.503 and a ROC-AUC score of 0.61. While the accuracy suggests room for improvement, the ROC-AUC score indicates that the model can reasonably distinguish between bot and human accounts, performing better than random guessing.

- **Causal Inference**: The causal analysis reveals that eligibility for Twitter's subscription program significantly reduces tweet count by ~4935 tweets (p = 0.024), while follower count positively affects tweet count (+6.64 tweets per follower, p < 0.001). The interaction between subscription eligibility and follower count weakens the positive effect of followers on engagement.

These findings highlight the potential of using group-based interactions and centrality measures to improve bot detection, provide insights into the impact of platform policies on user engagement, and enhance the understanding of bot behavior in social media networks.

## Poster
![Bot Detection in Social Media Poster](https://github.com/Rising-Stars-by-Sunshine/Boen-Final-Project/blob/main/poster.png)

## Future Work
- Further refine the HGNN model to improve detection accuracy and reduce false positives.
- Explore additional features, such as text-based embeddings, to complement group-level interactions.
- Extend the analysis to other social media platforms like Facebook and Instagram.

## Acknowledgments
We would like to thank the authors of the Twibot-22 dataset for their contributions to bot detection research.

