# Lorelock-Online
https://discord.gg/fA3HFwTyfK

Lorelock Online is a persistent fantasy world simulation that runs inside Discord.

It is not a chatbot telling a story.

It is a shared world where thousands of autonomous characters live their lives, remember what happens, form relationships, spread information socially, and react to conditions that continue evolving even when players are offline.

Outcomes are not decided by dice.

They emerge from physical state, mental state, social context, environmental conditions, and what actually happens in the world.

What Lorelock Is

Lorelock Online is a persistent multi-agent world simulation with embodied characters and state-based outcome resolution.

When you log out:

NPCs continue their routines
factions gain or lose power
trade routes get attacked
alliances shift
buildings change ownership
information spreads through gossip
seasons advance
time passes

The world does not pause for players.

You are one character inside it.

Core Design Principles
1. Physics Over Dice

There are no random rolls.

Actions resolve based on conditions such as:

fatigue
injuries
balance
stress
visibility
terrain
equipment weight
social reputation
attention and focus
who is watching
how an NPC actually feels about you

Reality is the resolution system.

2. Persistent World Timeline

Lorelock runs continuously.

NPCs:

open shops
patrol districts
study
socialize
spread rumors
pursue goals

even when players are offline.

If you return weeks later:

weeks have passed in-world.

3. Autonomous NPC Cognition

NPCs are not scripted responders.

Each NPC has:

Big Five personality traits
knowledge limited by profession and experience
relationships with other NPCs
memory of past interactions
routines and schedules
reputation awareness
emotional state
goals independent of players

They do not exist to serve the player.

They exist inside the world.

4. Knowledge Propagation Is Local and Social

Information spreads through the population organically.

Example:

A merchant learns something
tells another merchant
a guard hears about it
a rumor becomes common knowledge

Different NPCs know different things.

There is no global knowledge state.

5. Embodied Characters

Characters are physical entities.

Each character includes:

14 core stats
92 derived substats
individual limb health
70+ continuous body states
inventory weight tracking
positioning and movement context
equipment slot system (34 slots)
reputation with factions
relationships with individuals
guild memberships
property ownership

Every condition contributes to outcomes.

6. Situations Evolve Without Players

Lorelock does not freeze scenarios waiting for interaction.

Example:

A player accepts a retrieval job

By the time they arrive:

the target object may be gone
damaged
moved
stolen
eaten
or replaced

The situation continues forward.

7. Quests Are Detected, Not Assigned

Lorelock does not rely on quest boards.

Instead:

situations become quests once they matter

Example:

A missing ledger is not a quest

until retrieving it affects someone

The world identifies significance dynamically.

8. Multiplayer Shared World

Lorelock is not single-player.

Players:

exist simultaneously
affect shared factions
influence economies
change political balance
trade items
form groups
compete
cooperate

One player’s actions affect everyone.

9. Persistent Consequences

Nothing resets.

NPCs remember:

promises
insults
help
betrayal

Factions remember:

loyalty
violence
support

Relationships change permanently.

If an NPC dies:

they stay dead.

Character Resolution Model

Lorelock resolves actions through layered state interaction rather than probability.

Example influences include:

Physical State

fatigue
injuries
balance
hunger
sickness
blood loss
stress

Mental State

focus
panic
confidence
perception
experience

Environmental Context

terrain
visibility
lighting
weather
obstacles
positioning

Social Context

reputation
relationships
faction standing
trust
authority

Outcome = interaction between these layers.

NPC Simulation Layer

NPCs are persistent agents with:

personality structure (Big Five)
knowledge scope filtering
memory continuity
schedules
goals
relationships
emotional states
faction alignment
gossip participation

They interact with:

each other
the world
players

without requiring player presence.

World Systems

Lorelock includes:

Persistent Geography
Calendar and Seasons
Faction Politics
Guild Hierarchies
Property Ownership
Dynamic Economy
Academies
Skill Growth Through Use
Emergent Quests
NPC Relationship Tracking
Information Propagation
Autonomous World Events

The world evolves continuously.

Example Emergent Situation

A player accepts a retrieval task.

They infiltrate a building.

Access the target location.

Find the objective already partially destroyed by something else in the world.

The system continues from the new situation instead of resetting the scenario.

This is normal behavior in Lorelock.

Why Discord?

Lorelock runs inside Discord intentionally.

Advantages:

no client install
persistent communication layer
shared narrative channel
private perspective channels
real-time multiplayer interaction
asynchronous play support

Players connect to a world instead of launching an instance.

Comparison With Other Approaches
System	      Memory	    NPC Autonomy	Persistence	Resolution
Chatbot RPGs	short-term	none	        session-based	narrative
AI Dungeon	  limited	    none	        sandbox	narrative
Tabletop	    manual	    DM-limited	  campaign-based	dice
Lorelock	    permanent	  agent-level	  world-level	state-based

Lorelock simulates a world.

It does not generate stories.

Stories emerge from interaction with the world.

Design Goal

Lorelock explores a question:

What happens if a fantasy RPG world continues existing whether players are present or not?

The answer is a system where:

situations evolve
characters remember
information spreads
factions shift
and consequences accumulate

before players even arrive.

Status

Lorelock Online is an active experimental world simulation project.

Development focuses on:

persistent agent cognition
state-driven resolution
emergent narrative structures
shared multiplayer persistence

Philosophy

Most RPG systems generate stories for players.

Lorelock generates a world.

Players live inside it.
