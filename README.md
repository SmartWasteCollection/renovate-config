# Renovate Config

Reusable *Renovate Bot* configurations. To use, add to your repo the file ```renovate.json``` with the following content:

```yaml
{
  "extends": [
    "github>SmartWasteCollection/renovate-config:<file-name>"
  ]
}
```

replacing ```<file-name>``` with the config file you want to inherit from. If you remove it, the ```default.json``` config file will be used.