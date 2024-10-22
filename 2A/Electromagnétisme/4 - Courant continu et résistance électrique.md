### Lois d’Ohm-Kirchhoff locales
**Densité de courant électrique**
$$\vec{j}=nq\vec{v}$$

$$\mathrm{d}q=nqvS\mathrm{d}t$$

**Conductivité :**
$$\gamma= \frac{nq^{2}\tau}{m}$$
$\tau$ : frottements
$$\vec{j}=\gamma \vec{E}$$
$div(\vec{j})=0$ : le flux de $\vec{j}$ sortant d'une surface fermée est conservatif lorsque les charges circules dans un milieu sans s'arrêter


Conducteur droit de longueur $l$ et de section $S$ :
$$I=jS$$
$$U=RI$$
$$R=\frac{l}{\gamma S}=\frac{\rho l}{S}$$
où $\rho = 1/\gamma$ est la résistivité du conducteur

Un porteur de charge animé de la vitesse $\vec{v}$ dans le champ $\vec{E}$ dissipe la puissance $q\vec{E}\cdot\vec{v}$ donc les porteurs de charge de la longueur $l$ d'un conducteur de section $S$ dissipent $S\ln qvE=SI(\vec{j}\cdot \vec{E})=SI\rho j^{2}$

$\vec{j}\cdot \vec{E}$ : W/m^3 Puissance de dissipation par effet joule par unité de volume

## Dimensions
On peut idéaliser un courant comme filiforme (1D) ou surfacique (2D).
* 1D: pas de densité de courant
* 2D : $\vec{j}$ (A/m^2) est remplacé par une densité de courant surfacique $\vec{k}$ (A/m)




## Régime lentement variable

En courant alternatif de basse fréquence ($<<1 \text{ GHz}$), les équations vue précédemment sont toujours valables

Paradoxe du condensateur : 

Dans le cas où la charge est autorisée à s'accumuler, il faut modifier la loi de maxwell:

$$\vec{\nabla} \cdot (\vec{j}+\vec{j_{D}})=0$$
Avec
* $\vec{j}$ courant de conduction
* $\vec{j_{D}}$ courant de déplacement (accumulation des charges)
$$\vec{j_{D}} =\epsilon\frac{ \partial \vec{E}}{\partial t}$$
