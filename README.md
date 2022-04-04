# bbsakura/renovate-config

[Renovate Shareable Config Presets](https://docs.renovatebot.com/config-presets/) for BBSakura Networks.

## Usage

```json
{
  "extends": [
    "github>bbsakura/renovate-config"
  ]
}
```

- If you want to change the target branch to `dev`.

```json
{
  "extends": [
    "github>bbsakura/renovate-config"
    "github>bbsakura/renovate-config:baseBranchDev"
  ]
}
```

## Settings

See the settings in [package.json](https://github.com/bbsakura/renovate-config/blob/master/package.json) and [Configuration Options](https://renovatebot.com/docs/configuration-options/) in Renovate Docs

## License

MIT License
