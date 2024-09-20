# 🚀 starter-openapi

This repository contains a starting point for documenting an API with [OpenAPI](https://www.openapis.org) and displaying the documentation using [Framna Docs](https://github.com/shapehq/framna-docs).

## 📦 Contents of the repository

The repository contains the following files.

|File|Description|
|:-|:-|
|[openapi.yml](./openapi.yml)|An OpenAPI specification that documents the API.|
|[.framna-docs.yml](./.framna-docs.yml)|A configuration file that specifies the project name and icon to show on Framna Docs. For more information, see [the documentation of Framna Docs](https://github.com/shapehq/framna-docs/wiki/Adding-Documentation-to-Framna-Docs#customize-the-project).|
|[icon.png](./icon.png)|Thee icon displayed on Framna Docs.|
|[.spectral.yml](./.spectral.yml)| A configuration file for the open-source [Spectral](https://stoplight.io/open-source/spectral) linter that can be used to validate the OpenAPI specification in [openapi.yml](./openapi.yml).|
|[.github/workflows/lint.yml](./.github/workflows/lint.yml)| A workflow that lints the OpenAPI specification in pull requests using the [Spectral](https://stoplight.io/open-source/spectral) linter.|
