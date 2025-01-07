# Notes

## Côté client
Le navigateur web interprète le code HTML et CSS pour afficher la page web.

## Côté serveur
Le serveur traite les requêtes et renvoie les réponses appropriées au client.
*
## HTML
Le HTML est composé de **balises** qui structurent le contenu de la page web.

```html
<p>
    <b>
        Paragraphe
    </b>
</p>
        
        <style>p {color:blue}</style>
```

## Commandes

- ctrl + p : rechercher un fichier
- ctrl + shift + p : ouvrir les commandes vscode
- ctrl + shift + f : rechercher dans tous les fichiers

faire une maquette


## CSS

- inline :
```html
<p style = "color: red">Texte</p>
```
- interne :
```html
<style>
    p {color: "red"}
</style>
```
- externe : (Dans un fichier .css)
```css
p {color: "red"}
```

changer de police d'écriture : 
- copier le <link> dans le html et le code css dans le css à l'endroit souhaité

pseudo-classe : permet de modifier le css en fonction de l'état de l'élément sélectionné 
```css
div:hover {color: "red"}
```

-----------------------------------

## GIT

```sh
#Initialiser le repo
git init

#Le status du repo
git status

#Ajouter tous les fichiers non sauvegardés
git add .

#Sauvegarder les fichiers
git commit -m "message de commit"
```