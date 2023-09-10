This short project employs various tree-based algorithms (LightGBM, XGBoost, random forests) to classify particle tracks as either motile or non-motile. This project highlights the importance of feature engineering: for example, by inspecting a few of the tracks, we observe that the trajectory of the non-motile particles seemed to be ”more linear” with time compared to the motile (1) particles. As a result of this
observation, we created a feature linearity with the goal to capture the degree of linearity of the path of a given particle. This model achieved 83.6% accuracy on unseen data. 
