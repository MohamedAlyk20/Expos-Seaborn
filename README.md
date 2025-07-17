cet exposé a été réalisé par Mohamed Aly KOUYATE et Fodé Moussa FOFANA


# 📊 Présentation de la bibliothèque Seaborn

## 🔹 Introduction à la bibliothèque Seaborn

### ➤ Définition

**Seaborn** est une bibliothèque de visualisation de données en Python, basée sur Matplotlib. Elle fournit une interface de haut niveau pour créer des graphiques statistiques attrayants et informatifs. Conçue pour fonctionner parfaitement avec les structures de données Pandas, Seaborn simplifie considérablement la création de graphiques complexes.

---

## 🔹 Pourquoi faire de la visualisation ?

La visualisation des données est une étape cruciale dans tout processus d’analyse. Elle permet de :

* Résumer rapidement de grands volumes de données.
* Mettre en évidence des tendances, des schémas et des anomalies.
* Faciliter la communication des résultats.
* Servir d’outil exploratoire pour guider les analyses statistiques.

---

## 🔹 Pourquoi utiliser Seaborn ?

Seaborn offre plusieurs avantages par rapport à Matplotlib seul :

* Syntaxe simple et concise.
* Intégration naturelle avec les DataFrames Pandas.
* Thèmes graphiques élégants par défaut.
* Prise en charge native des graphiques statistiques : distribution, régression, corrélation, etc.
* Paramètres puissants comme `hue`, `style`, `palette`, `cmap`...

---

## 🔹 Comment utiliser Seaborn ?

### Installation :

```bash
pip install seaborn
```

### Importation dans un script Python :

```python
import seaborn as sns
import matplotlib.pyplot as plt
```

### Utilisation typique :

Seaborn fonctionne bien avec les **DataFrames Pandas**. Par exemple :

```python
import pandas as pd
import seaborn as sns

df = pd.read_csv("data.csv")
sns.histplot(data=df, x="prix", kde=True)
```

---

## 🔹 Les fonctions courantes

Voici quelques fonctions populaires de Seaborn :

| Fonction            | Description                                      |
| ------------------- | ------------------------------------------------ |
| `sns.histplot()`    | Histogramme (distribution)                       |
| `sns.countplot()`   | Nombre d’occurrences d’une variable catégorielle |
| `sns.boxplot()`     | Visualisation des médianes et des outliers       |
| `sns.scatterplot()` | Nuage de points                                  |
| `sns.heatmap()`     | Matrice de corrélation ou de valeurs             |
| `sns.barplot()`     | Moyennes groupées par catégorie                  |

---

## 🔹 Différences entre Matplotlib et Seaborn

| Matplotlib                                 | Seaborn                                   |
| ------------------------------------------ | ----------------------------------------- |
| Niveau bas (plus flexible, mais plus long) | Niveau haut (plus simple à utiliser)      |
| Moins esthétique par défaut                | Graphiques stylisés automatiquement       |
| Nécessite plus de configuration            | Fournit des fonctions "prêtes à l’emploi" |
| Faible intégration avec Pandas             | Forte compatibilité avec les DataFrames   |

---

## 🔹 Quelques réalisations graphiques avec Seaborn

Dans le cadre de ce projet, plusieurs types de visualisations ont été réalisés à partir d’un dataset de voitures d’occasion :

* Histogrammes des prix (`histplot`)
* Nuages de points (`scatterplot`) pour visualiser la relation entre le kilométrage et le prix
* Graphiques à barres (`countplot`) des marques les plus fréquentes
* Boîtes à moustaches (`boxplot`) pour étudier l’impact du nombre de propriétaires
* Cartes thermiques (`heatmap`) de la corrélation entre les variables numériques

---

## 🔹 Conclusion

**Seaborn** est un outil puissant pour analyser visuellement des données de manière simple, élégante et intuitive. Son intégration avec Pandas et ses fonctions riches permettent d’explorer efficacement des datasets, de mieux comprendre les tendances et de présenter les résultats de manière convaincante.

---

## 🙏 Merci pour votre attention

