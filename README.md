# Optimisation Numérique : Gradient et Newton

## Description

Ce projet illustre l'application de différentes méthodes d'optimisation pour trouver le minimum d'une fonction quadratique convexe à deux variables :

$$
f(x, y) = x^2 + 2y^2 + xy - 6x - 8y
$$

Les méthodes implémentées sont :

1. **Gradient à pas fixe**
2. **Gradient à pas variable**
3. **Gradient à pas optimal**
4. **Méthode de Newton**

Le projet permet de comparer les trajectoires et performances de ces méthodes.

---

## Contenu du projet

* `Algorithmes_Optimisation.ipynb` : Notebook principal contenant :

  * Implémentation des 4 méthodes d'optimisation
  * Calcul du gradient et de la Hessienne
  * Visualisations 2D et 3D des trajectoires
  * Comparaison des performances
* `requirements.txt` : Dépendances Python nécessaires (`numpy`, `matplotlib`, `plotly`)
* `.gitignore` : Fichiers à ignorer .

---

## Visualisations

* **2D** : Projection des trajectoires des quatre algorithmes dans le plan (x)-(y).
* **3D interactive** : Surface de la fonction et trajectoires des algorithmes avec possibilité de rotation et zoom.

Le minimum réel de la fonction est :
$$
(x^*, y^*) = \left(\frac{16}{7}, \frac{10}{7}\right)
$$

---

## Instructions d'utilisation

1. Créer un environnement virtuel Python (optionnel mais recommandé) :

```bash
python -m venv venv
source venv/bin/activate  # mac/linux
venv\Scripts\activate     # windows
```

2. Installer les dépendances :

```bash
pip install -r requirements.txt
```

3. Lancer le notebook :

```bash
jupyter notebook Algorithmes_Optimisation.ipynb
```

---

## Résultats attendus

* Comparaison des performances des 4 algorithmes : nombre d’itérations, rapidité, trajectoire.
* Visualisation claire des différences entre pas fixe, pas variable, pas optimal et méthode de Newton.

---

## Auteur

Bargouth Eya — Projet réalisé dans le cadre d’un cours d’optimisation numérique.
