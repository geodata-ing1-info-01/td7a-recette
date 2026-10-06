# Recette à l'échelle

Le programme calcule les ingrédients d'une recette pour un nombre de
personnes, en unités SI (grammes, millilitres) ou américaines (onces,
tasses), et écrit le résultat dans un fichier CSV.

## Exécution

Dans le terminal, dans le dossier du projet :

```
python recette.py crepes -p 6 -u US
python recette.py --help
```

Le fichier produit est dans `sortie/`, par exemple `sortie/crepes_6_US.csv`.

## Recettes disponibles

Les fichiers de `recettes/`, chacun écrit pour 4 personnes : `cookies`
(en unités américaines), `crepes`, `mousse_chocolat`, `pate_pizza`.
