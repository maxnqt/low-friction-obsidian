# low-friction-obsidian

An Obsidian vault that's built for ADHD. If you're after dashboards, spaced repetition or a weekly review, this isn't it.

## Layout

```
+/                              anything you can't be bothered to place
daily/                       daily notes
notes/                     everything durable. FLAT. no subfolders.
projects/               one folder per active project; archive by deleting
templates/
assets/
tasks.md               the only task list
curiosities.md    things to learn (deliberately NOT tasks)
```

## Use

1. **One file for tasks.** `tasks.md`, nowhere else. Work tickets stay in the work tracker. Keep the same task in two places and you'll trust neither.
2. **Things you want to learn are not tasks.** They go in `curiosities.md`, with no guilt attached. Put "learn electrical engineering" on a task list and you've added something that will never be checked off, which is how a list stops being believable.
3. **Before writing a note, ask:** will I go looking for this, and will I know what to search for? If either answer is no, don't write it.
4. **Name notes what you'd type when searching for them.** `image charges.md`, not `physics/E&M/ch3/methods.md`.

### When you drop it

You will. When you come back, don't read the backlog and don't try to catch up. Open `tasks.md`, delete what you no longer care about, write today's note.

## Setup

1. Open the folder as a vault.
2. Core plugins: Daily Notes, Templates, Command Palette. Point Templates at `templates/`.
3. Settings, then Files and Links, then set the attachment folder to `assets/`. Otherwise images land in the vault root.
4. Hotkeys for Quick Switcher and Daily Note.
5. Stop there. Don't install anything else yet.

## Templates

**daily** - one thing, a log, tasks. The prompts live in HTML comments.

**debug question** - open it when you've been stuck more than about 20 minutes. Write it as if you're posting publicly: what you did, what you expected, what you got, what you've ruled out. Usually you solve it before you finish. When you don't, you've got something worth sending to a person instead of "got a sec?"

Only two, because a template is worth having when filling it in makes you do something you'd otherwise skip. Prose notes don't need a shape.

## How to take notes, by situation

The default is: don't. Most notes are a waste and that's fine. The ones worth writing are the ones where writing *is* the work, or where you know you'll come looking and won't remember.

**Reading a book.** One bullet per idea, phrased as a claim in your own words: "bugs cluster in recently changed code", not "on bug distribution". If you're transcribing, close the book first. The filter: does this change something I do, or contradict something I believe? If neither, skip it. Three takeaways from a good book is a lot. Zero is a legitimate outcome.

**Studying a book with problems.** Different job. Problems get worked on paper: markdown is a terrible place to do physics. What goes in the vault is the error log: the problem you couldn't start, what you tried, what was actually needed, and the tell - the surface feature that should have pointed you at the rightmethod. Collecting tells is the skill. Mix in problems from three or four sections back rather than grinding one chapter; it feels worse and works better.

**Learning a skill you keep coming back to.** Debugging, problem-solving, writing. These fail as essays because you never open them. Write the trigger first - the felt symptom that should make you look, like "stuck on the same error for 20 minutes" - then a short menu of moves under it. A menu, not an algorithm; the point is retrieval at the moment you're stuck, not obedience. `templates/debug.md` is an example.

**Projects.** The note holds current state, not history. Rewrite it, don't append to it - the log belongs in your dailies, the commit history in git. Keep one next action filled in at all times, small enough to be embarrassing. Record decisions with dates and dead ends you shouldn't retry. If there's a repo, the split is: anything a collaborator would need goes there, anything only you need stays here. Never both.

**Everything else.** Title it what you'd type when hunting for it. Write the claim, link the source, stop.

## Design notes

**Why `notes/` is flat.** Subfolders put a "where does this go?" decision in front of every capture, and that's where capture stalls. Search and links do the retrieving, and they don't care about folders. Tags are fine, since a note can carry several and you're not forced to pick one. The rule is that a tag has to be something you'd actually type into search. If you never have, delete it.

**Why `+/` exists.** So that "I don't know where this goes" has an answer other than stopping. It can hold three hundred files. Things leave when you happen to touch them, never on a schedule.

**Why there's no `archive/`.** Nobody opens archives. It's a slower delete.

**What's missing on purpose.** No weekly review, no dashboard, no PARA, no MOCs, no Johnny Decimal, no spaced repetition, no book-note template. All cut for the same reason: each one assumes you keep showing up. A weekly review assumes a weekly you. A dashboard assumes a backlog small enough to look at. Anything that degrades while you're gone makes coming back expensive, and coming back is the part that has to stay cheap.

Add any of them later, once something specific goes wrong and you want it. Not in advance.

**Ceiling.** This is a scaffold, aimed directly at time management and organization in adults with ADHD show small effects on work outcomes even when clinicians run them, and a folder layout sits well below that. If the real problem is following through, the lever is somewhere else.

## License

MIT
