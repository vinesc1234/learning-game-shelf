---
name: game-mapper
description: Use when someone drops in raw, mixed-up information for a learning game and wants to work out together what's in it and which game format fits, step by step, ending in a game brief.
---

# Game Mapper

Learning designers get handed mismatched information: slide decks, Slack threads, notes, half-finished docs, conflicting versions. Often nobody knows what's really in it until it's laid out. This skill is a working session, not an automatic converter. Claude does the heavy reading and sorting; the designer makes the calls.

The goal is a game that fits the content, so you aren't rebuilding the same board game with a new map every time.

## How to run the session

- **One step at a time.** Finish a step, show the result, and wait for the designer before moving on. Never jump to a game recommendation before the content is mapped.
- **Plain language.** Short sentences. No jargon without a quick explanation.
- **The designer decides.** Claude proposes; they confirm, move, or override. When they change something, go with it.
- **Never invent content to fill a gap.** If something is missing or unclear, list it as a question for the subject matter expert.
- **Mismatched info gets shown, not fixed.** When two sources disagree, show both versions side by side and ask which is right or who would know.
- **Confidential stays private.** Work content stays in this session and the brief. Never suggest putting it anywhere public.

## Step 1: Take everything in

Accept whatever they drop in, in any form: pasted text, files, screenshots, slides, Slack threads, notes. Don't ask them to clean it up first. Read all of it before saying anything about it.

## Step 2: Show what's in here

Break the material into distinct pieces and list them, numbered, one line each, with where it came from (for example "slide 4" or "Priya's Slack note").

Then flag, in a short separate list:
- **Duplicates:** the same thing said in two places
- **Conflicts:** sources that disagree (show both versions)
- **Probably outdated:** dates, tool names, or steps that look old
- **Not really content:** logistics, opinions, or background that won't become game material

End by asking: "Anything missing, wrong, or that I misread?"

## Step 3: Get the context

Ask only what you don't already know, in one short message, at most four questions:
1. Who's playing? (roles, how familiar they are with the topic)
2. Where will they play? Use the settings list below.
3. How much time do they have?
4. After playing, what should people be able to do that they can't today?

## Step 4: Sort the content together

Propose a content type for each piece, using these eight types:

| Type | What it looks like |
|---|---|
| Facts & terms | Names, definitions, numbers people should recall |
| Steps & processes | Things done in a set order |
| Judgment calls | Situations where the right move depends on context |
| Finding problems | Spotting what's wrong, risky, or broken |
| Tradeoffs & priorities | Choosing between good options with limited time or resources |
| Hands-on tool skills | Doing something in a real tool |
| Big ideas & how things connect | Concepts, systems, why things work |
| Habits & behavior change | Things people should start doing regularly |

Show the sort as a table grouped by type. Mark any piece you're unsure about with a question mark and ask about those specifically. After they adjust, sum up the mix in one line, for example: "Mostly judgment calls, with some steps and a few terms."

If the mix is surprising, that's useful. Say so plainly, since it often shows the content is different from what the requester thought they were sending.

## Step 5: Name the learning goals

Turn the content into at most three goals, each written as "After playing, people can...". Check every piece against the goals. Suggest cutting pieces that don't support any goal, and let the designer decide.

## Step 6: Recommend games

First ask which formats they've used recently, so you can steer away from them.

Then recommend two or three games from the shelf below that fit the dominant content type and the setting. Include one stretch pick they probably haven't tried. For each:
- Why it fits this specific content (point to actual pieces)
- How the pieces would become game parts (for example, "the 5 escalation steps become 5 locks")
- Build effort
- One way to keep it fresh

Let them choose. If they want to combine two formats, help with that. If the content is mostly habits or tool skills for an ongoing community, remember the AI adoption formats that real companies have reported results with: House Cup, Team Participation Challenge, Promptathon, Learning Expo, and Best-Of Library Contest.

## Step 7: Write the game brief

Once they pick, write a short brief:
- **Title** (a working name)
- **Learning goals** (from Step 5)
- **Players, setting, and time**
- **Game format** and one sentence on how it plays
- **Content map:** a table of each content piece and the game part it becomes (card, lock, branch, clue, quest, round)
- **Gaps to fill before building:** open questions and conflicts, and who to ask
- **Keep it fresh:** the twist that makes this version feel new
- **First build prompt:** a ready-to-paste prompt for Claude (and Claude Design if there are visuals or 3D models) to start building

Ask if they want changes, then offer to start the build.

## Settings

- Room: live, in the room
- Video call: live, on a video call
- Self-paced: on their own
- Community: ongoing in Slack or a community
- Big event: 100+ people
- Team meeting: 10 minutes in a team meeting

## The game shelf

This matches the Learning Game Shelf page in this repo (index.html), which has 74 formats with how each plays, build tips, twists, pitfalls, and links to real-world examples. Effort: 1 low, 2 medium, 3 high.

| Game | Best content types | Settings | Effort |
|---|---|---|---|
| Trivia Race | Facts, Big ideas | Video call, Room, Big event, Team meeting | 1 |
| Memory Match | Facts | Self-paced, Room | 1 |
| Bingo | Facts, Habits, Tool skills | Big event, Video call, Community | 1 |
| Jeopardy Board | Facts, Big ideas | Video call, Room, Team meeting | 1 |
| Board Race | Facts, Big ideas, Tool skills | Self-paced, Room, Community | 2 |
| Escape Room | Steps, Finding problems, Tool skills | Self-paced, Video call | 3 |
| Sequence Sort | Steps | Self-paced, Video call, Room, Team meeting | 1 |
| Branching Scenario | Judgment, Finding problems | Self-paced, Video call | 2 |
| Mystery | Finding problems, Judgment, Big ideas | Self-paced, Room, Community | 3 |
| Spot the Mistake | Finding problems, Judgment, Tool skills | All settings | 1 |
| Two Truths and a Lie | Facts, Big ideas | Team meeting, Video call, Room, Community | 1 |
| Token Budget | Tradeoffs, Judgment | Room, Video call, Team meeting | 1 |
| Triage Rush | Tradeoffs, Steps, Judgment | Self-paced, Video call | 2 |
| Real-Tool Scavenger Hunt | Tool skills, Habits | Self-paced, Community, Video call | 1 |
| Quest Board | Habits, Tool skills | Community | 2 |
| Streak Challenge | Habits, Tool skills | Community, Self-paced | 1 |
| Role-Play Simulation | Judgment, Tool skills | Self-paced, Video call | 2 |
| Prompt Golf | Tool skills | Video call, Room, Community, Big event | 1 |
| Story Campaign | Big ideas, Judgment, Habits | Community, Team meeting | 3 |
| Sort It | Big ideas, Facts, Judgment | Self-paced, Video call, Room, Team meeting | 1 |
| Lightning Drill | Facts, Tool skills | Team meeting, Video call | 1 |
| Build the Map | Big ideas, Steps | Room, Video call, Self-paced | 2 |
| Defend the Decision | Judgment, Tradeoffs | Room, Video call, Team meeting | 1 |
| Build Sprint | Tool skills, Habits | Big event, Community, Room | 2 |
| Show-and-Tell Bounty | Habits, Tool skills | Community, Video call | 1 |
| Feature Auction | Tradeoffs, Big ideas | Room, Video call, Big event | 1 |
| Find the Risk | Finding problems, Judgment | Self-paced, Video call, Big event | 1 |
| Relay | Steps | Room, Video call | 1 |
| Choose Your Path | Big ideas, Tool skills, Habits | Self-paced, Community | 2 |
| This or That | Judgment, Tradeoffs | Team meeting, Community, Big event, Video call | 1 |
| Survey Says | Judgment, Facts, Big ideas | Room, Video call, Big event | 1 |
| Ball Toss Review | Facts, Big ideas | Room, Video call, Team meeting | 1 |
| Snowball Fight | Big ideas, Judgment | Room | 1 |
| Word Scramble & Hangman | Facts | Self-paced, Video call | 1 |
| Daily Puzzle | Facts, Habits | Community | 2 |
| Press Your Luck | Facts, Judgment | Self-paced, Video call | 2 |
| Arcade Runner | Facts | Self-paced | 2 |
| Daily Drip Quiz | Facts, Judgment, Steps | Self-paced, Community | 2 |
| Alternate Reality Game | Big ideas, Judgment, Habits | Community, Big event | 3 |
| Crisis Simulation | Judgment, Tradeoffs, Finding problems | Room, Video call | 2 |
| Tabletop Card Drill | Finding problems, Steps, Judgment | Room, Video call | 2 |
| Risk Card Game | Finding problems, Big ideas | Room, Video call | 1 |
| Dungeon One-Shot | Judgment, Big ideas | Self-paced, Video call, Room | 2 |
| Chat Escape Room | Tool skills, Steps | Community, Self-paced | 1 |
| House Cup | Habits, Tool skills | Community, Big event | 2 |
| Team Participation Challenge | Habits, Tool skills | Community | 1 |
| Promptathon | Tool skills, Habits | Community, Big event | 2 |
| Best-Of Library Contest | Tool skills, Habits | Community | 1 |
| Learning Expo | Tool skills, Habits, Big ideas | Video call, Big event, Community | 3 |
| Station Passport | Tool skills, Facts, Big ideas | Big event, Room | 2 |
| People Bingo | Habits | Big event, Room, Video call | 1 |
| Bracket Tournament | Tradeoffs, Judgment | Community, Big event | 1 |
| Fantasy League | Habits | Community | 2 |
| Virtual Journey | Habits | Community, Self-paced | 2 |
| Software Practice Sim | Tool skills, Steps | Self-paced | 3 |
| Business Simulation | Big ideas, Tradeoffs | Room, Video call | 3 |
| Build It Challenge | Big ideas | Room, Big event | 1 |
| Brick Models | Big ideas, Judgment | Room | 2 |
| Blind Builder | Steps, Big ideas | Room, Video call | 1 |
| Jigsaw Teach-Back | Big ideas, Steps | Room, Video call | 1 |
| Gallery Walk | Big ideas, Judgment | Room, Video call | 1 |
| Reverse Brainstorm | Finding problems, Judgment | Room, Video call, Team meeting | 1 |
| Ranking Challenge | Tradeoffs, Judgment | Room, Video call, Team meeting | 1 |
| Roleplay Rumble | Judgment | Room, Big event, Video call | 1 |
| Pitch Challenge | Big ideas, Judgment | Community, Big event | 1 |
| Mash-Up Pitch | Big ideas | Room, Big event, Video call | 1 |
| Capture the Flag | Tool skills, Finding problems | Big event, Community, Self-paced | 3 |
| Break the Bot | Finding problems, Tool skills, Judgment | Big event, Community, Video call | 1 |
| AI or Not | Finding problems, Judgment | Video call, Big event, Team meeting, Room | 1 |
| Slow Reveal | Facts, Big ideas | Video call, Team meeting, Room | 1 |
| Interactive Video | Judgment, Steps | Self-paced | 2 |
| 360 Explore | Facts, Big ideas, Finding problems | Self-paced | 2 |
| Improv Scenes | Judgment | Room | 1 |
| Puzzle Inside the Tool | Tool skills, Finding problems | Self-paced, Community | 2 |

Thin spots on the shelf, where few formats fit: steps and processes at big events or in communities, habits in a 10-minute team meeting, and tradeoffs for self-paced play. If the content lands in one of these, say so, suggest adapting the closest format, and offer to add the new format to the shelf if it works.
