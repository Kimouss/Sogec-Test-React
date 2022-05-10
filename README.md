# Sujet test React

Le but du test est de récupérer les information depuis l'API [PokéApi](https://pokeapi.co/).

Pré-requis:
* Version React supérieur ou égale à 17.x.x
* Redux (utiliser "[Redux-toolkit](https://redux-toolkit.js.org/)" pour vous faciliter la vie)
* React-router (utiliser "[React Router](https://reactrouter.com/)" pour la gestion des routes)
* [Formik](https://formik.org/) pour vos formulaires
* Functional components

## Pokémon:

### Homepage:
- Doit être accessible à partir de l'URL `/`
- Récupérer une liste de "Card" composée de l'image du pokémon, nom et numéro
  - Consommer l'API sous cette forme
    - Liste des pokémons: https://pokeapi.co/api/v2/pokemon
    - Récupération d'une image d'un pokémon: https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/{numéro_du_pokémon}.png
- Pagination

### Homepage search:
- Création d'un formulaire de recherche
  - Recherche par nom
  - Recherche par numéro
- Doit afficher un message d'erreur si la recherche n'a pas abouti
- Présence d'un loader durant le chargement de la page

### Profil d'un pokémon:
- Doit être accessible à partir au clique d'une card
- Doit être accessible à partir de l'URL `/pokemon/:id`
- Affichage:
  - Nom du pokémon
  - Numéro du pokémon
  - Image du pokémon (rappel: https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/{numéro_du_pokémon}.png )
  - Liste des types du pokémon
  - Description du pokémon (consommer l'API sous cette forme: https://pokeapi.co/api/v2/pokemon-species/{numéro_du_pokémon})
    - Vous êtes libre de choisir la version de la description que vous souhaitez afficher

## Nice to have :
- Pour la création de votre application, nous vous recommendons l'un de ses outils:
  - [next-js](https://nextjs.org/)
  - [create-react-app](https://create-react-app.dev/)

## Bonus:
* InfiniteScroll
* Recherche avancée (type, generation, etc.)
* Projet en TypeScript
* Utilisation de Docker
* Soyez créatif :)


