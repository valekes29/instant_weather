https://valekes29.github.io/instant_weather/

# Instant Weather

Instant Weather est une application web qui permet aux utilisateurs d'obtenir des informations météorologiques pour une commune de leur choix en utilisant un code postal.

## Socle technique

- **Langages** : JavaScript, HTML, CSS
- **Outil de développement** : Visual Studio Code
- **Versionnage** : Git et GitHub

## Objectifs

- Utiliser une API conformément à sa documentation.
- Manipuler le DOM pour intégrer dynamiquement du contenu dans une page HTML.
- Interagir avec la mise en forme de la page Web via JavaScript.

## Fonctionnalités

### Version de base (V1)

- Saisie d'un code postal pour sélectionner une commune.
- Affichage des informations météorologiques suivantes :
  - Température minimale
  - Température maximale
  - Probabilité de pluie
  - Nombre d'heures d'ensoleillement
- Page responsive et conforme aux validateurs HTML et CSS du W3C.
- Respect des exigences d'accessibilité de la norme WCAG AA 2.0.

### Version avancée (V2) 

- Choix du nombre de jours (de 1 à 7) pour les prévisions météorologiques.
- Affichage d'informations supplémentaires via des cases à cocher :
  - Latitude décimale de la commune
  - Longitude décimale de la commune
  - Cumul de pluie sur la journée en mm
  - Vent moyen à 10 mètres en km/h
  - Direction du vent en degrés (0 à 360°)
- Affichage des résultats dans des cartes (classe WeatherCard).

## API utilisées

- [API de découpage administratif par commune](https://geo.api.gouv.fr/decoupage-administratif/communes)
- [API météo de MétéoConcept](https://api.meteo-concept.com/)


