Cloner ce projet en utlisant git et suivre les insctructions ...
Astronomie Blog
Le projet consite a creer un blog d'astronomie avec administration des
articles , le tout en HTML,CSS et PHP
Frontend
Creer une page d'acceuil qui liste les derniers articles d'un blog
nomme Astronomie Blog
Creer une page d'inscription avec un formulaire (nom,prenom,email,mot
de passe,role) , il faut 2 roles admin et redacteur
Creer une page de connexion avec un formulaire (email,mot de passe)
Creer une page pour la creation d'un nouvel article avec un formulaire
(titre de l'article,contenu de l'article)
Anatomie de la page d'acceuil listant les derniers articles
Header
Nom du blog : Astronomie Blog en H1
Menu : 2 liens hypertextes Connexion/Inscription
Contenu de la page
Pour chaque article :
Titre de l'article en H2
Date de creation de l'article suivi de "Ecrit par" le prenom nom de 
l'auteur
Contenu de l'article
Footer
Afficher l'annee en cours suivi de votre prenom (2022 - xxx)
Backend
Base de donnee
Creer une base donnee mysql nomme astronomie
Dans la base de donnee astronomie creer 2 tables
utilisateurs (nom,prenom,email,role,created_at)
articles (titre,article,id_utilisateur,created_at)
Fichier de traitement
Creer les fichiers necessaires pour
la creation d'un nouveau compte
la connexion d'un utilisateur
la creation d'un nouvel article
Fonctionnement du blog
Le blog consiste en une seul page qui liste tous les articles
Lorque un utilisateur est connecte et qu'il a un role d'admin , il arrive sur
une page d'administration ou il peut ajouter,editer,supprimer,mettrà jour
un article
Lorque un utilisateur est connecte et qu'il a un role de redacteur , il peut
que creer un article
Charte graphique
Frontend
Pour les titres utliser la fonte raleway regular 400 et open sans regular 
400 pour le texte des articles
Couleur du texte du blog : #344344
Couleurs des liens hypertextes : #183770
Le blog doit s'adapter à toutes les resolutions d'ecran (responsive)
Backend
Utliser la fonte open sans regular 400 pour la page d'administration des 
articles
Code
Utliser git pour versionner votre projet , creer un depot sur une plateforme au
choix github,gitlab,bitbucket,... afin de montrer votre travail.
Travail avec des branches , develop , feature_xxx
Document
Metter votre schema de base de donne dans un repertoire document
