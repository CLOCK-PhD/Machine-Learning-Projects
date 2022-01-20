# Chapitre 4 - Training Models

Dans ce chapitre, on va s'intéresser à comment les choses fonctionnent de manière plus approfondie afin de mieux pouvoir choisir un modèle approprié.

On va commencer avec le modèle de *Régression Linéaire*, un des plus simples. Puis, on va discuter de deux manières très différentes de l'entraîner :
- En utilisant une équation directe de « forme fermée » qui calcule directement les paramètres du modèle qui font correspondre le mieux le modèle au jeu d'entraînement.
- En utilisant une approche d'optimisation itérative appelée *Gradient Descent* (GD) qui va progressivement modifier les paramètres du modèle pour minimiser la fonction de coût sur le JdE, pour finir par converger vers les mêmes jeux de paramètres que lors de la première méthode.

On regardera ensuite la *Régression polynomiale*, un modèle plus complexe qui peut s'adapter aux jeux de données non-linéaires. Comme ce modèle a plus de paramètres que la régression linéaire, il est plus enclin au surapprentissage des données d'entraînement, donc on va regarder comment détecter si c'est le cas ou non en utilisant des *courbes d'apprentissage*, puis on regardera plusieurs techniques de régularisation qui peuvent rédire le risque de surapprentissage du JdE.

Enfin, on va regarder deux autres modèles qui sont communément utilisés pour la classification : la *Régression Logistique* et la *SoftMax Regression*.