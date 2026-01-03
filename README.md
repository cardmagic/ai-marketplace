# AI Marketplace

Claude Code plugins by Lucas Carlson.

## Plugins

| Plugin | Description |
|--------|-------------|
| **reminders** | Search, create, and complete Apple Reminders |
| **notes** | Search and browse Apple Notes with fuzzy matching |
| **messages** | Fuzzy search Apple Messages/iMessage conversations |
| **classifier** | Text classification CLI using Bayesian, LSI, KNN, and more |

## Installation

```bash
# Add the marketplace
claude plugin marketplace add cardmagic/ai-marketplace

# Install individual plugins
claude plugin install reminders@cardmagic
claude plugin install notes@cardmagic
claude plugin install messages@cardmagic
claude plugin install classifier@cardmagic
```

## Development

Each plugin lives in its own repository:
- https://github.com/cardmagic/reminders
- https://github.com/cardmagic/notes
- https://github.com/cardmagic/messages
- https://github.com/cardmagic/classifier
