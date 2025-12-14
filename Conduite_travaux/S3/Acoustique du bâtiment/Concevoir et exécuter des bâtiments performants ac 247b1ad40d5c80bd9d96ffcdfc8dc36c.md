# Concevoir et exécuter des bâtiments performants acoustiquement : théorie et terrain

<p>&nbsp;</p>

## Théorie

<p>&nbsp;</p>

### Indices essentiels à maîtriser

<p>&nbsp;</p>

Chaque produit utilisé dans la construction d’un bâtiment possède une **performance acoustique propre** mesurée en laboratoire : **l’indice d’affaiblissement**.

À la fin du chantier, des **mesures acoustiques** sont réalisées pour déterminer les **isolements acoustiques** finaux, lesquels sont comparés aux objectifs définis dans la **notice acoustique**.

Le tableau suivant expose les principaux **indices liés aux bruits aériens** à connaître :

| Origine du bruit | Bruit aérien INTÉRIEUR | Bruit aérien EXTÉRIEUR |
| --- | --- | --- |
| Quelle performance est évaluée ? | Différence de niveau sonore entre deux pièces internes au bâtiment | Différence de niveau sonore entre l’extérieur et l’intérieur |
| Indice mesuré |  |  |
| EN LABORATOIRE | L’**indice d’affaiblissement au bruit aérien** d’un élément du bâtiment se note $R_w(C;C_{tr})$ |  |
| Remarque : Pour les petites pièces (grille, **CVR**), il s’exprime sous la forme $D_{new}(C;C_{tr})$ |  |  |
| Indice d’affaiblissement aux bruits aériens intérieurs |  |  |
| $R_w +C$ |  |  |
| $D_{new} + C$ | Indice d’affaiblissement aux bruits aériens extérieurs |  |
| $R_w + C_{tr}$ |  |  |
| $D_{new} + C_{tr}$ |  |  |
| Plus **R** est élevé, plus la performance de l’élément est importante |  |  |
| Indice mesuré |  |  |
| IN SITU | **Isolement acoustique** aux bruits aériens intérieurs |  |
| $D_{nTA}$ | **Isolement acoustique** vis-à-vis des bruits extérieurs |  |
| $D_{nTA,tr}$ |  |  |
| Plus **D** est élevé, meilleur est l’isolement acoustique |  |  |

Exemple :

Un fabricant de menuiseries annonce dans sa documentation une porte avec une performance $R_w(C;C_{tr}) = 34(2;-3)$.

Ainsi :

$R_w+C = 34+2 = 36$ dB

$R_w+C_{tr} = 34+(-3) = 31$ dB

Remarque : On retient **$R_w+C$** car la porte se situe **à l’intérieur** du bâtiment et ne subit donc que les **bruits aériens intérieurs**.<p>&nbsp;</p>
<p>&nbsp;</p>

### Calcul de la performance d’une paroi complexe

<p>&nbsp;</p>

Pour une paroi constituée de plusieurs éléments, son **indice d’affaiblissement global** n’est pas mesuré mais **calculé**. Il dépend des **surfaces** et des **indices d’affaiblissement** de chaque composant.

La formule pour déterminer l’indice global $R$ d’une paroi est :

<p>&nbsp;</p>

![](https://raw.githubusercontent.com/bc-ars/plateform-images/refs/heads/main/Conduite_travaux/S3/Acoustique%20du%20b%C3%A2timent/Concevoir%20et%20ex%C3%A9cuter%20des%20b%C3%A2timents%20performants%20ac/imagea.png)

<p>&nbsp;</p>

Avec :

- $S_i$ : **surface** de chaque élément $i$
- $R_i$ : **indice d’affaiblissement** de chaque élément $i$

Exemple :

Une paroi de 15 m² est composée :

- d’une cloison **SAD** ayant $R_w+C = 64$ dB
- d’une porte de 0,9 × 2 m ayant $R_w+C = 40$ dB

La performance globale $R$ de la paroi est donc :

<p>&nbsp;</p>

![](https://raw.githubusercontent.com/bc-ars/plateform-images/refs/heads/main/Conduite_travaux/S3/Acoustique%20du%20b%C3%A2timent/Concevoir%20et%20ex%C3%A9cuter%20des%20b%C3%A2timents%20performants%20ac/imageb.png)

<p>&nbsp;</p>

### Calcul de l’isolement aux bruits aériens intérieurs $D_{nTA}$

<p>&nbsp;</p>

L’**isolement aux bruits aériens intérieurs** $D_{nTA}$ peut être estimé grâce aux performances d’affaiblissement des composants :<p>&nbsp;</p>
<p>&nbsp;</p>

![](https://raw.githubusercontent.com/bc-ars/plateform-images/refs/heads/main/Conduite_travaux/S3/Acoustique%20du%20b%C3%A2timent/Concevoir%20et%20ex%C3%A9cuter%20des%20b%C3%A2timents%20performants%20ac/imagec.png)

<p>&nbsp;</p>

Avec :

- $R_w+C$ : **indice d’affaiblissement** de la cloison (en cas de paroi mixte, faire une recomposition)
- $V$ : **volume** du local récepteur
- $T_r$ : **temps de réverbération** du local récepteur
- $S$ : **surface séparatrice** commune entre les deux pièces
- $TL = 5 + S_r/10 – N$ avec $S_r$ : somme des surfaces des parois latérales et $N$ : nombre de **cloisons doublées** du local récepteur

Exemple :

Pour une école, une paroi entre deux classes est un **refend béton** de 20 cm, avec $R_w+C = 67$ dB.

Dimensions : 6,5 m × 2,8 m ; surface des classes : 60 m².

Remarques :

- $T_r = 1 s$
- $TL = 5$

Le calcul de l’isolement est donc :

[D_{nT,A} ;\approx; (R_w + C);+;10\log_{10}!\left(\frac{0{,}32,V}{S}\right);-;TL]

où (TL) représente la diminution par transmissions latérales (ici donnée). ([Rockwool](https://www.rockwool.com/siteassets/rw-f/telechargements/docs-par-themes/acoustique/rockwool_guide_acoustique_maitrisez_l_energie_sonore_201604.pdf))

Données :

- (R_w + C = 67\ \text{dB}) (refend béton 20 cm)
- Dimensions de la paroi : (6{,}5 \times 2{,}8 \Rightarrow S = 18{,}2\ \text{m}^2)
- Surface au sol d’une classe : (60\ \text{m}^2), hauteur (2{,}8\ \text{m} \Rightarrow V = 60 \times 2{,}8 = 168\ \text{m}^3)
- (TL = 5) (donné)
- (Le terme (T_r) ne rentre pas ici car (D_{nT}) est standardisé à (T_0 = 0{,}5,\text{s}), d’où le facteur (0{,}32=0{,}16/0{,}5).) ([Bruit](https://www.bruit.fr/images/stories/pdf/B1_performances_acoustiques_batiments_construction.pdf?utm_source=chatgpt.com))

Calcul du terme géométrique :

[10\log_{10}!\left(\frac{0{,}32\times 168}{18{,}2}\right)

= 10\log_{10}(2{,}9538) \approx 4{,}70\ \text{dB}]

Donc :

[

D_{nT,A} \approx 67 + 4{,}70 - 5 ;=; 66{,}7\ \text{dB}

]

🧮 **Résultat** (arrondi) : (\boxed{D_{nT,A} \approx 67\ \text{dB}}).

*Réfs. formule et définitions : méthode simplifiée (D_{nT,w}=R_w+10\log(0{,}32V/S)-a) avec (a=5+S_r/10-N) pour séparatifs lourds (béton), et passage à (D_{nT,A}=D_{nT,w}+C).*

<p>&nbsp;</p>

### Calcul de l’isolement aux bruits aériens extérieurs $D_{nTA,tr}$

<p>&nbsp;</p>

L’**isolement aux bruits aériens extérieurs** $D_{nTA,tr}$ est évalué à partir des performances des composants de la façade :

![image.png](https://raw.githubusercontent.com/bc-ars/plateform-images/refs/heads/main/Conduite_travaux/S3/Acoustique%20du%20b%C3%A2timent/Concevoir%20et%20ex%C3%A9cuter%20des%20b%C3%A2timents%20performants%20ac/image.png)

Dn,T,A,tr=10⋅log⁡(A2Tr⋅1X+Y+Z)D_{n,T,A,tr} = 10 \cdot \log \left( \frac{A}{2 T_r} \cdot \frac{1}{X+Y+Z} \right)

### Avec :

🔹 **Surface équivalente d’absorption du local récepteur**

A=0,16⋅VTrA = \frac{0,16 \cdot V}{T_r}

- $V$ : volume du local récepteur (m³)
- $T_r$ : temps de réverbération du local (s)

---

🔹 **Contribution des éléments de façade (menuiseries, parois…)**

X=∑i=0nSi⋅10−0,1⋅RiX = \sum_{i=0}^{n} S_i \cdot 10^{-0,1 \cdot R_i}

- $S_i$ : surface de l’élément $i$ (m²)
- $R_i$ : indice d’affaiblissement $R_{w}+C_{tr}$ de l’élément $i$

---

🔹 **Transmission latérale** (souvent négligée si objectif $D_{nTA,tr} < 35 ,\text{dB}$)

Y=Slat⋅10−0,1⋅(Rlat+10)Y = S_{lat} \cdot 10^{-0,1 \cdot (R_{lat}+10)}

- $S_{lat}$ : surface des parois latérales (m²)
- $R_{lat}$ : indice d’affaiblissement latéral

---

🔹 **Fuites par les entrées d’air et coffres de volets roulants**

Z=nEA⋅10−0,1⋅(DEA−10)  +  nCVR⋅10−0,1⋅(DCVR−10)Z = n_{EA} \cdot 10^{-0,1 \cdot (D_{EA}-10)} \;+\; n_{CVR} \cdot 10^{-0,1 \cdot (D_{CVR}-10)}

- $n_{EA}$ : nombre d’entrées d’air
- $D_{EA}$ : affaiblissement des entrées d’air ($D_{new}+C_{tr}$)
- $n_{CVR}$ : nombre de coffres de volets roulants
- $D_{CVR}$ : affaiblissement des coffres ($D_{new}+C_{tr}$)
- <p>&nbsp;</p>

---

✅ **Interprétation** :

- Plus $X$, $Y$, $Z$ sont **grands** (façade peu isolante, nombreuses fuites), plus l’isolement global $D_{nTA,tr}$ sera **faible**.
- Plus l’absorption intérieure $A$ est **grande** (local volumineux et réverbérant), plus l’isolement global est **faible**.

<p>&nbsp;</p>

Exemple :

Une chambre de 3 × 4 × 2,5 m présente :

- une façade béton de 16 cm ($R_w+C_{tr} = 54$ dB)
- une menuiserie de 1,5 × 2 m ($R_w+C_{tr} = 40$ dB)
- un **coffre de volet roulant** ($D_{new}+C_{tr} = 54$ dB)
- une **entrée d’air** ($D_{new}+C_{tr} = 37$ dB)

Surface totale : 10 m²

Remarques :

- $T_r = 0,5 s$
- Le terme $Y$ lié aux transmissions latérales est négligé
- <p>&nbsp;</p>

![](https://raw.githubusercontent.com/bc-ars/plateform-images/refs/heads/main/Conduite_travaux/S3/Acoustique%20du%20b%C3%A2timent/Concevoir%20et%20ex%C3%A9cuter%20des%20b%C3%A2timents%20performants%20ac/imaged.png)

<p>&nbsp;</p>

## En pratique

<p>&nbsp;</p>

### Objectifs d’isolement à retenir

<p>&nbsp;</p>

### Objectifs d’isolement vis-à-vis du bruit aérien extérieur

<p>&nbsp;</p>

Les **objectifs d’isolement des façades** $D_{nTA,tr}$ contre les bruits extérieurs varient selon la **localisation du projet** et nécessitent une **étude spécifique**.

La **méthode simplifiée** pour déterminer ces objectifs $D_{nTA,tr}$ est détaillée dans le cours « **Enveloppe du bâtiment – définition des objectifs acoustiques** ».

**Rappel :** les objectifs $D_{nTA,tr}$ ne doivent jamais être **inférieurs à 30 dB**.

Le tableau suivant présente la **qualité sonore de l’environnement** selon les objectifs $D_{nTA,tr}$ :

| Objectif d’isolement | Ambiance sonore |
| --- | --- |
| ≥ 30 dB | **Site calme** |
| ≥ 35 dB | **Site bruyant** |
| ≥ 38 dB | **Site très bruyant** |

### Objectifs d’isolement vis-à-vis du bruit aérien intérieur

<p>&nbsp;</p>

Le tableau suivant synthétise les objectifs usuels d’**isolement aux bruits aériens intérieurs** $D_{nTA}$ :

| Typologie | Objectif $D_{nTA}$ à atteindre |
| --- | --- |
| **Logements** | ≥ 53 dB entre logements |
| **Établissements scolaires** | ≥ 43 dB entre salles de classe **sans porte de communication** |
| ≥ 40 dB entre salles de classe **avec porte de communication** |  |
| ≥ 25 dB entre salles de classe avec **porte anti pince-doigt** |  |
| **Bureaux** | ≥ 40 dB entre bureaux **individuels ou collectifs** avec cloison fixe |

---

<p>&nbsp;</p>

### Bonnes pratiques de mise en œuvre

<p>&nbsp;</p>

Pour garantir l’atteinte des **objectifs acoustiques**, la pose des différents éléments du bâtiment (**gros œuvre**, **doublages**, **menuiseries**…) doit prévenir et contrôler :

- les **fuites acoustiques**
- les **court-circuits acoustiques**

Ainsi, la **qualité de mise en œuvre** de chaque lot est essentielle.

Les sections ci-dessous détaillent, lot par lot, les **problèmes fréquemment rencontrés** et les **solutions adaptées**.

<p>&nbsp;</p>

---

### Lot **gros œuvre**

<p>&nbsp;</p>

Problèmes fréquemment constatés et solutions :

| Problèmes rencontrés | Solutions proposées |
| --- | --- |
| **Réservations non calfeutrées** (trous de banches, réservations inutilisées…) | Effectuer un **calfeutrement** avec un **mortier approprié** |
| **Ouvrages maçonnés sans enduit** | Appliquer un **enduit** d’au moins **1,5 cm d’épaisseur** |
| **Jours entre éléments structurels** (plancher/mur, traversées de plancher : poteau, réseau…) |  |
| *Voir photo* : *Jeu non calfeutré entre éléments* | Réaliser un **calfeutrement** au **mortier approprié**. |
| Pour les constructions bois, possibilité d’utiliser une **pièce de bois**. |  |
| **Mousse PU interdite**. |  |

<p>&nbsp;</p>

### Lot menuiseries extérieures - occultations

<p>&nbsp;</p>

Problèmes courants et solutions :

| Problèmes rencontrés | Solutions proposées |
| --- | --- |
| **Jeux entre dormant de menuiserie et structure** |  |
| *Voir photo* | Réaliser un **calfeutrement** avec **mortier adapté**. |
| En bois : ajouter une **pièce de bois**. |  |
| **Mousse PU interdite**. |  |
| **Jeux entre coffre de volet roulant et structure** |  |
| *Voir photo* | Même solution : **calfeutrement adapté** |
| **Joints d’étanchéité mal comprimés** entre dormant et structure |  |
| *Voir photo* | **Reposer la menuiserie** et installer des **joints adaptés** à l’épaisseur |
| **Menuiserie mal réglée : joints non comprimés** | **Régler correctement** la menuiserie |
|  |  |

![image.png](https://raw.githubusercontent.com/bc-ars/plateform-images/refs/heads/main/Conduite_travaux/S3/Acoustique%20du%20b%C3%A2timent/Concevoir%20et%20ex%C3%A9cuter%20des%20b%C3%A2timents%20performants%20ac/image%201.png)

*Photo - Jeu non calfeutré menuiserie extérieure/CVR*

<p>&nbsp;</p>

![image.png](https://raw.githubusercontent.com/bc-ars/plateform-images/refs/heads/main/Conduite_travaux/S3/Acoustique%20du%20b%C3%A2timent/Concevoir%20et%20ex%C3%A9cuter%20des%20b%C3%A2timents%20performants%20ac/image%202.png)

*Image - Joint d’étanchéité structure mal comprimé. On peut observer un espace notable entre la cloison et le joint, ce qui engendre une infiltration sonore ou d'air non maîtrisée—un point faible acoustique critique.*

<p>&nbsp;</p>

![image.png](https://raw.githubusercontent.com/bc-ars/plateform-images/refs/heads/main/Conduite_travaux/S3/Acoustique%20du%20b%C3%A2timent/Concevoir%20et%20ex%C3%A9cuter%20des%20b%C3%A2timents%20performants%20ac/image%203.png)

<p>&nbsp;</p>

### Lot **menuiseries intérieures**

<p>&nbsp;</p>

Problèmes courants et solutions :

| Problèmes rencontrés | Solutions proposées |
| --- | --- |
| **Absence de joints périphériques** (entre dormant/ouvrant ou sous le seuil) | Vérifier la **pose correcte des joints acoustiques** sur les portes palières |
| **Menuiseries mal réglées : joints non comprimés** | **Régler correctement** la menuiserie |
|  |  |

---

<p>&nbsp;</p>

### Lot **CVC**

<p>&nbsp;</p>

Problèmes courants et solutions :

| Problèmes rencontrés | Solutions proposées |
| --- | --- |
| **Piquage en vis-à-vis** créant un effet d’interphonie dans le réseau | Prévoir **au moins 1,5 m de distance** entre les piquages VMC |

---

<p>&nbsp;</p>

### Lot **électricité**

<p>&nbsp;</p>

Problèmes courants et solutions :

| Problèmes rencontrés | Solutions proposées |
| --- | --- |
| **Prises électriques en vis-à-vis** de part et d’autre d’un refend | Ajouter un **renfort au mortier MAP** ou une **plaque de plâtre** pour limiter l’interphonie. |
| Respecter **30 cm d’écart minimum** entre prises. |  |
| **Boîtiers de réservation traversants** |  |
| *Voir photo* | **Remplir** les boîtiers au **mortier** ou avec de la **vermiculite** |

<p>&nbsp;</p>

### **Tableau de synthèse – Problèmes et solutions acoustiques par lot**

<p>&nbsp;</p>

| **Lot** | **Problèmes fréquents** | **Solutions à mettre en œuvre** |
| --- | --- | --- |
| **Gros œuvre** | - Réservations non calfeutrées (trous, cônes de banches)   - Absence d’enduit sur les maçonneries   - Jours entre planchers/murs ou traversées de plancher | - Calfeutrer avec **mortier adapté**  - Appliquer un **enduit ≥ 1,5 cm**  - En bois : **ajout de pièce de bois**  - **Mousse PU interdite** |
| **Menuiseries extérieures – occultations** | - Jeux entre dormant et structure   - Jeux entre coffre de volet roulant et structure   - Joints d’étanchéité mal comprimés   - Menuiseries mal réglées | - **Calfeutrer** avec mortier adapté ou pièce bois  - **Reposer** les menuiseries avec joints adaptés  - **Régler** correctement les menuiseries |
| **Plâtrerie** | - Cloisons/doublages filants entre locaux   - Plaques de plâtre assemblées sur la hauteur   - Réservations non bouchées | - **Respecter l’ordre de pose** : séparatives > doublages > plafonds > distributions  - **Couper les plaques filantes** (trait de scie)  - **Remplacer les plaques** mal posées par des plaques entières  - **Calfeutrer** au mortier MAP |
| **Menuiseries intérieures** | - Absence de joints périphériques   - Menuiseries mal réglées | - **Contrôler la pose** des joints acoustiques  - **Régler** correctement les menuiseries |
| **CVC** | - Piquages en vis-à-vis créant un effet d’interphonie | - **Espacer les piquages d’au moins 1,5 m** |
| **Électricité** | - Prises électriques en vis-à-vis  - Boîtiers traversants non rebouchés | - **Renfort au mortier MAP** ou **plaque de plâtre**  - Respecter **30 cm minimum** entre prises  - **Remplir les boîtiers** au mortier ou à la vermiculite |

<p>&nbsp;</p>

### 🎬 **Concepts fondamentaux de l’acoustique**

*Pour conclure ce cours, nous vous proposons de suivre ce **webinar animé par Stéphane Lesoinne de Buildwise** sur l’acoustique du bâtiment, consacré à l’**isolation des murs simples**.*

*Vous y découvrirez comment les performances d’affaiblissement acoustique sont mesurées, comment les murs réagissent face aux **bruits aériens** et quelles solutions constructives permettent d’améliorer leur efficacité.*

<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>

[https://www.youtube.com/watch?v=lVL3NHXUujE](https://www.youtube.com/watch?v=lVL3NHXUujE)