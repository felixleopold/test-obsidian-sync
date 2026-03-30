# Configuration Reference

All configuration options for AwesomeProject.

## Config File

AwesomeProject reads from `awesome.config.js` or `awesome.config.yaml` in the project root.

```yaml
outDir: ./dist
watch: false
plugins:
  - name: my-plugin
    options:
      verbose: true
```

## Options

| Key       | Type    | Default   | Description                          |
| --------- | ------- | --------- | ------------------------------------ |
| `outDir`  | string  | `./dist`  | Output directory for build artifacts |
| `watch`   | boolean | `false`   | Enable file watching                 |
| `plugins` | array   | `[]`      | List of plugins to load              |
| `verbose` | boolean | `false`   | Enable verbose logging               |

## Environment Variables

| Variable            | Description                 |
| ------------------- | --------------------------- |
| `AWESOME_TOKEN`     | API token for cloud sync    |
| `AWESOME_LOG_LEVEL` | Log level (`info`, `debug`) |
