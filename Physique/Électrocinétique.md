nathalie.godin

## Les composants

**Dipôle :** composant avec 2 bornes
**Noeud :** Jonction entre au moins 3 fils

**Branche :** Ensemble de dipôles montés en série entre 2 noeud

**Maille :** Portion fermée d'un circuit

**Réseau :** ensemble de composants reliés par des fils de connexion

**Fils de connexion :** Fil conducteur dont la résistance est négligeable

* **Fil**
![[Pasted image 20231013133810.png]]
* **Noeuds**
![[Pasted image 20231013133831.png]]
* **Croisement** (sans noeud)
![[Pasted image 20231013133842.png]]
### Dipôles passifs

* **Résistance**
![[Pasted image 20231013133925.png]]
* **Capacité**
![[Pasted image 20231013133933.png]]
* **Inductance**
![[Pasted image 20231013133941.png]]
* **Résistance variable**
![[Pasted image 20231013134024.png]]
* **Interrupteur**
![[Pasted image 20231013134035.png]]
* **Lampe**
![[Pasted image 20231013134045.png]]
### Dipôles actifs
|Source de courant|Source de tension|
|--|--|
|![[Pasted image 20231013134138.png]]|![[Pasted image 20231013134208.png]]|
||*On peut avoir une tension non nulle même si $I=0$ A*|



Branchement en série $\implies$ Même intensité
Branchement en dérivation $\implies$ Même tension

Loi des mailles : $\Sigma$ tensions $= 0$

**Représentation du courant et de la tension :**
Convention récepteur :
Tension dans le sens opposé du courant

### Différents régimes
* Continue
* Variable
	* Variable périodique
* Transitoire

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

