---
# Grid :)

- __[:')](https://getuikit.com/docs/grid)__ - Documentation sur la manière de création de div.
- __[:')](https://getuikit.com/docs/width)__ - Choisir une taille à sa gouttière.
- __[Tester Ulkit](https://getuikit.com/assets/uikit/tests/)__

__Exercice 1 :D__

Nous allons crée une div Parent avec trois enfants.

```
    <div uk-grid>
        <div>test1</div>
        <div>test2</div>
        <div>test3</div>
    </div>
```

Si tout ce passe bien, vous verrez bien trois div, séparé l'une des autres sur le même axe (horizontal).

Avant de jouer avec les différentes tailles, nous allons jouer avec des boites de style. [Card Ulkit](https://getuikit.com/docs/card) 

__Exercice 2__

Insérer une class à la div test1 et test3:

```
uk-card uk-card-default uk-card-body
```
__Exercice 3__

Maintenant on va parler des différentes tailles.[Width](https://getuikit.com/docs/width).


|   CLASSE	                    | LA DESCRIPTION                                           |
| ----------------------------- |:---------------------------------------------------------|
| .uk-width-1-1	                | Remplit 100% de la largeur disponible.                   |
| .uk-width-1-2	                | L'élément occupe la moitié de son conteneur parent.      |
| .uk-width-1-3 à .uk-width-2-3	| L'élément occupe les tiers de son conteneur parent.      |
| .uk-width-1-4 à .uk-width-3-4	| L'élément occupe les quarts de son conteneur parent.     |
| .uk-width-1-5 à .uk-width-4-5	| L'élément occupe les cinquièmes de son conteneur parent. |
| .uk-width-1-6 à .uk-width-5-6	| L'élément occupe les sixièmes de son conteneur parent.   |


### Modificateur de gouttière


Le composant Grid est livré avec une gouttière par défaut qui est automatiquement réduite à partir d'un certain point d'arrêt, généralement sur une largeur de fenêtre d'affichage de bureau inférieure. Pour appliquer une gouttière différente, ajoutez l'une des classes suivantes.

|CLASSE	            |LA DESCRIPTION                                                                                            |
|------------------:|:--------------------------------------------------------------------------------------------------------:|
|.uk-grid-small	    |Ajoutez cette classe pour appliquer une petite gouttière.                                                 |
|.uk-grid-medium	|Ajoutez cette classe pour appliquer une gouttière moyenne comme celle par défaut, mais sans point d'arrêt.|
|.uk-grid-large	    |Ajoutez cette classe pour appliquer une grande gouttière avec des points d'arrêt.                         |
|.uk-grid-collapse	|Ajoutez cette classe pour supprimer entièrement la gouttière.                                             |

# [Découverte](./docs2.md)
