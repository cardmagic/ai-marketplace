---
description: List all reminder lists with counts
allowed-tools: Bash(reminders:*)
---

# Reminder Lists

Show all reminder lists with their counts.

## Instructions

1. **Check if reminders CLI is installed** - if `which reminders` fails, install it:

```bash
npm install -g @cardmagic/reminders
```

2. **Run the command**:

```bash
reminders lists
```

3. Present the lists clearly showing:
   - List name
   - Number of pending reminders
   - Total reminders

## Examples

User: `/reminders:lists`
-> `reminders lists`
