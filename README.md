<!-- НАЧАЛО МЕТКИ ЗЕРКАЛА (управляется workflow, не редактируй) -->
# NeoForge — зеркало официальной документации

> Это **зеркало** (fork) официального репозитория
> [`neoforged/Documentation`](https://github.com/neoforged/Documentation).
> Контент подтягивается автоматически — GitHub Actions синхронизирует его
> с оригиналом ежедневно.

Официальная документация NeoForged: ModDevGradle, структурирование мода, регистрации, ресурсы, миграционные primers между версиями.

| | |
|---|---|
| Оригинал | <https://github.com/neoforged/Documentation> |
| Сайт документации | <https://docs.neoforged.net> |
| Ветка | `main` |
| Последняя синхронизация | **2026-10-09** |

## Связанные репозитории

- Собственный справочник по моддингу (живые версии, матрица совместимости,
  миграция на 26.x): [`ssr33242/modding-docs`](https://github.com/ssr33242/modding-docs)
- Fabric: [`ssr33242/fabric-docs`](https://github.com/ssr33242/fabric-docs)
- Forge: [`ssr33242/forge-docs`](https://github.com/ssr33242/forge-docs)

---

<!-- КОНЕЦ МЕТКИ ЗЕРКАЛА. Ниже — оригинальный README без изменений. -->

# NeoForged Documentation

This repository is used to store documentation on NeoForge, the Minecraft modding API. It also contains documentation on NeoGradle, a Gradle plugin for developing NeoForge and mods using NeoForge.

The documentation is built using [Docusaurus 3](https://docusaurus.io)

## Contributing

You can read the [contribution guidelines on the docs](https://docs.neoforged.net/contributing/).

If you wish to contribute to the documentation, fork and clone this repository.

The documentation uses Node.js 18. This can either be installed manually or using a version manager that supports `.node-version` or `.nvmrc`. For most version managers, the `install` and/or `use` command can be used to setup the correct Node.js version.

For example:

```bash
nvm install # or 'nvs use'
```

You can run the following commands if you wish to preview the documentation website locally through the live development server. Most changes are reflected live without having to restart the server.

```bash
npm install
npm run start
```

### Building

If you wish to build a static version of the documentation which can be deployed, you can run the following command:

```bash
npm run build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.
