---
layout: page
title: Alzheimer's disease classification
description: a classifier for Alzheimer's disease using genetic data
img: assets/img/alzheimers.webp
importance: 1
category: work
---

As part of my internship at the Agency for Science, Technology and Research (A*STAR), Institute for High Performance Computing (IHPC), I worked under Dr. Wu Yonghui to investigate methods to build classifiers for Alzheimer's disease based on genetic data. 

My internship focused on four different areas:

1. Feature selection
    - Monte Carlo Tree Search (MCTS)
        - MCTS is a best-first tree search algorithm first described by Romaric and Sebag. This can be used to run feature selection, a critical issue in genetic data as the number of features is in the order of millions and there are features with significant correlations. 
        - A notebook containing the experiments to run feature selection can be found [here](www.google.com).
        
    -  SparSNP
        - a tool used to fit lasso linear models for large SNP datasets, useful also for feature selection
	 
	- Notebook performing experiments with various feature selection methods, including Lasso, MCTS, Variance Inflation Factors (VIFs) and SparSNP can be found [here](www.google.com)
	 
2. Reinforcement Learning

	a. An attempt was made to use reinforcement learning methods, specifically Deep Q-Networks (DQN) and PPO (proximal policy optimiztaion) to perform classification. The notebook can be found [here](www.google.com)
	 - Can Reinforcement Learning be used in classification.pptx (presentation on using DQN, PPO and MCTS feature selection with comparison to other machine learning techniques)
		
3. Logic Regression

    - I investigated the use of logic regression, a method for ensembling binary classifiers by [Kooperberg and Ruczinski](www.google.com).
    - [Monte Carlo Logic Regression](www.google.com) was implemented and the notebook can be found [here](www.google.com)
	
4. Investigated ratio of features to samples. Powerpoint presentation can be found [here](/assets/img/alzheimers.webp)
