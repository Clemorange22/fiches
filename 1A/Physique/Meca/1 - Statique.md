### Système matériel

* Point matériel
* Solide indéformable
* Systèmes complexes
* Milieu déformables
* Mécanique des fluides

### Intro
Statique : étude de l'équilibre

Pour un point : une seule relation
* Somme des forces = 0

Pour un système :
* Somme des forces = 0 est nécessaire mais ne suffit pas
* Il faut aussi somme des moments des forces = 0 

![[Statique 2023-11-06 08.29.58.excalidraw.svg]]
%%[[Statique 2023-11-06 08.29.58.excalidraw|🖋 Edit in Excalidraw]], and the [[Statique 2023-11-06 08.29.58.excalidraw.dark.svg|dark exported image]]%%

#### Réaction
Si un élément matériel A exerce sur un autre élément matériel A’ une force $\vec{F}$ , réciproquement A’ exerce sur A une force $\vec{F’}$, de même support et telle que $\vec{F'}=-\vec{F}$

### Moment d'une force

```ad-important
**Moment d'une force par rapport à un point**
Soit une force dont le point d’application est A.
On la notera $\vec{F_A}$
Le moment de cette force par rapport à un point P
quelconque de l’espace est par définition :
$$\overrightarrow{M_p}(\overrightarrow{F_A})=\overrightarrow{PA}\wedge\overrightarrow{F_A}$$
```

```ad-important
**Moment d'une force par rapport à un axe**
Soit une force dont le point d’application est A.
On la notera $\vec{F_A}$
Soit un axe $\Delta$ de vecteur directeur $\vec{u}$
Le moment de la force $\vec{F_A}$ par rapport à l'axe $\Delta$
est :
$$\overrightarrow{M_{\Delta}}(\overrightarrow{F_{A}})=\overrightarrow{M_{P\in \Delta}}(\overrightarrow{F_{A}}).\overrightarrow{u}=(\overrightarrow{PA}\wedge \overrightarrow{F_{A}}).\overrightarrow{u}=(\overrightarrow{PM},\overrightarrow{F_{A}},\overrightarrow{u})$$
```

**Forces intérieures :** forces qui proviennent d'autres point du système

**Forces extérieures :** forces provenant de l'action d'agents extérieurs au système

### Loi de l'action/réaction
#### Forces intérieures
Somme géométrique des forces intérieures

$$\sum_{j}\overrightarrow{F_{jint}}=\vec{0}$$

Somme géométrique des moments des forces intérieures par rapport à tout point P

$$\sum_{j} \overrightarrow{M_{P}}(\overrightarrow{F_{jint}})=\vec{0}$$
#### Forces extérieures

**Résultante des forces**
$$\sum_{j}\overrightarrow{F_{jext}}=\vec{R}$$
**Moment résultant**
$$\sum_{j}\overrightarrow{M_{P}}(\overrightarrow{F_{jext}})=\vec{\Gamma_{P}}$$

### Systèmes de force équivalents

**Deux conditions :**
* Égalité des résultantes
$$\overrightarrow{R_{1}}=\overrightarrow{R_{2}}$$
* Égalité des moments résultants en un même point P quelconque
$$\overrightarrow{\Gamma_{1}}=\overrightarrow{\Gamma_{2}}$$
### Réduction d'un système de forces

```ad-note
**Réduire un système de forces :** trouver un
système plus simple qui lui soit équivalent (mêmes
éléments vectoriels en un point P)
```

#### Système de force équivalent à 0

**Deux conditions :**

**Deux conditions :**
* Résultante nulle
$$\overrightarrow{R}=\vec{0}$$
* Moment des forces nul en tout point P

$$\overrightarrow{\Gamma_{P}}=\vec{0}$$

#### Torseur

Donnée d'une résultante et d'un moment résultant
//TODO 2A


### Système de forces équivalent à un couple

Tout système tel que $\vec{R}=\vec{0}$ et $\vec{\Gamma_{P}}\neq\vec{0}$
est réductible à un couple
### Système de force équivalent à une force unique

$$\overrightarrow{R}=\overrightarrow{F_{A}}$$
$$\overrightarrow{M_{P}}(\vec{F_{A}})=\vec{0}$$

#### Force concourantes en un point A

![[Pasted image 20231113084749.png]]

#### Forces parallèles et de même sens

![[Pasted image 20231113084830.png]]
**A est le barycentre des points $A_{i}$ de coefficients $\|\vec{F_{i}}\|$**

### Frottement statique

![[Pasted image 20231120081419.png]]

$\sum{\overrightarrow{F_{ext}}}+\vec{f_{s}}=\vec{0}$

Le rôle du frottement statique est de « bloquer » les autres forces
tendant à provoquer un mouvement parallèle à la surface de
contact, jusqu’à une valeur limite $f_{s(max)}$ :  $0 < f_{s} < f_{s(max)}$

$f_{s(max)} = \mu_{s} n$

$f_{s(max)}$ : force de frottement statique maximale en Newtons pour laquelle $\sum \vec{F} = 0$
$\mu_{s}$ : coefficient de frottement statique (sans dimension)
$n$ : module de la réaction normale

### Énergie potentielle

#### de pesanteur
$\vec{P}=M\vec{g}$

$E_{p}=MgZ+constante$

```ad-caution
Formule différente si on utilise une autre axe que $Oz$ ou ci celle-ci n'est pas collinéaire à la gravité
```

$\mathrm{d}W=\vec{P}.\mathrm{d}\vec{l}=-\mathrm{d}E_{f}$

#### élastique (ressort)

![[Pasted image 20231120083422.png]]
$\vec{X}=k\vec{OP}$
$\overline{OP}=x$
$E_{p}=\frac{1}{2}kx^2+constante$

#### élastique (fil de torsion)

$E_{c}=\frac{1}{2}C \theta^{2}+constante$

### Positions d'équilibre

Les positions d'équilibre correspondent à des extremums de l'énergie potentielle

```ad-info
Un équilibre est **stable** si lorsqu’on écarte légèrement
(le point ou le système) de la position d’équilibre il
revient à cette position.
```

Si $E_p$ existe cette position correspond à un minimum de $E_p$

