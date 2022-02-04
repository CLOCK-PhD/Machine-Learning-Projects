# Apprentissage ensembliste et Forêts Aléatoires

Si on agrège les prédictions d'un groupe de prédicteurs (commes les classificateurs ou les régresseurs), on trouvera souvent de meilleures prédictions qu'avec le meilleur des prédicteurs seul. Un groupe de prédicteurs est appelé un *ensemble*, et donc cette technique est appelée *apprentissage ensembliste* (*ensemble learning*, *EL*), et un algo d'EL est appelée une *méthode ensembliste* (*ensemble method*, *EM*).

Les EM sont souvent utilisées vers la fin d'un projet , une fois qu'on dispose de quelques bons prédicteurs, pour les combiner en un prédicteur encore meilleur.

Dans cette partie, on verra les EM les plus populaires, dont *baging*, *boosting* et *stacking*. On va également explorer les forêts aléatoires (Random Forests, RF).