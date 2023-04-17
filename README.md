# Hypergraph Cognitive Networks

## Use

This repository contains the basic analytical pipeline of the data we used in the work cited above.

Data includes:
 - Features from the <a href=https://link.springer.com/article/10.3758/s13428-018-1099-3>Glasgow Norms</a>;
 - English Free Associations from the <a href=https://smallworldofwords.org/en/project/home>Small World of Words</a> project.
 
 An example notebook contains the basic pipeline of the work:
  - Data Preprocessing;
  - Graph and Hypergraph-based representations of Free Associations;
  - Features' Aggregation Strategies based on the above representations;
  - Predicting a Target Feature (e.g., ground-truth concreteness) based on the other aggregated features;
 
Other details:
  - Graph-based representations include the following strategies:
    - G123 Ego-Network.
    - Community Detection based representations: Louvain, EVA, Lemon;
  - Prediction:
    - Random Forest Regressor;
    - Evaluation with RMSE, R2.
 
