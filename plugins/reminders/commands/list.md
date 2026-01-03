---
description: Show reminders in a specific list
allowed-tools: Bash(reminders:*)
argument-hint: <list-name> [--all]
---

# List Reminders

Show reminders in a specific list.

## Instructions

1. **Check if reminders CLI is installed** - if `which reminders` fails, install it:

```bash
npm install -g @cardmagic/reminders
```

2. **Run the command**:

```bash
reminders list "$ARGUMENTS"
```

3. Options:
   - `--all` to include completed reminders

## Examples

User: `/reminders:list Groceries`
-> `reminders list "Groceries"`

User: `/reminders:list Work --all`
-> `reminders list "Work" --all`

User: `/reminders:list "Shopping List"`
-> `reminders list "Shopping List"`
