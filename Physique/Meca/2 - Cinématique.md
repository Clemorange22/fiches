**Cinématique :** Étude des mouvements indépendamment des forces

## Repères et référentiels
#### Localisation d'un point dans l'espace

Un point est repéré par ses coordonnées dans un repère orthonormé direct

Autres systèmes de coordonnées :
* Polaires
* Cylindriques
* Sphériques

#### Mouvement d'un point dans un référentiel

à l ’instant t : M (x,y,z)
à l ’instant t+dt : M ’(x+dx, y+dy,z+dz)
MM' = ds

$\mathrm{d}s(t)$ est l'abscisse curviligne
$s(t)$ est l'équation horaire
$$\mathrm{d}s(t)=\sqrt{ \mathrm{d}x(t)^2+\mathrm{d}y(t)^2+\mathrm{d}z(t)^2 }$$
$$s(t_{0})=0$$
$$s(t)=\int_{t0}^{t} ds(t) \, dt= \int _{t0}^{t} \left[ \sqrt{ \left( \frac{\mathrm{d}x}{\mathrm{d}t} \right)^2 +  \left( \frac{\mathrm{d}y}{\mathrm{d}t} \right)^{2 } \left( \frac{\mathrm{d}z}{\mathrm{d}t} \right)^{2 }}\right] \, dt$$

#### Vitesse du point M par rapport au référentiel

Vitesse : dérivée du mouvement en fonction du temps (peut être représentée dans n'importe quelle base)

Accélération : dérivée de la vitesse en fonction du temps

### Repère de Frenet

#### Vecteur $\vec{T}$

On cherche un vecteur $\vec{T}$ tangent à la courbe (trajectoire) et unitaire

$\vec{T}=\frac{\vec{V}}{\|\vec{V}\|}$
#### Vecteur $\vec{N}$

On cherche un vecteur $\vec{N}$ 
Les vecteurs $\vec{T}$ et $\vec{\frac{T}{\mathrm{d}t}}$ sont orthogonaux

$$\frac{\mathrm{d}}{\mathrm{d}t}(\vec{T}.\vec{T})=2\vec{T}\frac{\mathrm{d}\vec{T}}{\mathrm{d}t}=0$$
$$\vec{N}=\frac{\frac{\mathrm{d}\vec{T}}{\mathrm{d}t}}{\|\frac{\mathrm{d}\vec{T}}{\mathrm{d}t}\|}$$

$$\vec{N}=\frac{R.\mathrm{d}t}{\mathrm{d}s}$$
Où $\frac{1}{R}$ est la courbure

$(M,\vec{T},\vec{N})$ définissent le plan osculateur en $M$

#### Vecteur $\vec{B}$
$$\vec{B}=\vec{T}\wedge\vec{N}$$
$(M,\vec{T},\vec{N},\vec{B})$ définissent le **repère de Frénet**

