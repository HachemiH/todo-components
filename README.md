# todo-components

## Project setup
```
npm install
```


# Toutes les étapes pour créer une Todo Liste sous Vue JS

1. Création du projet `vue create todolist`
2. Nettoyage du boilerplate (suppression des composants, nettoyage de `App.vue`)
3. Installation de [Bulma](https://bulma.io/)
4. Création du composant `TodoList.vue`
5. Câbler le composant `TodoList.vue`  vers `App.vue` (import)
  5.1 => 3 étapes : import, export et ajout de la balise
6. Création du composant `TodoInputText.vue`
7. Câbler le composant `TodoInputText.vue` vers `TodoList.vue` (export, import)
  7.1 => 3 étapes : import, export et ajout de la balise
8. Insérer un `input` de `Bulma` dans le composant `TodoInputText.vue`
9. Ajouter de la `data` dans le composant `TodoList.vue`
10. Création du composant `TodoListItem.vue`
11. Câbler le composant `TodoListItem.vue` vers `TodoList.vue` (export, import, props)
  11.1 => 5 étapes : import, export, ajout de la balise, props et v-for
12. Brancher un `v-model` sur la balise `TodoInputText` dans `TodoList.vue` (+ v-bind value dans `TodoInputText.vue`)
13. Brancher un écouteur de la touche `enter` pour déclencher la méthode `addTodo` dans la balise `TodoInputText` dans `TodoList.vue`
14. Remplir la méthode `addTodo`




### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Run your tests
```
npm run test
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
