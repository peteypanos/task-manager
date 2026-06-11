# Task Manager

A single-page to-do list app built while learning Claude Code.

## File

- `index.html` — the only file; open it directly in any browser, no server needed.

## What it does

- Add tasks with an optional priority level (high, medium, low)
- Mark tasks complete via checkbox or by clicking the task text (strikethrough style)
- Edit tasks in place — click the task text to edit, save with Enter or by clicking away, cancel with Escape
- Delete tasks with the × button
- Filter tasks by All, Active, or Completed
- Shows a count of remaining (incomplete) tasks in the footer
- Persists all tasks to localStorage — survives page refresh and browser restarts

## Design

- White card on a light gray background, centered on the page
- Font: system sans-serif (`-apple-system`, `BlinkMacSystemFont`, `Segoe UI`)
- Priority shown as a colored dot: red (high), orange (medium), green (low), gray (none)
- Filter pills in the card header; active filter highlighted in black
- Inline edit replaces task label with a borderless input, underlined in black

## How to run

```
open index.html
```
