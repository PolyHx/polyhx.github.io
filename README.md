Ceci est le repo pour le site web de formation de PolyAI

## Local setup du projet

1. Télécharger Git si ce n'est pas déjà fait [ici]()
2. Télécharer VSCode si ce n'est pas déjà fait [ici]()
3. Intaller Ruby [ici](https://www.ruby-lang.org/en/)
4. Installer Bundler [ici](https://bundler.io/)
5. Cloner le repos
6. Execute cette commande à la racine: `bundle install`

## Partir le projet localement
à la racine du projet, rouler cette commande: `bundle exec jekyll serve`
Ensuite, ouvrez par vous même cette page dans votre navigateur: `http://localhost:4000/`

Note: Pour voir vos changement, il faut rafraîchir votre page

## Petit détails

Pour modifier le look général du template, modifiez le html directement dans _layout/default.html

Pour modifier le contenu du site, modifiez les fichiers .md, les fichiers html sont générés à partir de ceux-ci!
Si c'est impossible de faire ce que vous voulez avec les règles de markdown, ça accepte le HTML aussi dans le fichier .md.
(*à utiliser seulement si pas le choix*)