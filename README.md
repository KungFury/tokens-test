# Design Tokens

Single source of truth for all client design tokens.

## Structure

```
mapped/
  mapped.json          ← all mapped token names + value per client
clients/
  sportradar/
    core.json          ← Sportradar core palette
  bethog/
    core.json          ← BetHog core palette
  aposta-ganha/
    core.json
  zenobet/
    core.json
  vinn/
    core.json
  betr9/
    core.json
```

## How values are stored in mapped.json

Each token has a value per client:
```json
{
  "mapped/color/text/primary": {
    "sportradar": "{core/color/neutral/1100}",
    "bethog": "{core/color/neutral/1100}",
    "aposta-ganha": "{core/color/neutral/1100}"
  }
}
```

## Managed by Token Manager Figma plugin

Do not edit these files manually. Use the Token Manager plugin.
