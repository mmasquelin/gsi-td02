# TD02

Un TD sur l'utilisation de GitLab avec Scrum

## Exercice 1

Le FizzBuzz est un type de test qui a été rendu populaire par [Imran Ghory](http://imranontech.com/2007/01/24/using-fizzbuzz-to-find-developers-who-grok-coding/) et ayant pour but de gagner du temps dans l’embauche de développeurs.

### Cahier des charges

Vous devez construire une fonction fizzBuzz qui transforme un entier en chaine de carractères selon des règles précises.

### Règles

 - Si le nombre est divisible par 3, on le remplace par Fizz
 - Si le nombre est divisible par 5, on le remplace par Buzz
 - Si le nombre est divisible par 3 et 5, alors on le remplace par FizzBuzz 
 - Dans tous les autres cas, on retourne le nombre sous forme de chaine de carractères.

### Exemple de sortie

```
1 => 1
2 => 2
3 => Fizz
4 => 4
5 => Buzz
6 => Fizz
15 => FizzBuzz
```

### Travail à faire

1. Proposer un schéma de l'application
2. Réaliser une application en Python (ou en Golang, PHP, etc.) qui réalise le traitement décrit pour des entiers allant de 1 à 100.

> Utilisez GitLab pour héberger votre production logicielle. Utilisez les principes des méthodes agiles : pensez à décomposez votre travail en "Issues" par exemple ...

## Exercice 2

On se propose d'implémenter une application capable d'aider à gérer les scores d'une partie de bowling.

### Règles du bowling

Le jeu se déroule en 10 tours.

A chaque tour, le joueur a 2 lancers pour faire tomber 10 quilles. Le score d'un tour est le nombre total de quilles renversées, plus des bonus pour les spare et les strike.

Un spare est quand le joueur renverse les 10 quilles en deux lancers lors d'un tour. Le bonus pour un spare est le nombre de quilles renversées par le prochain lancer.

Un strike est quand le joueur renverse les 10 quilles lors du premier lancer de son tour. Dans ce cas, son tour est terminé. Le bonus pour un strike est la valeur des deux prochains lancers.
                                                
Dans le dixième tour, un joueur qui réalise un spare ou un strike est autorisé à effectuer des lancers supplémentaires pour compléter le tour. Cependant, pas plus de trois lancer ne peuvent être effectués au dixième tour.
                                                            
La partie parfaite (que des strike) a un score total de 300 points.

### Objectifs

Ecrire une classe qui a deux méthodes :
 - `roll(...)` (qui prend en paramètre un entier) qui est appelé à chaque fois qu'un joueur effectue un lancer. L'argument est le nombre de quilles tombées à ce lancer.
 - `score()` retourne le score total de la partie.

### Informations supplémentaires

On considère que la méthode score ne sera appelée qu'à la fin de la partie. On considère également que le nombre de lancers effectués avant d'appeler la méthode `score` est toujours valide.

### Travail à faire

1. Proposer un schéma de l'application
2. Réaliser une application en Python (ou en Golang, PHP, etc.) qui réalise le traitement décrit.

> Utilisez GitLab pour héberger votre production logicielle. Utilisez les principes des méthodes agiles : pensez à décomposez votre travail en "Issues" par exemple ...


