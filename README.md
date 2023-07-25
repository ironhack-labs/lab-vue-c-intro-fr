![logo_ironhack_blue 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)

# LAB | Bonjour Vue

## Introduction

Aujourd'hui, nous avons appris les bases de Vue.js et comment créer une application simple en utilisant le package **`npm init vue@latest`**. Dans cet exercice, nous allons mettre en pratique ce que nous venons d'apprendre en créant une page d'accueil simple (avec un peu de style :blossom:).

## Configuration

- Fork ce repo
- Clone ce repo
- Ouvre le LAB et commence :

  ```bash
  $ cd lab-vue-c-intro
  $ npm install
  $ npm run dev
  ```

## Remise

- Une fois terminé, exécute les commandes suivantes : 

  ```
  git add .
  git commit -m "done"
  git push origin master
  ```

- Crée une Pull Request pour que tes TAs puissent vérifier ton travail.

## Instructions

### Itération 1 | Crée une application Vue

Commençons ! Tout d'abord, tu devras créer une nouvelle application Vue.

Accède au dossier racine du LAB. Lorsque tu te trouves dans le dossier racine, utilise `npm init vue@latest` dans la ligne de commande pour créer un nouveau projet Vue.

Une fois que tu as créé l'application, accède au dossier racine de l'application. À partir de là, lance l'application en mode développement et ouvre-la dans le navigateur.

Si tu as besoin d'aide, n'oublie pas que tu peux toujours consulter la documentation officielle de Vue. Jette un coup d'œil à la page de démarrage ici : [Créer une application Vue - Guide de démarrage rapide](https://vuejs.org/guide/quick-start.html).


### Itération 2 | Prépare l'application

Maintenant que tu as créé l'application, nettoyons le fichier `App.Vue`. Supprime le contenu initial généré par le CLI pour obtenir la structure suivante :

```jsx
<template>
  <div id="app">
  </div>
</template>

<script>
  export default {
    name: 'App',
  }
</script>

<style>
  #app {
  }
</style>
```

<br>

### Itération 3 | Télécharge les ressources

Pour créer la page d'accueil, nous aurons besoin de quelques images. À l'intérieur du dossier `src/`, crée un nouveau dossier nommé `images`. Le dossier doit être imbriqué de la manière suivante : `src/images/`. 

Ensuite, télécharge les images suivantes et enregistre-les dans le dossier `src/images/`. 

Tu peux récupérer toutes les images à partir de [ce fichier Figma](https://www.figma.com/file/2rSKMls9ZscT4VjggWpvfL/Vue-Lab---Welcome-to-Vue.js?node-id=0%3A1). Figma est un outil de prototypage et de conception gratuit très populaire auprès des concepteurs. En tant que développeur web, il est probable que tu devras reproduire fréquemment des designs créés dans Figma. Utiliser Figma est utile car tu peux voir exactement quelle est la taille et la position des éléments, plutôt que de simplement visualiser un fichier image. 

<br>

### Itération 4 | Page d'accueil

Enfin, créons notre page d'accueil. À l'aide des ressources que tu as téléchargées depuis Figma lors de l'itération précédente, recrée la page d'accueil suivante :

<details>
  <summary>Clique ici pour voir l'image</summary>

![web-frontend-vue/lab-vue-intro-finished](https://education-team-2020.s3.eu-west-1.amazonaws.com/web-frontend-vue/lab-vue-intro-finished.png)

</details>

Pour l'instant, ne t'inquiète pas de créer plus d'un composant, nous verrons cela dans les prochaines leçons !

<br>

Bon développement ! :heart: