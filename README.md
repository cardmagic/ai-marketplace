# cardmagic Claude Code Marketplace

A unified marketplace for Apple ecosystem Claude Code plugins.

## Plugins

| Plugin | Description |
|--------|-------------|
| **reminders** | Search, create, and complete Apple Reminders |
| **notes** | Search and browse Apple Notes with fuzzy matching |
| **messages** | Fuzzy search Apple Messages/iMessage conversations |

## Installation

```bash
# Add the marketplace
claude plugin marketplace add cardmagic/cardmagic-marketplace

# Install individual plugins
claude plugin install reminders@cardmagic
claude plugin install notes@cardmagic
claude plugin install messages@cardmagic
```

## Development

Each plugin lives in its own repository:
- https://github.com/cardmagic/reminders
- https://github.com/cardmagic/notes
- https://github.com/cardmagic/messages
