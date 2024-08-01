# Projet de visualisation de données - Les lieux de tournages à Paris depuis 2016
Ce projet a été réalisé par **Ruth**, **Fiona** et **Nathan** dans le cadre de notre formation à **Ada Tech School** à Nantes.

## Description du projet
Nous souhaitions représenter les différents lieux de tournage à Paris en 2016, de façon interactive. Nous avons donc utilisé la librairie [Leaflet](https://leafletjs.com/) pour intégrer une carte à notre application, et une [API publique de la ville de Paris](https://opendata.paris.fr/explore/dataset/lieux-de-tournage-a-paris/information/?disjunctive.type_tournage&disjunctive.nom_tournage&disjunctive.nom_realisateur&disjunctive.nom_producteur&disjunctive.ardt_lieu). Enfin, nous avons récupéré les données géographiques des lieux de tournages pour placer les marqueurs correspondant sur la carte.

### Technologies utilisées
- **HTML** : structure et lien entre les différents fichiers
- **CSS** : mise en forme des blocs, design
- **JavaScript** : fonctionnalités
- **JSON** : données récupérées par l'API
- **Leaflet** : librairie open-source de carte interactive

### Difficultés rencontrées et potentielles améliorations
- Intégration d'une liste déroulante avec auto-complétion : du fait que nous travaillions en JS natif, cet élément n'existe pas, et il a fallu l'implémenter en le créant intégralement. Cela a été fait sur la fin du projet, et pourrait être amélioré, notamment en ajoutant un scroll.
- Fournir d'avantages d'informations sur les oeuvres : intégrer le nombre de lieux de tournage par oeuvre, un  lien cliquable redirigeant vers une recherche google, ajouter des images aux pop-ups des marqueurs.

## Installation, lancement, et utilisation
#### En utilisant un terminal
1. Clonez ce repo sur votre machine, cela créera un dossier à l'endroit sélectionné
```
git clone https://github.com/nathanc8/dataviz_project_tournages_paris.git
```
2. Lancez le fichier index_amelio.html
3. Cherchez un film, en prenant en compte qu'il est possible qu'il ne soit pas présent dans les résultats.

#### Sans utiliser un terminal
1. Cliquez sur l'icône verte "code" et téléchargez le zip
2. Extrayez les fichiers à l'endroit voulu
3. Cherchez un film, en prenant en compte qu'il est possible qu'il ne soit pas présent dans les résultats.

## Contributeurs
- **Ruth** : [Profil GitHub](https://github.com/VicRuth)
- **Fiona** : [Profil GitHub](https://github.com/Aodhfaolan)
- **Nathan** : [Profil GitHub](https://github.com/nathanc8)
