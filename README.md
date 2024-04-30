**Projet AGL**

> **Auteurs:**
>
> •Aloui Muhammed Amine\
> •Jlassi Takwa\
> •Dridi Wael
>
> **1. Introduction au Projet:**
>
> Le projet vise à développer un logiciel de peinture qui offre aux
> utilisateurs une plateforme intuitive pour créer des œuvres d\'art
> numériques. Le projet inclut la conception et l\'implémentation d\'une
> interface utilisateur conviviale, la mise en place d\'une boîte à
> outils complète pour la peinture, le support de différents styles\
> artistiques tels que l\'impressionnisme, ainsi que l\'intégration
> d\'une fonctionnalité d\'intelligence artificielle pour transformer
> des tableaux existants en divers styles artistiques. Nous avons choisi
> ce projet car il offre une opportunité de combiner notre intérêt pour
> la programmation informatique avec notre passion pour les arts
> visuels.
>
> **2. Spécification du Projet:**
>
> **2.1 Notions de Base et Contraintes:**

+-----------------------------------+-----------------------------------+
| > •\                              | > Le logiciel de peinture sera    |
| > •\                              | > développé en utilisant des      |
| > •\                              | > technologies avancées pour      |
| > •\                              | > offrir des performances         |
| > •                               | > optimales et une expérience     |
|                                   | > utilisateur fluide.             |
|                                   | >                                 |
|                                   | > Il doit être compatible avec    |
|                                   | > les principaux systèmes         |
|                                   | > d\'exploitation tels que        |
|                                   | > Windows, macOS et Linux,        |
|                                   | > assurant une large              |
|                                   | > accessibilité.                  |
|                                   | >                                 |
|                                   | > Le logiciel doit prendre en     |
|                                   | > charge les périphériques de     |
|                                   | > dessin tels que les tablettes   |
|                                   | > graphiques et les stylets,      |
|                                   | > garantissant une utilisation    |
|                                   | > intuitive et précise.           |
|                                   | >                                 |
|                                   | > Il doit inclure des             |
|                                   | > fonctionnalités avancées telles |
|                                   | > que la transformation de style  |
|                                   | > via l\'intelligence             |
|                                   | > artificielle et l\'application  |
|                                   | > de filtres et effets            |
|                                   | > artistiques personnalisables.   |
|                                   | >                                 |
|                                   | > La sécurité et la stabilité du  |
|                                   | > logiciel sont des priorités,    |
|                                   | > avec une gestion efficace de la |
|                                   | > mémoire et des protections      |
|                                   | > contre les vulnérabilités.      |
+===================================+===================================+
+-----------------------------------+-----------------------------------+

> **2.2 Acteurs:**

+-----------------------------------+-----------------------------------+
| > •\                              | > Utilisateur : L\'acteur         |
| > •\                              | > principal qui interagit avec le |
| > •\                              | > logiciel pour créer et          |
| > •                               | > manipuler des œuvres d\'art     |
|                                   | > numériques.                     |
|                                   | >                                 |
|                                   | > Stylus : Un outil de dessin     |
|                                   | > utilisé avec une tablette       |
|                                   | > graphique pour dessiner et      |
|                                   | > peindre avec précision.         |
|                                   | >                                 |
|                                   | > Tablet : Permet la connexion et |
|                                   | > la gestion du stylet pour       |
|                                   | > faciliter le travail de         |
|                                   | > l\'utilisateur.                 |
|                                   | >                                 |
|                                   | > AI System : Fournit des         |
|                                   | > fonctionnalités d\'intelligence |
|                                   | > artificielle pour transformer   |
|                                   | > le style de l\'œuvre et fournir |
|                                   | > des suggestions artistiques.    |
+===================================+===================================+
+-----------------------------------+-----------------------------------+

> **2.3 Fonctionnalités Attendues:**
>
> •Créer un Nouvel Espace de Travail:\
> •L\'utilisateur peut créer un nouvel espace de travail avec des\
> dimensions personnalisées, un nom de fichier, des paramètres initiaux
> tels que la couleur d\'arrière-plan, et la sélection d\'un modèle de
> document si nécessaire.
>
> •Le workspace est configuré selon les préférences de l\'utilisateur et
> prêt à être utilisé.
>
> •Charger un Espace de Travail:\
> •L\'utilisateur peut charger un espace de travail existant pour
> continuer à travailler sur une œuvre.
>
> •Utiliser un Outil:\
> •L\'utilisateur peut sélectionner un outil parmi ceux disponibles dans
> la barre d\'outils et l\'utiliser sur un espace de travail ouvert.
>
> •Le stylet est utilisé pour appliquer l\'outil aux zones ou calques
> spécifiques.
>
> •Transformer le Style:\
> •L\'utilisateur peut choisir un style parmi les options disponibles, y
> compris les styles basés sur l\'IA, pour transformer l\'œuvre.
>
> •L\'AI System applique le style choisi aux calques ou zones définies.
>
> •Gérer les Calques:\
> •L\'utilisateur peut gérer les calques en les fusionnant, les
> dupliquant, les déplaçant ou les verrouillant selon les besoins.
>
> •Appliquer des Filtres et Effets:\
> •L\'utilisateur peut choisir et appliquer des filtres et effets
> artistiques aux calques ou zones sélectionnées.
>
> •Les paramètres des filtres et effets sont configurables selon les
> préférences de l\'utilisateur.
>
> •Enregistrer et Exporter des Œuvres:
>
> •L\'utilisateur peut enregistrer et exporter les œuvres créées dans
> divers formats, résolution et qualité.
>
> •Les fichiers sont enregistrés dans un emplacement spécifié ou
> exportés vers une destination externe.
>
> •Utiliser la Tablette et le Stylet:\
> •L\'utilisateur peut connecter et utiliser la tablette et le stylet
> pour dessiner et peindre de manière plus précise et intuitive.
>
> **Cas d\'Utilisation**
>
> **1. Créer un Nouvel Espace de Travail:**
>
> **Préconditions:**
>
> •Choix de dimensions personnalisées (hauteur et largeur) pour
> l\'espace de travail.
>
> •Sélection d\'un nom de fichier.
>
> •Vérification de l\'espace de stockage disponible.
>
> •Configuration des paramètres initiaux tels que la couleur
> d\'arrière-plan et la résolution.
>
> •Sélection d\'un modèle de document s\'il y a lieu.
>
> **Postconditions:**
>
> •Un nouvel espace de travail est créé, prêt à être utilisé.
>
> Table de décision:

+-----------+-----------+-----------+-----------+-----------+-----------+
| **Choix   | *         | >         | >         | >         | **R       |
| de la     | *Choix**\ |  **Espace | **Configu |  **Modèle | ésultat** |
| di        | **d\'un   | > de      | ration**\ | > de      |           |
| mension** | nom de    | >         | > **des   | >         |           |
|           | fichier** |  stockage | > p       |  document |           |
|           |           | > su      | aramètres | > séle    |           |
|           |           | ffisant** | > i       | ctionné** |           |
|           |           |           | nitiaux** |           |           |
+===========+===========+===========+===========+===========+===========+
| > Vrai    | > Vrai    | > Vrai    | > Vrai    | > Vrai    | > Le\     |
|           |           |           |           |           | >         |
|           |           |           |           |           | workspace |
|           |           |           |           |           | > est     |
|           |           |           |           |           | > créé    |
+-----------+-----------+-----------+-----------+-----------+-----------+
| > Vrai    | > Vrai    | > Faux    | > Vrai    | > Vrai    | > Le\     |
|           |           |           |           |           | >         |
|           |           |           |           |           | workspace |
|           |           |           |           |           | > n\'est  |
|           |           |           |           |           | > pas\    |
|           |           |           |           |           | > créé    |
+-----------+-----------+-----------+-----------+-----------+-----------+

+-----------+-----------+-----------+-----------+-----------+-----------+
| > Vrai    | > Vrai    | > Vrai    | > Faux    | > Vrai    | > Le\     |
|           |           |           |           |           | >         |
|           |           |           |           |           | workspace |
|           |           |           |           |           | > n\'est  |
|           |           |           |           |           | > pas\    |
|           |           |           |           |           | > créé    |
+===========+===========+===========+===========+===========+===========+
| > Vrai    | > Vrai    | > Vrai    | > Vrai    | > Faux    | > Le\     |
|           |           |           |           |           | >         |
|           |           |           |           |           | workspace |
|           |           |           |           |           | > est     |
|           |           |           |           |           | > créé    |
+-----------+-----------+-----------+-----------+-----------+-----------+
| > Faux    | > Vrai    | > Vrai    | > Vrai    | > Vrai    | > Le\     |
|           |           |           |           |           | >         |
|           |           |           |           |           | workspace |
|           |           |           |           |           | > n\'est  |
|           |           |           |           |           | > pas\    |
|           |           |           |           |           | > créé    |
+-----------+-----------+-----------+-----------+-----------+-----------+
| > Vrai    | > Faux    | > Vrai    | > Vrai    | > Vrai    | > Le\     |
|           |           |           |           |           | >         |
|           |           |           |           |           | workspace |
|           |           |           |           |           | > n\'est  |
|           |           |           |           |           | > pas\    |
|           |           |           |           |           | > créé    |
+-----------+-----------+-----------+-----------+-----------+-----------+
| > Vrai    | > Vrai    | > Vrai    | > Vrai    | > N/A     | > Le\     |
|           |           |           |           |           | >         |
|           |           |           |           |           | workspace |
|           |           |           |           |           | > est     |
|           |           |           |           |           | > créé    |
+-----------+-----------+-----------+-----------+-----------+-----------+

> **2. Utiliser un Outil:**
>
> **Préconditions:**
>
> •Un outil est choisi parmi ceux disponibles dans la barre d\'outils.
>
> •Un espace de travail est ouvert et sélectionné.
>
> •Les calques, masques ou zones spécifiques à modifier sont définis.
> •L\'outil est configuré selon les préférences de l\'utilisateur
> (opacité, taille, dureté, etc.).
>
> **Postconditions:**
>
> •L\'outil modifie le workspace en fonction des paramètres de l\'outil
> et des zones ciblées.
>
> •Les modifications sont appliquées aux calques spécifiques ou à
> l\'ensemble du document, selon le choix de l\'utilisateur.
>
> Table de décision:

+-------------+-------------+-------------+-------------+-------------+
| >           | >           | > **Zones   | >           | *           |
|  **Outil**\ | **Workspace | > ciblées   |  **Outil**\ | *Résultat** |
| >           | > ouvert**  | >           | > **        |             |
|  **choisi** |             |  définies** | configuré** |             |
+=============+=============+=============+=============+=============+
| > Vrai      | > Vrai      | > Vrai      | > Vrai      | > M         |
|             |             |             |             | odification |
|             |             |             |             | > précise   |
+-------------+-------------+-------------+-------------+-------------+
| > Vrai      | > Vrai      | > Vrai      | > Faux      | > M         |
|             |             |             |             | odification |
|             |             |             |             | > imprécise |
+-------------+-------------+-------------+-------------+-------------+
| > Vrai      | > Vrai      | > Faux      | > Vrai      | > M         |
|             |             |             |             | odification |
|             |             |             |             | > générale  |
+-------------+-------------+-------------+-------------+-------------+
| > Vrai      | > Faux      | > N/A       | > N/A       | > Pas de\   |
|             |             |             |             | > m         |
|             |             |             |             | odification |
+-------------+-------------+-------------+-------------+-------------+
| > Faux      | > Vrai      | > N/A       | > N/A       | > Pas de\   |
|             |             |             |             | > m         |
|             |             |             |             | odification |
+-------------+-------------+-------------+-------------+-------------+

> **3. Transformer le Style:**
>
> **Préconditions:**
>
> •Un espace de travail est ouvert.
>
> •Un style est choisi parmi les styles disponibles, y compris les
> options IA. •Les calques à transformer sont sélectionnés.
>
> •Paramètres du style configurés (intensité, palette de couleurs,
> etc.).
>
> **Postconditions:**
>
> •Le style des calques sélectionnés est transformé selon les paramètres
> choisis.
>
> •Le style global de l\'œuvre est modifié si souhaité.
>
> Table de décision:

+-------------+-------------+-------------+-------------+-------------+
| >           | > **Style   | > **Calques | > *         | *           |
| **Workspace | > choisi**  | > ou zones  | *Paramètres | *Résultat** |
| > ouvert**  |             | > à         | > de style  |             |
|             |             | >           | > c         |             |
|             |             | transformer | onfigurés** |             |
|             |             | > définis** |             |             |
+=============+=============+=============+=============+=============+
+-------------+-------------+-------------+-------------+-------------+

+-------------+-------------+-------------+-------------+-------------+
| > Vrai      | > Vrai      | > Vrai      | > Vrai      | > Le style  |
|             |             |             |             | > est       |
|             |             |             |             | >           |
|             |             |             |             |  transformé |
|             |             |             |             | > selon les |
|             |             |             |             | >           |
|             |             |             |             |  paramètres |
+=============+=============+=============+=============+=============+
| > Faux      | > Vrai      | > N/A       | > N/A       | Pas de      |
|             |             |             |             | tra         |
|             |             |             |             | nsformation |
+-------------+-------------+-------------+-------------+-------------+
| > Vrai      | > Faux      | > N/A       | > N/A       | Pas de      |
|             |             |             |             | tra         |
|             |             |             |             | nsformation |
+-------------+-------------+-------------+-------------+-------------+
| > Vrai      | > Vrai      | > Faux      | > N/A       | Pas de      |
|             |             |             |             | tra         |
|             |             |             |             | nsformation |
+-------------+-------------+-------------+-------------+-------------+
| > Vrai      | > Vrai      | > Vrai      | > Faux      | Pas de      |
|             |             |             |             | tra         |
|             |             |             |             | nsformation |
+-------------+-------------+-------------+-------------+-------------+

**Diagramme de Cas d'utilisation:**

![](vertopal_3a3f759e1ec94454a620ffe768547124/media/image1.png){width="6.259722222222222in"
height="3.7694433508311462in"}

**Diagramme de Séquence 1:**

![](vertopal_3a3f759e1ec94454a620ffe768547124/media/image2.png){width="6.259722222222222in"
height="5.030555555555556in"}

**Diagramme de Séquence 2:**

![](vertopal_3a3f759e1ec94454a620ffe768547124/media/image3.png){width="6.259722222222222in"
height="3.0194444444444444in"}

**Diagramme de Séquence 3:**

![](vertopal_3a3f759e1ec94454a620ffe768547124/media/image4.png){width="6.259722222222222in"
height="2.1458333333333335in"}

Diagramme de Classe:

![](vertopal_3a3f759e1ec94454a620ffe768547124/media/image5.png){width="6.238888888888889in"
height="6.259722222222222in"}

> **Diagramme de conception détaillé:**
>
> ![](vertopal_3a3f759e1ec94454a620ffe768547124/media/image6.png){width="5.0in"
> height="3.7291666666666665in"}
>
> Diagramme de machine d'état:

![](vertopal_3a3f759e1ec94454a620ffe768547124/media/image7.png){width="6.259722222222222in"
height="2.0722222222222224in"}

> Diagramme de Classe Raffinée:

![](vertopal_3a3f759e1ec94454a620ffe768547124/media/image5.png){width="6.238888888888889in"
height="6.259722222222222in"}

> **Invariant pour la classe Calque:**
>
> L\'invariant de la classe Calque peut être exprimé en logique
> propositionnelle de la manière suivante :

+-----------------------------------+-----------------------------------+
| > •\                              | > Opacité : 0 \<= opacité \<= 1\  |
| > •\                              | > Visibilité : visible == True ou |
| > •\                              | > visible == False\               |
| > •                               | > Contenu : contenu n\'est pas    |
|                                   | > None\                           |
|                                   | > Initialisation correcte : nom   |
|                                   | > n\'est pas None et nom != \"\"  |
+===================================+===================================+
+-----------------------------------+-----------------------------------+

> Ainsi, l\'invariant pour la classe Calque peut être exprimé comme suit
> : (0 \<= opacité \<= 1) ∧
>
> (visible == True ∨ visible == False) ∧\
> (contenu n\'est pas None) ∧\
> (nom n\'est pas None ∧ nom != \"\")\
> (0 \<= opacité \<= 1) ∧
>
> Cet invariant garantit que la classe Calque maintient un état correct
> à tout moment.
>
> **Tables de décision pour les tests unitaires**
>
> **Opération 1 : fusionner(autre: Calque)**\
> Construisons la table de décision pour l\'opération fusionner de la
> classe Calque. Cette méthode fusionne le calque courant avec un autre
> calque (autre).
>
> La table prendra en compte les conditions suivantes et les résultats
> attendus :
>
> •Préconditions :\
> •Les calques this et autre doivent être visibles (visible == True).
> •L\'opacité des deux calques doit être dans la plage valide \[0,1\].
>
> •Postconditions :\
> •Un nouveau calque est renvoyé, représentant l\'état fusionné de this
> et autre.
>
> •L\'opacité du nouveau calque est une valeur valide (moyenne de
> this.opacité et autre.opacité).
>
> •Le nouveau calque est visible si this et autre sont visibles.
>
> Voici la table de décision pour l\'opération fusionner :

+-----------+-----------+-----------+-----------+-----------+-----------+
| > **Cas   | **t       | **au      | **t       | **au      | > **Ré    |
| > de      | his.visib | tre.visib | his.opaci | tre.opaci | sultat**\ |
| > test**  | le**      | le**      | té**      | té**      | > **      |
|           |           |           |           |           | attendu** |
+===========+===========+===========+===========+===========+===========+
| > 1       | > True    | > True    | > 0.5     | > 0.5     | > Succès  |
+-----------+-----------+-----------+-----------+-----------+-----------+
| > 2       | > False   | > True    | > 0.5     | > 0.5     | >         |
|           |           |           |           |           | Exception |
+-----------+-----------+-----------+-----------+-----------+-----------+
| > 3       | > True    | > False   | > 0.5     | > 0.5     | >         |
|           |           |           |           |           | Exception |
+-----------+-----------+-----------+-----------+-----------+-----------+
| > 4       | > True    | > True    | > -0.1    | > 0.5     | >         |
|           |           |           |           |           | Exception |
+-----------+-----------+-----------+-----------+-----------+-----------+

+-----------+-----------+-----------+-----------+-----------+-----------+
| > 5       | > True    | > True    | > 0.5     | > 1.1     | >         |
|           |           |           |           |           | Exception |
+===========+===========+===========+===========+===========+===========+
+-----------+-----------+-----------+-----------+-----------+-----------+

> **Opération 2 : dupliquer()**
>
> Construisons la table de décision pour l\'opération dupliquer de la
> classe Calque. Cette méthode duplique le calque courant et renvoie un
> nouveau calque avec des attributs identiques.
>
> La table prendra en compte les conditions suivantes et les résultats
> attendus :
>
> •Préconditions :\
> oLe calque doit être visible (visible == True).
>
> oL\'opacité doit être dans la plage valide \[0,1\].
>
> •Postconditions :\
> oUn nouveau calque est renvoyé, représentant une copie identique du
> calque courant.
>
> oL\'opacité du nouveau calque est identique à this.opacité.

oLa visibilité du nouveau calque est identique à this.visible.

> Voici la table de décision pour l\'opération dupliquer :

+-----------------+-----------------+-----------------+-----------------+
| **Cas de test** | *               | *               | **Résultat      |
|                 | *this.visible** | *this.opacité** | attendu**       |
+=================+=================+=================+=================+
| > 1             | > True          | > 0.5           | > Succès        |
+-----------------+-----------------+-----------------+-----------------+
| > 2             | > False         | > 0.5           | > Exception     |
+-----------------+-----------------+-----------------+-----------------+
| > 3             | > True          | > 1.1           | > Exception     |
+-----------------+-----------------+-----------------+-----------------+
| > 4             | > True          | > -0.1          | > Exception     |
+-----------------+-----------------+-----------------+-----------------+
