# Learning Game Shelf

A catalog of 74 learning game formats, matched to the kind of content you have and where people will play. It comes with a Claude skill that helps you sort messy source material and pick a game that fits.

**Try it:** https://vinesc1234.github.io/learning-game-shelf/

## Why I made it

I build learning games at work, and the information people send me is usually a mix of slides, Slack threads, notes, and half-finished docs. I kept turning all of it into the same board game with a different map, and I could tell people were going to get bored.

The fix ended up being simple: the mechanic should come from the content. A process works as an escape room, judgment calls work as a branching story, facts work as a quiz race. Changing the map doesn't make it a new game. Changing the mechanic does.

## What's in here

- `index.html` is the shelf. Pick what the content mostly is (facts, steps, judgment calls, finding problems, tradeoffs, tool skills, big ideas, or habits) and where people will play (in the room, on a video call, self-paced, in Slack, at a big event, or in a 10-minute team meeting). It shows the games that fit, easiest to build first.
- Every game card has how it plays, build effort, group size, time, a tip for building it with Claude, a twist to keep it fresh, the most common way it goes wrong, and links to real examples where I found them.
- A fit grid shows how many formats fit each pairing, so you can see where the gaps are.
- "Mark as used" and "Hide games I've used recently" help you avoid repeating yourself. Those marks are saved in your own browser only.
- `skills/game-mapper/SKILL.md` is a Claude skill for the step before the shelf. You drop in everything you were given, and Claude walks through it with you: what's actually in there, what conflicts, what type of content each piece is, what the learning goals are, and which two or three games fit. It ends with a game brief and a prompt to start building.

## Using the skill

- **In the Claude app:** attach `SKILL.md` to a chat and ask Claude to save it as a skill.
- **In Claude Code:** copy the `game-mapper` folder into `.claude/skills/` in your project.

Then drop in your source material and say "let's map this."

## Where the formats came from

I started with about 30 formats I knew, then went looking for what other people are actually running: L&D blogs, game tool makers like H5P and ELB Learning, sales kickoff planners, security training card games on GitHub, and companies that gamified their AI rollouts (Microsoft, Netskope, Google Workspace customers, and a Salesforce partner). The full source list is at the bottom of the page.

## Known limits

- It's not truly exhaustive. Facilitation books like Gamestorming have 80+ more workshop techniques, though a lot of those are meeting methods more than games.
- Some pairings are thin. There aren't many formats for teaching step-by-step processes at big events or in Slack, or habits in a 10-minute meeting. If you've run something that works there, I'd love to hear about it.
- Ideas shared on Reddit and LinkedIn are underrepresented, since a lot of that is hard to search. Most sources are published articles.
- Group sizes and times are starting points, not rules.
