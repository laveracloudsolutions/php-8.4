# php-8.4

> php-8.4 (apache) | php-runner (php + commons lib / config) | php-tools (php-runner + Dev Tools: node, composer, etc)

## Php 8.4

Docker Image Base Php Apache > Identique à la version Docker Hub

> [Liste des Tags disponibles](https://github.com/orgs/laveracloudsolutions/packages/container/package/php)

## Php Runner 8.4

Docker Image utilisé pour exécuter des applications de type PHP | PHP Runner: Base Php Apache + Commons Lib / Config (OpenTelemetry, etc)

> [Liste des Tags disponibles](https://github.com/orgs/laveracloudsolutions/packages/container/package/php-runner)

```bash
# Docker Build and Push
docker build -t ghcr.io/laveracloudsolutions/php-runner:8.4-apache-trixie .
docker push ghcr.io/laveracloudsolutions/php-runner:8.4-apache-trixie
```

## Php Tools 8.4

Docker Images de type PHP à destination des dev (avec utilitaires pour "devcontainer / sonarqube / etc") | PHP Tools: Base Php Runner + Dev Tools (NodeJS, Yarn, Composer, etc)

> [Liste des Tags disponibles](https://github.com/orgs/laveracloudsolutions/packages/container/package/php-tools)

```bash
# Docker Build and Push
docker build -t ghcr.io/laveracloudsolutions/php-tools:8.4-apache-trixie .
docker push ghcr.io/laveracloudsolutions/php-tools:8.4-apache-trixie
```

## Docker Image | GHCR.IO | Github Action

Plus d'infos sur les images de ce projet Github et sur son fonctionnement ?
___
> [Voir Wiki](https://dev.azure.com/petrolavera/ArchitectureApplicative/_wiki/wikis/Architecture%20applicative/340/Images-Docker-(-GitHub))
___