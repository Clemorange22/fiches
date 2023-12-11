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

### Repère local polaire

![[Pasted image 20231204082111.png]]
$$\vec{e_{p}}=\cos(\phi)\vec{e_{x}}+\sin(\phi)\vec{e_{y}}$$
$$\vec{e_{\phi}}=-\sin(\phi)\vec{e_{x}}+\cos(\phi)\vec{e_{y}}$$

$\frac{\mathrm{d}\phi}{\mathrm{d}t}$ : vitesse angulaire

$$\frac{\mathrm{d}\vec{e_{\rho(t)}}}{\mathrm{d}t}=\frac{\mathrm{d}\vec{e_{\rho}}}{\mathrm{d}\phi}\times \frac{\mathrm{d}\phi}{\mathrm{d}t}$$
Mouvement circulaire : 
$\vec{T}(t)=\vec{e_{\phi(t)}}$
$\vec{N}(t)=-\vec{e_{\rho(t)}}$

### Repère local cylindrique
![[Pasted image 20231204085801.png]]
$$\vec{e_{p}}=\cos(\phi)\vec{e_{x}}+\sin(\phi)\vec{e_{y}}$$
$$\vec{e_{\phi}}=-\sin(\phi)\vec{e_{x}}+\cos(\phi)\vec{e_{y}}$$


### Repère local sphérique
![[Pasted image 20231204085905.png]]
![[Pasted image 20231204085915.png]]
![[Pasted image 20231204090002.png]]

## Mouvements simples d’un point matériel

### Mouvement rectiligne
![[Pasted image 20231204090427.png]]
Trajectoire = droite
#### Mouvement rectiligne uniformément accéléré (décéléré)
accélération constante $\implies$ vitesse affine

donc $x(t)=\frac{1}{2}at^{2}+V_{0}t+x_{0}$

#### Mouvement rectiligne uniforme
Vitesse constante $\implies$ accélération nulle
Donc $x(t)$ affine

#### Mouvement circulaire

$$V(M/R)=\frac{\mathrm{d}\overrightarrow{OM}}{dt}=R \omega(t) \overrightarrow{e_{\phi}}$$
avec : 
* $\omega$ la vitesse angulaire en radians/seconde

Vecteur rotation $\omega$

### Changement de référentiel
Composition des vitesses : 
$$V_{absolue}=V_{relative}+V_{entrainement}$$

Vitesse de P par rapport au disque D : vitesse relative

$$\vec{V_{r}}=\vec{V}(P/R_{1})=\frac{\mathrm{d}\overrightarrow{CP}}{\mathrm{d}t}$$
