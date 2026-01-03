---
description: Show reminders due soon
allowed-tools: Bash(reminders:*)
argument-hint: [--days N]
---

# Due Reminders

Show reminders due within a specified number of days.

## Instructions

1. **Check if reminders CLI is installed** - if `which reminders` fails, install it:

```bash
npm install -g @cardmagic/reminders
```

2. **Run the command**:

```bash
reminders due $ARGUMENTS
```

3. If the user specifies a timeframe:
   - `--days N` to look ahead N days (default: 7)

## Examples

User: `/reminders:due`
-> `reminders due`

User: `/reminders:due --days 3`
-> `reminders due --days 3`

User: `/reminders:due --days 14`
-> `reminders due --days 14`
