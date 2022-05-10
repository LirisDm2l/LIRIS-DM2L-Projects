This repository contains links to the projects made by the Team LIRIS DM2L:
# Subgroup Discovery / Exceptional Model Mining

* __RefineAndMine__ is an algorithm for discovering subgroups in numerical data. It has three key properties w.r.t. the state of the art: (i) It yields progressively interval patterns whose quality improves over time; (ii) It can be interrupted anytime and always gives a guarantee bounding the error on the top pattern quality and (iii) It always bounds a distance to the exhaustive exploration. 
  * https://github.com/Adnene93/RefineAndMine
  * > [	Aimene Belfodil, Adnene Belfodil, Mehdi Kaytoue: Anytime Subgroup Discovery in Numerical Domains with Guarantees. ECML/PKDD (2) 2018: 500-516]

* __MCTS4DM__: Pattern mining & Subgroup Discovery with Monte Carlo Tree Search. By formally defining pattern mining as a game, we can  solve it with Monte Carlo tree search (MCTS). It can be seen as an exhaustive search guided by random simulations which can be stopped early (limited budget) by virtue of its best-first search property. MCTS4DM allows one to mine subgroups in symbolic/numerical data (considering all possible intervals without discretization) with various quality measure (such as the weighted relative accuracy) and can be easily extended to other measures.
  * https://github.com/guillaume-bosc/MCTS4DM
  * > [Guillaume Bosc, Jean-François Boulicaut, Chedy Raïssi, Mehdi Kaytoue:
Anytime discovery of a diverse set of patterns with Monte Carlo tree search. Data Min. Knowl. Discov. 32(3): 604-650 (2018)]

* __DSC__: Exceptional Model Mining in vote or rating data. This algorithm makes it possible to discover exceptional (dis)agreements between two groups of individuals. The discovered patterns are of the form (c,g1,g2) where __c__ is the context in which an exceptional (dis)agreement is observed between the two groups of individuals __g1__ and __g2__.
  * https://github.com/Adnene93/DiscoveringSimilarityChanges
  * > [Adnene Belfodil, Sylvie Cazalens, Philippe Lamarre, Marc Plantevit: Flash Points: Discovering Exceptional Pairwise Behaviors in Vote or Rating Data. ECML/PKDD (2) 2017: 442-458]

* __Olfamine__: Linking molecules to their odors with supervised descriptive rules discovery.
  * https://projet.liris.cnrs.fr/olfamine/
  * >[Guillaume Bosc, Marc Plantevit, Jean-François Boulicaut, Moustafa Bensafi, Mehdi Kaytoue: h(odor): Interactive Discovery of Hypotheses on the Structure-Odor Relationship in Neuroscience. ECML/PKDD (3) 2016: 17-21]
  * >[Licon CC, Bosc G, Sabri M, Mantel M, Fournel A, Bushdid C, et al. (2019) Chemical features mining provides new descriptive structure-odor relationships. PLoS Comput Biol 15(4): e1006945. https://doi.org/10.1371/journal.pcbi.1006945]
  
 * __MICA_Miner__: Mining contrastive antichains in hierarchies. 
   * https://bitbucket.org/ghentdatascience/mica-miner/src/master/
   * >[Anes Bendimerad, Jefrey Lijffijt, Marc Plantevit, Céline Robardet, and Tijl De Bie. 2019. Contrastive antichains in hierarchies. In The 25th ACM SIGKDD Conference on Knowledge Discovery and Data Mining (KDD ’19).]

# Pattern mining algorithms for attributed graphs

* __ENERGETICS__ and __EXPRESS__ are two algorithms that allow to discover exceptional patterns in __vertex attributed graphs__. ENERGETICS is an exhaustive algorithm while EXPRESS is an output space sampling algorithm. These algorithms were presented at IEEE ICDM 2016. For more details:
  * https://github.com/AnesBendimerad/Exceptional-Sub-graph-Mining

  * > [A. Bendimerad, M. Plantevit, C. Robardet. Unsupervised Exceptional Attributed Sub-graph Mining in Urban Data. In ICDM 2016.] 
  
* __CENERGETICS__ and __EXCESS__   are built respectively on top  ENERGETICS and EXPRESS by considering closed patterns. For more details: 
  * https://github.com/AnesBendimerad/ClosedExceptionalSubgraphMining/tree/master/Algorithms
  * > [Ahmed Anes Bendimerad, Marc Plantevit, Céline Robardet: Mining exceptional closed patterns in attributed graphs. Knowl. Inf. Syst. 56(1): 1-25 (2018)]
  
* __SIAS_MINER__ allows the discovery of subjectively interesting patterns in __vertex attributed graphs__ by taking into account the background knowledge. 
  * https://github.com/AnesBendimerad/SIAS-miner
  * > [Bendimerad, A., Mel, A., Lijffijt, J., Plantevit, M., Robardet abd C., De Bie, T. Data Min Knowl Disc (2019). https://doi.org/10.1007/s10618-019-00664-w]

 
* __COSMIC__ allows the discovery of exceptional subgraphs in __edge-attributed graphs__. For more details: 
  * https://github.com/mehdi-kaytoue/contextual-exceptional-subgraph-mining
  * > [Mehdi Kaytoue, Marc Plantevit, Albrecht Zimmermann, Ahmed Anes Bendimerad, Céline Robardet: Exceptional contextual subgraph mining. Machine Learning 106(8): 1171-1211 (2017)]

# Pattern mining algorithms for sequences 
* __BalanceSpan__ is an algorithm designed to extract frequent patterns (strategies) from StarCraft II replays. It efficiently computes a measure that evaluates the __balance of a strategy__, i.e., if the strategy is likely to win or to lose. It allows the user (i) studying his opponent in an E-sport match, (ii) learning from his own games, and (iii), for the game editor, to study if the rules of the game needs to be adapted due to imbalanced strategies used too often.
  * http://guillaume-bosc.github.io/BalanceSpan/
  * >[Guillaume Bosc, Philip Tan, Jean-François Boulicaut, Chedy Raïssi, Mehdi Kaytoue:
A Pattern Mining Approach to Study Strategy Balance in RTS Games. IEEE Trans. Comput. Intellig. and AI in Games 9(2): 123-132 (2017)]

* __SITS-P2miner__ is a mining system for extracting patterns from Satellite Image Time Series. It includes four main modules for pre-processing, pattern extraction, pattern ranking and pattern visualization. It is based on the extraction of grouped frequent sequential patterns and on swap randomization.
  * https://sites.google.com/view/sits-p2miner
  * > [N. Meger, C. Rigotti, C. Pothier, T. Nguyen, F. Lodge, L. Gueguen, R. Andreoli, M.-P. Doin and M. Datcu. Ranking Evolution Maps for Satellite Image Time Series Exploration - Application to Crustal Deformation and Environmental Monitoring. In journal: Data Mining and Knowledge Discovery. Springer, 2019, 33 (1), pp.131-167.]

# Other pattern domains
* __MCPP__: Mining Convex Polygon Patterns in Spatial Datasets. Pattern mining considers the search space of numerical data as a set of hyperectangles with sides parallel to the cordinates. We present here several algorithms to mine more expresive numerical patterns: convex polygons.
  * https://github.com/BelfodilAimene/MiningConvexPolygonPatterns
  * > [Aimene Belfodil, Sergei O. Kuznetsov, Céline Robardet, Mehdi Kaytoue: Mining Convex Polygon Patterns with Formal Concept Analysis. IJCAI 2017: 1425-1432]


# Data generators
* EPCIS is a GS1 standard to encode products as they travel throughout the supply chain. As this kind of data is generally sensitive, and because random generators can not easily capture real behaviors, we propose to capture data from the famous game OpenTTD version 1.5.0. This plugin captures all the transportation and the manufacturing events that happen in the game (made by real players of the myriad of available artificial agents) and writes them into an output file using the EPCIS format.
  * https://anesbendimerad.github.io/EPCIS-Events-Generator-Based-On-OpenTTD/
  * [A. Bendimerad, V. Codocedo, J.-F. Boulicaut, M. Kaytoue. Generating EPCIS events data with the video game OpenTTD, 2016]

# Python library
* __CDlib__ is a python library dedicated to the community detection problem on graphs. It contains implementation of algorithms, evaluation functions, visualizations, and other tools related to this research topic. 
  * https://github.com/GiulioRossetti/cdlib
  * Article: [G. Rossetti, L. Milli, R. Cazabet. CDlib: a Python Library to Extract, Compare and Evaluate Communities from Complex Networks, Sumbitted]

* __tnetwork__ is a python library dedicated to the manipulation of temporal/dynamic networks, and in particular for dynamic community detection. It contains implementation of algorithms, evaluation functions, visualizations, and other tools related to this research topic. 
  * https://tnetwork.readthedocs.io/en/latest/
  * https://github.com/Yquetzal/tnetwork
  * Article: [G. Rossetti, L. Milli, R. Cazabet. CDlib: a Python Library to Extract, Compare and Evaluate Communities from Complex Networks, Sumbitted]

# Chatbot
  * __chatbotinfo__  is a context aware  education chatbot based on hierarchical recurrent attention network. This chatbot is now online and answer to questions from applicants to the Master in Data Science of University CLaude Bernard Lyon 1.   
  * chatbotinfo.univ-lyon1.fr
  * Article: [J-B. Aujogue and Alex Aussem. Hierarchical Recurrent Attention Networks for Context-Aware Education Chatbots. International Joint Conference on Neural Networks (IJCNN), Budapest, Hungary, July 14-19, 2019.]
