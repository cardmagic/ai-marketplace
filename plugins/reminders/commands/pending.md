---
description: Show pending (incomplete) reminders
allowed-tools: Bash(reminders:*)
argument-hint: [--list name]
---

# Pending Reminders

Show all pending (incomplete) reminders.

## Instructions

1. **Check if reminders CLI is installed** - if `which reminders` fails, install it:

```bash
npm install -g @cardmagic/reminders
```

2. **Run the command**:

```bash
reminders pending $ARGUMENTS
```

3. If the user specifies a list, filter by it:
   - `--list "List Name"`

## Examples

User: `/reminders:pending`
-> `reminders pending`

User: `/reminders:pending --list Work`
-> `reminders pending --list "Work"`
