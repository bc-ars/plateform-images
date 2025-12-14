# Structuration de la data

<p>&nbsp;</p>

Dans cette leçon, nous allons vous présenter la démarche ECOFLEX sur le thème de la structuration de la data. La data, ou les données, est en effet devenue une nouvelle richesse pour les entreprises en raison de sa valeur et de son potentiel pour générer des avantages compétitifs. Néanmoins, pour nuancer le tableau, il faut noter que le digital est responsable de 3 à 4 % des émissions mondiales de gaz à effet de serre.

<p>&nbsp;</p>

![data.gif](Structuration%20de%20la%20data/data.gif)

<p>&nbsp;</p>

# La data : une nouvelle richesse

<p>&nbsp;</p>

Tout d'abord, **la data représente un ensemble d'informations numériques collecté à partir de diverses sources**, telles que les transactions commerciales, les interactions clients, les capteurs, les réseaux sociaux, et autres. 

Les données jouent un rôle de plus en plus crucial dans tous les secteurs, y compris dans la construction. Les données sont générées à partir de différentes sources telles que : 

- les relevés topographiques ;
- les modèles 3D ;
- les systèmes de surveillance ;
- les capteurs IoT ;
- les historiques de maintenance, et autres.

**L'exploitation de ces données peut améliorer la productivité, l'efficacité, et la qualité des projets de construction.**

L'utilisation stratégique et intelligente des données peut avoir un impact significatif sur les performances des entreprises. En exploitant et en analysant les données de manière appropriée, les entreprises peuvent identifier des tendances, détecter des modèles, prévoir des comportements et prendre des décisions éclairées. 

**Dans le secteur de la construction, l'analyse des données peut contribuer à réduire les retards des projets, à minimiser les erreurs de conception, à optimiser l'utilisation des ressources et à améliorer la sécurité sur les chantiers.**

La data peut également stimuler l'innovation en permettant aux entreprises de découvrir de nouvelles idées, de développer de nouveaux produits ou services et d'adapter leurs offres aux besoins changeants du marché. 

<p>&nbsp;</p>

# La structuration de la donnée

<p>&nbsp;</p>

**Une structure de données est un format spécial destiné à organiser, traiter, extraire, et stocker des données.** Cette structure vise à organiser les données pour répondre à un besoin précis, afin de pouvoir y accéder et les traiter de façon appropriée. 

Dans le contexte du *Building Information Modelling* (BIM) et de la construction, **cela consiste à organiser les données liées au projet de construction, aux éléments du bâtiment** et aux processus associés.

La structuration des données permet d'attribuer des informations spécifiques à chaque élément du bâtiment, telles que sa fonction, sa localisation, ses caractéristiques techniques, ses performances énergétiques, et autres. Cela permet d'établir une relation claire entre les différentes données, créant ainsi un modèle cohérent et complet du bâtiment.

<p>&nbsp;</p>

# Caractéristiques

<p>&nbsp;</p>

Il existe plusieurs structures de données que nous allons vous présenter :

<p>&nbsp;</p>

![data1.png](Structuration%20de%20la%20data/data1.png)

<p>&nbsp;</p>

## Organisation des données

<p>&nbsp;</p>

- Il y a tout d'abord celles qui sont basées sur la façon dont les données sont organisées :
    - Si les éléments de données sont organisés chronologiquement de manière séquentielle, où chaque élément est lié au suivant et au précédent, alors les **données sont dites linéaires:**
    - **Les structures de données hiérarchiques** sont celles où les données sont organisées dans une structure en arborescence, avec des niveaux de parenté et de sous-niveaux ;
    - **Les structures de données tabulaires** sont celles où les données sont organisées dans des tableaux à deux dimensions, avec des rangées et des colonnes.

<p>&nbsp;</p>

## Opérations possibles sur les données

<p>&nbsp;</p>

Il existe aussi des structures basées sur les opérations possibles sur les données : 

- **Les structures de données statiques** fixent la taille des données à l'avance, elles ne peuvent pas être modifiées dynamiquement pendant l'exécution du programme ;
- **Les structures de données dynamiques** permettent de modifier la taille des données pendant l'exécution du programme.

<p>&nbsp;</p>

## Accessibilité des données

<p>&nbsp;</p>

Enfin, il y a des structures basées sur la manière dont les données sont accessibles : 

- **Les données sont accessibles séquentiellement**, c'est-à-dire une par une, en suivant un ordre déterminé ;
- **Les structures de données associatives** permettent aux données d'être associées à des clés uniques pour faciliter l'accès rapide.

<p>&nbsp;</p>

# Structuration des donnéess en BIM

<p>&nbsp;</p>

Il faut savoir que l'organisation et l'accessibilité des données sont intrinsèquement liées. La structuration des données en BIM repose sur certains principes clés qui permettent d'organiser et de rendre cohérentes les informations dans un modèle BIM. 

Voici une explication simple de ces principes à travers des exemples concrets :

<p>&nbsp;</p>

![data2.png](Structuration%20de%20la%20data/data2.png)

<p>&nbsp;</p>

- **Les normes de données, comme les IFC, sont des références communes utilisées dans le domaine du BIM pour assurer l'interopérabilité et l'échange d'information entre différents logiciels et acteurs**. Par exemple, si un architecte utilise un logiciel de conception et qu'un ingénieur utilise un logiciel de calcul de structure, les normes IFC permettent de garantir que les données du modèle BIM peuvent être échangées et interprétées correctement par les deux logiciels ;

<p>&nbsp;</p>

![data3.png](Structuration%20de%20la%20data/data3.png)

<p>&nbsp;</p>

- **La classification consiste à regrouper les objets du modèle BIM en catégories ou en classes selon des critères spécifiques.** Par exemple, les murs peuvent être classés en murs porteurs et non porteurs, en murs intérieurs et extérieurs, en murs de différentes hauteurs et ainsi de suite. Cette classification permet de structurer les données en les organisant de manière logique et cohérente. Cela facilite la recherche d'informations spécifiques et permet aux utilisateurs de comprendre rapidement la fonction et les caractéristiques des différents éléments du bâtiment ;

<p>&nbsp;</p>

![data4.png](Structuration%20de%20la%20data/data4.png)

<p>&nbsp;</p>

- **Les attributs sont des informations spécifiques associées à chaque objet du modèle BIM.** Par exemple, pour une porte, les attributs peuvent inclure la largeur, la hauteur, le matériau, la couleur, et ainsi de suite. En attribuant des attributs pertinents à chaque objet, les données deviennent plus riches et fournissent des détails importants sur les caractéristiques et les propriétés des éléments du bâtiment. Cela permet d'effectuer des recherches avancées, des filtrages, et des analyses plus précises.

En utilisant les standards de données, tels que les normes IFC, en classifiant les objets selon des critères pertinents et en attribuant des attributs appropriés, la structuration des données en BIM permet de rendre les informations cohérentes et compréhensibles pour tous les acteurs impliqués. Cela **facilite la collaboration** entre les différents métiers et **permet des échanges d'informations** fluides tout au long du cycle de vie du projet.

En résumé, la structuration des données en BIM repose sur l'utilisation de standards de données, la classification des objets et l'attribution d'attributs pertinents. Ces principes permettent de rendre les données cohérentes, compréhensibles, et facilement échangeables entre différents logiciels et acteurs du projet, favorisant ainsi la collaboration et l'efficacité dans la gestion des projets de construction.

<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>

[https://youtu.be/xE0NBfGY2cQ](https://youtu.be/xE0NBfGY2cQ)