

### Exceptional Model Mining meets Multi-objective Optimization
**Day and Time**: February 5, 13h

**Speaker**: Alexandre Millot, DM2L

**Abstract** : 
Exceptional Model Mining (EMM) is a local pattern mining framework that generalizes subgroup discovery. In EMM, we look for subsets of objects - subgroups - whose model deviates significantly from the same model fitted on the overall dataset. Multi-objective Optimization (MOO) is an area of Multiple Criteria Decision Making where two or more functions need to be optimized at the same time and the goal is to find the best compromise between the concurrent objectives. We introduce a new model class for EMM in a MOO setting called Exceptional Pareto Front Mining. We design fitting quality measures that take into account both the difference between models and the relevance of the subgroups and study the discovery 4 skyline patterns according to said measures. We propose beam search based algorithms for EMM whose added-value is studied on both synthetic and real life datasets. Among others, we discuss a use case on hyperparameter optimization in machine learning for both regression and multi-label classification.

----
### Recherche et développement de nouvelles méthodes AIOps pour la maintenance préventive d’un grand parc de serveurs d’applications.
**Day and Time**:January 29, 2021, 13h

**Speaker**: Youcef Remil, DM2L/Infologic

**Abstract**: 
Les processus de la maintenance industrielle constituent un pilier de la productivité des entreprises. Ainsi, de nombreux types de maintenance coexistent afin de fournir aux industriels des possibilités d’optimisation de leurs chaînes de production, de réduire les coûts, de garantir la qualité de la production et préserver l’image de marque de l’entreprise. La maintenance préventive cherche à anticiper et à prévoir un dysfonctionnement. Les solutions classiques de maintenance préventive sont généralement basées sur des systèmes à bases de règles. Ces systèmes nécessitent de déclarer explicitement des règles d'alertes sur les flux de données. Ces derniers sont limités car ils ne permettent pas un passage efficace à l'échelle et font face aux limites connues des systèmes experts : la maintenance d’une base de règle et le contrôle de sa cohérence deviennent très rapidement une tâche difficile, voire impossible. Par contre, les règles, utilisées pour gérer des cas simples, sont très puissantes. Il faut donc les coupler avec des techniques plus sophistiquées d’apprentissage et détection d’anomalies, qui en retour peuvent souffrir de problèmes d’interprétation des prédictions ou de levées d’alertes. L'objectif principal de la thèse est de concevoir et mettre en œuvre des méthodes d'intelligence artificielle afin d'automatiser au maximum le processus de maintenance préventive et corrective. La réalisation de ce projet nécessite toutefois de répondre à plusieurs problématiques complexes liées d'un côté à la nature et la quantité des données, et d'un autre côté aux contraintes applicatives. En effet, cela nécessite de traiter efficacement et en temps réel un flux de données qui sont hétérogènes et en évolution continue, et réussir à en extraire des informations utiles et actionnables à l’aide de modèles de détection puissants et interprétables, sans quoi certaines prises de décision sont impossibles. La découverte de sous-groupes est une technique qui se révèle aujourd’hui très pertinente pour “faire parler” les modèles performants dits "boîtes-noires", une piste que nous allons développer dans cette thèse. Les complexités et les enjeux liés à cette problématique font d'elle un sujet de recherche très actif, tant au niveau applicatif que théorique (sous le vocable anglais AIOps, resp. XAI pour Explainability).

---
### Recommandation séquentielle et explications ###
**Day and Time**:January 07, 2021, 14h

**Speaker**: Corentin Lonjarret, DM2L/Visiativ

**Abstract**: 
Ces dernière années, les systèmes de recommandation ont reçu beaucoup d'attention avec l'élaboration de nombreuses propositions qui tirent parti des nouvelles avancées dans les domaines du Machine Learning et du Deep Learning. Grâce à l'automatisation de la collecte des données des actions des utilisateurs tels que l'achat d'un objet, le visionnage d'un film ou le clic sur un article de presse, les systèmes de recommandation ont accès à de plus en plus d'information. Ces données sont des retours implicites des utilisateurs (appelé «~implicit feedback~» en anglais) et permettent de conserver l'ordre séquentiel des actions de l’utilisateur. C'est dans ce contexte qu'ont émergé les systèmes de recommandations qui prennent en compte l’aspect séquentiel des données. Le but de ces approches est de combiner les préférences des utilisateurs (le goût général de l’utilisateur) et la dynamique séquentielle (les tendances à court terme des actions de l'utilisateur) afin de prévoir la ou les prochaines actions d'un utilisateur.
Dans cette thèse, nous étudions la recommandation séquentielle qui vise à prédire le prochain article/action de l'utilisateur à partir des retours implicites des utilisateurs. Notre principale contribution, REBUS, est un nouveau modèle dans lequel seuls les items sont projetés dans un espace euclidien d'une manière qui intègre et unifie les préférences de l'utilisateur et la dynamique séquentielle. Pour saisir la dynamique séquentielle, REBUS utilise des séquences fréquentes afin de capturer des chaînes de Markov d'ordre personnalisé. Nous avons mené une étude empirique approfondie et démontré que notre modèle surpasse les performances des différents modèles de l’état de l’art, en particulier sur des jeux de données éparses. Nous avons également intégré REBUS dans myCADservices, une plateforme collaborative de la société française Visiativ. Nous présentons notre retour d'expérience sur cette mise en production du fruit de nos travaux de recherche.
Enfin, nous avons proposé une nouvelle approche pour expliquer les recommandations fournies aux utilisateurs. Le fait de pouvoir expliquer une recommandation permet de contribuer à accroître la confiance qu'un utilisateur peut avoir dans un système de recommandation. Notre approche est basée sur la découverte de sous-groupes pour fournir des explications interprétables d'une recommandation pour tous types de modèles qui utilisent comme données d’entrée les retours implicites des utilisateurs.

---
### Some challenges surrounding recent advances in computational social sciences
**Day and Time**:December 11, 2020, 11h

**Speaker**: Pedro Ramaciotti, Medialab Science Po

**Abstract**:  At the interface between sociology, mathematics, political, and computer science,
computational social science seeks to match concepts from research questions in the humanities, 
to computational methods and quantifiable measures.
One prolific area of research is the mining of opinions and ideologies
from social networks for the study of phenomena such as polarization or fragmentation (the so-called bubbles).
In this brief presentation, we will analyze case studies in ideology mining on social networks
 in order to identify promising areas of collaboration with computer sciences.
In particular, we will examine the case of the extraction and validation of ideologies on Twitter in France 
in connection with different research programs in political sciences. This will provide the setting
for an exploration into possible data mining research programs regarding multi-dimensional network scaling and 
graph models for the study of social networks and ideologies.


---
### Leveraging semantic for community mining in multilayer networks
**Day and Time**: October 8, 2020, 12h30

**Speaker**: Mohamed Benabdelkrim, DM2L 

**Abstract**: We introduce a method for community detection in multilayer networks with semantic attributes. We use the framework of multiplex graphs, endowed with layers' text attributes. We evaluate semantic similarities of nodes across layers by computing sentence embeddings. A generalization of the membership of nodes to layers is proposed to take into account the semantic similarities. We extract a set of diversified communities by grouping nodes with similar high membership values. A community is specified by an interval of membership values for each layer. We propose a method based on closed interval patterns on the numerical dataset crossing nodes with layers, whose entries are membership values, that detects top-ranked diversified communities of nodes across semantically similar layers. We compare our results to two algorithms from the literature, showing in particular, that our method is better fit to analyse networks with large numbers of layers.

---
### Détection d'anomalies dans les flux de données par structure d'indexation et approximation. Application à l'analyse en continu des flux de messages du système d'information de la SNCF

**Day and Time**: October 1, 2020, 12h30

**Speaker**: Lucas Foulon, DM2L/SNCF

**Abstract**: Dans cette thèse, nous proposons des méthodes de calcul approchées d'un score d'anomalie, pouvant être mises en oeuvre sur des flux de données pour détecter des portions anormales. La difficulté du problème est de deux ordres. D'une part, la haute dimensionnalité des objets manipulés pour décrire les séries temporelles extraites d'un flux brut, et d'autre part la nécessité de limiter le coût de détection afin de pouvoir la réaliser en continu au fil du flux. Concernant le premier aspect du problème, notre étude bibliographique a permis de sélectionner un score de détection d'anomalies proposé récemment, le score CFOF, qui est le seul pour lequel il existe des garanties formelles quant à son adéquation pour les données en haute dimensionnalité. Nos contributions ont alors porté sur la proposition de deux méthodes d'approximation du score CFOF pour permettre son usage en continu sur des flux. La première est une approche combinant élagage et approximation lors du parcours des voisinages dans l'espace de description des objets. Notre second apport est une approximation par agrégation de scores obtenus sur des sous-espaces, qui complète la première contribution et se combine avec elle. Nous avons montré sur une collection de jeux de données, utilisés comme cadre d'évaluation de référence dans le domaine, que nos méthodes permettaient des gains importants en temps de calcul, tout en fournissant des approximations qui préservent la qualité des détections. Enfin, nous présentons également l'application de ces approches au sein du système d'information de la SNCF dans lequel de nombreux flux sont collectés en temps réel, transformés et rediffusés. Dans ce contexte, nous avons étendu la supervision de bout-en-bout existante par la mise en oeuvre d'un outil d'aide à la détection d'anomalies sur le flux de messages entrant d'une des principales plateformes de traitement.

---
### Rule discovery in labeled sequential data: application to game analytics.
**Day and Time**: September 25, 12h30

**Speaker**: Romain Mathonat, DM2L/Atos 

**Abstract**:  It is extremely useful to exploit labeled datasets not only to learn models and perform predictive analytics but also to improve our understanding of a domain and its available targeted classes. The subgroup discovery task has been considered for more than two decades. It concerns the discovery of rules covering sets of objects having interesting properties, e.g., they characterize a given target class. Though many subgroup discovery algorithms have been proposed for both transactional and numerical data, discovering rules within labeled sequential data has been much less studied.

In that context, exhaustive exploration strategies can not be used for real-life applications and we have to look for heuristic approaches. In this thesis, we propose to apply bandit models and Monte Carlo Tree Search to explore the search space of possible rules using an exploration-exploitation trade-off, on different data types such as sequences of itemset or time series. For a given budget, they find a collection of top-k best rules in the search space w.r.t chosen quality measure. They require a light configuration and are independent from the quality measure used for pattern scoring. To the best of our knowledge, this is the first time that the Monte Carlo Tree Search framework has been exploited in a sequential data mining setting. We have conducted  thorough and comprehensive evaluations of our algorithms on several datasets to illustrate their added-value, and we discuss their qualitative and quantitative results.

To assess the added-value of one or our algorithms, we propose a use case of game analytics, more precisely Rocket League match analysis. Discovering interesting rules in sequences of actions performed by players and using them in a supervised classification model shows the efficiency and the relevance of our approach in the difficult and realistic context of high dimensional data. It supports the automatic discovery of skills and it can be used to create new game modes, to improve the ranking system, to help e-sport commentators, or to better analyse opponent teams, for example.

---
###  Graph Neural Networks and an application to traffic speed prediction

**Day and Time**: June 25, 2020, 16h

**Speaker**: Fabio Mensi

---
### Word embeddings et Deep Learning pour la segmentation automatique de textes et l’extraction d’informations géographiques. 

**Day and Time**: June 18, 2020, 16h

**Speaker**: Hussam Ghanem

---
### Classification des entités du réseau de Bitcoin

**Day and Time**: June 11, 2020, 16h

**Speaker**: Théo Rabut

---
### Détection de communautés dans les graphes dynamiques

**Day and Time**: June 4, 2020, 16h

**Speaker**: Fabrice Lécuyer 

---
### Vers une identification des utilisateurs Bitcoin

**Day and Time**: May 28, 2020, 16h

**Speaker**: Rafael Ramos Tubino, D2ML


---
### Approches ML pour la prévision des prix de l’électricité sur le marché européen

**Day and Time**: May 14, 2020, 16h

**Speaker**: Léonard Tschora, DM2L/BCM Energy


---
### Contribution à la découverte de sous-groupes corrélés : Application à l’analyse des systèmes territoriaux et des réseaux alimentaires

**Day and Time**: May 7, 2020, 16h

**Speaker**: Mohamed Ali Hammal, DM2L


 
---
### Comparaison de modèles statistiques de graphe

**Day and Time**: April 30, 2020, 16h

**Speaker**: Louis Duvivier, DM2L

**Abstract**: De nombreux modèles existent pour tenter d'expliquer la structure des graphes comme résultant d'une répartition aléatoire des arêtes soumises à certaines contraintes : distribution de degré, densité entre certains groupes de noeuds, distance entre les noeuds, etc. En pratique, face à un réseau, la question se pose de savoir quel modèle choisir. Or, la diversité de ces modèles, qui utilisent des paramètres différents en nombre et en nature, fait qu'il n'existe pas de dénominateur commun sur la base duquel ils pourraient être facilement comparés entre eux.

Dans cette présentation, je présenterai plusieurs pistes pour tenter de résoudre ce problème, en s'appuyant d'une part sur des espaces de graphes dotés à la fois d'une structure géométrique et probabiliste, et d'autre part sur la théorie de l'information et la longueur de description minimale.


---
### Exploitation de l'information géographique dans les données textuelles hétérogènes

**Day and Time**: April 17, 2020, 16h

**Speaker**: Jacques Fize, DM2L

**Abstract**: Dans la communauté des sciences de l'information géographique (ou GIS), il existe un sous-domaine particulier qui se focalise sur l'exploitation de l'information géographique dans les données textuelles (news, réseaux sociaux, documents historiques, etc.). Dans une première partie, je présenterai les travaux menées durant ma thèse sur le thème de la mise en correspondance de données textuelles hétérogènes fondée sur la spatialité. Puis, dans une seconde partie je détaillerai les travaux en cours sur le geocoding réalisés dans le cadre du projet HextGEO dont l’objectif est de concevoir des modèles et de développer une plateforme pour extraire et analyser les informations géographiques présentes dans des données textuelles hétérogènes. 
Le geocoding regroupe les techniques permettant d'associer des coordonnées à un nom de lieu (ou toponyme). Nous proposons ici un modèle de geocoding s'appuyant sur deux toponymes et qui renvoie des coordonnées en latitude-longitude. Les coordonnées retournées correspondent à celles du premier toponyme. Le second toponyme est utilisé comme contexte pour réduire les ambiguïtés (Paris, FR ou Paris,US?). Le modèle que nous proposons s'appuie sur un réseau de neurones récurrents (Bi-LSTM) et une transformation des toponymes en n-grams de caractères. Pour entraîner notre modèle, nous utilisons des cooccurrences de toponymes dans divers contextes : textuels (i.e. articles de Wikipédia) et géographiques (i.e. inclusion et proximité de lieux basées sur les données de Geonames). Enfin, je présenterai les résultats de nos premières expérimentations construites à partir de différents contextes géographiques : (i) un contexte local correspondant à la France métropolitaine ; (ii) un contexte plus large correspondant à l'État du Texas et à la région Île-de-France.




