---
layout: page
title: Alzheimer's disease classification
description: a classifier for Alzheimer's disease using genetic data
img: assets/img/bears.jpg
importance: 1
category: work
---

As part of my internship at the Agency for Science, Technology and Research (A*STAR), Institute for High Performance Computing (IHPC), I worked under Dr. Wu Yonghui to investigate methods to build classifiers for Alzheimer's disease based on genetic data. 

1. Feature Selection
Folder containing material related to feature selection, and includes additional subfolders:

	a. MCTS
	folder containing material related to feature selection using Monte Carlo Tree Search based on the paper by Romaric and Sebag
	 - Feature Selection as a One-Player Game.pdf (the paper by Romaric and Sebag)
	 - MCTS and Feature Selection.pptx (slides explaining the paper)
	 - Monte Carlo Tree Search - From Playing Go to Feature Selection.pdf (slides created by paper authors to explain the paper)
	 - notebook (folder containing Jupyter notebook containing code snippets to run MCTS feature selection. contains example alzheimers dataset as well)
	 - alphaFUSE (folder containing program for MCTS feature selection algorithm)
	 
	b. SparSNP
	folder containing material related to SparSNP, a tool used to fit lasso linear models for large SNP datasets, useful also for feature selection
	 - SparSNP.pptx (slides explaining the paper)
	 - sparsnp_paper.pdf (the paper explaining SparSNP)
	 - SparSNP (folder containing the SparSNP program - run on linux/WSL)
	 - cmd.txt (contains bash arguments to run SparSNP on linux)
	 - SparSNP_processing.ipynb (to process the topsnps.csv file produced by SparSNP)
	 
	- Feature_selection_comparison_VIFs,_MCTS,_Lasso,_SparSNP.ipynb (jupyter notebook performing experiments with various feature selection methods, including Lasso, MCTS, Variance Inflation Factors (VIFs) and SparSNP)
	 
2. Reinforcement Learning
Folder containing material related to reinforcement learning

	a. Alphago
	folder containing material related to AlphaGo/AlphaGo Zero/MuZero
	 - Alphago Zero.pptx (slides explaining the three AlphaGos)
	 - Reinforcement Learning, AlphaZero and MuZero.pptx (simpler presentation on Reinforcement Learning)
	 - DQN, PPO.pptx (slides explaining Deep Q Networks and Proximal Policy Optimisation with results of using DQN and PPO on the alzheimer's dataset
	 - notebook (folder containing jupyter notebook for running DQN, PPO on alzheimer's dataset, with comparison to other methods)
	 - Can Reinforcement Learning be used in classification.pptx (presentation on using DQN, PPO and MCTS feature selection with comparison to other machine learning techniques)
	 
3.GenNet
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

