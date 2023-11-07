---
title: Semaine 9
layout: post
---

##Myrianne
J'ai créer et modifier quelque objets pour le bateau. 

![image du coffre en 3D](../medias/coffre_couvert.png)
Le même coffre mais avec une toile faite avec le paramètre tissu

![image du barrie avec couverture en 3D](../medias/barrie_couverture.png)
Le même barrie mais avec une toile faite avec le paramètre tissu

![image du poche en 3D](../medias/poche.png)
Poche faite en 3D sur blender

j'ai fait un banc mais j'ai decider de ne pas le mettre dans le projet 

nous avons réorganiser les tache et j'ai ajoutée les objet a la scène Unity.

![image du poche en 3D](../medias/props_unity.png)
Objet mise sur le bateau.


##Nicolas

Cette semaine, j'ai fait le modèle du bateau du joueur avec son volant ainsi que les boucliers des deux bateaux. J'ai aussi amélioré le modèle des bateaux ennemies et j'ai commencé à faire le modèle des canons. J'ai aussi ajouter des étiquette sur le trello pour bien organisé l'ordre des choses à faire

##Jacob

Cette semaine, j'ai collaboré sur le projet sur le côté de l'organisation. J'ai libelled le trello et j'ai checker sur ce quoi faisait l'équipe et assigné un job. J'ai majoritairement travaillé sur le son durant cette semaine. J'ai fait une tonne de recherche sur des sites avec des sons libre de droit comme Pixabay, freesounds, Upbeat et autres. J'ai remixé 15 sons par moi-même avec Audition. J'ai aussi créer le fichier de Gestionnaire de sons et intégré du code et par la suite, Myrianne et Mathieu se sont occupés de le modifier pour qu'il marche selon des fonctions précises.

##Alex 

Cette semaine, j'ai créer une animation pour notre logo sur After Effect. Je pense qu'elle va bien avec le thème de notre projet. J'ai aussi créer une courte video pour nos réseaux sociaux. Elle présente vite fait l'équipe qui travaille. J'ai passé une grande partie de mon temps à l'animations du logo. La courte video me permettra aussi de l'uttiliser pour des plans dans la vidéo de présentations. 

##Mathieu

Cette semaine, j'ai finalisé le système d'apparition des ennemis ainsi que leur mode de déplacement. Le système est assez flexible et permet de changer facilement le nombre d'ennemis. Il se compose de trois anneaux contenant plusieurs points d'apparition, orbite autour du bateau du joueur.

![image du poche en 3D](../medias/boats_top_view.png)                  
Image des bateaux vue de haut.

Le système fait réapparaître les ennemis après un certain délai après leur destruction et s'auto-détruit dans le cas rare où les bateaux apparaissent l'un par-dessus l'autre.

J'ai également ajusté le système de calibration du monde pour prendre en charge la rotation du bateau du joueur. J'ai rencontré quelques difficultés car je pensais que la rotation ne revenait pas à 0, mais j'avais simplement oublié de remettre l'origine du monde à 0 avant de recommencer la calibration. Il faudra légèrement adapter le code pour prendre en charge un vrai volant, car pour le moment, le bateau est seulement contrôlé avec les touches A et D sur le clavier.

J'ai écrit des fonctions préliminaires pour gérer la vie du joueur et des ennemis, en préparation pour coder le système de visée du joueur avec les canons que Nicolas a terminé de modéliser et de texturer.

J'ai également aider Myrianne à coder le système de son préliminaire, et l'implémenter dans le jeu.
