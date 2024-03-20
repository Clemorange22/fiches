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
$$\vec{C}=\int_{S} \vec{\mathrm{d}q}(M)=\int_{S} \vec{V}(M)\mathrm{d}m(M)$$
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




