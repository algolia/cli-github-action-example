# [Algolia CLI](https://github.com/algolia/cli) + [Github Actions](https://github.com/features/actions)

This repository contains examples of how to use the Algolia CLI and the Github Actions together in order to control and operationalize your Algolia data (objects, synonyms, rules, indexes, etc.).

## How to use

The examples are located in the [.github/workflows](.github/workflows) directory.

## Available examples

### 1. Automatic backup and versionning of your Algolia data

By doing a regular versionned backup of your Algolia data, you can more easily track the changes, compare and even restore your settings, synonyms, rules, etc. to an earlier version if needed.

Examples:
- [Automatic backup of your Settings](.github/workflows/backup-settings.yml)
- [Automatic backup of your Rules](.github/workflows/backup-rules.yml)


### 2. Automatic Deployment of your Algolia data

In a context of multiple environments (development, production, etc.), you can more easily control, validate and deploy the changes to your Algolia data accross all your environments.

Examples:
- [Automatic Deployment of your Settings](.github/workflows/deploy-settings.yml)
