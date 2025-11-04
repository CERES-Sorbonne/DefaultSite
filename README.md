# Comment créer son site ?

1. Tout d'abord avoir un compte Github.
2. Ensuite créer un fork de ce repository. 
3. Le cloner, changer les fichiers csv et les photos dans scripts/inputs pour correspondre à votre site.
4. Lancer la commande python init_from_csv.py
5. Dans /scripts/resources changer les fichiers désirés:
  a. LogoLabo.png pour le logo qui s'affichera en haut
  b. avatar.webp pour les images par défaut des membres
  c. customisation.jsx pour changer l'introduction sur la page d'accueil ainsi que le footer
  d. icon.svg pour l'icone du site
  e. siteConfig.json pour le titre du site   
7. Add, commit et push vers github. 
8. Renommer le répertoire github <votre_nom_d'utilisateur>.github.io 
9. Aller dans actions, choisir "Mettre le site en ligne", appuyer sur Run
10. Votre site devrait être en ligne sur <votre_nom_d'utilisateur>.github.io 
