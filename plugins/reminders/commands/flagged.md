---
description: Show flagged reminders
allowed-tools: Bash(reminders:*)
argument-hint: [--list name]
---

# Flagged Reminders

Show all flagged reminders.

## Instructions

1. **Check if reminders CLI is installed** - if `which reminders` fails, install it:

```bash
npm install -g @cardmagic/reminders
```

2. **Run the command**:

```bash
reminders flagged $ARGUMENTS
```

3. If the user specifies a list, filter by it:
   - `--list "List Name"`

## Examples

User: `/reminders:flagged`
-> `reminders flagged`

User: `/reminders:flagged --list Work`
-> `reminders flagged --list "Work"`
