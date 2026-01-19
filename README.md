# SDP-using-LOA

In this project, the Lyrebird Optimization Algorithm (LOA) is employed as a meta-heuristic optimizer to enhance the machine learning classifiers. Inspired by the foraging and mating behaviors of lyrebirds in nature, LOA efficiently explores the solution space to solve complex optimization problems.

<ins>Exploration Phase</ins> (Global Search): The LOA agents move over the whole solution space. For our SDP, this implies wide experimentation across various sets of features and hyperparameters in order to escape local optima. This guarantees thorough search over all possibilities, which is crucial for identifying the most relevant subset of features from a large set of candidates. 

<ins>Exploitation Phase</ins> (Local Search): After identifying the promising areas, LOA turns to intensive local search. During exploitation, the agents focus on perfecting the best solutions found. In our case, we run the optimization for incremental changes in feature set and hyperparameter values to improve classifier's final accuracy and F1-score.

Under this project, we propose an improved Software defect prediction framework a set of four machine learning classifiers:
1.SVM 
2.Decision Tree
3.KNN 
4.Naive Bayes
enhanced by Lyrebird optimization algorithm (LOA) which is employed with feature selection and hyperparameter tunning. 

Experiments on NASA PROMISE benchmark datasets (PC1, PC4, KC2, KC3 and MC1) indicate enhanced accuracy compared with Decision Tree that yields 98.74% on the MC1 dataset. The approach conducts pre-processing of data, performs dimensionality reduction and can be used for fast and reliable defect detection.
