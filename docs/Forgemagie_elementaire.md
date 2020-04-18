---
title: Forgemagie élémentaire
has_children: true
nav_order: 2
---

# Forgemagie élémentaire

Il est possible de modifier l'élément de frappe d'une arme (épée, marteau, pelle, arc, bâton ou baguette) : Une ligne de dommages Neutre peut être transformée en une ligne de dommages d'un autre élément (Feu, Air, Eau ou Terre). Il s'agit de la seule direction de transformation possible, et cette transformation sur une arme est irréversible (hormis la pose d'un Orbe Régénérant, on y reviendra).

Le succès d'une modification d'élément de frappe va cependant baisser le nombre de dommages infligés par l'arme de manière pré-déterminée.

La modification de l'élément de frappe nécessite de modifier l'objet avec une potion spécifique. Il existe une potion par élément, et 3 qualités possibles, ce qui fait un total de 12 objets différents.

La qualité d'une potion décide quel pourcentage de dommages l'arme va conserver après le changement d'élément. Les trois qualités possibles sont 50%, 65% et 80%.

Le tableau suivant montre la potion particulière nécessaire à chaque type de changement d'élément :

|     | Terre                                                                                                 | Feu                                                                                                 | Eau                                                                                              | Air                                                                                                        |
|-----|-------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------|
| 50% | [Potion de Secousse](https://www.dofus.com/fr/mmorpg/encyclopedie/ressources/1338-potion-secousse)    | [Potion d'Étincelle](https://www.dofus.com/fr/mmorpg/encyclopedie/ressources/1333-potion-etincelle) | [Potion de Crachin](https://www.dofus.com/fr/mmorpg/encyclopedie/ressources/1335-potion-crachin) | [Potion de Courant d'Air](https://www.dofus.com/fr/mmorpg/encyclopedie/ressources/1337-potion-courant-air) |
| 68% | [Potion d'Eboulement](https://www.dofus.com/fr/mmorpg/encyclopedie/ressources/1340-potion-eboulement) | [Potion de Flambée](https://www.dofus.com/fr/mmorpg/encyclopedie/ressources/1343-potion-flambee)    | [Potion d'Averse](https://www.dofus.com/fr/mmorpg/encyclopedie/ressources/1341-potion-averse)    | [Potion de Rafale](https://www.dofus.com/fr/mmorpg/encyclopedie/ressources/1342-potion-rafale)             |
| 85% | [Potion de Séisme](https://www.dofus.com/fr/mmorpg/encyclopedie/ressources/1348-potion-seisme)        | [Potion d'Incendie](https://www.dofus.com/fr/mmorpg/encyclopedie/ressources/1345-potion-incendie)   | [Potion de Tsunami](https://www.dofus.com/fr/mmorpg/encyclopedie/ressources/1346-potion-tsunami) | [Potion d'Ouragan](https://www.dofus.com/fr/mmorpg/encyclopedie/ressources/1347-potion-ouragan)            |

Le passage d'une potion de modification d'élément de frappe modifie toutes les lignes de Dommages Neutre ainsi que les lignes de Vol de Vie Neutre d'un seul coup selon la même logique.

#### Exemple

Pour illustrer le mécanisme, imaginons que l'on possède une [Cruelle Pelle-Truelle](https://www.dofus.com/fr/mmorpg/encyclopedie/armes/1054-cruelle-pelle-truelle) dont on veut  modifier l'élément de frappe en Air. Nous avons pu nous procurer une [Potion d'Ouragan](https://www.dofus.com/fr/mmorpg/encyclopedie/ressources/1347-potion-ouragan) afin de conserver au maximum les dégâts de l'arme.

Pour savoir quels seront les dégâts finaux de l'arme en cas de Succès, on applique simplement le taux de la qualité de la potion au jet minimum et au jet maximum de chaque ligne de dégâts. Dans notre cas, il n'y a qu'une ligne. Le résultat en cas de succès est donc simple :

`6 à 10 (dommages Neutre)`

Dommages min : `6 * 0.85 = 5.1`. On arrondit toujours à l'inférieur, donc `5`.
Dommages max : `10 * 0.85 = 8.5`. On arrondit toujours à l'inférieur, donc `8`.
La potion est une potion d'Air, la ligne de dommages final sera donc :

`5 à 8 (dommages Air)`
