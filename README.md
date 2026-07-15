# My Espanso configuration

Public backup of my personal Espanso configuration.

## Structure

- `config/default.yml` — Espanso application settings.
- `match/*.yml` — snippets grouped by topic.
- `backup/base-before-split.yml` — original monolithic configuration before organization.

## Installation

Copy `config` and `match` into the Espanso configuration directory. On Windows, run `espanso path` to locate it.

Espanso watches the configuration directory and reloads changed files automatically.

## Synchronization

GitHub is used only for versioned backups. Device-to-device synchronization is handled separately with Syncthing.

## Safety

Do not commit passwords, tokens, API keys, private addresses, or `.env` files.
