---


# Table des matières
1. [Introduction](https://docs.google.com/presentation/d/1ePlkLwS9Ew6DiZe_D98PFSBxpbx93JIVX8h5atwk-Dg/edit?usp=sharing) Qu'est-ce que Uikit et comment l'installer.
2. [Exercice](../Exercice/README.md) Pour bien commencer.
    1. [Grid](#Grid)
    2. [Exercice2](#Exercice2)
    3. [Exercice3](#Exercice3)
    4. [Exercice modification de la gouttière](#Exercice3gouttiere)
3. [Découverte](#decouverte)
4. [Projet de groupe](#Projet)

<a name="Grid"></a>

# Grid

- __[Grid](https://getuikit.com/docs/grid)__ - Documentation sur la méthode de création de div.
- __[Width](https://getuikit.com/docs/width)__ - Choisir une taille à sa gouttière.
- __[Tester Uikit](https://getuikit.com/assets/uikit/tests/)__


<a name="Exercice1"></a>

__Exercice 1 __

Nous allons créer une div Parent avec trois enfants.

```
    <div uk-grid>
        <div>test1</div>
        <div>test2</div>
        <div>test3</div>
    </div>
```

Si tout ce passe bien, vous verrez bien trois div, séparé l'une des autres sur le même axe (horizontal).

Avant de jouer avec les différentes tailles, nous allons nous amuser avec des boites de style. [Card Uikit](https://getuikit.com/docs/card) 


<a name="Exercice2"></a>

__Exercice 2__

Insérer une class à la div test1 et test3:

```
uk-card uk-card-default uk-card-body
```
<a name="Exercice3"></a>

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

<a name="Exercice3gouttiere"></a>

### Modificateur de gouttière


Le composant Grid est livré avec une gouttière par défaut qui est automatiquement réduite à partir d'un certain point d'arrêt, généralement sur une largeur de fenêtre d'affichage de bureau inférieure. Pour appliquer une gouttière différente, ajoutez l'une des classes suivantes.

|CLASSE	            |LA DESCRIPTION                                                                                            |
|------------------:|:--------------------------------------------------------------------------------------------------------:|
|.uk-grid-small	    |Ajoutez cette classe pour appliquer une petite gouttière.                                                 |
|.uk-grid-medium	|Ajoutez cette classe pour appliquer une gouttière moyenne comme celle par défaut, mais sans point d'arrêt.|
|.uk-grid-large	    |Ajoutez cette classe pour appliquer une grande gouttière avec des points d'arrêt.                         |
|.uk-grid-collapse	|Ajoutez cette classe pour supprimer entièrement la gouttière.                                             |

<a name="Decouverte"></a>

# On va passer à la découverte

<a name="Prendrelalargeurdelatoutelapage"></a>

```
<div class="uk-child-width-expand@s" uk-grid>
```

= prendre toute la largeur de la page

Exemple

```
    <div class="uk-child-width-expand@s uk-text-center" uk-grid>
    <div>
        <div class="uk-card uk-card-primary uk-card-body">Item</div>
    </div>
    <div>
        <div class="uk-card uk-card-primary uk-card-body">Item</div>
    </div>
    <div>
        <div class="uk-card uk-card-primary uk-card-body">Item</div>
    </div>
```

<img src="./img/1.png" height="100" />

On va rajouter uk-grid-collapse dans la class parent, ce qui va nous permettre d'avoir aucune marge entre les div enfants.


```
<div class="uk-grid-collapse uk-child-width-expand@s uk-text-center" uk-grid>
    <div>
        <div class="uk-card uk-card-primary uk-card-body">Item</div>
    </div>
    <div>
        <div class="uk-card uk-card-primary uk-card-body">Item</div>
    </div>
    <div>
        <div class="uk-card uk-card-primary uk-card-body">Item</div>
    </div>
</div>
```

<img src="./img/2.png" height="100" />

Comme vous pouvez le remarquer, uk-width-auto@ porte bien son nom, il va automatiquement s'adapter aux autres. Ainsi que uk-width-expand@m lui prendra la place qui lui reste.

```
    <div class="uk-text-center" uk-grid>
        <div class="uk-width-auto@m">
            <div class="uk-card uk-card-primary uk-card-body">Auto</div>
        </div>
        <div class="uk-width-1-3@m">
            <div class="uk-card uk-card-primary uk-card-body">1-3</div>
        </div>
        <div class="uk-width-expand@m">
            <div class="uk-card uk-card-primary uk-card-body">Expand</div>
        </div>
    </div>
```

<img src="./img/3.png" height="100" />


# [Découverte](https://getuikit.com/assets/uikit/tests)

<a name="Projet"></a>

# [Projet de groupe](../Projet)

