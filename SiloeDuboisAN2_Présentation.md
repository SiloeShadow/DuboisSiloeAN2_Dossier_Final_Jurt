# Liens externes

•Fichier Unity: https://siloeshadow.itch.io/duboissiloe-remisejury2020-unitybuild

•Build Linux: https://siloeshadow.itch.io/buildlinux

•Vidéos: https://www.dropbox.com/home/Vid%C3%A9os 

•Lien Google Drive: https://drive.google.com/drive/u/3/folders/1YZoH-dcvCAry663kURZv6oQ4Ihqr2M9b

# The Path Beyond

## • Biographie

Siloé, 20 ans, étudiante en Arts Numériques à l’ESA Saint-Luc, passionnée par l’Histoire et le dessin concept art. Surnommée “Shadow” sur les réseaux sociaux, je suis également musicienne et compositrice. Bilingue en français-anglais, je travaille souvent en partenariat avec d’autres artistes afin de compléter leurs œuvres ou d’apporter un visuel à leur audio. 

## • Note d'intention

“The Path Beyond” se positionne par rapport à la question suivante: que se passe-t-il lorsque qu’un objet numérique de notre quotidien (GSM, ordinateur, télévision,…) meurt? 

Le titre fait référence à l'inconnu auquel l'homme (ou la machine dans ce cas-ci) est confronté lorsqu'il meurt: on ne sait pas ce qu'il y a au-delà de la mort.

L’idée de départ était dans un premier temps de reconstituer les funérailles d’un robot et de le mettre en parallèle avec les funérailles humaines. Le projet s’est petit-à-petit concentré sur l’intérieur plutôt que l’extérieur, se tournant alors vers le voyage d’une entité énergétique, représentant l’âme de l’objet, vers le repos éternel.

## • Synopsis

Le spectateur se retrouve dans une pièce sombre avec seulement une faible lumière. Il est alors reçu par une personne en tenue de rituel lui proposant d'être témoin des funérailles de son appareil électronique ou d'un autre appareil ancien qu'il aurait rapporté. La personne est alors invitée à placer son appareil dans un petit cercueil disposée à côté d’un ordinateur, ce qui lancera le projet. 

Une fois le projet lancé, le spectateur pourra suivre le voyage de l’énergie interne de son appareil et pourra prendre part dans le projet en guidant l’énergie vers son repos éternel grâce à un Hapy Drum placé devant l’ordinateur. 

Le spectateur frappe sur le Hapy Drum afin d’ouvrir les différentes portes du parcours, rapprochant l’énergie son repos éternel. 

## • Positionnement artistique

La principale inspiration de ce travail est tout d’abord les différentes mythologies anciennes, allant de la mythologie celte à celle de l’Egypte Antique. Le parcours combine toutes ces mythologies et évolue dans un monde inspiré de *Just Shapes & Beats* et de l’artiste *Igeking* pour les designs des dieux environnants, notamment la position des rouages les constituant. 

Les couleurs sont directement inspirées du travail de *Daro Montag* intitulé “Bioglyphs” et du duo *Evelina Domnitch et Dmitry Gelfand* et leur œuvre nommé “Camera Lucida” qui mixe le monde organique et robotique. 

On évoque souvent le fait que le gouffre entre homme et robot se restreint de plus en plus avec l’avancée de la technologie. Je me suis donc questionnée sur l’aspect interne de la question en reprenant les mythes du passage de l’âme vers l’au-delà. 

Est-ce qu’un appareil technologique pourrait avoir une âme et celle-ci devrait-elle être guidée par une entité supérieure afin de pouvoir reposer en paix après sa mort? 

Cette âme est-elle partiellement organique ou complètement robotique? Cette entité supérieure est-elle un homme ou une force de la nature? 

Le spectateur est libre de délivrer sa/ses propre(s) réponse(s) face à ce questionnement.

## • Descritpion

L’élément principal du projet est tout d’abord l’ordinateur central de la pièce. C’est sur celui-ci que ce trouve le projet monté dans Unity avec des modélisations faites dans Blender. Les modélisations du projet sont censées rayonner un halo bleuté et doivent avoir une animation en loop mais je dois encore me familiariser avec l’export Blender vers Unity. Dans un premier temps, j’ai exporté les animations sous forme de vidéos que j’ai joint au projet. 

L'avancée de la source énergétique allait également être projetée dans la pièce sombre afin de complètement immerger le spectateur. Il se retrouverait alors face à la projection et l’ordinateur ainsi que le Hapy Drum. 

La source (le personnage) s’arrête avant chaque porte qui s’illumine après un instant. La spectateur devait alors faire un son sur le Hapy Drum afin d’ouvrir cette porte pour que l’énergie puisse continuer son chemin. 

Tout au long du parcours, la personne pourra observer la vie de son objet électronique, de sa construction jusqu’à sa mort. Les souvenirs errant aux alentours seront sous forme de sprite planant le long du trajet. 

L’instrument allait dans un premier temps être connecté à Unity via l'Arduino mais cette idée va peut-être être mise de côté afin de laisser place à une composition sonore originale avec laquelle l'environnement réagirais, la base de ce code étant déjà réalisée lors du premier essai du projet.

## • Calendrier de production (Etat d'avancement)

### Prise en main des programmes

Dans un premier temps, j'ai dû d'abord prendre en main Blender avant de pouvoir modéliser quoi que ce soit.

S'en est suivi le problème de l'exportation de Blender vers Unity. Qualité de la modélisation qui chute, animations refusant de se looper,... Aucun tutoriel en ligne expliquaient clairement pourquoi ces choses arrivent et ce fut seulement lorsque je suis passée de la version 2.8 à 2.83 que l'export s'est fait plus facilement.

Après avoir fait plusieurs modélisations hors cours je me suis donc attelé à la conceptualisation des bras mécaniques, la sphère principale de la scène ainsi que les portes.

### Musique

Avant d'aller plus loin, je devais avant tout composer la musique de fond sur laquelle le projet se baserait.

Après avoir enregistré le Hapy Drum, j'ai ensuite expérimenté avec les libraires musicales; allant d'une mélodie plus rythmée à des mélodies plus lentes, etc.

La musique est certes présente, mais elle ne devait pas prendre toute la place, elle devait fusionner avec la scène ambiante. Je me suis donc décidée à faire un son embient, sans mélodie claire, mais parsemé de murmures. Ceci étant peut-être des murmures d'ancêtres? Ou de simples courants électriques?

L'interprétation reste libre...

### Codes

Après les modélisations le code fut la chose primordiale à faire.

Je me suis d'abord concentrée sur le code du son (AudioWave) avant de passer sur le code du "personnage" afin de le faire avancer et de le détruire une fois qu'il rentre en collision avec les portes ou la lumière finale au bout du chemin.

Il m'a fallu ensuite faire un AnimController afin de mettre en marche l'ouverture des portes, ceci étant une alternative à l'interaction avec le Hapy Drum originalement pensé.

### Couleurs

Une fois les codes faits et les modèles importés, il me fallait reproduire la colorimétrie désirée. En effet, si les exports des animations se sont mieux déroulés par la suite, les textures sont malheureusement restées un problème. L'aspect "glowing" des bras mécaniques et des portes refusait tout simplement de s'importer dans Unity.

### Animations

Toutes les animations 3D ont été réalisées dans Blender mais les "dieux" mécaniques en 2D sur les côtés ont directement été réalisés dans Unity. J'ai dû donc animer chaque rouage individuellement.

### "Souvenirs"

Le chemin étant parsemé de divers souvenirs propres au GSM tel que sa construction et certaines données recueillies au cours de sa vie, j'avais au départ pensé à intégrer ces vidéos directement dans Unity sous forme de Sprite cependant il ne prend que des images...

J'ai dû donc faire des captures d'écran de chaque frame et les inclure sous forme d'animation dans un sprite multiple avant de les placer le long du trajet.
