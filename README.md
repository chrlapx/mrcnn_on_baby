# mrcnn_on_baby
train / val dataset 

main python file mrcnn(2)_(1) (1).ipybn as main file
test images (that are mistakes or not) dossier images
the hyperparameters you used (bonus points if you tried several) all in the main file
log obtained during training showing the last epoch's losses (bbox loss, train loss...) in the main file
graph of the losses for each epoch in the main file
smart human-generated comments on the results and the process 
 get a matrix of confusion to detect potential biases in the main file

# Analyse des Images - Résultats et Limitations

## Introduction

Ce projet vise à utiliser le model MRCNN pour effectuer une detection du visage et du nez des bébés afin de part la suite dire s'il sont de face ou de dos pour alerter d'un possible étouffement. Bien que les résultats obtenus soient encore perfectibles, le projet reflète une démarche d'apprentissage et une approche méthodique.

## Méthodologie

1. **Collection des Données :**  
   Le projet s'appuie sur un jeu de données constitué de 3 sous dossiers : train/test/valid contenant chacun 10 images de bébés et un fichier d'annotation correspondant aux images du sous dossier. Cependant, la taille limitée du jeu de données (30 images) a été une contrainte majeure.

2. **Augmentation des Données :**  
   Afin de pallier le manque d'images, diverses techniques d'augmentation des données ont été mises en œuvre, telles que :
   - Rotation
   - Recadrage
   - Modification de la luminosité et du contraste

3. **Modélisation :**  
   Le modèle MRCNN a été entraîné sur ce jeu de données avec des ajustements hyperparamétriques pour optimiser les performances.


## Limitations

1. **Taille du Jeu de Données :**  
   Le manque de diversité et de volume d'images a eu un impact direct sur la généralisation du modèle.

2. **Efficacité de l'Augmentation :**  
   Bien que l'augmentation des données ait été mise en œuvre, elle n'a pas permis de compenser entièrement la faible quantité d'images d'origine.

3. **Complexité des Modèles :**  
   Des modèles plus complexes auraient pu être explorés, mais leur efficacité reste conditionnée par la quantité de données.

## Pistes d'Amélioration

- **Collecte de Données Supplémentaires :**  
  Augmenter la taille et la diversité du jeu de données pour améliorer les performances.  
- **Optimisation des Hyperparamètres :**  
  Tester davantage d'architectures et de configurations pour obtenir un modèle plus performant.  
- **Approches Alternatives :**  
  Explorer des modèles pré-entraînés ou des techniques semi-supervisées.

## Conclusion

Ce projet, bien qu'incomplet, constitue une étape importante dans la compréhension des défis liés au comuter vision. Les enseignements tirés orienteront les efforts futurs pour surmonter les limitations actuelles.


