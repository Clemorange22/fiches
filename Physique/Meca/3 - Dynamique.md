## Masse d'un système
### Solide
$$M=\int \dots \, dm $$
#### Masse linéque
$$\mathrm{d}m = \lambda \mathrm{d}l$$
$\lambda$ (kg/m) = masse linéique
#### Masse surfacique
$$\mathrm{d}m = \sigma \mathrm{d}s$$
$\sigma$ (kg/m²) masse surfacique

#### Masse volumique
$$\mathrm{d}m = \rho \mathrm{d}v$$
### Barycentre : centre d'inertie
Def : voir OMNI

### Centre d'inertie
Les coefficients sont des masses
Trouver le centre d'inertie : analyser la répartition de masse (symétries)

**Axe de révolution :** axe commun à une infinité de plans de symétrie

Solide en rotation autour d'un axe
Pour calculer l'énergie cinétique, il faut savoir comment la masse du solide est répartie par rapport à l'axe de rotation

### Moment d'inertie par rapport à un axe

Le moment d'inertie par rapport à un axe $\Delta$ d'un système (S) formé de n points $P_{i}$ de masses $m_{i}$ est donné par :
$$J_{\Delta}=\sum^{N}_{i=1}m_{i} \times [d(P_{i}, \Delta)]^{2}$$
$d(P_{i}, \Delta)$ est la distance du point $P_{i}$ à l'axe $\Delta$

Pour une répartition continue de masse :
$$J_{\Delta}= \int \mathrm{d}J_{\Delta}$$
Où $\mathrm{d}J_{\Delta}=[d(P, \Delta)]^{2} \times \mathrm{d}m$

>[!info]
>Le moment d’inertie d’un système matériel (S) par rapport à un axe $\Delta$, est égal au moment d’inertie de (S) par rapport à un axe $\Delta_G$ parallèle à $\Delta$ , passant par $G$ centre d’inertie de (S), augmenté du moment d’inertie par rapport à $\Delta$ de la masse totale du système supposée centrée en G.

$$J_{\Delta}= J_{\Delta_{G}} + M d^{2}$$

## Cinétique
### Quantité de mouvement
homogène à une masse fois une vitesse

Loi de répartition de masse pour un solide : $\mathrm{d}m(M)=\rho(M)\mathrm{d}v$

**Quantité de mouvement élémentaire :** $$\overrightarrow{\mathrm{d}q(M)}=\overrightarrow{V}(M) \times \mathrm{d}m(M)$$
Pour un point matériel $M$ de masse $m$ : $\vec{q}(M)=m\vec{V}(M)$
Avec $\vec{V}$ la vitesse du point
### Moment cinétique
#### Point matériel
$$\overrightarrow{\sigma_{O}}=\overrightarrow{OM}\wedge \vec{q}(M)$$
#### Solide indéformable
#### Système
$$\overrightarrow{M_{O}}(C)=\int_{S}  \overrightarrow{OM} \wedge \vec{\mathrm{d}q}=\int_{S} \overrightarrow{OM} \wedge \vec{V}(M)\mathrm{d}m(M) $$

**Résultante cinétique**
$$\vec{C}=\int_{S} \vec{\mathrm{d}q}(M)=\int_{S} \vec{V}(M)\mathrm{d}m(M)=\int \frac{\vec{\mathrm{d}OG}}{\mathrm{d}t} \, dm + \int \frac{\vec{\mathrm{d}GM}}{\mathrm{d}t} \, dm =\vec{V}(G) \times M + \vec{0}$$
On en déduit (à démontrer) : $$\vec{C}=M \times \vec{V}(G)$$
avec $G$ le centre de masse
**Torseur :**

$$[C]=\begin{cases} \vec{C} = \text{résulante cinétique} \\ \overrightarrow{M_{O}}(C) = \text{moment cinétique résultant} \end{cases}$$
![[Pasted image 20240313115506.png]]
### Énergie cinétique
On doit pouvoir démonter les expressions suivantes :

#### Point matériel
$$E_{k}=\frac{1}{2}m\vec{V}^{2}(M)=\frac{1}{2} \vec{q}(M) \times \vec{V}(M)$$

#### Solide indéformable en translation
$$E_{k}=\frac{1}{2}M\vec{V}^{2}(G)$$

#### Solide indéformable en rotation
$$E_{k}=\frac{1}{2} J_{\Delta}\omega^{2}$$

#### Système

### Éléments de réduction en dynamique

**Quantité d'accélération :**
$$\vec{\mathrm{d}j(M)}=\vec{a_{R_{0}}}(M)\mathrm{d}m(M)$$
**Résultante dynamique :**
$$\vec{D}=\int_{S}  \, \vec{dj}=\int_{S}  \,\vec{a}(M)dm(M)$$
$$\vec{D}=M. \vec{a}(G)$$
**Moment dynamique résulant en O :**
$$\vec{M_{O}}(D)=\int_{S} \overrightarrow{OM}\wedge \overrightarrow{dj} = \int_{S} \overrightarrow{OM} \wedge \overrightarrow{a}(M)dm(M)$$
$$[D]=\begin{cases} \overrightarrow{D} \\ \overrightarrow{M_{O}}(D)\end{cases}$$

# Dynamique du point matériel
**Principes de base :**
*   masse des particules matérielles constantes
* vitesses très faibles devant celle de la lumière
* actions à distance transmises instantanément

### 1ère loi de Newton
Dans un repère absolu $R^{A}$ et avec une chronologie absolue un point matériel $P$ isolé possède une quantité de mouvement constante
$\vec{q_{R^{A}}}=m \vec{V_{R^{A}}}=\vec{cte}$

### 2ème loi de Newton
Soit un point matériel $P$ soumis à des actions de la part d'autres points matériels. À l'instant t, ces actions sont représentables par un vecteur force $\vec{F}$ s'exerçant sur $P$.
Si $\vec{F}$ est non nulle, la variation de la quantité de mouvement de $P$ est liée à $\vec{F}$ par :
$$\frac{\mathrm{d}}{\mathrm{d}t}(\vec{q_{R^{A}}})=\vec{F} \iff \vec{F}=m. \vec{a_{R^{A}}}$$
### 3ème loi de Newton

Si à l'instant t il y a interaction entre deux points matériels $P_{1}$ et $P_{2}$, les forces que chaque point exerce sur l'autre sont opposées.

## Principe de la dynamique
Dans un référentiel absolu
$$\vec{F}=m\vec{a}$$
**Référentiel absolu :** Dans un référentiel absolu on devrait pouvoir suivre le mouvement de n’importe quel point matériel de l’Univers

**Reférentiel galiléen ou inertiel :** C’est un référentiel dans lequel le principe d’inertie (1ère loi de Newton) est vérifié.

### Principe fondamental de la dynamique
À partir de toutes les forces mises en jeu on définit les torseurs suivants : 
- torseur des forces intérieures $[F_{i}]$
- torseur des forces extérieures $[F_{e}]$

Il existe un référentiel galiléen $R^{G}$ et une manière de mesurer le temps dite chronologique absolue tels que le torseur des forces extérieures exercées sur un système soit à chaque instant égal au torseur dynamique
$$[F_{e}]=[D]_{R^{G}}$$

