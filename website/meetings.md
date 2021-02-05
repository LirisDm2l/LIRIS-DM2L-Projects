

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




