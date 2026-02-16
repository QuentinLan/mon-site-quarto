# Un modèle de site web quarto pour le cerema

Ce site est un template pour publier des rapports d'étude au format web.

Le modèle de site est visible sur [https://app-nc.cerema.fr/quarto-website-modele/](https://app-nc.cerema.fr/quarto-website-modele/)

# Comment utiliser ce modèle

Sur le présent lien gitlab [https://gitlab.cerema.fr/normandie-centre/quarto-website-modele](https://gitlab.cerema.fr/normandie-centre/quarto-website-modele), vous avez une bouton `Code` bleu avec menu déroulant qui vous propose télécharger le code source au format zip.

Cliquer sur `Télécharger le zip` puis dézipper le sur votre disque dur, renommer le répertoire avec le nom de votre projet et c'est parti !

# Trucs et astuces

-   Ne **jamais travailler sur box**, box est trop lent pour générer les dizaines de fichiers qui constituent un site web. Travailler en local et mettre en place un projet git pour qu'ils soient sauvegardés (ou sauvegarder votre projet manuellement de temps en temps !).  
-   Deux modèles de "menu" sont disponibles [TODO : expliquer les différences et comment copier coller le modèle qu'on veut dans _quarto.yml].   
-   Pour mettre à jour un ancien site avec les améliorations de styles et de menus [TODO : expliquer les fichiers clefs avec le css, le yaml + le rep js].  
-   Pour la mise en ligne sur le web, contacter un admin du serveur app-nc.cerema.fr. Si besoin, les sites quarto peuvent être hébergés sur des pages github ou le site quarto publish ou simplement déposer sur l'intra ou internet d'un maître d'ouvrage.
-   Projet git + job jenkins = déploiement sur le web en deux clic !  
-   Rendez-vous sur [la documentation officielle de quarto](https://quarto.org/) pour maîtriser toutes les subtilités de quarto !  


# On vous demande des pdf ?

Clic droit + imprimer dans le navigateur puis compiler les pages pdf (avec pdfsam par exemple), cela permet de garder la mémoire du rendu numérique et de le verser sur ceremadoc !