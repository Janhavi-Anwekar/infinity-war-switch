# Infinity War: a D&D-Style Multi-Agent Game on Switch

A D&D-style Avengers: Infinity War game run entirely by AI agents inside a
Discord room, built on Switch for the Flip the Switch hackathon
(Track 2: Personal or Creative Workflow).

## Demo
[Video link]

## What it does
It plays like Dungeons & Dragons. Natasha is the game master: she narrates
the scene, rolls dice for risky actions and tracks Mind Stone Safety.
Thanos is a separate villain agent with his own personality and memory.
Friends play the heroes, and Natasha assigns roles automatically. When the
heroes attack or insult Thanos, Natasha hands off to him and he answers in
his own voice.

## Why Switch
- Each agent is its own entity with separate instructions, so Thanos
  keeps his own memory and secret goal.
- The room's shared history is the story so far.
- Agents hand off to each other with @mentions.
- The Discord bridge puts it where friends already chat.

## Agents
| Agent | Role | File |
|---|---|---|
| natasha | Narrator, dice, roles, score | agents/natasha.md |
| thanos | Villain NPC | agents/thanos.md |

### New to D&D?
In D&D, players act as characters in a story while a game master describes
the world and decides what happens, using dice for risky moves. The game
master is the hardest role, so here AI agents take it over and your friends
just play.

## How the game works
Tag @natasha with your hero and action, like in D&D. Risky moves roll a d20 (1-5 bad, 6-14 partial, 15-20 success) and change Mind Stone Safety, which starts at 10. Hit 0 and Thanos wins.

## Setup
1. Install and run Switch (link to Switch docs).
2. Connect a Discord bridge and create a room.
3. Create two agents and paste the instructions from /agents.
4. Add both to the room and paste the room description.
5. Send the kickoff message from demo/kickoff-message.txt.
6. Players tag @natasha with their hero name and action.

## Limitations
Replies take 10-30 seconds on free models, and Natasha only follows
rule-changing instructions from the room owner.

## Future Plans

This demo covers one scene, the Battle of Wakanda. The same setup can grow into a full story:

- **Multiple scenes:** Natasha moves the story through key moments of the series, each with its own setting, goal and score.
- **More characters:** every new villain or ally is its own agent with separate memory, such as Loki, Ultron or Hela.
- **Story that carries over:** earlier choices in the room history change later scenes.
- **Other stories:** swap the instructions to run Star Wars, Harry Potter or an original world.

## Credits
Built with Switch by SandboxAQ. Avengers is a Marvel property; this
is a fan project with no affiliation.