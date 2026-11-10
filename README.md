# Retours – Courses Du Coin

Ce dépôt recueille vos retours sur [Courses Du Coin](https://www.coursesducoin.fr), le calendrier des courses et randonnées cyclistes : les épreuves FFC et les randonnées FFVélo de toute la France, et les courses FSGT de Saône-et-Loire, de Rhône-Alpes et des Alpes-Maritimes.

## Comment participer

[Ouvrez un ticket](https://github.com/CoursesDuCoin/Retours/issues/new/choose) et choisissez le formulaire qui correspond :

| Formulaire | Pour… |
|---|---|
| 🐞 Signaler une erreur | une date, un lieu, une catégorie faux, une course annulée ou manquante |
| 🏆 Proposer un lien vers les résultats | des résultats publiés ailleurs (club, chronométreur, fédération) |
| 🗺️ Proposer un tracé | le parcours d'une course (OpenRunner, Strava, Komoot…) |
| 💡 Proposer une fonctionnalité | une idée pour améliorer le site |

Indiquez l'adresse de la page de la course quand c'est possible (par ex. `https://www.coursesducoin.fr/courses/…`) : c'est ce qui nous permet de retrouver la bonne épreuve.

## Ce qui se passe ensuite

1. Nous relisons chaque ticket.
2. Pour un tracé ou des résultats, un robot vérifie d’abord que le lien s’ouvre sans être connecté (`lien-vérifié`, sinon `à-corriger` avec une explication). Une fois relu et validé, le lien (résultats, tracé) est ajouté automatiquement sur la page de la course, puis le ticket est fermé avec un commentaire.
3. Une erreur est corrigée à la source quand c'est possible (les données viennent des calendriers des fédérations).

## Vie privée

- Les tickets sont **publics** : n'y mettez ni adresse e-mail, ni numéro de téléphone, ni information personnelle.
- Nous ne collectons aucune adresse e-mail. Un compte GitHub suffit pour ouvrir un ticket et suivre sa réponse.

## Étiquettes

| Étiquette | Sens |
|---|---|
| `erreur` | information fausse sur une course |
| `manquante` | course absente du calendrier |
| `tracé` | proposition de parcours |
| `résultats` | proposition de lien vers les résultats |
| `idée` | proposition de fonctionnalité |
| `site` | problème d'affichage ou de fonctionnement du site |
| `autre` | le reste |
| `lien-vérifié` | le robot a ouvert le lien sans être connecté (à relire) |
| `validé` | relu, prêt à être ajouté automatiquement |
| `refusé` | non retenu (raison en commentaire) |
| `édition-seule` | le tracé ne vaut que pour cette édition, pas les suivantes |
| `à-corriger` | l'ajout automatique a échoué, voir le commentaire |
