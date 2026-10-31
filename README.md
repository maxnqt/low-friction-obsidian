# low-friction-obsidian
 
A deliberately small Obsidian vault.
 
## Layout
 
```
+/              anything you can't be bothered to place
daily/          daily notes
notes/          everything durable. FLAT. no subfolders.
projects/       one folder per active project; archive by deleting
templates/
assets/
tasks.md        the only task list
curiosities.md  things to learn (deliberately NOT tasks)
```
 
`notes/` is flat on purpose. Subfolders reintroduce a "where does this go?"
decision on every capture (stall risk). Retrieval comes from
search, links, and tags, which don't care about folders.
 
Name notes what you'd type when hunting for them later: `image charges.md`,
not `Physics/E&M/Ch3/methods.md`.
 
`+/` for anything "I don't know where this goes." Things leave it when you happen to touch them, not based on a schedule.
 
There's no `archive/`. You never open archives, so it's just a slower delete.
 
## Setup
 
1. Open the folder as a vault.
2. Core plugins: Daily Notes, Templates, Command Palette. Point Templates at `templates/`.
3. Hotkeys for Quick Switcher and Daily Note.
4. That's it. Don't install anything else yet.

Dataview isn't needed; Bases is core since 1.9. Tasks is worth adding *if* you
ever lose a task. Not before.
 
## Rules
 
1. One file for tasks. `tasks.md`, nowhere else. Work tickets stay in the work tracker.
2. Things you want to learn are not tasks. They are `curiosities(.md)`.
3. Before writing a note: will I go looking for this, and will I know what to search for?
   If either answer is no, don't write it.
4. Templates only exist where filling one in *does* something.

## Templates
 
- **Daily:** one thing, a log, tasks. The prompts are in the comments.
- **Debug question:** open when stuck for more than ~20 minutes. Writing it usually solves it;
  when it doesn't, you have something worth sending to a person.

## What's deliberately missing
 
No weekly review, no dashboard, no PARA, no MOCs, no numbering scheme, no spaced repetition, no book-note template. Each was considered and cut. Add any of them only after a specific failure makes you want it.
 
