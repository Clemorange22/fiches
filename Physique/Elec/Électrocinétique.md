nathalie.godin

## Les composants

**Dipôle :** composant avec 2 bornes : générateur ou récepteur
**Noeud :** Jonction entre au moins 3 fils

**Branche :** Ensemble de dipôles montés en série entre 2 noeud

**Maille :** Portion fermée d'un circuit

**Réseau :** ensemble de composants reliés par des fils de connexion

**Fils de connexion :** Fil conducteur dont la résistance est négligeable

|Fil|Noeuds|Croisement (sans noeud)|
|--|--|--|
|![[Pasted image 20231013133810.png]]|![[Pasted image 20231013133831.png]]|![[Pasted image 20231013133842.png]]|

### Dipôles passifs

|Résistance|Capacité|Inductance|Résistance variable|Interrupteur|Lampe|
|--|--|-|-|-|-|
|![[Pasted image 20231013133925.png]]|![[Pasted image 20231013133933.png]]|![[Pasted image 20231013133941.png]] |![[Pasted image 20231013134024.png]]|![[Pasted image 20231013134035.png]]|![[Pasted image 20231013134045.png]]|

### Dipôles actifs
|Source de courant|Source de tension|
|--|--|
|![[Pasted image 20231013134138.png]]|![[Pasted image 20231013134208.png]]|
||*On peut avoir une tension non nulle même si $I=0$ A*|
||*Pour une source, la tension est orientée du - vers le +*|
|Quand éteinte, équivaut à un interrupteur ouvert|Quand éteinte, équivaut à un fil
Peut être électromoteur ou contre-électromoteur





Branchement en série $\implies$ Même intensité
Branchement en dérivation $\implies$ Même tension

Loi des mailles : $\Sigma$ tensions $= 0$
Loi des noeuds : Intensités d'entrée = Intensités de sortie


**Représentation du courant et de la tension :**
**Convention récepteur :**
![[Pasted image 20231013135542.png]]
Tension dans le sens opposé du courant

### Caractéristique
Représente le rapport entre l'intensité du courant circulant dans un dipôle et la tension à ses bornes

**Symétrie par rapport au point (0,0)**
Indique que le dipôle est **non-polarisé**, on peut le brancher dans l'autre sens sans changer son fonctionnement
À l'inverse, quand cette symétrie n'est pas présente on parle d'un dipôle **polarisé**

**Passif ou actif ?**
La caractéristique d'un dipôle passif passe par le point (0,0)

**Linéarité**
Le dipôle est dit **linéaire** si sa courbe caractéristique est une droite

### Différents régimes
* Continu
* Variable
	* Variable périodique
* Transitoire (correspond au démarrage d'un système)

**Caractéristique :** Lien entre intensité et tension aux bornes d'un dipôle
* passe par l'origine pour un dipôle passif
* ne passe pas par l'origine pour un dipôle actif

Conductance $G=\frac{1}{R}$
unité : siemer/mho

### Résistance
Effet joule : $E_{perdue}=Ri^{2}$

Résistances en série : $R=R_{1}+R_{2}+R_{3}$

Résistances en parallèle : $\frac{1}{R}=\frac{1}{R_{1}}+\frac{1}{R_{2}}+\frac{1}{R_{3}}$

```ad-note
Procéder par étape lors des calculs de résistance
```

**Transfigurer le réseau :** Modifier représentation d'un réseau électrique

### Condensateur

$i(t)=C\frac{\mathrm{d}u}{\mathrm{d}t}$ (0 quand le courant est continu)
* Modèle condensateur parfait $\neq$ condensateur réel (résistance)

### Bobine
Bobine parfaite
$u(t)=L\frac{\mathrm{d}i }{\mathrm{d}t}$
L : inductance en Henry (H)
Bobine réelle
$u(t)=L\frac{\mathrm{d}i}{\mathrm{d}t}+Ri(t)$

$\vec{E}$ : force électromotrice (tension en V)

### Puissance électrique disponible dans une portion de circuit
$P=UI$

**En convention récepteur :**
$P>0 \implies$ Le dipôle est récepteur
$P<0 \implies$ Le dipôle est émetteur

### Association de générateurs (théorème de millman)
#### En série
$E$ : force électro-motrice = tension aux bornes d'un générateur
$P_{totale} = P_{1} + P_{2}+P_{3}+\dots+P_{k}=(E_{1}+E_{2}+E_{3}+\dots+E_{k})I$
$E=\sum_{k=0}^{n}E_{k}$

#### En parallèle

$\frac{1}{R_{e}}=\sum_{i}\frac{1}{R_{}i}$
$\frac{E_{e}}{R_{e}}=\sum_{i}\frac{E_{i}}{R_{i}}$

### Représentation d'un générateur
Même tension à vide
Même résistance
#### Thévenin
![[Pasted image 20231013154436.png]]
#### Norton
![[Pasted image 20231013154447.png]]
**Pour passer d'une représentation à l'autre :**
$E_{th}=RI_{n}$
$R_{th}=R_{n}$

**Principe de superposition**
$I_{totale}=\sum I_{source}$

### Théorème de Thévenin

```ad-note
Permet de simplifier la représentation d'un ensemble de générateurs en le remplaçant par un générateur de thévenin équivalent
```

1. Définir la partie du circuit que l'on veut remplacer
2. Calculer la résistance à l'état passif de notre partie du circuit et l'utiliser comme résistance pour le générateur de thévenin
3. Calculer tension à vide aux bornes de la partie du circuit étudiée $\rightarrow$ Force électromotrice $\vec{E}$ du générateur de thévenin
