<!-- ELUCENIA technical documentation · escore-twist · fr · no clinical/professional/rights approval -->

# Score TWIST (torsion testiculaire)

[conditions, sources et autorisations](https://elucenia.org/fr/outils/escore-twist)

## Mode d’emploi

Utilisez l’outil sur le portail ou ouvrez index.html via un serveur HTTP local. Sélectionnez la langue, remplissez les champs et lancez le calcul.

## Données d’entrée et unités

### Augmentation de volume (œdème) du testicule

`edema`

### Testicule dur

`duro`

### Réflexe crémastérien absent

`cremaster`

### Nausées ou vomissements

`nausea`

### Testicule ascensionné (haut dans la bourse)

`alto`

## Édition de la méthode

TWIST/Barbosa 2013 : 5 facteurs pondérés, total 0–7

## Formule documentée

2 points : œdème testiculaire ; testicule dur. 1 point : réflexe crémastérien absent ; nausées/vomissements ; testicule haut situé. Total de 0 à 7.

## Limites et population

Le TWIST 2013 a été initialement développé chez des enfants présentant un scrotum aigu, avec examen par un urologue et échographie chez les 338 patients de la cohorte prospective. Les seuils 2 et 5 ont aussi été évalués rétrospectivement ; les auteurs demandaient encore une validation prospective. Ces résultats ne garantissent pas l’absence de torsion chez une personne et ne remplacent pas l’évaluation urgente d’une possible urgence chirurgicale.

## Références

- [Barbosa JA et al. Development and initial validation of a scoring system to diagnose testicular torsion in children. J Urol, 2013.](https://doi.org/10.1016/j.juro.2012.10.056)

## Reproduire les tests techniques

Exécutez node test.cjs dans le répertoire racine de ce dépôt pour reproduire les cas synthétiques enregistrés. Les données d’entrée, les résultats attendus et les tolérances d’origine sont conservés. Les tests techniques ne constituent pas une validation clinique.

```sh
node test.cjs
```

tool.json contient les sources, l’édition et le périmètre de la revue. examples.json conserve les données d’entrée et les résultats attendus des cas synthétiques ; results.json consigne les résultats obtenus.

[Fiche et références](../tool.json) · [Code JavaScript](../calculator.js) · [Cas de référence](../examples.json) · [results.json](../results.json)

## Revue et conditions d’utilisation

Aucune révision clinique indépendante n’a été effectuée.

Cette interface est une traduction réalisée par nos soins, et non une édition officielle ou certifiée. La revue clinique indépendante, la révision linguistique professionnelle et l’autorisation des droits sur les instruments n’ont pas été réalisées.

Résultat de la formule ou de la classification. L’interprétation, la conduite et l’applicabilité dépendent de l’évaluation professionnelle et de la source sélectionnée.

## Licence et attribution

Apache-2.0 s’applique uniquement au code d’ELUCENIA. Les droits sur les instruments, publications, traductions et données restent ceux de leurs titulaires respectifs. Conservez LICENSE et NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Résultats documentés

Les informations ci-dessous conservent les sorties de la méthode pour des exemples synthétiques. Elles ne constituent pas une validation clinique indépendante.

### 1

Risque faible (0 à 2) : torsion improbable

Dans la dérivation, valeur prédictive négative de 100 % : l'échographie en urgence n'est pas nécessaire si le tableau clinique est concordant.


### 2

Risque intermédiaire (3 à 4)

Échographie Doppler en urgence, sans retarder l’exploration en cas de doute.


### 3

Risque élevé (5 à 7) : exploration chirurgicale immédiate

Lors de la dérivation, valeur prédictive positive de 100 % : ne retardez pas la chirurgie pour l’imagerie.


### 4

Risque élevé (5 à 7) : exploration chirurgicale immédiate

Lors de la dérivation, valeur prédictive positive de 100 % : ne retardez pas la chirurgie pour l’imagerie.

