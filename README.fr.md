<p align="right">
  <a href="README.md"><img src="https://img.shields.io/badge/%F0%9F%8C%90%20Read%20in%20English-7A5AE0?style=for-the-badge" alt="Read in English"></a>
</p>

# Plugins Claude de RandomFab

Le catalogue de mes plugins pour Claude : l'app Claude (web et ordinateur), Cowork et [Claude Code](https://code.claude.com). L'ajouter n'installe rien : vous choisissez ensuite les plugins que vous voulez.

## Installation dans l'app Claude (abonnement Pro ou plus)

1. Ouvrez **Plug-ins** dans la barre de gauche, cliquez sur **Ajouter**, puis **Ajouter une marketplace**.
2. Saisissez `RandomFab/claude-plugins` et validez.
3. Choisissez un plugin dans la liste et cliquez sur **Installer**.

Activez **Synchroniser automatiquement** sur la marketplace pour recevoir les nouvelles versions tout seul. Un plugin installé ici arrive aussi dans Cowork, les tâches planifiées et Claude Code.

## Installation dans Claude Code

Ajoutez le catalogue une fois :

```text
/plugin marketplace add RandomFab/claude-plugins
```

Puis installez un plugin par son nom :

```text
/plugin install meal-planner@randomfab
```

Les mises à jour passent par le catalogue : lancez `/plugin marketplace update randomfab` pour obtenir les dernières versions.

## Plugins

| Plugin | Ce qu'il fait |
| --- | --- |
| [meal-planner](https://github.com/RandomFab/meal-planner) | Planifie les repas de votre foyer dans votre propre Notion : menu de la semaine, recettes depuis une photo ou un lien, liste de courses par magasin, brief du jour. |
## Licence

[MIT](LICENSE) © Fabien Bardouil
