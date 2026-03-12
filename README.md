Table des matières
1.	Structure générale
2.	Page d'accueil (index.html)
3.	Page À Propos (a_propos.html)
4.	Page Programmes (programmes.html)
5.	Page Admission (admission.html)
6.	Page Galerie (Galerie.html)
7.	Page Contact (contact.html)
8.	Composants communs
9.	Technologies utilisées
________________________________________
Structure générale
Le site web de l'Université de Technologie d'Haïti (UNITECH) est composé de 6 pages principales :
Page	Fichier	Description
Accueil	index.html	Page d'entrée du site
À Propos	a_propos.html	Présentation de l'université
Programmes	programmes.html	Liste des formations
Admission	admission.html	Processus d'admission et formulaire
Galerie	Galerie.html	Photos des événements et campus
Contact	contact.html	Coordonnées et formulaire de contact
Caractéristiques communes à toutes les pages :
•	Même en-tête (header) avec menu de navigation
•	Même pied de page (footer) avec coordonnées
•	Mêmes couleurs et styles (variables CSS)
•	Système de lightbox pour agrandir les images
•	Design responsive (adapté aux mobiles, tablettes et desktop)
________________________________________
Page d'accueil (index.html)
Objectif
Présenter l'université de manière attrayante et donner un aperçu général.
Sections principales
1. Bannière d'accueil
Rôle : Accueillir le visiteur avec un message fort
Contenu :
•	Titre "Bienvenue à l'UNITECH"
•	Phrase d'accroche "L'Université de Technologie d'Haïti forme des professionnels compétents et engagés pour bâtir l'avenir du pays."
Particularité : Fond dégradé bleu et animations
2. Carrousel d'images
Rôle : Montrer des photos du campus de façon dynamique
Contenu : 3 images qui défilent automatiquement :
•	Le Campus en Image
•	Nos Infirmière
•	Le Recteur J. Val
Fonctionnalité :
•	Légendes sur chaque image
•	Boutons de navigation
•	Défilement automatique toutes les 2 secondes
•	Indicateurs de position
3. Section Histoire
Rôle : Raconter la création et la mission de l'université
Contenu :
•	Texte sur la fondation le 8 novembre 2007 à Port-au-Prince
•	Mission de promouvoir un enseignement de qualité
•	Formation de professionnels compétents
4. Section "Pourquoi nous choisir"
Rôle : Mettre en avant les points forts de l'université
Contenu : 4 cartes avec :
•	Formation de qualité : Programmes modernes, professeurs qualifiés
•	Programmes variés : Administration, génie, éducation, santé, agronomie
•	Approche pratique : Théorie et pratique pour le marché du travail
•	Développement du pays : Former des professionnels pour Haïti
Particularité : Fond dégradé bleu, effet de survol avec agrandissement
5. Section Statistiques
Rôle : Donner des chiffres clés de façon visuelle
Contenu : 4 statistiques avec compteurs animés :
•	3000+ étudiants
•	10 facultés
•	100+ professeurs
•	500+ diplômés par an
Fonctionnalité : Les chiffres augmentent progressivement au chargement de la page
________________________________________
Page À Propos (a_propos.html)
Objectif
Présenter l'histoire, la mission et l'équipe de l'université.
Sections principales
1. Bannière
Contenu :
•	Titre "À Propos de l'UNITECH"
•	Description "Découvrez l'histoire, la mission et les valeurs de notre institution"
2. Section Histoire (avec Flexbox)
Rôle : Raconter en détail la création de l'université
Mise en page : Texte à gauche, image à droite (Flexbox)
Contenu texte :
•	Fondation le 8 novembre 2007
•	Vision d'un groupe d'intellectuels haïtiens
•	Évolution et adaptation aux besoins du marché
•	Valeurs d'excellence, d'intégrité et d'engagement social
Image : Photo du campus principal avec légende, cliquable pour agrandir
3. Section Mission, Vision, Valeurs (avec Flexbox)
Rôle : Présenter les fondements de l'institution
Mission :
•	Former des professionnels compétents, innovants et engagés
•	Contribuer au développement durable d'Haïti
•	Promouvoir la recherche et l'innovation
Vision :
•	Devenir une référence régionale
•	Excellence des programmes
•	Impact des diplômés sur la société
Valeurs :
•	Excellence académique
•	Innovation
•	Intégrité
•	Engagement social
•	Esprit d'équipe
4. Section Équipe Administrative (avec Flexbox)
Rôle : Présenter les dirigeants de l'université avec Cartes, photos, noms et titres :
Fonctionnalité : Photos cliquables pour agrandir
5. Section Campus (avec Flexbox)
Rôle : Montrer les différents Annexe de l'université
Contenu : Photos avec adresses :
•	Campus Avenue N - 60, Avenue N
•	Campus des Cayes - 171, Boulevard des 4 Chemins, Cayes
•	Campus de Carrefour - 25, Côtes Plage 16
•	Campus de Hinche - 92, Rue Charlemagne Péralte
Fonctionnalité : Photos cliquables pour agrandir, icônes de localisation
________________________________________
Page Programmes (programmes.html)
Objectif
Présenter tous les programmes de formation offerts.
Sections principales
1. Bannière
Contenu :
•	Titre "Nos Differents Programmes"
•	Description "Découvrir Nos Differents Programmes en Licences 4, 5ans et en Diplome 2ans"
2. Programmes de Licence (4-5 ans)
Rôle : Lister les formations de longue durée
Mise en page : Grille de 3 cartes par ligne
Programmes présentés :
Les different programme :
•	Sciences Informatique - Projets innovants, programmation
•	Sciences Administratives - Leadership, stratégie
•	Sciences de l'Agriculture - Agriculture durable, innovations rurales
•	Diplomatie - Politiques étrangères, résolution des conflits
•	Génie civil - Bâtiments, routes, solutions durables
•	Sciences Juridiques - Politiques publiques, législation
•	Sciences Infirmière - Soins infirmiers, professionnalisme
•	Architecture - Conception de bâtiments
•	Mécanique - Solutions durables
Contenu par carte :
•	Image représentative
•	Titre du programme
•	Description courte
•	Bouton "Inscrire" qui redirige vers le formulaire d'admission
Fonctionnalité : Images cliquables pour agrandir
3. Programmes Diplôme (2 ans)
Rôle : Présenter les formations courtes
Mise en page : 2 cartes par ligne
Programmes :
•	Réseau - Infrastructure réseau, protocoles, technologies connectées
•	Pharmacologie Médicale - Études des médicaments, pratiques cliniques
Contenu : Image, titre, description, bouton "Inscrire"
________________________________________
Page Admission (admission.html)
Objectif
Expliquer le processus d'admission et fournir un formulaire.
Sections principales
1. Paragraphes d'introduction (2 colonnes)
Rôle : Accueillir et informer les candidats
•	Processus simple et rapide
•	Vision de former des bâtisseurs et innovateurs
•	Cadre d'apprentissage moderne
•	Processus transparent et accessible
•	Invitation à déposer sa candidature
2. Étapes d'admission (grille 2x2)
Rôle : Guider le candidat pas à pas
Étape 1 : Identifier la faculté adaptée à vos ressources
Étape 2 : Terminer les études classiques
Étape 3 : Avoir tous les documents demandés
Étape 4 : Être prêt à obtenir les notes demandées
3. Formulaire d'admission
Rôle : Recueillir les informations des candidats
Champs du formulaire :
Champ	Type	Requis
Nom	Texte	Oui
Prénom	Texte	Oui
Email	Email	Oui
Téléphone	Téléphone	Oui
Faculté	Liste déroulante	Oui
Date de naissance	Date	Oui
Certificat	Fichier	Oui
Photo d'identité	Fichier	Oui
Message	Zone de texte	Non
Boutons :
•	ANNULER - Efface tous les champs
•	VALIDER VOTRE INSCRIPTION - Soumet le formulaire
Message de remerciement : "Merci de votre intérêt pour l'UNITECH !"
Validation HTML5 : Format email, format téléphone, champs requis
________________________________________
Page Galerie (Galerie.html)
Objectif
Exposer les photos des événements et de la vie universitaire.
Sections principales
1. Bannière
Contenu :
•	Titre "Galerie"
•	Phrase d'invitation "Nous vous invitons à découvrir la beauté de nos campus. Regardez nos belles photos."
2. Grille de photos (16 images)
Rôle : Afficher toutes les photos de façon organisée
Mise en page responsive :
•	Desktop : 4 colonnes
•	Tablette : 3 colonnes
•	Mobile : 2 colonnes
•	Petit mobile : 1 colonne
Liste des photos avec légendes :
Image	Légende
Unitech1.jpg	le Campuc principal
1.jpg	Le Courloir Du Campuc Principal
2.jpg	La bénédiction d'un curé pendant la remise des diplômes
3.jpg	Un moment de danse
4.jpg	Deux Icônes Du Pays lors d'une remise des diplômes
5.jpg	La major de la promotion génie 2017-2022
7.jpg	Un étudiant à la guitare
8.jpg	La remise du tableau d'honneur avec le major agronomie
9.jpg	Les étudiants célèbrent leur succès
10.jpg	Les majors de la promotion agronomie
12.jpg	Les stages des infirmiers
13.jpg	Conférence-débat
14.jpg	Prof Hancy PIERRE
15.jpg	Conférence-débat
16.jpg	M. Benoit
16.jpg	Les étudiants pendant un match de basket
3. Système de lightbox avec navigation
Rôle : Afficher les images en grand quand on clique dessus
Fonctionnalités :
•	Fond sombre pour mettre l'image en valeur
•	Bouton de fermeture (×) en haut à droite
•	Flèches de navigation (précédent/suivant) sur les côtés
•	Navigation circulaire (de la dernière à la première)
•	Indicateur de position (ex: "1/16", "2/16", etc.)
•	Animations d'ouverture (zoom et fondu)
Technique : Utilisation des ancres CSS avec :target 
________________________________________
Page Contact (contact.html)
Objectif
Permettre aux visiteurs de contacter l'université.
Sections principales
1. Bannière
Contenu :
•	Titre "Contactez-nous"
•	Description "Nous sommes là pour répondre à toutes vos questions"
2. Coordonnées complètes (4 cartes)
Rôle : Fournir toutes les informations de contact
3. Cartes avec iframes (4 rectangles)
Rôle : Montrer l'emplacement des campus sur Google Maps
Détails des iframes :
•	Iframe 1 : Campus de Pétion-Ville (123 Rte de Freres)
•	Iframe 2 : Campus des Cayes (171, Bd des 4 Chemins)
•	Iframe 3 : Bureau d'Accueil - Port-au-Prince (45 Rue du Centre)
•	Iframe 4 : Bureau d'Information - Delmas (89 Boulevard Toussaint)
Fonctionnalité : Iframes responsives (s'adaptent à la taille de l'écran)
4. Formulaire de contact
Rôle : Permettre d'envoyer un message Rapide
Boutons :
•	Envoyer le message - Soumet le formulaire
•	Effacer - Réinitialise tous les champs
Validation HTML5 :
•	Champs requis vérifiés
•	Format email validé
•	Format téléphone avec pattern
________________________________________
Composants communs
Header (En-tête)
Rôle : Navigation principale sur toutes les pages
Structure :
•	Logo : Image cliquable qui ramène à la page d'accueil
•	Menu de navigation : Liens vers les 6 pages
o	Accueil
o	À Propos
o	Programmes
o	Admission
o	Galerie
o	Contact
•	Menu mobile : Icône "☰" qui affiche le menu en version mobile
Fonctionnalités :
•	Position fixe en haut de la page (toujours visible)
•	Effet de survol sur les liens (fond jaune)
•	Responsive : menu en ligne sur desktop, menu déroulant sur mobile
Footer (Pied de page)
Rôle : Informations complémentaires sur toutes les pages
•	Description et Slogan 
Liens rapides :
•	Université (Accueil)
•	Facultés (Programmes)
•	Admission
•	Contact
•	Galerie
Contact :
•	Adresse complète
•	Email
•	Téléphone
•	Heures d'ouverture
Copyright : "© 2026 Université de Technologie d'Haïti (UNITECH). Tous droits réservés."
Lightbox (Agrandissement d'images)
Rôle : Afficher les images en grand sur toutes les pages
Fonctionnement :
1.	L'utilisateur clique sur une image
2.	Une fenêtre modale s'ouvre avec l'image agrandie
3.	Fond sombre pour focus sur l'image
4.	Bouton de fermeture (×) en haut à droite
5.	Flèches de navigation (précédent/suivant) sur les côtés
6.	Navigation circulaire (de la dernière à la première)
7.	Indicateur de position (ex: "1/16")
8.	Animation d'ouverture (zoom et fondu)
Technique : Utilisation des ancres CSS avec la pseudo-classe :target (sans JavaScript)
Avantages :
•	Léger et rapide
•	Fonctionne sans JavaScript
•	Compatible avec tous les navigateurs
Variables CSS communes
css
:root {
    --primary-color: #003366;    /* Bleu principal */
    --secondary-color: #ffd700;   /* Or */
    --accent-color: #c41e3a;      /* Rouge */
    --text-dark: #333;
    --text-light: #666;
    --white: #fff;
    --bg-light: #f8f9fa;
    --shadow: 0 4px 6px rgba(0,0,0,0.1);
    --transition: all 0.3s ease;
}
Utilisation :
•	--primary-color : Fond du header, footer, boutons
•	--secondary-color : Accents, survols, bordures
•	--accent-color : Chiffres des statistiques
•	--shadow : Ombres pour les cartes
•	--transition : Animations au survol
________________________________________
Technologies utilisées
Langages
Technologie	Utilisation
HTML5	Structure de toutes les pages
CSS3	Styles, animations, mise en page
JavaScript	Menu mobile, compteurs animés
Frameworks et bibliothèques
Outil	Version	Utilisation
Bootstrap 5	5.x	Carrousel, grilles, composants responsives
Font Awesome	6.5.0	Icônes (email, téléphone, localisation, navigation)
Concepts techniques
Concept	Utilisation
Flexbox	Mise en page des sections (À Propos, Programmes)
CSS Grid	Grilles de cartes et galerie d'images
Media Queries	Design responsive (3 breakpoints)
Pseudo-classes	:target pour la lightbox sans JavaScript
Animations CSS	FadeIn, zoomIn, transitions au survol
Validation HTML5	Formulaires avec required et pattern

