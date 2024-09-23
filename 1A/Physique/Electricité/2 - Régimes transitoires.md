![[Régimes transitoires 2023-10-23 08.05.35.excalidraw.svg]]
%%[[Régimes transitoires 2023-10-23 08.05.35.excalidraw|🖋 Edit in Excalidraw]], and the [[Régimes transitoires 2023-10-23 08.05.35.excalidraw.dark.svg|dark exported image]]%%

Quand courant continu : condensateur $\iff$ interrupteur ouvert
on cherche à trouver une expression de $U_{c}$ en fonction de $t$

1. solution générale
 $$\frac{dU_{c}(t)}{dt}+\frac{1}{RC}=0$$
 $$\frac{dU_{c}(t)}{dt}=-\frac{1}{RC}U_{c}(t)$$
 $$\implies \frac{\frac{dU_{c}(t)}{dt}}{U_{c}(t)}=-\frac{1}{RC}$$
 $$\implies \ln(U_{c}(t))=-\frac{1}{RC}+K$$$$\implies U_{c}(t)=e^{-\frac{1}{RC}+K}$$
 $$\implies U_{c}(t)=e^{-\frac{1}{RC}}\times e^K$$
2. solution particulière
 $$\frac{dU_{c}(t)}{dt}+\frac{1}{RC}=\frac{E}{RC}$$
 Tension aux bornes d'un condensateur : fonction continue
On utilise $U_{c}(0)$ pour en déduire la constante

$$i(t)=C \frac{dU_{c}(t)}{dt}=C \frac{E}{RC}e^{-\frac{1}{RC}}=\frac{E}{R}e^{-1/RC}$$
![[Régimes transitoires 2023-10-23 08.33.47.excalidraw.svg]]
%%[[Régimes transitoires 2023-10-23 08.33.47.excalidraw|🖋 Edit in Excalidraw]], and the [[Régimes transitoires 2023-10-23 08.33.47.excalidraw.dark.svg|dark exported image]]%%

### Puissance fournie/absorbée
**Par le générateur**
$$W_{g}=\int_{0}^{\infty} U.i \, dt =CU^{2}$$
**Par le condensateur**
$$W_{E}=\int_{0}^{\infty} u.i \, dt =\frac{1}{2} CU^{2}$$
**Par la résistance**
$$W_{R}=\int_{0}^{\infty} R.i^{2} \, dt =\int_{0}^{\infty} u.i \, dt =\frac{1}{2} CU^{2}$$

### Bobine
Courant toujours continu (et non pas la tension)
Peut être remplacée par un fil

$$W_{E}=\int_{0}^{\infty} ? \, dt =\frac{1}{2} Li^2$$

$$\int_{0}^{\infty}\frac{\mathrm{d}t}{t}$$
