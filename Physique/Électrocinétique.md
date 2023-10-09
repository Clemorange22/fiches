nathalie.godin

## Les composants

**Dipôle :** composant avec 2 bornes
**Noeud :** Jonction entre au moins 3 fils

**Branche :** Ensemble de dipôles montés en série entre 2 noeud

**Maille :** Portion fermée d'un circuit

**Réseau :** ensemble de composants reliés par des fils de connexion

**Fils de connexion :** Fil conducteur dont la résistance est négligeable

* Fil
* Noeuds
* Croisement (sans noeud)
### Dipôles passif

* Résistance
* Capacité
* Inductance
* Résistance variable
* Interrupteur
* Lampe
### Dipôles actifs

* Source de courant
* Source de tension

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
$u(t)=L\frac{\mathrm{d}i}{\mathrm{d}t}$
L : inductance en Henry (H)
Bobine réelle
$u(t)=L\frac{\mathrm{d}i}{\mathrm{d}t}+Ri(t)$

