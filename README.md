# @trutify/renovate-config

Renovate Config for Trutify

## Usage

### Non-JavaScript Projects

Add `renovate.json` with:

```json
{
  "extends": ["local>Trutify/renovate-config"]
}
```

### JavaScript Projects

In `package.json`, add:

```json
{
  "renovate": {
    "extends": ["local>Trutify/renovate-config"]
  }
}
```
