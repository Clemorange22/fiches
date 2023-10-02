
## Chiffres significatifs

Tous les chiffres d'un résultat **autres que les zéros précédant le premier chiffre différent de zéro**

```ad-example
$0.0415\ kg$ $\rightarrow$ Les deux premiers zéros sont non significatifs
$4.1500\ kg$ $\rightarrow$ Les derniers zéros sont significatifs
```

## Incertitude

Une incertitude doit être **cohérente**

```ad-example
$R=(10.2\pm0.2)\ \Omega$ : Incertitude trop grande par rapport à la précison du résultat

$R=(10\pm1)\ \Omega$ : Incertitude cohérente
```

### Estimation de l'incertitude

#### Mesures directes
##### Erreurs systématiques
Écart fixe entre la valeur mesurée et la valeur réelle

**Solution :** Estimation de $\Delta G \ \rightarrow$ Correction
##### Erreurs aléatoires
Écart aléatoire entre la valeur mesurée et la valeur réelle

* Type **B** : $1$ mesure $\rightarrow$ Traitement *probabiliste*
	*  (pas au programme)
* Type **A** : $n$ mesures $\rightarrow$ Traitement *statistique*
	* Historigramme des résultats
	* Moyenne
	* Écart type $s$
	* Incertitude type $u=\Delta X=k\frac{s}{\sqrt{n}}$

|Valeur de **k**|1|2|3|
|--|--|--|--|
|Niveau de confiance|68,3%|95% | 99,8%|

**Solution :** Estimation de $\Delta G \ \rightarrow$ Correction

#### Mesures indirectes

$G=f(X,Y,Z,\cdots)$
Mesure de $G$ liée aux mesures directes de $X$,$Y$,$Z$ par une loi de dépendance

**Solution :** Estimation de $\Delta X$, $\Delta Y$, $\Delta Z$
$\rightarrow$ Estimation de $\Delta G$
* Encadrement
	* $\Delta g = \frac{g_{max}-g_{min}}{2}$
* Propagation
* Différentielle
	* $\Delta g=\sqrt{\sum_{i=1}^{N}{\left( \frac{\partial f}{\partial x_{i}} \right)^2(\Delta x_{i})^2}}$

```ad-caution
Les incertitudes s'**additionnent** et **ne se compensent pas**
```

