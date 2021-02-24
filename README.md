# My Digitial School - B1 - PHP - DS1

Vous allez réaliser un site d'annonces de voitures.

Pour les données, vous vous appuierez sur le fichier `cars.php` présent dans le dossier `data` de ce dépôt de sources. Il contient des données aléatoires de 80 annonces.

Vous trouverez les informations suivantes :

- ID
- Nom
- Type
- Marque
- Image (les images correspondantes se trouvent dans le dossier `images`)
- Description
- Nombre de places
- Transmission
- Prix
- Tags
- Contact (un email)

## Pages demandées

- Page d'accueil
- Page de liste de toutes les annonces avec moteur de recherche pour filtrer la liste
- Page de détail d'une annonces

## Page d'accueil

La page d'accueil présentera les 10 premières annonces du tableau fourni.

Chaque annonce sera un cadre à partir duquel on pourra cliquer sur un lien "Voir le détail" pour accéder à sa fiche.

> Vous utiliserez l'ID de l'annonce pour l'identifier de manière unique quand vous accèderez à sa fiche

## Page de liste

La page de liste des annonces présentera l'ensemble des annonces présentes dans le tableau de données.

> L'apparence d'une annonce devra être identique à celle de la page d'accueil. On pourra donc cliquer sur un lien "Voir le détail" de la même façon, pour accéder à la fiche de l'annonce

### Moteur de recherche

Dans la page de liste, vous intègrerez un moteur de recherche d'annonce.

Champs du moteur :

- Nom de la voiture (champ texte)
- Nombre de places (nombre entier)
- Prix minimum (nombre entier)
- Transmission (liste déroulante : "manuelle" ou "automatique")

> Note pour la liste déroulante des transmissions : les valeurs de chaque élément seront les suivantes : `manual` pour les transmissions manuelles, `automatic` pour les transmissions automatiques. Ce sont les valeurs possibles pour l'information "Transmission" dans le fichier de données

## Page de détail

La page de détail présentera l'ensemble des informations d'une annonce dont l'ID aura été récupéré à partir d'un paramètre GET.

Ainsi, vous construirez votre page pour qu'on voie apparaître :

- Le nom de la voiture
- Le type
- La marque
- L'image d'illustration de l'annonce
- La description complète
- Le nombre de places
- La transmission
- Le prix
- Les tags
- L'adresse email de contact du vendeur
