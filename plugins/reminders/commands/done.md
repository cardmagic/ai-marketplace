---
description: Mark a reminder as completed
allowed-tools: Bash(reminders:*)
argument-hint: <title> [--list name]
---

# Complete Reminder

Mark a reminder as completed using fuzzy matching.

## Instructions

1. **Check if reminders CLI is installed** - if `which reminders` fails, install it:

```bash
npm install -g @cardmagic/reminders
```

2. **Run the command**:

```bash
reminders done "$ARGUMENTS"
```

3. Options:
   - `--list "List Name"` - search in specific list (faster)

4. The command uses fuzzy matching, so partial titles work.

## Examples

User: `/reminders:done Buy milk`
-> `reminders done "Buy milk"`

User: `/reminders:done meeting notes --list Work`
-> `reminders done "meeting notes" --list "Work"`

User: `/reminders:done groceries`
-> `reminders done "groceries"`
