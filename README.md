# Datagotchi Report Template

Ce modèle Quarto permet de créer des rapports au format PDF dans le style Datagotchi.

## Installation

Pour utiliser ce modèle, vous avez besoin de [Quarto](https://quarto.org/) installé sur votre système. Ensuite, utilisez la commande suivante :

```bash
quarto use template clessnverse/template_datagotchi_report
```

## Personnalisation du rapport

Le modèle inclut plusieurs champs personnalisables que vous pouvez modifier selon vos besoins :

### Dans l'en-tête YAML

- Dans la section `include-in-header` :
  - `\fancyhead[L]`: Texte d'en-tête gauche (par défaut `CLESSN`)
  - `\fancyhead[C]`: Texte d'en-tête central (par défaut `Rapport présenté à Léger`)
  - `\fancyhead[R]`: Texte d'en-tête droit (par défaut `Datagotchi USA 2024`)

### Dans la page de titre

- Titre principal: `{\titlepagefont\fontsize{48pt}{18pt}\selectfont \textbf{Datagotchi}}`
- Sous-titre: `{\titlepagefont\fontsize{32pt}{18pt}\selectfont \textbf{Rapport USA 2024}}`
- Logo: `\includegraphics[width=0.2\textwidth]{img/datagotchi.png}`
- Organisation: `{\titlepagefont\fontsize{32pt}{16pt}\selectfont \textbf{CLESSN}}`
- Destinataire du rapport: `{\titlepagefont\fontsize{24pt}{16pt}\selectfont \textbf{Léger Marketing}}`
- Département/Faculté: `{\titlepagefont\fontsize{16pt}{14pt}\selectfont Département de Science Politique\\Faculté des Sciences Sociales\\Université Laval}`
- Localisation: `{\titlepagefont\fontsize{16pt}{14pt}\selectfont Québec, Canada}`
- Copyright: `{\titlepagefont\fontsize{12pt}{12pt}\selectfont \copyright \thinspace CLESSN, \today}`

### Images

- Image d'arrière-plan de la page de titre: `\includegraphics[width=1\textwidth]{img/datagotchi_folks.png}` (dans la section `backgroundsetup`)
- Remplacez ou ajoutez des images dans le dossier `img/`

### Contenu

- Modifiez la section `# Description` et ajoutez d'autres sections selon vos besoins.
- Vous pouvez inclure des graphiques et des tableaux en utilisant la syntaxe Quarto/Markdown.

## Polices et styles

Le modèle utilise deux polices principales :
- `Roboto-Regular.ttf` pour le texte général
- `PixelOperatorSC.ttf` pour les titres et les en-têtes (style pixelisé Datagotchi)

Ces polices sont incluses dans le modèle.
