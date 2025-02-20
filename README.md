# Analyseur de label
Cet utilitaire permet de vérifier le contenu d'un paramètre `label` associé à une URL.

## Usage
1. Télécharger les deux fichiers: `config.json` et `label-analyzer.html`
2. Ouvrir le fichier html
3. Cliquer sur "Importer Configuration" et choisir le fichier config.json précédemment téléchargé
4. Insérer une URL à analyser

Les valeurs du label sont alors présentées sous la forme d'un tableau avec les différentes valeurs attendues. Il y a également la possibilité d'implémenter la validation de la valeur récupérée.

## Validation des valeurs extraites
La 3e colonne du tableau permet de recevoir une `regex` permettant de valider la valeur extraite de l'url. En cas de soucis avec ce concept, demandez à l'ami `chatgpt` ou `claude` (ou autres) de vous la réaliser en indiquant vos contraintes ou même de vous expliquer une règle existante. Cool non ?

## Sauvegarde
Quand vous modifiez les regex, vous pouvez exporter un nouveau fichier de configuration via le bouton "Exporter Configuration" au bas du tableau.

## Comment ajouter/modifier/supprimer un label ?
Simple ! 
Editez votre fichier `config.json` et modifiez le nom, le regex, voir même la liste (ordre, nouvel élément etc) des labels attendus. Une fois modifié, il ne vous reste plus qu'à l'importer dans la page html.

## Accès directe à l'outil
Si vous avez déjà votre fichier config, vous pouvez accéder directement à l'outil via ce lien :

https://aurelienkun.github.io/label-analyzer/label-analyzer.html