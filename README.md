# 📊 Analyse de la Croissance des Plantes (Projet ANOVA)

## 📝 Description du Projet
Ce projet a été réalisé dans le cadre du cursus **ISE 2 (Ingénieur Statisticien Économiste)** à l'**ENSAE Dakar / ANSD**. L'objectif est d'étudier l'impact de différents traitements sur la croissance végétale via une analyse de la variance (ANOVA) à un facteur.

Le livrable final est un **rapport interactif en format HTML**, alliant rigueur statistique et mise en page dynamique (CSS personnalisé).

## 🚀 Étapes de l'Analyse
Le projet suit une démarche structurée en 5 étapes clés :

1. **Exploration des Données (EDA)** : 
   - Nettoyage du dataset et statistiques descriptives.
   - Visualisation via des **Boxplots** pour comparer la distribution des croissances par groupe.
2. **Vérification des Hypothèses (Gauss-Markov)** :
   - Test de **Shapiro-Wilk** pour la normalité des résidus.
   - Test de **Bartlett** (ou Levene) pour l'homoscédasticité (égalité des variances).
3. **Modélisation ANOVA** :
   - Calcul de la décomposition de la variance ($SS_{Total} = SS_{Ter} + SS_{Res}$).
   - Test de Fisher pour déterminer l'existence d'un effet traitement significatif.
4. **Tests Post-hoc** :
   - Application du test de **Tukey HSD** pour identifier précisément quels groupes diffèrent les uns des autres.
5. **Reporting Professionnel** :
   - Génération du rapport via **RMarkdown** avec intégration de logos (ENSAE/ANSD) et stylisation CSS.

## 🛠️ Technologies Utilisées
- **Langage** : R
- **Format de Sortie** : HTML (interactif)
- **Design** : CSS3 personnalisé & RMarkdown
- **Librairies clés** : `ggplot2`, `dplyr`, `knitr`, `kableExtra`

## 📁 Structure du Dépôt
- `Projet_ANOVA.Rmd` : Le code source complet.
- `Projet_ANOVA.html` : Le rapport final (à ouvrir dans un navigateur).
- `Base de donné` : Jeu de données utilisé.
- `images/` : Ressources graphiques (logos).

## 🎓 Auteurs
* **ILLY Jacques** - *Élève Ingénieur Statisticien*
* **ZINABA Albert** - *Élève Ingénieur Statisticien*
* **Sous la direction de** : M.  A. Carlos (Enseignant)

---
*Projet réalisé dans le cadre du module "Analyse de la Variance" - 2026*
