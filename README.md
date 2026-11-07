# Infinity War: a Multi-Agent Role-Play Game on Switch

An Avengers: Infinity War game run entirely by AI agents inside a
Discord room, built on Switch for the Flip the Switch hackathon
(Track 2: Personal or Creative Workflow).

## Demo
[Video link]

## What it does
Natasha is the narrator and game master. Thanos is a separate villain
agent with his own personality and memory. Friends play the heroes.
Natasha assigns roles, explains the scene, rolls dice, and tracks
Mind Stone Safety. When the heroes attack or insult Thanos, Natasha
hands off to him and he answers in his own voice.

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

## How the game works
(Short rules: Mind Stone Safety 10/10, dice table, how to end.)

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

## Credits
Built with Switch by SandboxAQ. Avengers is a Marvel property; this
is a fan project with no affiliation.