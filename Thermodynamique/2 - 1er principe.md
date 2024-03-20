
## Énergie interne
Premier principe : 
Il existe un fonction d'état extensive  $U$, appelée énergie interne et homogène à une énergie.
Au cours d'une transformation d'un système d'un état 1 à  un état 2,
$\Delta E_{\text{mecanique macro}} + \Delta U= W+Q$

* Transformation fermée : $\Delta U= W+Q=0$
* Transformation ouverte 

**Fonction d'état :** dépend seulement de l'état de départ et d'arrivée, et non pas de manière de passer de l'un à l'autre

$U$ est une fonction d'état
$W$ et $Q$ n'en sont pas

>[!warning] 
>On peut avoir une transformation ouverte avec un système fermé.
>Exemple : piston

## Travail des forces de pression
$\delta W=-P_{ext} \times \mathrm{d}V$

Piston compresssé par un poids
2 cas :
* Transformation réversible $P_{ext}=P_{\sigma}$ à tout instant
* Transformation brusque $P_{ext}=cte=P_{B}$
 Soit $\vec{du }$ le déplacement élémentaire du point d'application
$W=\int  \overline{F_{ext}} \, \vec{du} = \int  \overline{F_{ext}} \times \vec{du}=\int P_{ext} \times S \times du=\int P_{ext} \times |dV|$
Or $dV < 0$ donc $|dV| = -dV$
Donc $W = \int - P_{ext} \times dV$

Il faut plus de travail pour une transformation brusque que réversible

Système fermé : En fonction du sens de la transformation, le travail $W$ est positif ou négatif

monobare : $P_{A}=P_{B}$
isobare : $P_{A}=P_{B} = cste$
monotherme : $T_{A}=T_{B}$
isotherme : $T_{A}=T_{B}=cste$
isochore : volume toujours constant
adiabatique : transformation qui n'échange pas de chaleur


| Conditions spécifiques             | $\Delta U_{AB}+W_{AB}$             |                                                              | Commentaires                                         | Gaz parfait                        |
| ---------------------------------- | ---------------------------------- | ------------------------------------------------------------ | ---------------------------------------------------- | ---------------------------------- |
|                                    | Réversible                         | Irréversible                                                 |                                                      |                                    |
| Monotherme ($T_{ext}$ = constante) | $T_{sys}=$ constante               | $T_{A}=T_{B}$ mais peut changer au cours de la tranformation | Dans les 2 cas, $W_{AB}$ et $Q_{AB}$ sont différents | $\Delta U=0$; $\Delta H=0$; $Q=-W$ |
| Isochore ($V$ constant)            | $W_{AB}=0$; $Q_{AB}=\Delta U_{AB}$ | $W_{AB}=0$; $Q_{AB}= \Delta U_{AB}$                          |                                                      |                                    |
| Monobare ($P_{ext}$ constante )    | $P$ constante                      | $P$ peut être différente                                     |                                                      |                                    |
| Adiabatique                        | $Q=0$; $W_{AB}=\Delta U_{AB}$      | $Q=0$                                                        |                                                      | $PV=nRT$                           |
$\Delta H=Q_{V}=\Delta U+ \Delta(PV)$
où $\Delta U=Q_{V}\neq Q_{P}$

$\Delta H$ : "chaleur échangée" = fonction enthalpie du système / fonction d'état

### Système fermé
Soit un système fermé avec $n$ variables d'état
$n-1$ dérivées partielles suffisent à 
$$\mathrm{d}U_{\sigma}=\left(\frac{\partial U}{\partial T} \right) \mathrm{d}T+ \left( \frac{\partial U}{\partial V} \right)\mathrm{d}V$$
$$\mathrm{d}U_{\sigma}=\delta W_{\sigma}+\delta Q_{\sigma}=-P_{ext}\mathrm{d}V+\delta Q_{\sigma}$$
$$C_{v}=\left( \frac{\partial U}{\partial T} \right)_{V}$$
$C_{v}$ : **capacité calorifique à volume constant**
$$l=P+\left( \frac{\partial U}{\partial V} \right)_{T}$$
$l$ : **chaleur latente d'expansion**

$\delta Q_{ev}=C_{v}\mathrm{d}T+l\mathrm{d}V$

>[!hint] 
>Une échange de chaleur n'implique pas forcément une variation de la température d'un système, il peut aussi agir sur son volume



### Gaz parfait
$$\Delta U=n\overline{C_{v}} \times \Delta T \frac{1}{\gamma-1}(P_{f}V_{f}-P_{i}V_{i})$$

$l=\frac{P}{h}=-V$
$\mathrm{d}U=n\overline{C_{V}}\mathrm{d}T$

### Transformations particulière
**Adiabatique :** $\Delta Q=0 \iff W=\Delta U=W_{\text{adiabatique, GP}}$

$\delta Q_{\text{rev}}=n\overline{C_{v}} \mathrm{d}T+l\mathrm{d}V$
$\delta Q_{\text{rev}}=n\overline{C_{p}}\mathrm{d}T+h\mathrm{d}P$

**Transformation adiabatique réversible d'un gaz parfait :** 
$TV^{\frac{R}{\overline{C_{v}}}}=cste$
$PV^{\frac{R}{\overline{C_{v}}}+1}=cste$

#### Transformation
* **fermée** : état initial = état final; $\Delta U=\Delta H=0$
* **Isochore** : $V_{\text{initial}}=V_{\text{final}}\implies W=0$; $\Delta U=Q=Q_{V}$
* **Monobare :** $P_{\text{initiale}}=P_{\text{finale}}=P_{\text{extérieure}}$; GP : $\Delta U=\Delta H=0$; liqu ou sol: $\Delta U=W$
* **Adiabatique :** ...