# PowerShell — organiser des fichiers
**Exercice de formation · 2024**

L'exercice consiste à répartir dix fichiers dans deux dossiers selon le numéro présent dans leur nom.

## Travail conservé

- [Commandes saisies dans PowerShell](Commande%20Taper%20pour%20Qu%C3%AAte%20PS2.md)
- [Sorties de console de l'exercice](RESULTATS-EXERCICE.md)

Le dépôt contient une suite de commandes manuelles, pas encore un script automatisé.

## Résultat consigné

| Dossier | Fichiers |
| --- | --- |
| `EvenFolder` | File2, File4, File6, File8, File10 |
| `OddFolder` | File1, File3, File5, File7, File9 |

## Compétences travaillées

Créer des répertoires avec `New-Item`, naviguer avec `Set-Location`, déplacer avec `Move-Item` et contrôler avec `Get-ChildItem`.

## Pour reproduire

Utiliser des fichiers factices dans un dossier de laboratoire. Adapter les chemins du document de commandes à ce dossier ; vérifier chaque source et destination avant le déplacement.

**Vérifications :** dix fichiers au total, aucun doublon, numéros pairs dans `EvenFolder`, impairs dans `OddFolder`.

Les sorties conservées proviennent de l'exercice initial. Les commandes n'ont pas été exécutées dans un environnement Windows lors de la relecture de novembre 2026.

[Retour au portfolio](https://github.com/A2lyn33)
