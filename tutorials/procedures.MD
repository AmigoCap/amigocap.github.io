## Procedures

* Get access to the room
* Enter / leave the room

https://messagerie.ec-lyon.fr/home/romain.vuillemot@ec-lyon.fr/Amigo
Demander à Romain pour être rajouté au calendrier
Quand la salle est occupée, mettre un panneau DO NOT DISTURB si besoin de ne pas être dérangé
Important
Ne pas oublier de rendre la clé
Éteindre après chaque manipulation
Ranger en partant
Signaler si un problème en arrivant, pendant, en partant


## Mocap

La création des masques pour cacher les réflecteurs doit être fait tout les semaines
	Démo
		Allumer les caméras
		Créer les masques des caméras (de 1 a 6), éliminer tous les reflets, éliminer tous les cercles croisés
		Calibration dynamique, les caméras mesurent 2000 fois les points pour être calibrés, on utilise le truc en format de T, les réflecteurs doivent être montré vers les caméras
		Fixer le zéro de référence du système en mettant le T au milieu de la salle
		Acquisition de données, on crée des patients et dedans un ou plusieurs sessions. Dans la nouvelle session on crée un sujet. On va aux outils et on pousse start pour l'acquisition.
			Replier le scotch pour le decoller
			Eviter de mettre les réflecteurs sur les vêtements pour éviter le mouvement
			Eviter la symétrie entre les membres (réflecteurs placés sur les bras) 
			Placer des triangles de réflecteurs
			L'intensité des jaunes indique la non captation d'un des réflecteurs
		Pour créer des marqueurs, on clique sur "Create" dans la section du panneau d'outils Create segment et on clique sur les réflecteurs qu'on veut marquer. On commence par l'origin, ensuite l'axe primaire et après l'axe secondaire et après on clique "Create" à nouveau pour valider.
		L'axe primaire est l'extension du membre et l'axe secondaire est au milieu du membre
		Après on clique sur les boules bleues, ainsi les zones jaunes peuvent disparaître à cause de la géométrie formée
		On va dans l'onglet "Quality" pour remplir les trous dans la trajectoire
		Les différents calculs peuvent être utilisés par le logiciel pour proposer des trajectoires manquants.
		Après dans l'onglet "Data management -> search" on peut sauvegarder les données
	Si on abime les réflecteurs, in y a des outiles pour les mettre dans les bonnes conditions.

	Zoom : clique droit et faire glisser
	Rotation : clique gauche et faire glisser

	Dans le panneau d'outils on peut changer les paramètres on peut récupérer un csv avec la position des marqueurs dans l'espace R3
	On peut exporter les vitesses, les accélérations, etc

	Skeleton
		Mise en place des réflecteurs au corps
		3 réflecteurs par membre
		Bras, avant bras, jambes et mollets gauches et droits, hanche et torse
		Marqueurs créés avec segments
		Plein de trous sur la trajectoire (+360)