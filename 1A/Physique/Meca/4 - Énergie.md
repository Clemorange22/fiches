## Travail
$$\delta T=\vec{f}\mathrm{d}\cdot\vec{l}=f_{x}\mathrm{d}x+f_{y}\mathrm{d}y+f_{z}\mathrm{d}z$$
Travail : résistant ou moteur

Une force "travaille" si son point d'application se déplace

$$\mathrm{d}\vec{l}=\vec{v}\times\mathrm{d}t$$
Puissance développée par la force
$$P=\frac{\mathrm{d}T}{\mathrm{d}t}=\vec{f}\cdot \vec{v}$$
$$P=M_{A(\vec{f})}\dots$$
#### Travail le long d'un arc fini
$$T_{A-B}=\int_{AB}  \, dT=\int_{AB} \vec{f} \cdot \vec{dl}$$

#### Travail des forces intérieures à un système
$$\sum_{i}T_{i}(\overrightarrow{F_{i\ int}})=0$$

#### Travail des forces extérieures à un système
##### Solide en translation
$\vec{R}(X,Y,Z)$ est la résultante des forces
$$dT=\vec{R}\cdot \vec{dl}=Xdx+Ydy+Zdz$$
Travail total le long de la courbe $\Gamma$ :
$$T = \int_{\Gamma} \vec{R}\cdot \vec{dl} $$
##### Solide en rotation autour d'un axe fixe
$$dT_{i}=M_{oz}(\overrightarrow{f_{i}}).\mathrm{d}\theta=N_{i}\mathrm{d}\theta$$
Avec $\overrightarrow{M_{O}(\vec{f_{i}})}=(L_{i},M_{i},N_{i})$

##### Rotation finie de $\theta_{1}$ à $\theta_{2}$
$$T=\int_{\theta_{1}}^{\theta_{2}} dT=\int_{\theta_{1}}^{\theta_{2}} N(\theta)\mathrm{d}\theta $$
## Unités de puissance et de travail
#### Puissance
$$P=\frac{\mathrm{dT}}{\mathrm{dt}}=\vec{f}\cdot \vec{v}$$
$$[P]=[f][v]=MLT^{-2}\times LT^{-1}=ML^{2}T^{-3}$$
Unité : watt (W)
#### Travail
$$[T]=[f][dl]=MLT^{-2}.L=ML^{2}T^{-2}$$
Unité : joule (J)

#### Énergie potentielle

Soit un système $\Sigma$ dont la position dépend de $n$ paramètres indépendants $q_{i}(t)$ et de $t$.
Les efforts exercés sur $\Sigma$ admettent une énergie
potentielle s’ il existe une fonction $E_{p}[q_{i}(t),t]$ telle que la puissance de ces efforts soit :
$$P=-\frac{\mathrm{d}}{\mathrm{d}t}(E_{p}[q_{i}(t),t])$$
>[!note]
>Seuls certains efforts particuliers admettent une énergie potentielle
>Si $E_{p}$ existe elle est définie à une constante près
## Travail des efforts
$$T(t_{1},t_{2})=E_{p}[q_{i}(t_{1}),t_{1}]-E_{p}[q_{i}(t_{2}),t_{2}]$$
**Ou lorsque $E_{p}$ ne dépend pas de t :**
$$T(t_{1},t_{2})=E_{p}[q_{i}(t_{1})]-E_{p}[q_{i}(t_{2})]$$
Le travail ne dépend alors que des positions initiale et finale

#### Énergie potentielle élastique
Travail du couple de rappel : $\mathrm{d}T=N\mathrm{d}\theta=-C \theta\mathrm{d}\theta=-\mathrm{d}E_{p}$

Si $E_{p}$ n'existe pas : travail non conservatif (ex: frottements)

### Énergie cinétique
Soit $\vec{F}$ la résultante de toutes les forces appliquées à un pont matériel $M$ de masse $m$ et $\vec{v}$ sa vitesse (ref galiléen)
$$\vec{F}=m\frac{\mathrm{d}\vec{v}}{\mathrm{d}t}$$
$$\mathrm{d}T=\vec{F} \cdot \vec{v}\ \mathrm{d}t=m\frac{\mathrm{d}\vec{v}}{\mathrm{d}t}\cdot \vec{v}\ \mathrm{d}t=\frac{1}{2}m \times\mathrm{d}(v^{2})$$
Donc :
$$E_{k}=E_{c}= \frac{1}{2}mv$$
#### Théorème de l'énergie cinétique pour un point matériel

>[!note]
>La **variation d'énergie cinétique** d'un point matériel entre deux instants quelconques est égale à **la somme des travaux** de toutes les forces appliquées à ce point, le long de la portion correspondante de trajectoire

#### Pour un système
##### Quelconque

>[!note]
>La **variation d’énergie cinétique** d’un système matériel entre deux instants quelconques est égale à la **somme algébrique des travaux** effectués entre ces deux instants par toutes les forces (intérieures et extérieures) appliquées au système.


### Énergie mécanique
Soit un **système conservatif** c'est à dire tel que les forces intérieures permettent de définir une énergie potentielle

$$E_{m}=E_{p}+E_{k}$$
$$E_{m_{2}}-E_{m_{1}}=\sum T_{ext}$$
Si le système est **mécaniquement isolé** (= soumis à aucune force extérieure) :
$$\sum T_{ext}=0 \iff E_{m_{2}}-E_{m_{1}} = 0$$
#### Stabilité des équilibres
Les positions d'équilibre stable correspondent à des minimas d'énergie potentielle

