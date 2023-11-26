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