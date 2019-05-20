This repository contains links to the projects made by the Team LIRIS DM2L:
# Subgroup Discovery / Exceptional Model Mining

* __RefineAndMine__
  * https://github.com/Adnene93/RefineAndMine
  * > [	Aimene Belfodil, Adnene Belfodil, Mehdi Kaytoue: Anytime Subgroup Discovery in Numerical Domains with Guarantees. ECML/PKDD (2) 2018: 500-516]

* MCTS4DM: Pattern mining & Subgroup Discovery with Monte Carlo Tree Search. By formally defining pattern mining as a game, we can  solve it with Monte Carlo tree search (MCTS). It can be seen as an exhaustive search guided by random simulations which can be stopped early (limited budget) by virtue of its best-first search property. MCTS4DM allows one to mine subgroups in symbolic/numerical data (considering all possible intervals without discretization) with various quality measure (such as the weighted relative accuracy) and can be easily extended to other measures.
  * https://github.com/guillaume-bosc/MCTS4DM
  * > [Guillaume Bosc, Jean-François Boulicaut, Chedy Raïssi, Mehdi Kaytoue:
Anytime discovery of a diverse set of patterns with Monte Carlo tree search. Data Min. Knowl. Discov. 32(3): 604-650 (2018)]

# Pattern mining algorithms for attributed graphs

* ENERGETICS and EXPRESS are two algorithms that allow to discover exceptional patterns in vertex attributed graphs. ENERGETICS is an exhaustive algorithm while EXPRESS is an output space sampling algorithm. These algorithms were presented at IEEE ICDM 2016. For more details:
  * https://github.com/AnesBendimerad/Exceptional-Sub-graph-Mining

  * > [A. Bendimerad, M. Plantevit, C. Robardet. Unsupervised Exceptional Attributed Sub-graph Mining in Urban Data. In ICDM 2016.] 
  
* CENERGETICS and EXCESS   are built respectively on top  ENERGETICS and EXPRESS by considering closed patterns. For more details: 
  * https://github.com/AnesBendimerad/ClosedExceptionalSubgraphMining/tree/master/Algorithms
  * > [Ahmed Anes Bendimerad, Marc Plantevit, Céline Robardet: Mining exceptional closed patterns in attributed graphs. Knowl. Inf. Syst. 56(1): 1-25 (2018)]
 
* COSMIC allows the discovery of exceptional subgraphs in __edge-attributed graphs__. For more details: 
  * https://github.com/mehdi-kaytoue/contextual-exceptional-subgraph-mining
  * > [Mehdi Kaytoue, Marc Plantevit, Albrecht Zimmermann, Ahmed Anes Bendimerad, Céline Robardet: Exceptional contextual subgraph mining. Machine Learning 106(8): 1171-1211 (2017)]

# Pattern mining algorithms for sequences 
* BalanceSpan is an algorithm designed to extract frequent patterns (strategies) from StarCraft II replays. It efficiently computes a measure that evaluates the balance of a strategy, i.e., if the strategy is likely to win or to lose. It allows the user (i) studying his opponent in an E-sport match, (ii) learning from his own games, and (iii), for the game editor, to study if the rules of the game needs to be adapted due to imbalanced strategies used too often.
  * http://guillaume-bosc.github.io/BalanceSpan/
  * >[Guillaume Bosc, Philip Tan, Jean-François Boulicaut, Chedy Raïssi, Mehdi Kaytoue:
A Pattern Mining Approach to Study Strategy Balance in RTS Games. IEEE Trans. Comput. Intellig. and AI in Games 9(2): 123-132 (2017)]

* SITS-P2miner is a mining system for extracting patterns from Satellite Image Time Series. It includes four main modules for pre-processing, pattern extraction, pattern ranking and pattern visualization. It is based on the extraction of grouped frequent sequential patterns and on swap randomization.
  * https://sites.google.com/view/sits-p2miner
  * > [N. Meger, C. Rigotti, C. Pothier, T. Nguyen, F. Lodge, L. Gueguen, R. Andreoli, M.-P. Doin and M. Datcu. Ranking Evolution Maps for Satellite Image Time Series Exploration - Application to Crustal Deformation and Environmental Monitoring. In journal: Data Mining and Knowledge Discovery. Springer, 2019, 33 (1), pp.131-167.]
  
# Data generators
* [A. Bendimerad, V. Codocedo, J.-F. Boulicaut, M. Kaytoue. Generating EPCIS events data with the video game OpenTTD, 2016](https://anesbendimerad.github.io/EPCIS-Events-Generator-Based-On-OpenTTD/)

# Python library
* CDlib is a python library dedicated to the community detection problem on graphs. It contains implementation of algorithms, evaluation functions, visualizations, and other tools related to this research topic. 
  * https://github.com/GiulioRossetti/cdlib
  * Article: [G. Rossetti, L. Milli, R. Cazabet. CDlib: a Python Library to Extract, Compare and Evaluate Communities from Complex Networks, Sumbitted]
