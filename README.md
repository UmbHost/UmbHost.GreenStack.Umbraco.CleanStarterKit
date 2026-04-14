# UmbHost.GreenStack.Umbraco.CleanStarterKit (v13)

A dotnet new template for Umbraco 13 LTS with Clean Starter Kit preconfigured for [GreenStack](https://umbhost.net/sustainable-cloud-hosting/modern-umbraco-hosting) hosting.

> This is the **v13 LTS** branch of the template. It targets Umbraco 13 (Long Term Support). For the latest Umbraco version, see the `main` branch.

## Installation

```bash
dotnet new install UmbHost.GreenStack.Umbraco.CleanStarterKit::13.*
```

## Usage

```bash
dotnet new greenstack-umbraco-cleanstarterkit -n MyProject
```

This creates a new Umbraco 13 LTS project with [Clean Starter Kit](https://marketplace.umbraco.com/package/clean) and:

- Forwarded headers middleware for Traefik proxy
- HTTPS runtime validator removed (SSL terminated by GreenStack)
- Data protection keys persisted to `/app/keys` in production
- Multi-stage Dockerfile exposing port 8080
- Docker launch profile (HTTP)

## Getting started

Follow the [Getting Started with Umbraco 17 on GreenStack](https://umbhost.net/gb/blog/2026/01/getting-started-with-umbraco-17-on-greenstack-with-github) guide (applies to v13 LTS with minor adjustments).

## Source

The template content comes from [GreenStack.Umbraco.CleanStarterKit-v13](https://github.com/UmbHost/GreenStack.Umbraco.CleanStarterKit-v13), which is also available as a GitHub template repository.

## GreenStack

- [Purchase GreenStack hosting](https://umbhost.net/sustainable-cloud-hosting/modern-umbraco-hosting)
- [GreenStack documentation](https://my.umbhost.net/knowledgebase/17/GreenStack)
- [GreenStack CI/CD samples](https://github.com/UmbHost/GreenStack.CICD.Samples)

## License

MIT
