# Anticipez les besoins en comsommations des bâtiments

Le projet a porté sur le nettoyage, l'analyse et la modélisation de la consommation en énergie et de l'émission en CO<sub>2</sub> de bâtiments.

Plusieurs modèles ont été utilisés :
- DummyRegressor
- linéaire et polynômiale
- ElasticNet
- Random forest
- AdaBoost
- Gradient Boosting
- KNN
- Support Vector regression

Le meilleur modèle à été choisi en se basant sur le score accuracy, la dispersion des scores obtenus via un gridsearchCV, les courbes d'apprentissage et les temps de calcul.

Enfin une comparaison a été obtenue entre les réultats obtenus avec l'ensemble des variables (34) et après avoir sélectionné les 5 variables les plus pertinentes (SHAP).
