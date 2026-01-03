---
description: Fuzzy search through Apple Reminders
allowed-tools: Bash(reminders:*)
argument-hint: <query> [--list name] [--pending] [--completed]
---

# Search Reminders

Fuzzy search through Apple Reminders to find tasks and todos.

## Instructions

1. **Check if reminders CLI is installed** - if `which reminders` fails, install it:

```bash
npm install -g @cardmagic/reminders
```

2. **Run the search**:

```bash
reminders search "$ARGUMENTS"
```

3. If the user provides filters, apply them:
   - List filter: `--list "List Name"`
   - Pending only: `--pending`
   - Completed only: `--completed`

4. Present results clearly, showing:
   - The reminder title
   - Which list it's in
   - Due date if set
   - Priority and flagged status

## Examples

User: `/reminders:search milk`
-> `reminders search "milk"`

User: `/reminders:search meeting --list Work`
-> `reminders search "meeting" --list "Work"`

User: `/reminders:search groceries --pending`
-> `reminders search "groceries" --pending`
