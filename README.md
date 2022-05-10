# Prérequis 

- [ ] 1. Connaissance en HTML/CSS et SASS
- [ ] 2. Node installé sur votre ordinateur

# Commandes effectués
1. yarn init
2. yarn add 
```cmd
yarn add node-sass -D
```
3. yarn sass
> Voir ceci : 
```json
"scripts": {
    "sass": "node-sass -w scss/ -o dist/css/ --recursive"
  },
  ```
  Cela permettra que chaque modification du scss  sera envoyé dans le dossier dist/css

  Pensée à augmenter la qualité de l'image