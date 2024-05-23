# Continuité
$sup(I)=$ plus petit majorant de I
$inf(I)=$ plus grand majorant de I

## Théorème des valeurs intermédiaires
Soit $f$ continue sur un intervalle $[a,b]$
Alors pour tout réel $y \in [f(a),f(b)]$, il existe au moins un réel $x_{0} \in [a,b]$ tel que $y = f(x_{0})$

## Image d'un segment par une application continue
**segment :** intervalle de la forme $[a,b]$ (fermé borné) avec $a$ et $b$ réels
$f([a,b])=[min(f), max(f)]$
**conséquence :** l'image d'un segment par une fonction continue est un segment

## Bijection
Soit $I$ un intervalle de $\mathbb{R}$ et $f$ une fonction continue et strictement monotone sur $I$
* $f$ bijective de $I$ dans $f(I)$
* $f(I)$ est un intervalle dont les bornes sont les limites de $f$ aux bornes de $I$
* $f^{-1}$ : $f(I) \to I$ est continue sur $f(I)$ et a le même sens de variation que $f$
* les courbes de $f$ et $f^{-1}$ sont symétriques par rapport à $y=x$

## Fonctions trigo
### sin
* sin :$\left[ -\frac{\pi}{2}, \frac{\pi}{2} \right] \to [-1,1]$ 
* continue et strictement croissante donc bijective
### arcsin
* arcsin : $[-1, 1] \to \left[ -\frac{\pi}{2}, \frac{\pi}{2} \right]$
* continue, strictement croissante, impaire
* $\forall x \in [-1,1], \sin(\arcsin(x))=x$
* $\forall \theta \in \left[ -\frac{\pi}{2}, \frac{\pi}{2} \right], \arcsin(\sin(\theta))=\theta$
* $\arcsin(x) \underset{0}{\sim} x$
* $\arcsin'(x)=\frac{1}{\sqrt{ 1-x^{2} }}$ $x \in ]-1,1[$
### cos
* cos :$\left[ 0,\pi \right] \to [-1,1]$ 
* continue et strictement décroissante donc bijective
### arccos
* arccos : $[-1, 1] \to \left[ 0,\pi \right]$
* continue, strictement croissante
* $\forall x \in [-1,1], \cos(\arccos(x))=x$
* $\forall \theta \in \left[ 0,\pi \right], \arccos(\cos(\theta))=\theta$
* $\arccos'(x)=-\frac{1}{\sqrt{ 1-x^{2} }}$ $x \in ]-1,1[$

### liens arcsin-arccos
* $\forall x \in [-1,1], \arccos(x)+\arcsin(x) = \frac{\pi}{2}$
* $\forall x \in [-1,1], \cos(\arcsin(x)) = \sin(\arccos(x)) = \sqrt{ 1-x^{2} }$
### tan
* tan: $]-\frac{\pi}{2}, \frac{\pi}{2}[ \to \mathbb{R}$
* continue et strictement croissante donc bijective
### arctan
* arctan : $\mathbb{R} \to ]-\frac{\pi}{2}, \frac{\pi}{2}[$
* continue, strictement croissante et impaire
* $\forall x \in \mathbb{R}, \tan(\arctan(x))=x$
* $\forall \theta \in ]-\frac{\pi}{2}, \frac{\pi}{2}[, \arctan(\tan(\theta))=\theta$
* $\arctan(x) \underset{0}{\sim} x$
* $\forall x>0, \arctan(x) + \arctan\left( \frac{1}{x} \right) = \frac{\pi}{2}$
* $\forall x<0, \arctan(x) + \arctan\left( \frac{1}{x} \right) = -\frac{\pi}{2}$
* $\arctan'(x)=\frac{1}{1+x^{2}}$

# Dérivation

### Formule de Taylor
$$\forall x \in \mathbb{R}, P(x)=\sum^{n}_{k=0}\frac{P^{(k)}(0)}{k!}x^{k}$$
ou $$\forall x \in \mathbb{R}, P(x)=\sum^{n}_{k=0}\frac{P^{(k)}(\alpha)}{k!}(x-\alpha)^{k}$$
### Classes de fonctions
#### Fonctions de classe $C^{\infty}$ sur les intervalles où elles sont dérivables
- exp
- ln
- sin
- cos
- tan
- racine carrée
- puissances
- polynômes
- ch
- th
## Théorème de la dérivée de la réciproque
$f^{-1}$ est dérivable en $a$ si et seulement si $f'(a)\neq 0$
$$(f^{-1})'(f(a))=\frac{1}{f'(a)}$$
ou encore, si on pose $b=f(a)$
$$(f^{-1})'(b)=\frac{1}{f' \circ f^{-1}(b)}$$
## Théorème de Rolle et conséquences

### Extremums locaux
Soit $f$ dérivable sur $I$ et $a \in I$ tq $a$ ne soit pas une borne de $I$. Si $f$ admet un extremum local en $a$, alors $f'(a)=0$

### Rolle
Soient $a$ et $b$ deux réels tq $a<b$. Soit $f$ continue sur $[a,b]$ et dérivable sur $]a,b[$
Si $f(a)=f(b)$, alors il existe $c \in ]a,b[$ tq $f'(c)=0$ 

### Acroissements finis
Soient $a$ et $b$ deux réels tq $a<b$. Soit $f$ continue sur $[a,b]$ et dérivable sur $]a,b[$
Alors il existe $c \in ]a,b[$ tq: 
$$f(b)-f(a)=f'(c)(b-a)$$
$$\iff f'(c)=\frac{f(b)-f(a)}{b-a}$$
### Inégalité des accroissements finis
 Soit $f$ continue sur $[a,b]$ et dérivable sur $]a,b[$
 