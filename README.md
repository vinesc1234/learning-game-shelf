# Learning Game Shelf

A catalog of 101 learning game formats for technology companies, matched to the focus (learning a technology, learning sales, implementing technology, or implementing sales), the kind of content you have, and where people will play. It comes with a Claude skill that helps you sort messy source material and pick a game that fits.

**Try it:** https://vinesc1234.github.io/learning-game-shelf/

## Why I made it

I build learning games at work, and the information people send me is usually a mix of slides, Slack threads, notes, and half-finished docs. I kept turning all of it into the same board game with a different map, and I could tell people were going to get bored.

The fix ended up being simple: the mechanic should come from the content. A process works as an escape room, judgment calls work as a branching story, facts work as a quiz race. Changing the map doesn't make it a new game. Changing the mechanic does.

## What's in here

- `index.html` is a 3D library. All 101 games sit on carved wood bookcases as real 3D boxes with their own original cover art. Drag to look around, scroll to zoom, and click a box to pull it off the shelf and see how to run it. Click **Let's build a game** to describe what you're working with, then fill your game box one card at a time: goal, players, time, where, AI, and feel. Every card can be skipped, and anything skipped is worked out from your description. It suggests the best-matching games, highlights them on the shelves, and writes a starter prompt you can copy into Claude to build the one you pick. The list view gives every game its own old-style library checkout card, with stamps for time, players, focus, where to play, and build effort, plus a **Let's build!** button that jumps straight to a starter prompt for that game. There's also a reset button for the camera.
- Every game's details panel has an example for a technology company, how it plays, build effort, group size, time, a tip for building it with Claude, a twist to keep it fresh, the most common way it goes wrong, and links to real examples where I found them.
- Every format names a well-known game to use as a reference, with what to borrow from it. Many borrow their mechanic straight from a popular board, party, video, or TV game, like Codenames, Overcooked, or Super Mario 64. The rest list a game that feels right, like Diner Dash for a triage game or Wordle for a daily puzzle. Giving Claude a specific game to match gets much better results than describing a feel from scratch.
- The game names belong to their owners. Borrow the mechanic by describing how it plays, never by copying code, art, or assets, and give your version its own name and look.
- Games that could leave someone out, like timed or competitive ones, have notes on keeping them inclusive, like team scoring and a relaxed mode.
- "Mark as used" puts a USED sticker on a game's box so you can avoid repeating yourself. Those marks are saved in your own browser only.
- `skills/game-mapper/SKILL.md` is a Claude skill for the step before the shelf. You drop in everything you were given, and Claude walks through it with you: what's actually in there, what conflicts, what type of content each piece is, what the learning goals are, and which two or three games fit. It ends with a game brief and a prompt to start building.

## Using the skill

- **In the Claude app:** attach `SKILL.md` to a chat and ask Claude to save it as a skill.
- **In Claude Code:** copy the `game-mapper` folder into `.claude/skills/` in your project.

Then drop in your source material and say "let's map this."

## Where the formats came from

I started with about 30 formats I knew, then went looking for what other people are actually running: L&D blogs, game tool makers like H5P and ELB Learning, sales kickoff planners, security training card games on GitHub, and companies that gamified their AI rollouts (Microsoft, Netskope, Google Workspace customers, and a Salesforce partner). A second pass looked specifically for sales and tech team games, like negotiation classics, sales meeting games, and sales card games. A third pass added solo games people can enjoy on their own, like a daily word puzzle, a Connections-style sorting puzzle, a daily deal puzzle for practicing a sales method, and a pipe puzzle for learning how a product's systems connect. A fourth pass added games where players use AI to win, like teaching an AI buddy, climbing a ladder of AI buyers, and hunting for planted mistakes in an AI-written explainer, so people learn AI while they learn the product or the sales method. Each game links to the examples behind it.

## Known limits

- It's tuned for technology and sales learning. Generic icebreakers and team-building games, like spaghetti towers or people bingo, are left out on purpose, and so are games that look too much like the real job, like ticket queues or deal desks, since they feel like more work.
- It's not truly exhaustive. Facilitation books like Gamestorming have 80+ more workshop techniques, though a lot of those are meeting methods more than games.
- Some pairings are thin. There aren't many formats for teaching step-by-step processes at big events or in Slack, or habits in a 10-minute meeting. If you've run something that works there, I'd love to hear about it.
- Ideas shared on Reddit, YouTube, and LinkedIn are underrepresented, since a lot of that is hard to search from outside. Most sources are published articles and GitHub projects.
- Group sizes and times are starting points, not rules.
