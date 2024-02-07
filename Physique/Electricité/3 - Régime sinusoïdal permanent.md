$P_{j}=R\times I^{2}$
Pour distribuer l'électricité, le courant continue n'est pas efficace en raison de l'effet Joule.

**Transformateur :** permet de modifier la tension (en fonctionnant en courant alternatif)

**Régime variable :**
$p(t)=u(t)\times i(t)$

**Régime variable périodique :** fonctions sinusoïdales

$u(t)=R \times i(t)$


**Régime permanent sinusoïdal :**

$u(t)=U_{\text{m}}\cos(\omega t+\phi_{u})$
$i(t)=I_{m}\cos\left( \frac{2\pi}{T}t+\phi_{i} \right)$

$U_{m}$ : amplitutde crête

Transformée de Fourrier : tte fonction périodique peut être décomposée en une somme de fonctions sinusoïdale

## Représentation de grandeurs sinusoïdales
### Représentation de Fresnel (vectorielle)
Vecteur qui effectue une rotation en fonction du temps
Permet d'obtenir $\cos(\omega t+\phi)$ ou $\sin(\omega t+\phi)$ en le projettant sur l'axe des ordonnées ou des abscisses.

![[3 - Régime sinusoïdal permanent 2024-02-06 17.27.21.excalidraw.svg]]
%%[[3 - Régime sinusoïdal permanent 2024-02-06 17.27.21.excalidraw.md|🖋 Edit in Excalidraw]]%%

$u_{1}(t)=U_{1}\cos(\omega t+\phi_{1})$
$u_{2}(t)=U_{2}\cos(\omega t+\phi_{2})$
$u(t)=U_{m}\cos(\omega t+\phi)$
Trouver $U_{m}$ et $\phi$ :

Origine des phases : axes des abscisses (convention mais pas obligatoire)
![[3 - Régime sinusoïdal permanent 2024-02-06 17.32.20.excalidraw.svg]]
%%[[3 - Régime sinusoïdal permanent 2024-02-06 17.32.20.excalidraw.md|🖋 Edit in Excalidraw]]%%
$\vec{u}=\vec{u_{1}}+\vec{u_{2}}$

### Nombres complexes
$$U(t)=U_{m}\cos(\omega t+\phi)+jU_{m}\sin(\omega t+\phi)$$

**Amplitude complexe**
$$U=U_{m}\cos(\phi )+jU_{m}\sin(\phi)$$ Si $u=\sqrt{ 2 }(1+j)$
$u(t)=2\cos\left( \omega t+\frac{\pi}{4} \right)$
Module du nombre complexe : $Um$
Argument : $\phi$ (utilisation de la fonction $\tan$ et $\arctan$)

#### Exemples
$$i(t)= I_{\text{m}}\cos(\omega t+\phi)$$
$$\underline{i} = I_{\text{m}}e^{j\phi}$$
$$i_{p}(t)=\frac{I_{\text{m}}}{\omega}\sin(\omega t+\phi)=\frac{I_{\text{m}}}{\omega}\cos\left( \omega t + \phi -\frac{\pi}{2} \right)$$
$$\underline{i_{p}}=-\frac{j}{\omega}I_{m}e^{j\phi}=-\frac{j}{\omega}\underline{i}=\frac{1}{j \omega}\underline{i}$$
La dérivée d'une grandeur sinusoïdale de pulsation $\omega$ est en avance de phase de $\frac{\pi}{2}$ et sa primitive est en retard de phase de $\frac{\pi}{2}$

**Bobine**
$u_{L}(t)=\frac{L\mathrm{d}i}{\mathrm{d}t}$

$\underline{u_{L}}=Lj \omega i$ d'après les relations ci dessus

**Condensateur**
$i(t)=C\frac{\mathrm{d}u}{\mathrm{d}t}$
$\underline{i}=Cj \omega \underline{u_{c}}$
$\underline{u_{c}}=\frac{1}{jC \omega}\underline{i}=-\frac{j}{C \omega}\underline{i}$

**Résistance**
$u_{R}(t)=R \times i(t)$
$\underline{u_{R}}=R \underline{i}$

$$u(t)=u_{R}(t)+u_{L}(t)+u_{C}(t)$$
$$\underline{u}=\underline{u_{L}}+\underline{u_{L}}+\underline{u_{C}}$$
$$\underline{u}=R \underline{i}+ jL \omega \underline{i}-\frac{j}{C \omega}\underline{i}$$
$$\underline{u}=\underline{i}\left( R+jL \omega-\frac{j}{C \omega} \right)$$
Où $R+jL \omega-\frac{j}{C \omega}= Z_{equ}$ l'impédance complexe

$$\underline{u}=\underline{i}\left( R+j\left( L \omega- \frac{1}{ C \omega} \right) \right)$$
En notation complexe, on peut remplacer une résistance, une bobine et un condensateur en série par une impédance équivalente.

