# Renovate Config

Shared [Renovate](https://docs.renovatebot.com/) configuration for automated dependency updates.

## Usage

Reference this config in your repository's `renovate.json`:

```json
{
  "$schema": "https://docs.renovatebot.com/renovate-schema.json",
  "extends": ["github>abtris/renovate-config"]
}
```

## Local Development

Validate the configuration locally:

```bash
make validate
```

## CI

The configuration is automatically validated on push and pull requests via GitHub Actions.

