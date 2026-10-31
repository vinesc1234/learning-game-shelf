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

Then recommend two or three games from the shelf below that fit the dominant content type and the setting. Include one stretch pick they probably haven't tried, and consider an adaptation of a popular game people already know, since familiar rules mean less explaining. For each:
- Why it fits this specific content (point to actual pieces)
- How the pieces would become game parts (for example, "the 5 escalation steps become 5 locks")
- Build effort
- One way to keep it fresh
- Its reference game from the table, and what to borrow from it

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

This matches the Learning Game Shelf page in this repo (index.html), which has 106 formats. Every format names a reference game: "Inspired by" means the mechanic comes from that game, and "Feels like" means it is a good reference for pacing and feel. The shelf also lists how each plays, what to borrow from the reference game, build tips, twists, pitfalls, and links to real-world examples. Effort: 1 low, 2 medium, 3 high.

| Game | Reference game | Best content types | Settings | Effort |
|---|---|---|---|---|
| Trivia Race | Feels like Kahoot! | Facts, Big ideas | Video call, Room, Big event, Team meeting | 1 |
| Memory Match | Feels like Concentration (the card game) | Facts | Self-paced, Room | 1 |
| Bingo | Feels like Bingo | Facts, Habits, Tool skills | Big event, Video call, Community | 1 |
| Jeopardy Board | Feels like Jeopardy! | Facts, Big ideas | Video call, Room, Team meeting | 1 |
| Board Race | Feels like Mario Party | Facts, Big ideas, Tool skills | Self-paced, Room, Community | 2 |
| Escape Room | Feels like The Room (puzzle game series) | Steps, Finding problems, Tool skills | Self-paced, Video call | 3 |
| Sequence Sort | Feels like Cooking Mama | Steps | Self-paced, Video call, Room, Team meeting | 1 |
| Branching Scenario | Feels like Telltale's The Walking Dead | Judgment, Finding problems | Self-paced, Video call | 2 |
| Mystery | Feels like Return of the Obra Dinn | Finding problems, Judgment, Big ideas | Self-paced, Room, Community | 3 |
| Spot the Mistake | Feels like The Exit 8 | Finding problems, Judgment, Tool skills | All settings | 1 |
| Two Truths and a Lie | Feels like Two Truths and a Lie | Facts, Big ideas | Team meeting, Video call, Room, Community | 1 |
| Token Budget | Feels like Plants vs. Zombies | Tradeoffs, Judgment | Room, Video call, Team meeting | 1 |
| Triage Rush | Feels like Diner Dash | Tradeoffs, Steps, Judgment | Self-paced, Video call | 2 |
| Real-Tool Scavenger Hunt | Feels like Pokémon GO | Tool skills, Habits | Self-paced, Community, Video call | 1 |
| Quest Board | Feels like Destiny bounties | Habits, Tool skills | Community | 2 |
| Streak Challenge | Feels like Duolingo | Habits, Tool skills | Community, Self-paced | 1 |
| Role-Play Simulation | Feels like Mass Effect dialogue | Judgment, Tool skills | Self-paced, Video call | 2 |
| Prompt Golf | Feels like Code golf | Tool skills | Video call, Room, Community, Big event | 1 |
| Story Campaign | Feels like Dungeons & Dragons campaigns | Big ideas, Judgment, Habits | Community, Team meeting | 3 |
| Sort It | Feels like Unpacking | Big ideas, Facts, Judgment | Self-paced, Video call, Room, Team meeting | 1 |
| Lightning Drill | Feels like WarioWare | Facts, Tool skills | Team meeting, Video call | 1 |
| Build the Map | Feels like Pipe Mania | Big ideas, Steps | Room, Video call, Self-paced | 2 |
| Defend the Decision | Feels like Ace Attorney | Judgment, Tradeoffs | Room, Video call, Team meeting | 1 |
| Build Sprint | Feels like Game jams like Ludum Dare | Tool skills, Habits | Big event, Community, Room | 2 |
| Show-and-Tell Bounty | Feels like Monster Hunter quest board | Habits, Tool skills | Community, Video call | 1 |
| Feature Auction | Feels like Modern Art (board game) | Tradeoffs, Big ideas | Room, Video call, Big event | 1 |
| Find the Risk | Feels like Hidden Folks | Finding problems, Judgment | Self-paced, Video call, Big event | 1 |
| Relay | Feels like Moving Out | Steps | Room, Video call | 1 |
| Choose Your Path | Feels like Skyrim skill trees | Big ideas, Tool skills, Habits | Self-paced, Community | 2 |
| This or That | Feels like Would You Rather | Judgment, Tradeoffs | Team meeting, Community, Big event, Video call | 1 |
| Survey Says | Feels like Family Feud | Judgment, Facts, Big ideas | Room, Video call, Big event | 1 |
| Ball Toss Review | Feels like Hot Potato | Facts, Big ideas | Room, Video call, Team meeting | 1 |
| Snowball Fight | Feels like Snowball fight | Big ideas, Judgment | Room | 1 |
| Word Scramble & Hangman | Feels like Wheel of Fortune | Facts | Self-paced, Video call | 1 |
| Daily Puzzle | Feels like Wordle | Facts, Habits | Community | 2 |
| Press Your Luck | Feels like Can't Stop (board game) | Facts, Judgment | Self-paced, Video call | 2 |
| Arcade Runner | Feels like Subway Surfers | Facts | Self-paced | 2 |
| Daily Drip Quiz | Feels like Anki flashcards | Facts, Judgment, Steps | Self-paced, Community | 2 |
| Alternate Reality Game | Feels like I Love Bees (Halo 2's alternate reality game) | Big ideas, Judgment, Habits | Community, Big event | 3 |
| Crisis Simulation | Feels like Frostpunk | Judgment, Tradeoffs, Finding problems | Room, Video call | 2 |
| Tabletop Card Drill | Feels like Backdoors & Breaches | Finding problems, Steps, Judgment | Room, Video call | 2 |
| Risk Card Game | Feels like Elevation of Privilege | Finding problems, Big ideas | Room, Video call | 1 |
| Dungeon One-Shot | Feels like Zelda dungeons | Judgment, Big ideas | Self-paced, Video call, Room | 2 |
| Chat Escape Room | Feels like Zork | Tool skills, Steps | Community, Self-paced | 1 |
| House Cup | Feels like Splatfest in Splatoon | Habits, Tool skills | Community, Big event | 2 |
| Team Participation Challenge | Feels like Strava club challenges | Habits, Tool skills | Community | 1 |
| Promptathon | Feels like Super Mario Maker | Tool skills, Habits | Community, Big event | 2 |
| Best-Of Library Contest | Feels like Steam Workshop | Tool skills, Habits | Community | 1 |
| Learning Expo | Feels like Fortnite seasons | Tool skills, Habits, Big ideas | Video call, Big event, Community | 3 |
| Station Passport | Feels like Pokémon Stamp Rally | Tool skills, Facts, Big ideas | Big event, Room | 2 |
| People Bingo | Feels like Find Someone Who | Habits | Big event, Room, Video call | 1 |
| Bracket Tournament | Feels like March Madness brackets | Tradeoffs, Judgment | Community, Big event | 1 |
| Fantasy League | Feels like Fantasy football | Habits | Community | 2 |
| Virtual Journey | Feels like The Oregon Trail | Habits | Community, Self-paced | 2 |
| Software Practice Sim | Feels like PC Building Simulator | Tool skills, Steps | Self-paced | 3 |
| Business Simulation | Feels like RollerCoaster Tycoon | Big ideas, Tradeoffs | Room, Video call | 3 |
| Build It Challenge | Feels like Poly Bridge | Big ideas | Room, Big event | 1 |
| Brick Models | Feels like LEGO Serious Play | Big ideas, Judgment | Room | 2 |
| Blind Builder | Feels like Spaceteam | Steps, Big ideas | Room, Video call | 1 |
| Jigsaw Teach-Back | Feels like Hanabi | Big ideas, Steps | Room, Video call | 1 |
| Gallery Walk | Feels like The museum in Animal Crossing | Big ideas, Judgment | Room, Video call | 1 |
| Reverse Brainstorm | Feels like Untitled Goose Game | Finding problems, Judgment | Room, Video call, Team meeting | 1 |
| Ranking Challenge | Feels like Top Trumps | Tradeoffs, Judgment | Room, Video call, Team meeting | 1 |
| Roleplay Rumble | Feels like Street Fighter | Judgment | Room, Big event, Video call | 1 |
| Pitch Challenge | Feels like American Idol | Big ideas, Judgment | Community, Big event | 1 |
| Mash-Up Pitch | Feels like Snake Oil (party game) | Big ideas | Room, Big event, Video call | 1 |
| Capture the Flag | Feels like picoCTF | Tool skills, Finding problems | Big event, Community, Self-paced | 3 |
| Break the Bot | Feels like Gandalf by Lakera | Finding problems, Tool skills, Judgment | Big event, Community, Video call | 1 |
| AI or Not | Feels like Human or Not | Finding problems, Judgment | Video call, Big event, Team meeting, Room | 1 |
| Slow Reveal | Feels like Framed (daily movie game) | Facts, Big ideas | Video call, Team meeting, Room | 1 |
| Interactive Video | Feels like Black Mirror: Bandersnatch | Judgment, Steps | Self-paced | 2 |
| 360 Explore | Feels like Myst | Facts, Big ideas, Finding problems | Self-paced | 2 |
| Improv Scenes | Feels like Whose Line Is It Anyway? | Judgment | Room | 1 |
| Puzzle Inside the Tool | Feels like SQL Murder Mystery | Tool skills, Finding problems | Self-paced, Community | 2 |
| Hub World | Inspired by Super Mario 64 and other 3D platformers | Big ideas, Tool skills, Habits | Self-paced, Community | 2 |
| Clue Giver | Inspired by Codenames | Big ideas, Facts | Room, Video call, Big event | 1 |
| Scale Guess | Inspired by Wavelength | Judgment, Tradeoffs | Room, Video call, Team meeting | 1 |
| Explain It Without | Inspired by Taboo | Big ideas | Room, Video call, Team meeting | 1 |
| Draw the Concept | Inspired by Pictionary and charades | Big ideas, Facts | Room, Video call, Team meeting | 1 |
| Prompt Telephone | Inspired by Telephone and Gartic Phone | Tool skills, Big ideas | Video call, Room, Community | 1 |
| Hidden Saboteur | Inspired by Werewolf and Mafia | Finding problems, Judgment | Room, Video call | 1 |
| Imposter Tasks | Inspired by Among Us | Tool skills, Finding problems | Video call, Room | 2 |
| Co-op Outbreak | Inspired by Pandemic | Tradeoffs, Judgment, Big ideas | Room, Video call | 3 |
| Trade & Build | Inspired by Catan | Tradeoffs | Room | 2 |
| Route Builder | Inspired by Ticket to Ride | Steps, Big ideas | Room, Self-paced | 2 |
| Deduction Grid | Inspired by Clue | Finding problems | Room, Video call, Self-paced | 2 |
| Twenty Questions | Inspired by Guess Who | Finding problems, Big ideas | Video call, Team meeting, Room | 1 |
| Best Match Card | Inspired by Apples to Apples | Judgment, Big ideas | Room, Video call, Community | 1 |
| Question Tower | Inspired by Jenga | Facts, Big ideas | Room | 1 |
| Kitchen Chaos | Inspired by Overcooked | Steps, Tradeoffs | Room, Video call | 2 |
| Inspector Desk | Inspired by Papers, Please | Judgment, Finding problems, Steps | Self-paced, Video call | 2 |
| Swipe Decisions | Inspired by Reigns | Judgment, Tradeoffs | Self-paced, Community | 2 |
| Defuse Together | Inspired by Keep Talking and Nobody Explodes | Steps, Finding problems, Tool skills | Video call, Room | 2 |
| Habit Garden | Inspired by Animal Crossing and Stardew Valley | Habits | Community | 2 |
| Collect the Set | Inspired by Pokémon cards | Habits, Tool skills | Community, Big event | 2 |
| Where Is This? | Inspired by GeoGuessr | Tool skills, Facts | Video call, Team meeting, Community | 1 |
| Elimination Quiz | Inspired by HQ Trivia and battle royale games | Facts, Big ideas | Big event, Video call | 1 |
| Lifeline Ladder | Inspired by Who Wants to Be a Millionaire | Facts, Judgment | Big event, Video call, Room | 1 |
| Estimate It | Inspired by The Price Is Right | Facts, Tradeoffs | Team meeting, Video call, Big event | 1 |
| Pitch Tank | Inspired by Shark Tank | Tradeoffs, Big ideas | Big event, Room, Video call | 1 |
| Technical Challenge | Inspired by The Great British Bake Off | Tool skills, Steps | Video call, Big event, Community | 1 |
| Mystery Basket | Inspired by Chopped | Tool skills | Big event, Video call, Community | 1 |
| Speedrun | Inspired by Video game speedrunning | Tool skills, Steps | Community, Big event, Self-paced | 1 |
| Secret Helper | Inspired by Secret Santa | Habits | Community | 1 |
| Crowd Plays | Inspired by Twitch Plays | Judgment | Big event, Video call | 2 |
| Timeline | Inspired by Timeline card game | Facts, Steps | Room, Video call, Self-paced | 1 |

Thin spots on the shelf, where few formats fit: steps and processes in a 10-minute team meeting or at big events, habits in a 10-minute team meeting, and tradeoffs for self-paced play. If the content lands in one of these, say so, suggest adapting the closest format, and offer to add the new format to the shelf if it works.
