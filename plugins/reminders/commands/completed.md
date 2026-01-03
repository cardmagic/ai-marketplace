---
description: Show recently completed reminders
allowed-tools: Bash(reminders:*)
argument-hint: [--list name]
---

# Completed Reminders

Show recently completed reminders.

## Instructions

1. **Check if reminders CLI is installed** - if `which reminders` fails, install it:

```bash
npm install -g @cardmagic/reminders
```

2. **Run the command**:

```bash
reminders completed $ARGUMENTS
```

3. If the user specifies a list, filter by it:
   - `--list "List Name"`

## Examples

User: `/reminders:completed`
-> `reminders completed`

User: `/reminders:completed --list Groceries`
-> `reminders completed --list "Groceries"`
