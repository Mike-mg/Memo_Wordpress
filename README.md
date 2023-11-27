# Memo_Wordpress
 
## ***__Installer et configurer WordPress sur son serveur : Hello world__***

- ***Contexte***  

    - Il existe deux modes d’utilisation du CMS :  

        - Le mode local  

            - WordPress peut etre installer sur un serveur local pour les 3 systèmes suivants :  
    
                - Mac OS  
                
                - Windows  
                
                - Linux  

            - On peut diviser la procédure en 2 étapes : 
        
                - Il va falloir installer le logiciel LocalWP sur votre ordinateur pour de créer un serveur local
                
                - Puis a l’intérieur, installer un nouveau site WordPress
        
        - Le mode en ligne  

    - On peut diviser la procédure en 2 étapes :  
        
        - Il va falloir installer le logiciel LocalWP sur votre ordinateur pour de créer un serveur local  
        
        - Puis a l’intérieur, installer un nouveau site WordPress  

- ### ***Installation et lancement d’un serveur local***  

  - #### ***Installation et lancement d’un serveur local***  

    - ***LocalWP***  
      
      - Afin d’installer le logiciel LocalWP nous allons télécharger la dernière version avec le lien ci-dessous :  

        - [***LocalWP***](https://localwp.com/)  

            - Installer le logiciel en fonction de l'OS choisi.  

- ### ***Installation de WordPress***  

  - #### ***Installation de WordPress***  

    - Dans l’interface principal de LocalWP, cliquez sur ***« Create a new site »*** pour créer votre premier site.  

    - L’écran suivant vous propose de créer un nouveau site, cliquez simplement sur ***« Continue »***.  

    - Entrez ensuite le nom de votre choix pour votre nouveau site puis cliquez simplement sur ***« Continue »***.  

    -  Choisir votre environnement de développement, rester sur le paramètre par défaut « Preferred », puis cliquez sur ***« Continue »***.  

    - Entrer un ***nom d’utilisateur*** WordPress et ***un mot de passe*** et ***un email*** qui sera associé à au compte.  

    - Cliquez sur ***« Add Site »*** pour lancer le processus automatisé d’installation de WordPress.  

    - ***Accéder au site WordPress***  

      - Pour accéder à votre administration WordPress c’est très simple, cliquer sur le bouton ***« WP Admin »***.  

        - Entrez ***les logins*** que vous avez précédemment configurés lors de l’installation du site dans LocalWP puis cliquez ***« Log In »***.  

      - Pour acceder au site directement, cliquez sur ***« Open site »***.  

    - ***Gestion des comptes***  

      - En se connectant au compte administrateur, se rendez dans l’onglet « Comptes » de l'interface.  

      - Il sera possible de gérer :

        - Les identifiants

        - Les rôles (administrateur, contributeur, éditeur, etc.)  

        -  Les mots de passe, etc.

    - ***Migration d’un site***  

      - Pour exporter le site local pour le mettre en ligne  

        - Une extension existe, il s’agit de ***All-In-One-WP-Migration*** par ServMask.

        - Il faut simplement la rechercher en accédant à la bibliothèque des extensions depuis l’interface d’administration dans l’onglet ***« Extensions »*** puis en cliquant sur ***« Ajouter »***.  
      
        - Ensuite vous pourrez exporter votre site dans un fichier spécifique.  

        - Depuis l’interface d’administration de WordPress sur votre serveur en ligne, vous pourrez installer cette extension et importer le fichier en question.  

 
##
## ***__L'administration de son site WordPress__***

- ### ***Présentation de l’interface de l’administration***

  - #### ***Présentation de l’interface de l’administration***

    - ***Qu’est-ce que l’espace d’administration de WordPress ?***
      
        - L’espace d’administration de WordPress est un espace qui vous permet de gérer votre site.  

        - En termes professionnels, on appelle cela le ***back-office***. Ceui-ci est la partie d’un site internet accessible uniquement par l’administrateur.

    - ***Comment se connecter à son tableau d’administration de WordPress ?***  

        - Pour se connecter au tableau de bord de WordPress, il faut aller sur le nom de domaine de son site et ajouter « wp-admin ». Par exemple, ***« monsite/wp-admin »***.

    - ***Comment récupérer son mot de passe en mode local ?***  

        - Avec LocalWP, vous avez la possibilité de récupérer un mot de passe oublié sur votre site local.  

        - Sur l’écran de connexion cliquez sur ***« Mot de passe oublié ? »***, entrez votre identifiant, puis cliquez sur le bouton ***« Générer un mot de passe »***.  

        - Puis rendez-vous dans l’encart de votre site et cliquez sur l’onglet ***« Tools »***.  

        - Cliquez sur ***« Open MailHog »*** en vert, une nouvelle fenêtre s’ouvre dans votre navigateur avec le service MailHog.  

        - Cliquer sur le mail que vous voyez, puis sur le lien présent à l’intérieur afin d’ouvrir une nouvelle fenêtre WordPress vous invitant à réinitialiser votre mot de passe.

    - ***Présentation générale des écrans d’administration***  

        - Chaque écran d’administration est présenté en quatre sections comm suit :

            - La barre d’outils  

            - Le menu de navigation principal  

            - L’espace de travail  

            - Le pied de page  

                - Image ci-dessous :

                    ![image](/pictures/administr-son-site-wordpr.png)

    - ***La barre d’information (haut de page)***  

        - En haut de la barre de menu à gauche, on trouve le logo WordPress, qui renvoie vers le site officiel de WordPress.  

        - vous avez une icône de maison avec le titre du site.  

        - Lorsque vous cliquez dessus, vous arrivez sur votre site tel qu’il est vu par vos visiteurs.  

        - le rond avec les doubles flèches vous indique s’il y a des mises à jour à faire.  

        -  l’icône dialogue vous indique s’il y a des commentaires en attente de modération et le signe « + » est un raccourci pour créer des articles ou des pages.  

        - À droite, vous avez les informations sur votre compte. Au-dessous, vous pouvez définir les options de l’écran, c’est-à-dire ce que vous voulez qui s’affiche sur votre tableau de bord.  

    - ***Onglet « Tableau de bord »***  

        - L’onglet « Tableau de bord » de WordPress permet en un coup d’œil de savoir si on a des soucis sur le site.  

        - Dans la première colonne, on voit les infos sur les plugins.  
      
        - Dans la deuxième, on voit l’onglet ***« Brouillon rapide »***. Cet onglet permet de noter des idées sur ce que l’on veut faire sur le site.  
      
        - Au-dessous, l’onglet ***« Événements et nouveautés WordPress »*** permet de visualiser les actualités du CMS, notamment sur les dernières mises à jour avec un guide des changements techniques.  
      
        - L’onglet « Glisser les blocs ici » vous permet de réorganiser vos blocs comme vous le souhaitez pour plus de visibilité.  

        - Dans l’onglet ***« Tableau de bord »***, vous trouvez également l’onglet ***« Mises à jour »***.

            - Image ci-dessous :  

                ![image](/pictures/administr-son-site-tab_de_bord.png)


    - ***Onglet Articles***  

        - L’onglet Articles est composé des sous-onglets :  

            - « Tous les articles »  

                - Grâce à l’onglet ***« Tous les articles »***, vous pourrez visualiser les articles publiés sur votre blog. Les actions groupées permettent de modifier les articles ou de les supprimer.  

            - « Ajouter »  

                - L’onglet ***« Ajouter »*** sert à aller directement sur l’éditeur de texte pour écrire votre article.  

            - « Catégories »  

                - L’onglet ***« Catégories »*** donne accès à l’ajout des catégories sur votre blog. Cela permet de hiérarchiser vos articles par thème.  

            - « Étiquettes »  

                - L’onglet ***« Étiquettes »***, vous pourrez trier les articles de manière plus fine. Chaque étiquette est indépendante l’une de l’autre, cet onglet est aussi appelé ***tag***.  

    - ***Onglet Médias***  

        - Dans l’onglet ***« Médias »***, vous pourrez ajouter des images dans votre site WordPress.  

            - Le sous-onglet « Médiathèque » vous permet de visualiser d’un seul coup d’œil les images téléchargées et de supprimer celles que vous n’utilisez pas.  

    - ***Onglet Pages***  

        - L’onglet ***« Pages »*** permet de publier les pages de votre site web, c’est-à-dire les sujets principaux et génériques de votre blog, comme les pages « Contact » et « À propos ». Pour ajouter des pages, c’est le même processus que pour les articles.  

    - ***Commentaires***  

        - Dans l’onglet ***« Commentaires »***, vous retrouverez les commentaires qui ont été postés sous votre blog. C’est ici que vous pouvez les approuver ou les supprimer.  

    - ***Onglet Apparence***  

        - Grâce à l’onglet « Apparence », vous pourrez gérer le design de votre site. L’onglet « Thèmes » vous permet de visualiser le thème actif sur votre site, d’ajouter un thème parmi les catalogues WordPress ou de téléverser un thème que vous auriez acheté sur une autre plate-forme.  

    - ***Qu’est-ce qu’un thème enfant ?***  

        - Un thème enfant est un thème rattaché à votre thème principal, appelé thème parent.  

        - Il hérite de toutes les fonctionnalités, du design et des mises en page du thème parent et peut être personnalisé sans toucher à ce dernier.  

    - ***Pied de page***
        
        - Le pied de page de l’administration WordPress regroupe des informations générales.

- ### ***Comment utiliser les différents outils de l’administration ?***

  - #### ***Comment utiliser les différents outils de l’administration ?***

    - ***Comment puis-je utiliser l’onglet « Apparence » → « Thèmes » pour le visuel de mon site ?***

        - Lorsqu’on arrive sur « Apparence » → « Thème » et que l’on clique sur « Ajouter », on arrive sur un catalogue gratuit de thèmes.  

        - Il y a différents outils pour vous aider dans votre recherche. Vous pouvez trier par les thèmes les plus populaires, les derniers publiés ou faire une recherche plus personnalisée.  

        - Ce filtre trie les thèmes suivant le type de votre site, les fonctionnalités que vous voulez et son style. Selon vos critères, vous aurez un choix de thèmes. Mais, si aucun ne vous convient, vous avez aussi des catalogues payants.  
        
        - Si vous voulez rajouter un logo dans votre thème, il faut aller dans ***« Apparence »*** > ***« Personnaliser »*** > ***« Identité du site »*** > ***« Logo »***, si votre thème le permet.  
        
    - ***Comment mettre en place le menu de mon site web ?***  

        - Dans la partie ***« Ajouter des éléments de menu »***, il y a un onglet ***« Pages »***. Il est suivi de ***« Articles »***, et ***« Liens personnalisés »***. L’onglet ***« Structure de menu »*** permet justement d’ajouter les éléments que l’on veut par choix. On coche la page voulue et on clique sur le bouton ***« Ajouter au menu »***. Pour proposer une sous-navigation, il suffit de mettre l’élément sous la page voulue.  
        
    - ***Comment gérer les commentaires ?***

        - Se rendre dans ***« Options de l’écran »***, et cochez l’option ***« Commentaires »***.
        
        - Pour gérer les commentaires, rendez-vous dans ***« Commentaires »*** dans la barre latérale de l’administration de WordPress.  

        - Un commentaire peut prendre quatre états :  

            - Des commentaires en attente : ce sont les commentaires qui n’ont pas été validés et qui ne sont pas visibles sur votre site.  

            - Des commentaires approuvés : ce sont les commentaires approuvés et visibles sur le site.  

            - Des commentaires indésirables : ce sont des « spams », des commentaires envoyés par des robots, ou des propositions commerciales non sollicités.  

            - Des commentaires mis à la corbeille : ce sont les commentaires que vous avez supprimés. Ils ne sont donc pas visibles sur votre site. Mais si vous voulez, vous pouvez les rétablir.  

    - ***Est-il possible de personnaliser le pied de page de l’administration de WordPress ?***

        - Pour le personnaliser, rendez-vous dans le fichier « function.php » de votre thème enfant.  

            - Ajoutez-y à présent les lignes de code suivantes : 

                ```PHP
                function wpc_remove_footer_admin () {
                    $title = get_option('blogname');
                    $slogan = get_option('blogdescription');
                    echo '© ' . date('Y’) . ' ' . $title . ' - ' . $slogan;
                }
                
                add_filter('admin_footer_text', 'wpc_remove_footer_admin');                
                ```
 
##  
## ***__Les paramètres d'un site Wordpress__***  

- ### ***Comment se présente l’espace d’administration des accès sur WordPress ?***  

    - #### ***Présentation du tableau de bord WordPress***  

        - ***Le Dashboard***

            - La gestion de votre site WordPress se réalise depuis le Dashboard, le tableau d’administration est structuré en quatre différentes parties qui sont :  

                - L’en-tête, appelé la barre d’outils  

                - Le menu de navigation principal  

                - L’espace de travail  

                - Le pied de page  

        - ***La barre d’outils***

            - La barre d’outils est composée de liens vers diverses fonctions d’administration et se trouve en haut de chaque écran d’administration.  
            
                - Certains éléments de cette barre affichent un menu déroulant lorsque vous les survolez.  

        - ***Le menu de navigation principal***

            - Toute fonction administrative que vous pouvez effectuer est détaillée par le menu de navigation principal. Un sous-menu apparaît lorsque vous survolez un élément dans le menu. Ce sous-menu est totalement développé lorsque vous cliquez sur un élément.

            - le menu de navigation est constitué des éléments suivants :  
            
                - Tableau de bord (Dashboard)  
                
                - Accueil  
                
                - Articles  
                
                - Média  
                
                - Pages  
                
                - Commentaires  
                
                - Apparence  
                
                -  Extensions  
                
                - Utilisateurs  
                
                - Outils  
                
                - Réglages  
                
                    - En bas de la section se trouve un bouton Réduire le menu.  

        - ***L’espace de travail***

            - Dans l’espace de travail sont présentées les informations spécifiques relatives à un choix de navigation particulier. Par exemple, l’ajout d’un nouveau compte utilisateur.

        - ***Pieds de page***

            - En bas de chaque écran d’administration, le pied de page propose un lien vers wordpress.org tout en vous remerciant d’utiliser WordPress et affiche à droite la version de WordPress installée.

    - #### ***Comment se présente l’espace d’administration des accès ?***  

        - WordPress vous offre la possibilité de gérer les droits et permissions des utilisateurs de votre site grâce à son système de « rôles ».

        - En accédant au menu ***« Comptes »*** de la section menu principal, nous avons trois éléments qui s’affichent avec lesquels vous pouvez gerer :  
        
            - ***Tous les comptes***  

                - Modifier  
                
                - Supprimer  

                - Ajouter de nouveaux utilisateurs  
                
                - Changer le rôle  
                
                - Modifier en lot  
            
            - ***Ajouter nouveau***  

                - Saisir les différents champs d’informations de profil correspondant à chaque utilisateur, puis cliquer sur ***Ajouter un utilisateur***.
            
            - ***Profil***  

                - Affiche les informations de votre profil (autrement dit du compte actuellement connecté).

                - Vous pouvez modifier ces informations dans cet écran à tout moment. 
                    
                    - Ces informations varient selon le rôle associé à votre compte.

                    - Vous avez également accès à des options comme l’affichage de la barre d’outils, le choix des couleurs du tableau de bord, la langue, etc.

- ### ***Présentation du type de compte pour la collaboration sur Wordpress***  

    - #### ***Rôles utilisateurs sur Wordpress***  

        -  Il existe cinq rôles par défaut : Administrateur, Éditeur, Auteur, Contributeur et Abonné.  

            - Chacun de ces rôles dispose d’un certain nombre de tâches prédéfinies encore appelées ***« capacités »***

        - ***Le rôle Administrateur***  

            - le rôle Administrateur peut absolument tout faire.  

                - Pour une installation avec Wordpress multi sites, le rôle « Super Administrateur » est disponible. Ce rôle peut administrer tous les sites alors que l’administrateur ne peut gérer qu’un seul site Web.

        - ***Le rôle Éditeur***  

            - Un éditeur peut :  
            
                - Ecrire  
                
                - Editer  
                
                - Publier  
                
                - Supprimer des articles  

                - Gérer les commentaires  
                
                - Les catégories
                
                - Les tags
                
                - Les liens  

                    - Même ceux déjà publiés et ceux créés par d’autres utilisateurs (n’importe quel utilisateur). Il a par ailleurs accès à des pages et des articles privés.

        - ***Le rôle Auteur***  

            - Il peut : 
            
                - Ecrire  
                
                - Editer  
                
                - Publier
                
                - Supprimer ses propres articles  

                - Télécharger des fichiers
                
                - Gérer les commentaires en lien avec ses articles  

        - ***Le rôle Contributeur***  

            - Il permet d’écrire un article sur le site et de le supprimer, mais il ne lui permet pas de publier ou de modifier l’article.  

            -  le contributeur ne peut pas ajouter d’images à l’article qu’il a écrit. Il faut un éditeur ou l’administrateur du site même pour modifier l’article afin d’intégrer l’image.  

            -

        - ***Le rôle Abonné***  

            - C’est le rôle avec le moins de permissions.  
            
            - Il s’agit du rôle par défaut de tout nouveau compte sur Wordpress.  
            
            - L’abonné peut créer et gérer son profil sur le site Web Wordpress, mais il n’est pas en mesure d’écrire ou de publier des articles.  
            
            - Comparé à un visiteur non inscrit du site, l’abonné possède le seul avantage de pouvoir commenter les articles.  

        - ***Tableau Recapitulatif des roles et permissions***

            ![image](/pictures/actions_roles.png)

    - #### ***Créer et modifier des rôles sur Wordpress***  

        - Pour certains projets, les cinq rôles de base ne sont pas suffisants.  

        - Il est possible de créer sur Wordpress de nouveaux rôles à l’aide d’une extension comme par exemple :

            - ***User Role Editor***  

                - Installer et activer l’extension :  

                    - Accéder à la bibliothèque des extensions.  
                    
                        - ***« Extensions »*** puis ***« Ajouter »***

                        - Rechercher l’extension ***« User Role Editor »***  

                        - Ensuite, il faut cliquer sur ***Installer*** puis sur ***Activer*** pour utiliser cette extension

                - Quelques configurations sont nécessaires avant l’utilisation de cette extension.  

                    - Aller dans l'onglet :  

                        - ***Réglages*** puis ***User Role Editor***

                    - Il faut cocher les cases suivantes :  

                        - ***« Afficher les permissions dans une forme lisible par l’homme »***.  

                        - ***« Confirmer la mise à jour du rôle »*** 

                        - ***« Modifier les permissions de l’utilisateur »*** 

                            - Vous pouvez, comme vous le voulez, changer le nombre de colonnes pour l’affichage des permissions.  
                            
                    - Enfin, Enregistrer les modifications.  

                    - Après ces réglages, suivez le chemin ***Utilisateurs*** puis ***User Role Editor*** du menu Wordpress. Vous pouvez ajouter ou supprimer les permissions du rôle que vous aurez sélectionné. Après vos modifications, cliquez sur le bouton ***« Mettre à jour »*** pour confirmer.  

                - En plus de la modification des droits des rôles existants, vous pouvez aussi :  

                    -  Créer de nouveaux rôles avec le bouton ***« Ajouter un rôle »*** sous le bouton ***« Mettre à jour »***.  

                        - Deux informations sont nécessaires pour la création d’un nouveau rôle :  

                            - Le nom du rôle  
                            
                            - Son identifiant  

                                - Il est possible de copier les privilèges d’un rôle existant pour l’ajouter à un nouveau rôle. Une fois terminé, appuyer sur ***« Ajouter un rôle pour créer un nouveau rôle »***.  

                        - Pour ajouter des permissions à ce nouveau rôle, il faut le mettre à jour. On peut ajouter des permissions au rôle dans la liste des droits du site. Il ne faut pas oublier de cliquer sur le bouton ***« Mettre à jour »***.  

    - #### ***Comment ajouter des utilisateurs sur Wordpress ?***  

        - Se rendre dans le menu ***Comptes*** puis ***Ajouter***.  

        - Un accès au formulaire de création d’un nouvel utilisateur s'affiche et plusieurs champs (***ceux entre parentheses sont obligatoires***) sont disponibles : 

            - Identifiant  

                - L’information renseignée dans ce champ sera utilisée par l’utilisateur pour se connecter au site.

                    - Tres important, ***Choisir un identifiant securisé***

                        - ***Il n’y a plus de possibilité de modifier l’identifiant après l’avoir ajouté. Il faut alors bien le choisir.***
            
            - Adresse de messagerie  

                - Le champ Adresse de messagerie est, lui aussi, ***obligatoire***. Il sert, comme son nom l’indique, à renseigner l’adresse mail de l’utilisateur.
            
            - Prénom et nom  

                - Les champs Prénom et Nom sont quant à eux ***facultatifs***. Ils permettent de mettre respectivement le prénom et le nom de l’utilisateur.
            
            - Site web  

                - Si l'utilisateur a un site web, il peut etre mentionner ici.  
            
            - Mot de passe  

                - Le champ mot de passe n’est pas un champ à renseigner.  
                
                - C’est un générateur de mot de passe qui vous crée un mot de passe complexe automatiquement.  
                
                - Vous avez quand même le choix d’indiquer un autre mot de passe.  
                
                - Pour des questions de sécurité de votre site, utilisez des identifiants et des mots de passe un peu complexes.  
            
            - Envoyer une notification à l’utilisateur  

                - Le champ Envoyer une notification à l’utilisateur est une case à cocher.  
                
                - Il permet lorsqu’on le coche d’envoyer un mail à l’utilisateur. Ce mail lui donne son identifiant et lui demande de donner un nouveau mot de passe. 

                - Lorsque vous créez un éditeur par exemple, ce dernier doit choisir son propre mot de passe. En cochant la case Envoyer une notification à l’utilisateur, vous donnez au nouvel éditeur la possibilité de choisir son propre mot de passe.
            
            - Le Rôle  

                - le champ Rôle est un menu déroulant situé à la fin du formulaire. Il permet de choisir le rôle de l’utilisateur qu’on crée.

        - Après ça, il ne vous reste qu’à cliquer sur Ajouter un utilisateur pour terminer la procédure.

    - #### ***Gestion des utilisateurs sur Wordpress***  

        - Lorsque vous survolez le nom d’un utilisateur, des liens apparaissent :  

            - Modifier  

                - Modifier permet d’éditer le profil de cet utilisateur.  
            
            - Supprimer  

                - Supprimer permet de supprimer l’utilisateur. Mais l’option supprimer n'apparaît pas lorsque vous survolez votre compte.
            
            - Afficher  

                - Le lien Afficher ouvre une page qui présente les articles publiés par l’utilisateur.  

 
##
## ***__Les solutions de paiement en ligne__***  

- ### ***Introduction : pourquoi utiliser des solutions de paiement en ligne ?***  

    - #### ***Présentation des sites de e-commerce***  

        - ***Mise en contexte***

            - Il existe différents formats de site e-commerce. Ceux-ci peuvent être réalisés avec différentes technologies comme :  

                - WordPress  
                
                - Prestashop  
            
            - Pour tous les sites e-commerce, le but est d’amener l’utilisateur à procéder à l’acte d’achat. L’acte d’achat est l’acte final qui clôture son parcours utilisateur. Il procède aux actions suivantes pour y arriver :  

                - Consultation des fiches produits  

                - Mise au panier du produit qui l’intéresse  

                - Renseignement de ses données de facturation  

                - Paiement  

        - ***Qu’est-ce qu’un site e-commerce ?***  

            - Selon le dictionnaire Larousse, le site e-commerce se traduirait exactement par « commerce électronique ».  
            
            - Sa définition est la suivante, c’est un « mode de distribution de produits et de services par l’intermédiaire du site Web des entreprises. (On dit aussi commerce en ligne ou vente en ligne.) »
            
        - ***Le paiement sur les sites e-commerce*** 
            
            - Le paiement sur un site e-commerce est un objectif bien précis et commun à l’ensemble de ces sites.  
            
            - Il est donc primordial que le système de paiement en ligne soit opérationnel, le plus fluide possible et qu’il puisse proposer différents modes de paiement.  

    - #### ***Solutions de paiement en ligne***  
        
        - ***L’importance des solutions de paiement en ligne dans la stratégie d’un site e-commerce***  

            - Comme pour tout projet web, la stratégie d’un site e-commerce doit se travailler en amont et la conception doit se faire de manière minutieuse.  

            - Un site e-commerce doit donc absolument avoir une solution de paiement en ligne fonctionnelle et rassurante.  

            - Ces solutions dont nous allons parler sont non seulement conçues pour faciliter le processus de paiement, mais également pour respecter les normes légales strictes de protection des données personnelles, comme le RGPD dans l’Union européenne.  

        - ***Listing des différentes solutions de paiement en ligne***  

            - Une liste non exhaustive des solutions de paiement en ligne :  

                - PayPal  

                - Stripe  

                - PayPlug  

                - HiPay  

                - BrainTree  
            
    - ### ***Présentation des différentes solutions de paiement en ligne***  

        - #### ***PayPal***  

            - ***Présentation de PayPal***  

                - On ne présente plus PayPal, c’est un des leaders sur le marché.  
                
                - Il détient 56,55 % du marché des paiements en ligne. 
                
                - Autre fait important : les dernières études montrent que les utilisateurs sont 54 % plus enclins à acheter en ligne si le site marchand propose une solution PayPal.  

                - Parmi les fonctionnalités que PayPal propose, on trouve :  

                    - La possibilité de faire payer ses clients en ligne :  

                        - vous pouvez paramétrer PayPal sur votre site internet pour proposer ce mode de paiement sur les produits/services. Il est même possible de générer une facture professionnelle via l’application PayPal.  

                    - Gestion d’entreprise :  
                    
                        - en plus du service de paiement, PayPal met à disposition un gestionnaire de litiges entre commerçants et consommateurs. Il est également possible de consulter des statistiques de vente. Très utile pour optimiser une stratégie webmarketing.

            - ***À qui s’adresse PayPal ?***  

                - Cette solution de paiement s’adresse autant aux commerçants en ligne qu’aux particuliers !

            - ***Combien çà coute ?***  

                - PayPal fonctionne à la commission sur les transactions.  

                - Pour une transaction commerciale nationale, PayPal prendra 2,9 % de la transaction + une commission qui reste fixe de 35 centimes.  

                - Pour une transaction internationale, il faudra compter entre 0,50 et 2 % du montant de la transaction en fonction du pays.  

            - ***PayPal en image***  

                - PayPal permet de procéder à un acte d’achat très facilement et surtout rapidement ! Idéal pour convertir les prospects rapidement et pour les actes d’achat spontanés.  

                - En cliquant sur le bouton de paiement « Paypal », une fenêtre de connexion s’ouvre et il est possible de procéder à l’achat directement en quelques clics.  

                    ![image](/pictures/paypal.png) 

        - #### ***Stripe***  

            - ***Présentation de Stripe***  

                - Plateforme déjà bien reconnue sur le marché des solutions de paiement en ligne (20 % des parts de marché du paiement en ligne, deuxième leader après PayPal), Stripe est une solution plus que complète pour les e-commerçants !  

                - Stripe a prévu sa plateforme pour qu’elle soit la plus intuitive possible pour les développeurs lors de la conception des sites e-commerce en proposant 2 services :  

                    - La possibilité de concevoir un formulaire de paiement personnalisé de A à Z.  

                    - La possibilité de partir sur une page de paiement déjà créée avec l’option « Stripe Checkout ».  

                - Pour ceux qui souhaitent aller plus loin, Stripe propose d’autres fonctionnalités telles que :  

                    - La génération de factures personnalisables  

                    - La création d’une page de paiement personnalisée avec possibilité de partage via un lien  

                    - La connexion de Stripe avec d’autres services tiers (tels que des plug-in par exemple)

            - ***À qui s’adresse Stripe ?***  

                - Vous l’aurez compris, la cible principale sont les e-commerçants !  
                
            - ***Combien coûte Stripe ?***  

                - Pour les transactions avec une carte européenne, Stripe prendra une commission de 1,4 % + 25 centimes.  
                
                - Pour une carte non européenne, cela sera une commission de 2,9 % + 25 centimes.

                - Il est intéressant de noter que pour les entreprises qui génèrent un grand volume de paiement, Stripe peut proposer une solution sur mesure. Il faut les contacter directement.
                
            - ***Stripe en image***  

                ![image](/pictures/stripe.png)
                
        - #### ***Payplug***  

            - ***Présentation de Payplug***  

                - Payplug est une plateforme proposant une solution de paiement en ligne mais pas seulement. Elle propose également une solution de paiement en magasin, ce qui peut être un choix stratégique à faire si le site e-commerce sur lequel vous souhaitez mettre une solution de paiement en ligne détient également une boutique physique.  

            - ***À qui s’adresse Payplug ?***  

                - Payplug s’adresse aux commerçants et plus globalement aux PME (Petites et Moyennes Entreprises).  
                
            - ***Combien coûte Payplug ?***  

                - Au même titre que Stripe, Payplug peut proposer des tarifs sur mesure en fonction du nombre de ventes réalisées ou du type de paiement utilisé.

                - À titre indicatif, voici un exemple de tarif : si le chiffre d’affaires de l’entreprise est situé entre 100 000 € et 1 000 000 € par an, alors Payplus appliquera le tarif suivant : 0,8 % + quinze centimes par transaction + un abonnement de 30 € par mois.
                
            - ***Payplug en image***  

                ![image](/pictures/payplug.png)

        - #### ***Hipay***  

            - ***Présentation de HiPay***  

                - HiPay est une plateforme proposant des solutions de paiement en ligne. Très complet et abouti, ce ne sont pas moins de 200 méthodes de paiement qui sont proposées telles que les paiements suivants :  

                    - PayPal  
                    
                    - Visa  
                    
                    - Mastercard  
                    
                    - Maestro  
                    
                    - American Express  
                    
                    - Apple Pay  

                - Comme ses concurrents, cette solution permet la personnalisation des pages de paiement. Idéal pour les mettre aux couleurs d’une entreprise et respecter sa charte graphique.  

                - Elle propose également un tableau de bord qui permet d’avoir une vue d’ensemble de toutes les transactions en temps réel.  

            - ***À qui s’adresse HiPay ?***  

                - HiPay s’adresse à toutes les entreprises, elle est purement axée BtoB.

            - ***Combien coûte HiPay ?***  

                - HiPay fonctionne aussi au pourcentage sur les transactions :  

                    - Pour un règlement par carte, HiPay prend 1,60 % par transaction européenne (2,50 par transaction dans le reste du monde) + 25 centimes par transaction.
                
            - ***HiPay en image***  

                ![image](/pictures/hipay.png)

        - #### ***Braintree***  

            - ***Présentation de Braintree***  

                - Solution de paiement en ligne tout-en-un ! Idéal pour les moyens de paiement Apple Pay, Google Play, PayPal et carte bancaire !  

                - La plus-value de Braintree est justement de proposer une solution qui rassemble plusieurs types de paiement.  

                - Braintree permet également de se greffer facilement à un outil de facturation pour simplifier la gestion de la comptabilité.  

            - ***À qui s’adresse Braintree ?***  

                - Braintree s’adresse aux professionnels.  

            - ***Combien coûte Braintree ?***  

                - Braintree se rémunère en prenant une commission de 1,9 % + 30 centimes par transaction.  

            - ***Braintree en image***  

                ![image](/pictures/braintree.png)

    - ### ***Sélection et mise en place du mode de paiement sur son site e-commerce***  

        - #### ***Comment choisir le bon mode de paiement pour son site ?***  

            - ***Définir le type de site et le type de projet***  

                - Il faut sélectionner celle qui propose les meilleures expériences utilisateur par rapport à la cible du projet dans l’idée de convertir le plus de prospects et de générer le plus de vente.  

            - ***Le comparatif des différents modes de paiement***  

                - Nous avons listé les différentes solutions de paiement en ligne disponibles pour les sites e-commerce. Il y a des similitudes parmi elles, notamment en fonction des moyens de paiement.  
                
                - Globalement, nous retrouvons toujours l’option de paiement par carte bancaire. Il est primordial aujourd’hui de proposer cette option.  

                - Dans le cas d’un site en ligne de vente d’abonnement, il peut être intéressant de prendre une solution en ligne qui permet les prélèvements bancaires récurrents.  

                    - Il faudra dans ce cas de figure particulier demander l’autorisation au consommateur via un mandat de prélèvement SEPA
                
            - ***Comment choisir une solution plutôt qu’une autre ?***  

                - Il faut commencer à analyser le nombre de ventes moyen que va générer le site e-commerce.  

                - Ensuite, il faut analyser la cible, par exemple : est-elle sensible à PayPal ? Préfère-t-elle payer par carte bancaire ?  

                -  il faut se renseigner sur la compatibilité des solutions de paiement par rapport à la technologie du site. Il est judicieux de se poser les questions suivantes :  

                    - Si c’est un WordPress : existe-t-il un module PayPlug pour intégrer leur solution de paiement ?  

                    - Si c’est un Drupal : PayPal est-il une solution facile à mettre en place ? Combien de temps est-ce que cela va prendre et quelles sont les contraintes ?  

                    - Si c’est un Prestashop : Stripe a-t-il développé une extension pour faciliter l’installation ou suis-je contraint de passer par les outils que Prestashop met à ma disposition ?  

                        - Plus globalement : ai-je des ressources de développement pour mettre en place les systèmes de paiement en ligne ?  

                    - Ai-je déjà un compte entreprise sur une plateforme de paiement ou devrai-je en créer un ?

        - #### ***Sécuriser les transactions en ligne***  

            - ***La norme PCI DSS***  

                - Qu’est-ce que la norme PCI DSS ? En voici la définition : La norme PCI DSS est une norme relative à la sécurité multifacette.  
                
                - Elle inclut des exigences pour :  

                    - la gestion de la sécurité
                    
                    - Les politiques
                    
                    - Les procédures
                    
                    - L'architecture du réseau
                    
                    - La conception des logiciels
                    
                    - D'autres mesures de protection essentielles  
                    
                        - Elle existe pour accompagner les entreprises à protéger les données de leurs clients.  

                - Il s’agit d’une norme à respecter pour pouvoir garantir la confidentialité et la sécurité de toutes les transactions. Ce cadre est prévu pour protéger les données bancaires.  

                - Varonis, une société de protection des données bancaires, nous liste les 12 exigences principales de la norme PCI DSS :  

                    1. Installer et mettre à jour un pare-feu  

                    2. Éliminer les paramètres par défaut  

                    3. Protéger les données stockées des titulaires de carte  

                    4. Chiffrer la transmission des données de paiement  

                    5. Mettre à jour les logiciels antivirus régulièrement  

                    6. Déployer des systèmes et applications sécurisés  

                    7. Limiter les accès aux données des titulaires de carte aux personnes qui en ont besoin  

                    8. Identifier les accès des utilisateurs  

                    9. Restreindre l’accès physique aux données  

                    10. Suivre et surveiller les accès au réseau  

                    11. Procéder à des tests continus des systèmes et processus  

                    12. Créer et mettre à jour une stratégie de sécurité de l’information  

                - ***Il est donc important de s’entourer des personnes techniquement compétentes pour respecter toutes ces règles. Il faut également vérifier que les services tiers par lesquels vous souhaitez passer (par exemple, PayPal) soient aux normes de leur côté.***

            - ***La double authentification***  

                - Il faut être vigilant à ce que la double authentification soit bien mise en place pour toutes les transactions. Depuis quelques années déjà, la procédure d’authentification de paiement avait évolué.  

                - La DSP2 (directive sur les services de paiement) prévoit :  

                    - La mise en place (obligatoire) de l’authentification forte (double authentification)  

                    - La protection des droits des consommateurs en la renforçant  

                    - L'interdiction d’appliquer des frais en plus en cas de paiement par carte bancaire  

                        - En plus des informations bancaires, le consommateur doit valider son achat par l’un de ces moyens :  

                            - Son empreinte digitale (si l’achat est fait via son téléphone par exemple)  

                            - Un mot de passe complémentaire  

                            - Un code envoyé par SMS  

                            - Un acte de validation via son application de banque directement  

            - ***Le certificat SSL***  

                - Un certificat SSL permet d’authentifier l’identité même d’un site web et permet une connexion chiffrée, ce qui :  

                    - Rassure le visiteur du site par sa sécurité.  

                    - Permet de protéger les données et les traces que laisse derrière lui le visiteur. Pour faire clair, sur un site de vente en ligne, cela renforce la sécurité et permet que les informations renseignées ne soient pas déchiffrées, interceptées ou détournées.  

                - Concrètement SSL veut dire « Secure Sockets Layer ». C’est un certificat numérique et il est facile de vérifier la mise en place de ce certificat sur n’importe quel site en regardant la barre de recherche du navigateur, à gauche de l’URL : il faut tout simplement vérifier que le cadenas qui précède l’URL est bien fermé.

