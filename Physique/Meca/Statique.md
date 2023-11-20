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
%%[[Statique 2023-11-06 08.29.58.excalidraw.md|🖋 Edit in Excalidraw]], and the [[Statique 2023-11-06 08.29.58.excalidraw.dark.svg|dark exported image]]%%

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
### Sytème de force équivalent à une force unique

$$\overrightarrow{R}=\overrightarrow{F_{A}}$$
$$\overrightarrow{M_{P}}(\vec{F_{A}})=\vec{0}$$

#### Force concourantes en un point A

![[Pasted image 20231113084749.png]]

#### Forces parallèles et de même sens

![[Pasted image 20231113084830.png]]
**A est le barycentre des points $A_{i}$ de coefficients $\|\vec{F_{i}}\|$**

### Frottement statique

$\sum{\overrightarrow{F_{ext}}}+\vec{f_{s}}=\vec{0}$

