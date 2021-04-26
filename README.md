# FRE-7121-Final-Project: Coevolutionary Algorithms and Pairs Trading
Author: Raymond Luo, Zhiheng Wang

This is the repo for FRE 7121 Stastical Arbitrage Final Project: Coevolutionary Algorithms and Pairs Trading.

## Background
In the paper A Game-Theoretical Approach for Designing Market Trading Strategies, the authors suggest using co-evolve fuzzy trading rules to handle the partial form features. The results show that the coevolutionary process creates trading rule-bases that produce positive returns. While the authors also suggest some possible improvements of their model, our team further investigates this problem by first recreating their program and then modifying the statistics. Our conclusion is that out algorithm is valid by not beating
the Brownian Simulation while also producing optimized strategies.

## Methods
While the original authors utilized co-evolutionary algorithms, and the LEAP library provides various examples to implement co-evolutionary and island models, we chose to design our own classes to implement a singular evolution algorithm. The process of generating an optimized strategy with genetic algorithm follows
the following steps:
1. Calculate related features day membership with fuzzification and defuzzification
2. Generate a population
3. Evolve the population with training environment (trading data) and mutation
4. Test resulted optimized strategies with testing environment

The below mentioned methods are originated from the original project, where the author provided detailed functions and possible parameters values. They first defined feature days and membership functions to predict trading day, then they briefly introduced their co-evolution algorithm. Our trading mechanics are in the same manner as the original project but our evolution algorithm are modified for better fitness judgement.

## Details
Our work can be retrieved in the final project notebook and membership functions notebook. The final paper is in the FRE_GY_7121_Final_Project Report.pdf file. 
