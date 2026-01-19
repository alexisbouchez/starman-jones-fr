# Starman Jones - Traduction française

Traduction française du roman de science-fiction *Starman Jones* de Robert A. Heinlein (1953).

## À propos

*Starman Jones* raconte l'histoire de Max Jones, un jeune homme de la campagne américaine qui rêve de devenir astrogateur. Grâce à sa mémoire eidétique et à une série de circonstances extraordinaires, il se retrouve à bord du vaisseau spatial *Asgard* et doit faire face à des défis qui le mèneront bien au-delà de ce qu'il avait imaginé.

## Fichiers disponibles

- **PDF** : `starman-jones-fr.pdf`
- **EPUB** : `starman-jones-fr.epub`
- **Sources LaTeX** : `latex/`

## Traduction

Traduit de l'anglais (États-Unis) par [Alexis Bouchez](https://www.alexisbouchez.com).

## Compilation

Pour recompiler le PDF à partir des sources LaTeX :

```bash
cd latex
tectonic main.tex
```

Pour générer l'EPUB :

```bash
cd latex
pandoc main.tex -o ../starman-jones-fr.epub --metadata title="Starman Jones" --metadata author="Robert A. Heinlein" --metadata lang="fr" --toc
```

## Structure du projet

```
├── README.md
├── starman-jones-fr.pdf
├── starman-jones-fr.epub
└── latex/
    ├── main.tex
    └── chapters/
        ├── chapter01.tex  # Le Tomahawk
        ├── chapter02.tex  # Le bon Samaritain
        ├── chapter03.tex  # Terrport
        ├── chapter04.tex  # La Guilde des Astrogateurs
        ├── chapter05.tex  # Ton argent et mon savoir-faire
        ├── chapter06.tex  # L'homme de l'espace Jones
        ├── chapter07.tex  # Eldreth
        ├── chapter08.tex  # Doublure
        ├── chapter09.tex  # L'apprenti
        ├── chapter10.tex  # Le Trou aux Soucis
        ├── chapter11.tex  # Par la soute à cargaison
        ├── chapter12.tex  # Halcyon
        ├── chapter13.tex  # Transition
        ├── chapter14.tex  # N'importe où
        ├── chapter15.tex  # Ce n'est pas un pique-nique
        ├── chapter16.tex  # ...plus de cent ans...
        ├── chapter17.tex  # Charité
        ├── chapter18.tex  # Civilisation
        ├── chapter19.tex  # Un ami dans le besoin
        ├── chapter20.tex  # Un vaisseau n'est pas que de l'acier
        ├── chapter21.tex  # Le capitaine de l'Asgard
        └── chapter22.tex  # Le Tomahawk
```

## Licence

Le texte original de *Starman Jones* est sous copyright de Robert A. Heinlein (1953). Cette traduction est réalisée à des fins personnelles et éducatives.
