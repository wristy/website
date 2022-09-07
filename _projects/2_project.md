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
	 
	- Notebook performing experiments with various feature selection methods, including Lasso, MCTS, Variance Inflation Factors (VIFs) and SparSNP.
	 
2. Reinforcement Learning
Folder containing material related to reinforcement learning

	a. Alphago
	folder containing material related to AlphaGo/AlphaGo Zero/MuZero
	 - Alphago Zero.pptx (slides explaining the three AlphaGos)
	 - Reinforcement Learning, AlphaZero and MuZero.pptx (simpler presentation on Reinforcement Learning)
	 - DQN, PPO.pptx (slides explaining Deep Q Networks and Proximal Policy Optimisation with results of using DQN and PPO on the alzheimer's dataset
	 - notebook (folder containing jupyter notebook for running DQN, PPO on alzheimer's dataset, with comparison to other methods)
	 - Can Reinforcement Learning be used in classification.pptx (presentation on using DQN, PPO and MCTS feature selection with comparison to other machine learning techniques)
	 
3. GenNet
folder containing material related to GenNet (run on linux machine)
	 - GenNet (folder containing the GenNet program)
	 - cmd.txt (folder containing the command arguments to run GenNet on Linux)
	 - GenNet framework - interpretable neural networks for phenotype prediction.pdf (the paper describing GenNet)
	
4. Logic Regression
Folder containing material related to Logic Regression based on the paper by Kooperberg and Ruczinski
	- Identifying Interacting SNPs Using Monte Carlo Logic Regression.pdf (the paper)
	- Identifying Interacting SNPs Using Monte Carlo Logic Regression.pptx (powerpoint presentation on the paper)
	- LogicReg.pdf (documentation for the R package implementing Monte Carlo Logic Regression)
	- notebook (folder containing code and files for analysing the sample Alzheimers dataset using monte carlo logic regression)
	
5. Misc
Folder containing various other presentations and papers
	- AI + Genetics.pptx (AI Genetic companies)
	- Biobank UK.pptx (information on the Biobank dataset)
	- Deep Learning Classification of Polygenic Obesity using Genome.pptx (presentation on the paper Deep Learning Classification of Polygenic Obesity.pdf)
	- Ratio of Features to Samples.pptx (compilation of information on the recommended ratio of features to samples)
	- Public_SNP_Genotype_plink_data.pptx (various publicly available SNP data)

