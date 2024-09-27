QCM de révision d'élec (DC, AC, reg. variable) > test début novembre

Repère cartésien direct $(O, x, y, z)$
En un point $M$ de cet espace il existe un champ vectoriel $\vec{E}(x,y,z)$

## Circulation
$$\int_{A}^B \vec{E} \cdot \overrightarrow{\mathrm{d}OM}$$
## Flux
$$\iint \vec{E} \cdot \vec{\mathrm{d}S}$$

## Gradient
$$\vec{E}=-\vec{\nabla}V$$
Circulation conservative sur une courbe fermée
## Divergence
Transforme un champ vectoriel en champ scalaire.
Sert à exprimer des équations de conservation locales (de la charge électrique, matière...)
$$div(\vec{E})=\vec{\nabla} \cdot \vec{E}=\frac{\partial E_{x}}{\partial x} +  \frac{\partial E_{y}}{\partial y}+ \frac{\partial E_{z}}{\partial z}$$

**Théorème d'Ostrogradski :**

Le flux d'un champ $\vec{E}$ sortant d'une surface fermé est égale à l'intégrale triple de la divergence de $\vec{E}$ sur le volume délimité par la surface fermée

$$\iint \vec{E}\ \cdot\mathrm{d}\vec{S}=\iiint div(\vec{E})\mathrm{dV}$$
Si $\vec{B} = \vec{rot}(\vec{A})$, $div(\vec{B})=0$ **Divergence nulle** $\implies$ flux conservatif

### Exemple
$$div(\vec{j})+\frac{\partial \rho}{\partial t}=0$$

## Rotationnel
Transforme un champ vectoriel en champ vectoriel
$$rot(\vec{E})=\vec{\nabla} \wedge \vec{E} = \left( \frac{\partial E_{z}}{\partial y} -  \frac{\partial E_{y}}{\partial z}, \frac{\partial E_{x}}{\partial z} - \frac{\partial E_{z}}{\partial x}, \frac{\partial E_{y}}{\partial x} - \frac{\partial E_{x}}{\partial y} \right)$$
Si $\vec{E}$ est un vecteur, son rotationnel est un pseudo-vecteur (moment) et inversement
**Théorème de Stokes :**

La circulation d'un champ $\vec{E}$ le long d'un contour (fermé) orienté est égale au flux de son rotationnel à travers toute surface s'appuyant sur ce même contour orienté.

$$\int \vec{E} \cdot \vec{\mathrm{d}l} = \iint \vec{rot}(\vec{E}) \cdot \vec{\mathrm{d}S}$$
**Rotationnel nul** dans un domaine simplement connexe $\implies$ $\vec{E}$ dérive d'un potentiel scalaire (sa forme différentielle est exacte)
## Laplacien

