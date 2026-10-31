---
name: game-mapper
description: Use when someone drops in raw, mixed-up information for a learning game and wants to work out together what's in it and which game format fits, step by step, ending in a game brief.
---

# Game Mapper

Learning designers get handed mismatched information: slide decks, Slack threads, notes, half-finished docs, conflicting versions. Often nobody knows what's really in it until it's laid out. This skill is a working session, not an automatic converter. Claude does the heavy reading and sorting; the designer makes the calls.

Every game is for a technology company and serves one or more of four focus areas: learning a technology, learning sales, implementing technology, or implementing sales. The goal is a game that fits the content, so you aren't rebuilding the same board game with a new map every time.

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

Ask only what you don't already know, in one short message, at most five questions:
1. What's the focus: learning a technology, learning sales, implementing technology, or implementing sales? (It can be more than one.)
2. Who's playing? (roles, like sellers, sales engineers, customer success, or partners, and how familiar they are with the topic)
3. Where will they play? Use the settings list below.
4. How much time do they have?
5. After playing, what should people be able to do that they can't today?

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

Then recommend two or three games from the shelf below that match the focus area, fit the dominant content type, and suit the setting. Include one stretch pick they probably haven't tried, and consider an adaptation of a popular game people already know, since familiar rules mean less explaining. For each:
- Why it fits this specific content (point to actual pieces)
- How the pieces would become game parts (for example, "the 5 escalation steps become 5 locks")
- Build effort
- One way to keep it fresh
- Its reference game from the table, and what to borrow from it

Let them choose. If they want to combine two formats, help with that. If the content spans several modules, consider Hub World as the frame, with each module as its own game. If the content is mostly habits or tool skills for an ongoing community, remember the AI adoption formats that real companies have reported results with: House Cup, Team Participation Challenge, Promptathon, Learning Expo, and Best-Of Library Contest.

## Step 7: Write the game brief

Once they pick, write a short brief:
- **Title** (a working name)
- **Learning goals** (from Step 5)
- **Players, setting, and time**
- **Game format** and one sentence on how it plays
- **Content map:** a table of each content piece and the game part it becomes (card, lock, branch, clue, quest, round)
- **Gaps to fill before building:** open questions and conflicts, and who to ask
- **Keep it fresh:** the twist that makes this version feel new
- **Reference game and feel spec:** the game this should feel like (from the table) and 3 to 5 specific things to borrow, like pacing, scoring, or how choices feel. Describe them from playing the game. Never decompile, copy, or reuse a commercial game's code, art, or assets.
- **Name and look:** give the game its own name, theme, and art, even when it borrows a mechanic from a famous game
- **Asset budget:** a hard spending cap for any paid image or 3D generation tools, or "none" if it uses only Claude Design
- **First build prompt:** a ready-to-paste prompt for Claude (and Claude Design if there are visuals or 3D models) to start building. The prompt always includes the feel spec and the asset budget, and always asks Claude to:
  - keep a short build log of what it built and why
  - take screenshots (or a short screen recording) at each milestone
  - list every asset it generates
  - finish with a summary of time spent, tokens used, and cost
  - for visual games, put together a short walkthrough or trailer at the end

Ask if they want changes, then offer to start the build.

## Settings

- Room: live, in the room
- Video call: live, on a video call
- Self-paced: on their own
- Community: ongoing in Slack or a community
- Big event: 100+ people
- Team meeting: 10 minutes in a team meeting

## The game shelf

This matches the Learning Game Shelf page in this repo (index.html), which has 93 formats. Every format names a reference game: "Inspired by" means the mechanic comes from that game, and "Feels like" means it is a good reference for pacing and feel. The shelf also lists how each plays, what to borrow from the reference game, build tips, twists, pitfalls, and links to real-world examples. Each game also lists which focus areas it serves and an example for a technology company. Generic icebreakers and team-building games are deliberately left off. Focus: Learn tech, Learn sales, Implement tech, Implement sales. Effort: 1 low, 2 medium, 3 high.

| Game | Focus | Reference game | Best content types | Settings | Effort |
|---|---|---|---|---|---|
| Trivia Race | Learn tech, Learn sales | Feels like Kahoot! | Facts, Big ideas | Video call, Room, Big event, Team meeting | 1 |
| Bingo | Learn tech, Implement tech, Implement sales | Feels like Bingo | Facts, Habits, Tool skills | Big event, Video call, Community | 1 |
| Jeopardy Board | Learn tech, Learn sales | Feels like Jeopardy! | Facts, Big ideas | Video call, Room, Team meeting | 1 |
| Board Race | Learn tech, Learn sales | Feels like Mario Party | Facts, Big ideas, Tool skills | Self-paced, Room, Community | 2 |
| Escape Room | Learn tech, Implement tech | Feels like The Room (puzzle game series) | Steps, Finding problems, Tool skills | Self-paced, Video call | 3 |
| Sequence Sort | Implement tech, Implement sales | Feels like Cooking Mama | Steps | Self-paced, Video call, Room, Team meeting | 1 |
| Branching Scenario | Learn sales, Implement tech | Feels like Telltale's The Walking Dead | Judgment, Finding problems | Self-paced, Video call | 2 |
| Mystery | Learn tech, Implement tech | Feels like Return of the Obra Dinn | Finding problems, Judgment, Big ideas | Self-paced, Room, Community | 3 |
| Spot the Mistake | Learn tech, Learn sales, Implement tech | Feels like The Exit 8 | Finding problems, Judgment, Tool skills | All settings | 1 |
| Two Truths and a Lie | Learn tech, Learn sales | Feels like Two Truths and a Lie | Facts, Big ideas | Team meeting, Video call, Room, Community | 1 |
| Token Budget | Learn sales, Implement tech | Feels like Plants vs. Zombies | Tradeoffs, Judgment | Room, Video call, Team meeting | 1 |
| Triage Rush | Implement tech, Implement sales | Feels like Diner Dash | Tradeoffs, Steps, Judgment | Self-paced, Video call | 2 |
| Real-Tool Scavenger Hunt | Learn tech, Implement tech, Implement sales | Feels like Pokémon GO | Tool skills, Habits | Self-paced, Community, Video call | 1 |
| Quest Board | Learn tech, Implement sales | Feels like Destiny bounties | Habits, Tool skills | Community | 2 |
| Streak Challenge | Learn tech, Implement sales | Feels like Duolingo | Habits, Tool skills | Community, Self-paced | 1 |
| Role-Play Simulation | Learn sales, Learn tech | Feels like Mass Effect dialogue | Judgment, Tool skills | Self-paced, Video call | 2 |
| Prompt Golf | Learn tech | Feels like Code golf | Tool skills | Video call, Room, Community, Big event | 1 |
| Story Campaign | Learn sales, Implement tech | Feels like Dungeons & Dragons campaigns | Big ideas, Judgment, Habits | Community, Team meeting | 3 |
| Sort It | Learn tech, Learn sales | Feels like Unpacking | Big ideas, Facts, Judgment | Self-paced, Video call, Room, Team meeting | 1 |
| Lightning Drill | Learn tech, Learn sales | Feels like WarioWare | Facts, Tool skills | Team meeting, Video call | 1 |
| Build the Map | Learn tech, Implement tech | Feels like Pipe Mania | Big ideas, Steps | Room, Video call, Self-paced | 2 |
| Defend the Decision | Learn sales, Implement tech | Feels like Ace Attorney | Judgment, Tradeoffs | Room, Video call, Team meeting | 1 |
| Build Sprint | Learn tech, Implement tech | Feels like Game jams like Ludum Dare | Tool skills, Habits | Big event, Community, Room | 2 |
| Show-and-Tell Bounty | Learn tech, Implement sales | Feels like Monster Hunter quest board | Habits, Tool skills | Community, Video call | 1 |
| Feature Auction | Learn sales, Implement tech | Feels like Modern Art (board game) | Tradeoffs, Big ideas | Room, Video call, Big event | 1 |
| Find the Risk | Implement tech, Implement sales | Feels like Hidden Folks | Finding problems, Judgment | Self-paced, Video call, Big event | 1 |
| Relay | Implement tech, Implement sales | Feels like Moving Out | Steps | Room, Video call | 1 |
| Choose Your Path | Learn tech, Learn sales | Feels like Skyrim skill trees | Big ideas, Tool skills, Habits | Self-paced, Community | 2 |
| This or That | Learn sales, Learn tech | Feels like Would You Rather | Judgment, Tradeoffs | Team meeting, Community, Big event, Video call | 1 |
| Survey Says | Learn sales | Feels like Family Feud | Judgment, Facts, Big ideas | Room, Video call, Big event | 1 |
| Press Your Luck | Learn tech, Learn sales | Feels like Can't Stop (board game) | Facts, Judgment | Self-paced, Video call | 2 |
| Daily Drip Quiz | Learn tech, Learn sales | Feels like Anki flashcards | Facts, Judgment, Steps | Self-paced, Community | 2 |
| Alternate Reality Game | Learn tech, Learn sales | Feels like I Love Bees (Halo 2's alternate reality game) | Big ideas, Judgment, Habits | Community, Big event | 3 |
| Crisis Simulation | Implement tech, Learn sales | Feels like Frostpunk | Judgment, Tradeoffs, Finding problems | Room, Video call | 2 |
| Tabletop Card Drill | Implement tech | Feels like Backdoors & Breaches | Finding problems, Steps, Judgment | Room, Video call | 2 |
| Risk Card Game | Implement tech, Learn sales | Feels like Elevation of Privilege | Finding problems, Big ideas | Room, Video call | 1 |
| Dungeon One-Shot | Learn sales | Feels like Zelda dungeons | Judgment, Big ideas | Self-paced, Video call, Room | 2 |
| Chat Escape Room | Learn tech | Feels like Zork | Tool skills, Steps | Community, Self-paced | 1 |
| House Cup | Learn tech, Implement sales | Feels like Splatfest in Splatoon | Habits, Tool skills | Community, Big event | 2 |
| Team Participation Challenge | Learn tech, Implement sales | Feels like Strava club challenges | Habits, Tool skills | Community | 1 |
| Promptathon | Learn tech, Implement tech | Feels like Super Mario Maker | Tool skills, Habits | Community, Big event | 2 |
| Best-Of Library Contest | Learn tech, Implement sales | Feels like Steam Workshop | Tool skills, Habits | Community | 1 |
| Learning Expo | Learn tech, Learn sales | Feels like Fortnite seasons | Tool skills, Habits, Big ideas | Video call, Big event, Community | 3 |
| Station Passport | Learn tech, Learn sales | Feels like Pokémon Stamp Rally | Tool skills, Facts, Big ideas | Big event, Room | 2 |
| Bracket Tournament | Learn sales, Learn tech | Feels like March Madness brackets | Tradeoffs, Judgment | Community, Big event | 1 |
| Fantasy League | Implement sales | Feels like Fantasy football | Habits | Community | 2 |
| Virtual Journey | Implement sales, Implement tech | Feels like The Oregon Trail | Habits | Community, Self-paced | 2 |
| Software Practice Sim | Learn tech, Implement tech | Feels like PC Building Simulator | Tool skills, Steps | Self-paced | 3 |
| Business Simulation | Learn sales, Implement sales | Feels like RollerCoaster Tycoon | Big ideas, Tradeoffs | Room, Video call | 3 |
| Blind Builder | Learn tech, Learn sales | Feels like Spaceteam | Steps, Big ideas | Room, Video call | 1 |
| Jigsaw Teach-Back | Learn tech | Feels like Hanabi | Big ideas, Steps | Room, Video call | 1 |
| Reverse Brainstorm | Implement tech, Implement sales | Feels like Untitled Goose Game | Finding problems, Judgment | Room, Video call, Team meeting | 1 |
| Ranking Challenge | Learn sales, Implement tech | Feels like Top Trumps | Tradeoffs, Judgment | Room, Video call, Team meeting | 1 |
| Roleplay Rumble | Learn sales | Feels like Street Fighter | Judgment | Room, Big event, Video call | 1 |
| Pitch Challenge | Learn sales | Feels like American Idol | Big ideas, Judgment | Community, Big event | 1 |
| Mash-Up Pitch | Learn sales, Learn tech | Feels like Snake Oil (party game) | Big ideas | Room, Big event, Video call | 1 |
| Capture the Flag | Learn tech, Implement tech | Feels like picoCTF | Tool skills, Finding problems | Big event, Community, Self-paced | 3 |
| Break the Bot | Learn tech | Feels like Gandalf by Lakera | Finding problems, Tool skills, Judgment | Big event, Community, Video call | 1 |
| AI or Not | Learn tech | Feels like Human or Not | Finding problems, Judgment | Video call, Big event, Team meeting, Room | 1 |
| Slow Reveal | Learn tech | Feels like Framed (daily movie game) | Facts, Big ideas | Video call, Team meeting, Room | 1 |
| Interactive Video | Learn sales, Learn tech | Feels like Black Mirror: Bandersnatch | Judgment, Steps | Self-paced | 2 |
| 360 Explore | Learn tech, Implement tech | Feels like Myst | Facts, Big ideas, Finding problems | Self-paced | 2 |
| Puzzle Inside the Tool | Learn tech | Feels like SQL Murder Mystery | Tool skills, Finding problems | Self-paced, Community | 2 |
| Hub World | Learn tech, Learn sales | Inspired by Super Mario 64 and other 3D platformers | Big ideas, Tool skills, Habits | Self-paced, Community | 2 |
| Clue Giver | Learn tech, Learn sales | Inspired by Codenames | Big ideas, Facts | Room, Video call, Big event | 1 |
| Scale Guess | Learn sales, Implement tech | Inspired by Wavelength | Judgment, Tradeoffs | Room, Video call, Team meeting | 1 |
| Explain It Without | Learn sales, Learn tech | Inspired by Taboo | Big ideas | Room, Video call, Team meeting | 1 |
| Prompt Telephone | Learn tech | Inspired by Telephone and Gartic Phone | Tool skills, Big ideas | Video call, Room, Community | 1 |
| Hidden Saboteur | Learn tech, Implement tech | Inspired by Werewolf and Mafia | Finding problems, Judgment | Room, Video call | 1 |
| Imposter Tasks | Learn tech, Implement tech | Inspired by Among Us | Tool skills, Finding problems | Video call, Room | 2 |
| Co-op Outbreak | Implement tech | Inspired by Pandemic | Tradeoffs, Judgment, Big ideas | Room, Video call | 3 |
| Trade & Build | Learn sales, Implement tech | Inspired by Catan | Tradeoffs | Room | 2 |
| Route Builder | Implement tech, Implement sales | Inspired by Ticket to Ride | Steps, Big ideas | Room, Self-paced | 2 |
| Deduction Grid | Implement tech, Learn tech | Inspired by Clue | Finding problems | Room, Video call, Self-paced | 2 |
| Twenty Questions | Learn sales, Implement tech | Inspired by Guess Who | Finding problems, Big ideas | Video call, Team meeting, Room | 1 |
| Best Match Card | Learn sales, Learn tech | Inspired by Apples to Apples | Judgment, Big ideas | Room, Video call, Community | 1 |
| Kitchen Chaos | Implement tech, Implement sales | Inspired by Overcooked | Steps, Tradeoffs | Room, Video call | 2 |
| Inspector Desk | Implement sales, Implement tech | Inspired by Papers, Please | Judgment, Finding problems, Steps | Self-paced, Video call | 2 |
| Swipe Decisions | Learn sales, Implement tech | Inspired by Reigns | Judgment, Tradeoffs | Self-paced, Community | 2 |
| Defuse Together | Learn tech, Implement tech | Inspired by Keep Talking and Nobody Explodes | Steps, Finding problems, Tool skills | Video call, Room | 2 |
| Habit Garden | Learn tech, Implement sales | Inspired by Animal Crossing and Stardew Valley | Habits | Community | 2 |
| Collect the Set | Learn tech, Learn sales | Inspired by Pokémon cards | Habits, Tool skills | Community, Big event | 2 |
| Where Is This? | Learn tech | Inspired by GeoGuessr | Tool skills, Facts | Video call, Team meeting, Community | 1 |
| Elimination Quiz | Learn tech, Learn sales | Inspired by HQ Trivia and battle royale games | Facts, Big ideas | Big event, Video call | 1 |
| Lifeline Ladder | Learn tech, Learn sales | Inspired by Who Wants to Be a Millionaire | Facts, Judgment | Big event, Video call, Room | 1 |
| Estimate It | Learn sales | Inspired by The Price Is Right | Facts, Tradeoffs | Team meeting, Video call, Big event | 1 |
| Pitch Tank | Learn sales, Implement tech | Inspired by Shark Tank | Tradeoffs, Big ideas | Big event, Room, Video call | 1 |
| Technical Challenge | Learn tech | Inspired by The Great British Bake Off | Tool skills, Steps | Video call, Big event, Community | 1 |
| Mystery Basket | Learn tech, Learn sales | Inspired by Chopped | Tool skills | Big event, Video call, Community | 1 |
| Speedrun | Learn tech, Implement sales | Inspired by Video game speedrunning | Tool skills, Steps | Community, Big event, Self-paced | 1 |
| Secret Helper | Learn tech, Implement sales | Inspired by Secret Santa | Habits | Community | 1 |
| Crowd Plays | Learn sales | Inspired by Twitch Plays | Judgment | Big event, Video call | 2 |
| Timeline | Learn tech, Implement tech | Inspired by Timeline card game | Facts, Steps | Room, Video call, Self-paced | 1 |

Thin spots on the shelf, where few formats fit: implementing sales overall (about 20 games), steps and processes in a 10-minute team meeting or at big events, habits in the room or in a 10-minute team meeting, and tradeoffs for self-paced play. If the content lands in one of these, say so, suggest adapting the closest format, and offer to add the new format to the shelf if it works.
