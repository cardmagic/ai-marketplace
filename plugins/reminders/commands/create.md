---
description: Create a new reminder
allowed-tools: Bash(reminders:*)
argument-hint: <title> [--list name] [--due date] [--priority high|medium|low] [--flagged]
---

# Create Reminder

Create a new reminder with optional list, due date, and priority.

## Instructions

1. **Check if reminders CLI is installed** - if `which reminders` fails, install it:

```bash
npm install -g @cardmagic/reminders
```

2. **Run the command**:

```bash
reminders add "$ARGUMENTS"
```

3. Options:
   - `--list "List Name"` - specify which list (auto-detects if not provided)
   - `--due YYYY-MM-DD` or `--due tomorrow` - set due date
   - `--time HH:MM` - set due time
   - `--priority high|medium|low` - set priority
   - `--flagged` - mark as flagged
   - `--notes "Note text"` - add notes

4. The CLI auto-detects appropriate lists from content:
   - "Buy milk" → Groceries list
   - "Call mom" → Family list (if exists)

## Examples

User: `/reminders:create Buy eggs`
-> `reminders add "Buy eggs"`

User: `/reminders:create Review PR --list Work --due tomorrow`
-> `reminders add "Review PR" --list "Work" --due tomorrow`

User: `/reminders:create Doctor appointment --due 2024-01-15 --priority high`
-> `reminders add "Doctor appointment" --due 2024-01-15 --priority high`

User: `/reminders:create Urgent task --flagged --priority high`
-> `reminders add "Urgent task" --flagged --priority high`
