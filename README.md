# Projet 4 - La Chouette Agence
La chouette agence est une grande agence de web design basée à Lyon. L’activité de l’entreprise a bien démarré mais aujourd’hui, elle souffre d’une perte de vitesse.

La fondatrice de l’entreprise cherche une solution pour faire repartir l’activité. 

En tapant “Entreprise web design Lyon” sur Internet, elle s’aperçoit que le site de l’agence apparaît seulement en deuxième page des moteurs de recherche.

Elle fait un compte rendu par mail au spécialiste du référencement après la réunion de lancement nommé : ’’Amélioration du référencement ’’.

La fondatrice précise dans son mail de compte rendu que le site n’apparaît pas en deuxième page des moteurs de recherche et souhaite que le référencement soit en conséquence amélioré.

Analyse de l’état actuel de l’accessibilité et du SEO du site initial « La Chouette Agence »

Accessibilité : Pas de titre à côté de la favicon dans index.html et page2.html.

Un point est affiché à la place d’un titre.

Accessibilité : Le menu n’est pas bien nommé. En effet, il est nommé:   « accueil » et « page2> »  dans accueil.html  et  page2.html 

La Page2.html  n’est pas correctement nommé.

Accessibilité : Dans la page d’accueil, les mots importants ne sont pas en gras. La balise <strong> est absente dans les paragraphes.
  
Accessibilité : le formulaire de contact est assez basique et complètement à gauche de page2.html. Mauvaises propriétés et dimensions CSS.

Accessibilité : La toggle navigation est mal placée dans la page2.html. Elle est trop à droite du logo du site « La Chouette Agence »

SEO : le poids des images est trop lourd et n’est pas toujours au bon format. Une image en BMP très lourde (+ de 5 mo), 2 images en BMP avec + de 300 ko, le JPG dépasse 150 ko.

SEO : Pas de titre ni de texte dans la bannière de la page2. La balise titre principal <h1> et <p> sont absentes.
  
SEO : les scripts sont placés entre la balise <head> et </head> dans index.html et page2.html.

En conséquence, le site est plus long à charger car les scripts vont se charger directement impactant la vitesse de chargement de « La Chouette Agence »

SEO : certains scripts dans accueil.html et page2.html n’ont pas besoin d’être utilisés et ralentissent le chargement du site web.

Ces scripts chargent des ressources réduisant les performances d’affichage de « La Chouette Agence ».

SEO : la page2.html n’est pas responsive sur desktop et tablette.

En effet, Accueil et page2 sortent de la fenêtre de la page d’affichage dans accueil.html et page2.html

SEO : Les paragraphes présents dans index.html et page2.html sont assez petits. Cela risque de déplaire à l’utilisateur visitant le site web.

SEO : Peu de balises <meta> (uniquement les meta tags). 1 balises meta charset, 3 balises meta name dont une meta name avec description vide dans les 2 pages du site (index.html et page2.html).

SEO : Absence de CDN dans le code html du site web. Le site ne peut pas gagner en vitesse de chargement.

SEO : Trop de feuilles de styles CSS chargées, 4 au total dans index.html et page2.html. 

Les bonnes pratiques à adopter et les actions recommandées sur l’amélioration de l’accessibilité et du SEO du site optimisé « La Chouette Agence »

Accessibilité : Mettre un titre cohérent, en rapport avec le site. Le titre est nommé : « La Chouette Agence »

Accessibilité : Nommer correctement le menu de navigation (Accueil et page2>) de la façon suivante : (Accueil et Contact) et la deuxième page (page2.html) de la façon suivante : (Contact.html).

Accessibilité : La balise <strong> est inséré dans les paragraphes d’index.html pour montrer les mots importants.
  
Accessibilité : Le formulaire de contact est centré avec les bonnes dimensions dans le CSS, une cache à cocher est présente avec un consentement des données personnelles RGPD.

Accessibilité : Modification de l’emplacement de la toggle navigation dans contact.html de manière à ce qu'elle soit plus présentable. La toggle navigation est représentée dans le menu (accueil et contact) et sont deux boutons dans le menu de contact.html

SEO : Changement du format des photos en BMP pour le JPG, diminution du poids des images en JPG et en PNG pour gagner en vitesse de chargement.

SEO : Insertion d'un titre principal <h1> et d'un paragraphe <p> dans la bannière de la page contact.html
  
SEO : Mettre les scripts à la fin du code pour accélérer le chargement du site, entre <body> et </body> à la fin des blocs <div>. Le site se charge plus rapidement avec l'exécution des scripts sans erreur et placés à la fin des blocs <div> entre les balises <body> et </body> dans Index.html et Contact.html
  
 SEO : Garder les scripts utiles et les placer à la fin du code entre <body> et </body>. Dans index.html et contact.html, garder :   <script src="https://code.jquery.com/jquery-2.2.4.min.js"></script> et  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script> ;
 
SEO : Mettre des media queries au format desktop ou tablette. Les medias queries sont placées à la fin de la feuille de style : « la_chouette_agence_css » pour desktop, tablettes.

SEO : Mettre une taille appropriée pour les paragraphes. La police de texte en font-size:14px.

SEO : Ajout dans l'ordre des balises meta tags + meta robots + meta Facebook et meta Twitter. Cela optimise davantage le référencement du site.

SEO : insertion d’un cdn boostrap et d’un cdn Font Awesome pour le CSS. 2 CDN insérés dans index.html et contact.html, le CDN bootstrap pour la mise en page du site et de Font Awesome pour les îcones.

SEO : Garder au 2 feuilles de styles css pour gagner en vitesse de chargement. Garder : <link rel="stylesheet" type="text/css" href="./css/la_chouette_agence.css"> ; <link rel="stylesheet" type="text/css" href="./css/font-awesome.css">

Le site passe correctement la validation HTML et CSS au W3C (pas d’erreurs ni de warning).


