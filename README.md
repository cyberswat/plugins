# cyberswat's Claude Code Plugins

A marketplace of plugins for [Claude Code](https://claude.ai/code).

## Install

Add this marketplace to Claude Code:

```
/plugin marketplace add cyberswat/plugins
```

## Available Plugins

| Plugin | Description |
|--------|-------------|
| [projects](https://github.com/cyberswat/projects) | Multi-project management with context saving |

## Installing a Plugin

After adding the marketplace:

```
/plugin install projects@cyberswat
```

## Updating

**Option 1: Enable auto-update (recommended)**

1. Run `/plugin` to open the plugin manager
2. Go to **Marketplaces** tab
3. Select `cyberswat`
4. Enable auto-update

**Option 2: Manual update via CLI**

```bash
claude plugin update projects@cyberswat
```

**Option 3: Manual update via UI**

1. Run `/plugin`
2. Go to **Marketplaces** tab
3. Select `cyberswat` and update
