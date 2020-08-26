# Template de départ pour un schéma générique

Ce dépôt contient les fichiers nécessaires pour démarrer la création d'un dépôt d'un schéma **générique** pour un référencement sur [schema.data.gouv.fr](https://schema.data.gouv.fr).

Un schéma **générique** est à utiliser seulement si votre schéma n'est pas dans un format supporté par schema.data.gouv.fr (TableSchema, XSD, JSONSchema... — voir [cette page de documentation pour une liste à jour](https://schema.data.gouv.fr/documentation/ajouter-un-schema#référencer-son-schéma)). Un schéma **générique** référencé sur schema.data.gouv.fr permet simplement de décrire votre schéma et éventuellement de pointer vers une documentation externe plus complète. Il n'y a pas de validation associée sur schema.data.gouv.fr.

## Utiliser ce template

- Si vous créez votre dépôt sur GitHub, il vous suffit d'appuyer sur le bouton vert "Use this template". Consultez [la documentation](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/creating-a-repository-from-a-template) pour plus d'infos ;
- Si votre projet sera hébergé ailleurs (par exemple Gitlab), vous pouvez cloner ce répertoire ou télécharger les fichiers correspondants. Utilisez le bouton "Clone or download".

## Fichiers disponibles

- [`LICENSE.md`](LICENSE.md) est le fichier de licence du dépôt. Nous recommandons d'utiliser la [Licence Ouverte](https://www.etalab.gouv.fr/licence-ouverte-open-licence), cette licence est recommandée par l'administration française pour le partage de données et de documents ;
- [`README.md`](README.md) est le fichier que vous lisez actuellement. À terme, il devra présenter votre schéma ;
- [`schema.yml`](schema.yml) est la description du schéma au format Yaml.

## Étapes à suivre

Nous détaillons ci-dessous les étapes que nous vous conseillons de suivre après avoir créé votre dépôt Git, tout en utilisant les fichiers d'exemples.

- [ ] Décrire votre schéma dans le fichier `schema.yml` en incluant au moins les clés suivantes : `title`, `description`, `homepage` et `version`. Le fichier d'exemple comprend des valeurs d'exemples pour toutes les métadonnées possibles
- [ ] Modifier le fichier [`README.md`](README.md), en supprimant tout son contenu tout d'abord. Au sein de plusieurs paragraphes, vous indiquerez le contexte, les modalités de production des données, le cadre juridique, la finalité, les cas d’usage etc. Consultez plusieurs schémas sur [schema.data.gouv.fr](https://schema.data.gouv.fr) pour découvrir quelles informations sont pertinentes à indiquer
- [ ] Vérifier que la licence ouverte vous convient. Si vous devez utiliser une autre licence, modifiez le fichier [`LICENSE.md`](LICENSE.md)

## Documentation

Pour vous aider dans la construction de votre dépôt, nous vous recommandons de vous référer à :

- [Le guide à destination des producteurs de schéma](https://guides.etalab.gouv.fr/producteurs-schemas/)
- [La documentation de schema.data.gouv.fr](https://schema.data.gouv.fr)
