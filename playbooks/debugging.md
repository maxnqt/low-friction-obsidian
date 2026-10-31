---
type: playbook
---
 
# Debugging
 
> **Open this when:** I've been on the same bug for 20+ minutes, or I've started changing things to see what happens.
 
## Run it
 
1. **Say the bug out loud in one sentence.** "X happens when Y, I expected Z." If you can't, you don't have a bug, you have a vibe. Go get a reproduction first.
2. **Reproduce it on demand.** Smallest input, fewest steps. If it's intermittent, this step *is* the work - stop debugging and make it deterministic.
3. **Write down what you believe.** Three assumptions you're treating as true. The bug is almost always in one of them.
4. **Bisect.** Halve the search space with one observation. Git bisect, comment out half, log at the midpoint. Do not guess - halve.
5. **Check the boring things.** Wrong environment, stale build, cached value, wrong branch, wrong file open.
6. **Change one thing at a time.** Revert it if it didn't help. Shotgun edits turn one bug into three.
7. **Once fixed, explain the causal chain.** If you can't say why the fix works, it isn't fixed - it's hidden.

## Stop conditions
 
- 45 minutes with zero new information → walk away, take the walk, don't take the laptop
- Two hours total → ask someone, post the reproduction, or write it up and sleep on it
- "It works now and I don't know why" → this is a stop condition, not a finish line. Log it.

## What I keep getting wrong
 
- Starting to edit before I can reproduce
- Assuming my code is at fault when it's config, and assuming it's config when it's my code
- Not reading the whole error message, including the middle of the stack trace
- Debugging tired past 10pm, which reliably costs more time than it saves

## Evidence
 
- 

## Sources

- [[]]
