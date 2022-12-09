# Brief Kékés Voyages :airplane:

## Contexte du projet

> Notre client, une agence de voyages, souhaite proposer la possibilité de réserver en ligne des billets d'avion à leurs clients.

### Mission :

Concevoir à l'aide du standard UML la modélisation de la plateforme.

La plateforme devra permettre que :

- Un vol est ouvert à la réservation et refermé sur ordre de la compagnie.
- Un vol peut être annulé par la compagnie
- Un client peut réserver un ou plusieurs vols, pour des passagers différents.
- Une réservation concerne un seul vol et un seul passager.
- Une réservation peut être annulée ou confirmée.
- Un vol a un aéroport de départ et un aéroport d’arrivée.
- Un vol a un jour et une heure de départ, et un jour et une heure d’arrivée.
- Un vol peut comporter des escales dans des aéroports.
- Une escale a une heure d’arrivée et une heure de départ.
- Chaque aéroport dessert une ou plusieurs villes.
- Des compagnies aériennes proposent différents vols.

## Livrables

- [] Un MCD
- [] Un MLD
- [] Un MPD

- [] Un dictionnaire de données
- [] Des règles de gestion
- [] Un diagramme de cas d'utilisation
- [] Un diagramme de classe
- [] Un diagramme de Séquence

## Règle de gestion

#### Vol :

- Peut être réserver ou non par une compagnie.
- Il peut comporter des escales.
- Une compagnie peut annuler un vol.
- Contient un aéroport de départ, une date et une heure.
- Contient un aéroport d'arrivée, une date et une heure.
- Est un trajet d'un aéroport à un autre.

#### Client :

- Peut réserver un ou plusieurs vols.
- Peut réserver pour une autre personne.

#### Aéroport :

- Peut desservir une ou plusieurs villes.
- Appartient à une ville.

#### Ville :

- Peut avoir plusieurs aéroports.
- Se trouve dans un pays.

#### Escale :

- Contient une heure d'arrivée .
- Contient une heure de départ.
- Un aéroport de départ.
- Un aéroport d'arriver.

#### Réservation :

- Une compagnie peut annulée un vol.
- Une compagnie peut confirmer la réservation.
- Un client peut annulé une réservation.

#### Compagnie :

- Proposent plusieurs vols.
- Chaque compagnie propose s'est propre vol.

## Contributeur

[:bust_in_silhouette: @Kyllian](https://github.com/kyllianbou)
[:bust_in_silhouette: @Josué](https://github.com/Rowada)

## Ressources

- [uml-diagrams.org](https://www.uml-diagrams.org/uml-25-diagrams.html)
- [devdesignbook.tiankod.fr](https://www.devdesignbook.tiankod.fr/)
- [diagrams.net](https://app.diagrams.net/)
- [creately.com](https://creately.com/fr/home/)
- [Looping](https://www.looping-mcd.fr/)
