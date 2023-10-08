# PSY2008A - Session automne 2023

Ce repo contient les activités pratiques du cours PSY2008A, dispensé par le Dr. Karim Jerbi à l'Université de Montréal.

## Comment utiliser ce repo

Il existe plusieurs façons de suivre les activités pratiques de ce cours :

- **Lire les notebooks directement sur GitHub.** Cette méthode est la plus simple, mais elle ne vous permettra pas de modifier les notebooks ou d'interagir avec eux. De plus, vous ne pourrez pas remplir les espaces vides ni répondre aux questions lorsque cela sera nécessaire. Elle est donc déconseillée si vous souhaitez suivre le cours de manière interactive.

- **Télécharger les notebooks et les exécuter localement avec Jupyter Notebook.** Pour cela, vous aurez besoin d'un environnement Python installé sur votre ordinateur. Nous vous recommandons d'utiliser Anaconda pour créer un environnement Python et l'utiliser avec Jupyter Notebook. Vous pouvez trouver des instructions détaillées sur la façon de configurer un environnement Python dans Anaconda et de l'utiliser avec Jupyter Notebook ici : [lien vers les instructions](https://www.geeksforgeeks.org/how-to-setup-conda-environment-with-jupyter-notebook/).

- **Télécharger les notebooks et les ouvrir avec Google Colab.** Vous pouvez également télécharger les notebooks et les téléverser sur Google Drive pour les ouvrir avec [Google Colab](https://colab.research.google.com/). Cette méthode est utile si vous souhaitez exécuter les notebooks dans un environnement cloud (en ligne).

- **Utiliser Binder** [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/BabaSanfour/PSY2008A2023/HEAD)
Cliquez sur l'icône de Binder pour accéder aux notebooks de ce repo via un service cloud. Vous pouvez exécuter et modifier les notebooks de manière interactive, sans avoir à les télécharger localement. Mais vous ne pouvez pas sauvegarder vos modifications de manière permanente. Une fois la session terminée, toutes les modifications sont perdues. De plus le chargement des notebooks peut prendre du temps, en fonction de la taille du projet et de la connexion Internet.

Nous vous recommandons d'utiliser la deuxième ou la troisième méthode si vous souhaitez suivre le cours de manière interactive. Pour télécharger les notebooks, vous pouvez cliquer sur le bouton "Code" de la page GitHub puis "Télécharger". Une méthode alternative consiste à créer un dossier de travail, ouvrir le terminal et copier-coller la commande suivante :

`git clone https://github.com/BabaSanfour/PSY2008A2023.git`

## Comment contribuer

Si vous trouvez des erreurs ou des incohérences dans les notebooks, n'hésitez pas à les signaler en créant une issue sur GitHub. Vous pouvez également proposer des modifications en créant une pull request. De plus, vous pouvez nous contacter sur le forum de classe pour poser des questions.



# Liste des Activités Pratiques :

## AP1 - Manipulation des Données Électrophysiologiques dans MNE-Python
Présentation de MNE-Python et de sa logique de fonctionnement. Aperçu des objets et fonctions de base (par exemple, ouvrir/visualiser les données).

## AP2 - Pré-traitement (Nettoyage) des Données MEG et EEG
Création d'un pipeline de nettoyage des données électrophysiologiques, comprenant le filtrage, l'ICA et l'estimation automatique des seuils de rejet.

## AP3 - Analyses des Oscillations et des Potentiels Évoqués
Introduction aux outils de base pour la segmentation des données ainsi que le calcul des potentiels évoqués et des oscillations.

## AP4 - Apprentissage Machine et Classification d'Ondes Cérébrales
Exemple d'application de l'apprentissage automatique à l'analyse des données cérébrales. Classification gauche vs droite dans une expérience de présentation visuelle.

