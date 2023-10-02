## Conversions d'unités

1 Ångström $=1 Å=0.1nm$
## Modèle quantique de l'atome
### La double nature de la lumière

```ad-info
La nature de la lumière est double : elle est à la fois une **onde** et **corpusculaire**.
```
#### Onde

**Fréquence** $\nu$ (nu) exprimée en **hertz** (Hz) 
$\nu=\frac{1}{T}$
avec $T$ la **période** en secondes

![[Structure de l'atome periode.excalidraw.svg]]

$C$ : vitesse de la lumière $= 3.10^8\ m.s^{-1}$

$\lambda$ : longueur d'onde
Lumière visible : $0.4\ \micro m<\lambda<0.8\ \micro m$
$\lambda=\frac{C}{\nu}$
Nombre d'onde $\overline{\nu}=\frac{1}{\lambda}\ cm^{-1}$ 

#### Lumière corpusculaire

La lumière est consitituée de particules appelées photons

L'énergie d'un photon est donnée par cette formule :
$E=h\nu=\frac{hC}{\lambda}$
avec $h$ la constante de Planck
$h=6.62\times10^{-34}\ J.s$

L'électronvolt $eV$
$1\ eV=1.6 \times 10^{-19}\ J$

Si une particule est accélérée sous 3 volts, son énergie vaut 3 $eV$
### Modèle de Bohr (Hydrogène/Hydrogènoïdes)
#### 2 types de spectroscopie
![[Structure de l'atome grotrian.excalidraw.svg]]
%%[[Structure de l'atome grotrian.excalidraw|🖋 Edit in Excalidraw]],%%
#### Absorption
Au repos, l'électron est sur son niveau fondamental $n=1$
Quand il reçoit un rayonnement, il absorbe les photons dont le niveau d'énergie correspond à ce qui lui manque pour atteindre un niveau supérieur.

```ad-info
Certaines longueurs d'ondes bien précises sont alors absorbées car $E=h\nu=\frac{hC}{\lambda}$

```

#### Émission
Lorsqu'un électron ne reçoit plus d'énergie, il se désexcite. Son niveau d'énergie baisse et il émet des photons correspondants à la différence d'énergie entre les niveaux qu'il atteint successivement
#### Formules
Pour l'hydrogène :
$\frac{1}{\lambda}=R_{H}\left( \frac{1}{n_{1}^{2}}-\frac{1}{n_{2}^2} \right)$
Avec :
* $R_{H}$ une constante $R_{H}= 1096677.58\ cm^{-1}$
* $n_{1}$ le niveau le plus faible
* $n_{2}$ le niveau le plus grand

**Séries d'émission**

|Niveau d'arrivée|1|2|3|4|...|
|--|--|--|--|--|--|
|Série de|Lyman|Balmer|Pashen|Brackett|...|
|Domaine des ondes émises|Ultraviolets|Visible|Infrarouges|||

Pour chaque série, il existe une :
* **raie de tête** pour $n_{1}=n_{2}+1$ 
    * Correspond à la **plus grande** longueur d'onde de la série
* **raie limite** pour $n_{2}\rightarrow +\infty$
    * Correspond à la **plus petite** longueur d'onde de la série

Pour les hydrogènoïdes :
$\frac{1}{\lambda}=Z^2R_{X}\left( \frac{1}{n_{1}^{2}}-\frac{1}{n_{2}^2} \right)$
avec $Z$ le n° atomique
et $R_{X}$ l'énergie d'ionisation de l'atome
#### Problème de modèle de Bohr
Il ne prend pas en compte la structure des atomes ayant plusieurs électrons sur leur couche de valence

### Modèle ondulatoire de l'atome
À toute particule de masse $m$ et de vitesse $v$, on peut associer une longueur d'onde $\lambda$

$\lambda=\frac{h}{m.v}$

Un objet quantique, comme l'électron, peut adopter l'état d'onde ou de corpuscule

$E_{n}=-\frac{E_{X}Z_{eff}^2}{n^2}$
avec $Z_{eff}$ la charge nucléaire effective
#### Nombres quantiques

$n$ : nombre quantique principal = n° de la couche électronique
$n \geq 1$

$l$ : nombre quantique secondaire  = n° de la sous-couche
$0\leq l \leq n-1$ 
$l$ caractérise la façon dont l'électron bouge dans l'espace cad. la forme des orbitales
Sous-couches : spdf

$m_{l}$ : nombre quantique magnétique = n° de la "case"
$-l\leq m_{l}\leq l$
Il y a donc $2l+1$ valeurs de  $m_{l}$ pour une valeur $l$ donnée

$m_{s}$ : nombre quantique magnétique de spin
$m_{s}=\pm \frac{1}{2}$


$j$ : couplage spin/orbite
$j=l+m_{s}$

#### Principe de Pauli
Chaque électron possède des nombres quantiques différents

#### Règles de Klechkowski
Remplissage avec $n+l$ croissant
![[Structure de l'atome remplissage.excalidraw.svg]]
%%[[Structure de l'atome 2023-10-02 09.15.37.excalidraw.md|🖋 Edit in Excalidraw]], and the [[Structure de l'atome 2023-10-02 09.15.37.excalidraw.dark.svg|dark exported image]]%%

Exceptions : 
* Chrome Cr
* Cuivre Cu
on remplit 3d avant 4s

#### Règles de Hund
Les électrons occupent d'abord toutes les orbitales (cases quantiques) avant de s'apparier car cela leur coûte de l'énergie


