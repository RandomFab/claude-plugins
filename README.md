<p align="right">
  <a href="README.fr.md"><img src="https://img.shields.io/badge/%F0%9F%8C%90%20Lire%20en%20fran%C3%A7ais-7A5AE0?style=for-the-badge" alt="Lire en français"></a>
</p>

# Claude plugins by RandomFab

The catalogue of my plugins for Claude: the Claude app (web and desktop), Cowork and [Claude Code](https://code.claude.com). Adding it installs nothing: you then pick the plugins you want.

## Install in the Claude app

1. Open **Plugins** in the left sidebar, click **Add**, then **Add marketplace**.
2. Enter `RandomFab/claude-plugins` and confirm.
3. Pick a plugin in the list and click **Install**.

Turn on **Sync automatically** on the marketplace to get new versions by themselves. A plugin installed here also reaches Cowork, scheduled tasks and Claude Code.

## Install in Claude Code

Add the catalogue once:

```text
/plugin marketplace add RandomFab/claude-plugins
```

Then install a plugin by name:

```text
/plugin install meal-planner@randomfab
```

Updates come through the catalogue: run `/plugin marketplace update randomfab` to get the latest versions.

## Plugins

| Plugin | What it does |
| --- | --- |
| [meal-planner](https://github.com/RandomFab/meal-planner) | Plans your household's meals in your own Notion: weekly menu, recipes from a photo or a link, shopping list by store, daily brief. |
## License

[MIT](LICENSE) © Fabien Bardouil
