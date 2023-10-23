![[Régimes transitoires 2023-10-23 08.05.35.excalidraw.svg]]
%%[[Régimes transitoires 2023-10-23 08.05.35.excalidraw.md|🖋 Edit in Excalidraw]], and the [[Régimes transitoires 2023-10-23 08.05.35.excalidraw.dark.svg|dark exported image]]%%

Quand courant continu : condensateur $\iff$ fil
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
%%[[Régimes transitoires 2023-10-23 08.33.47.excalidraw.md|🖋 Edit in Excalidraw]], and the [[Régimes transitoires 2023-10-23 08.33.47.excalidraw.dark.svg|dark exported image]]%%

