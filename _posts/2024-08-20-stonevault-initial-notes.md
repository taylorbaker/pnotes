---
title: "Stonevault Initial Notes"
layout: post
date: 2024-08-20
headerImage: false
tag:
- The War Within
- Mythic+
category: blog
author: phunkp
description: Instance overview of the Stonevault for the first season of the War Within
---

vods:

- [The Bible ](https://youtu.be/2E01CFf2hag?si=uA3B7Z6Txs92F_Ef) (Quazzi Masterclass)
- [Phunk's blind run](https://youtu.be/oOU14wLwoRM?si=Di7HvW2y4-RDxGkq) (SV+0)

Decurses are a premium (stoneform ftw).

# EDNA Trash

Clear trash until double Earth Infused Golem pull (in central open space) spawns EDNA. Suggest taking the Golem-Loaderbot-Voidsoul pulls separately for a time.

mobs:

- Cursedheart Invader (ID 212389)
  - Arcing Void - *low-priority interrupt, spread 6+ yds to prevent dmg chain* (difficult in tight hallway and with Earth Infused Golem frontals)
  - Void Infection - *stacking dot, dispellable (decurse)*
- Earth Infused Golem (ID 210109)
  - Seismic Wave - *dodge frontal*
  - Ground Pound - *aoe pulsing dmg applying slow and stacking nature dmg dot* when multiple Golems are pulled
- Ghastly Voidsoul (ID 212453)
  - Howling Fear - ***mandatory interrupt*** group fear if goes off
- Repurposed Loaderbot (ID 222923)
  - Pulverizing Pounce - *don't stand in poop*

ui includes:

- Void Infection stacks
- Ground Pound stacks

# EDNA

Boss alternates spawning Volatile Spikes on players and targeting all with beams. Overlapping beam dmg applies additively; don't point arrows at your friends! Arrows will also destroy any Spikes in line. You do not want to break all Spikes at once!

Each time a Spike is broken, a stacking dot is applied to the group. Any spikes not manually cleared will be detonated with Earth Shatterer, acting as the counter-balance mechanic to consider when deciding how many Volatile Spikes to clear earlier in the phase. Boss then spawns another set of Volatile Spikes, continuing ad nosium.

Through this, the primary tankbuster Seismic Smash will be leaving a dispellable dot on the tank that ***should be healed through** until within 6 seconds of the next Seismic Smash*. Dispelling Seismic Reverberation triggers a 50% DR on the tank that's needed to keep group dmg manageable.

Adds spawn immediately on boss death. Be wary of their location before exiting combat.


core abilities:

- Earth Shatterer - *large aoe nature dmg that also breaks remaining Volatile Spikes*, triggering their dot(s)
- Seismic Smash - ***tank buster** applying dispellable Seismic Reverberation*.**should be healed through until within 6 seconds of next Seismic Smash***


ui includes:

- consider making visual for Seismic Reverberation unique (indicating delayed dispel)


Following combat, players have the choice of heading east to Skarmorak or West to Master Machinists. Void Speaker Eirich is only accessible once boss count is 3/4.

# Skarmorak Trash

Long runback means there's good value in being mindful of rez options prior to releasing. Generally, mobs are mechanically heavy and should be chain-pulled with caution.

mobs:

- Engine Speaker (ID 212764)
  - Concussive Smash - *stacking physical dot, slow, dispellable*. be aware if stacks are high
- Void Bound Despoiler (ID 212765)
  - Void Outburst - *pulsing groupwide shadow dmg*. believe unavoidable, heal baby heal
  - Shadow Claw -  *tankbuster, large shadow dmg to primary target*
- Turned Speaker (ID 214350)
  - Censoring Gear - *high-priority interrupt, silences player target*
- Void Bound Howler (ID 221979)
  - Piercing Wail - *large groupwide physical dmg burst with stacking dot that increases dmg taken from future Piercing Wails*
- Void Touched Elemental (ID 212400)
  - Crystal Salvo - *dodge purple poop*


carry-over mobs:

- Cursedheart Invader (ID 212389)
  - Arcing Void - *low-priority interrupt, spread 6+ yds to prevent dmg chain* (difficult in tight hallway and with Earth Infused Golem frontals)
  - Void Infection - *stacking dot, dispellable (decurse)*


ui includes:

- Concussive Smash stacks
- ensure m+ WA pack has good tracker for Piercing Wail (Howler debuff)

# Skarmorak

[WH encounter journal](https://www.wowhead.com/beta/npc=210156/skarmorak)

Killing Crystal Shards causes single pulse of groupwide dmg. On casting Unstable Crash, spawns orbs (Unstable Fragments). Orbs leave a pulsing aoe, but walking over one increases dmg to boss' Fortified Shell and healing throughput at the cost of suffering a dot. Idea is to stagger kill Shards so that the team stably enters the dmg-intensive Fortified Shell phase with a minimal shield and dmg/healing buffs.

core abilities:

- Crystalline Smash - *tankbuster, physical dmg, spawns Crystal Shard*
- Crystal Shard - *pulses proximity aoe shadow dmg. stagger kill to mitigate stacking on-death dmg, but any surviving shards when Fortified Shell is cast contribute to shield size*
- Fortified Shell - *large, pulsing, stacking groupwide aoe shadow dmg (Void Discharge) lasting until shield break*. Gather orbs to stack Unstable Energy, increasing shield dmg and healing throughput while suffering a dot.
- Unstable Crash - *large shadow dmg proximity aoe dmg, spawns orbs (Unstable Energy)*


ui includes:

- Unstable Energy stacks


Following combat, a minecart becomes available in the corner for quick access back to the EDNA encounter room.

# Master Machinists Trash

Room before boss is good to make up count if you skipped part of Skarmorak trash.


mobs:

- Aspiring Forgehand (ID 212405)
  - Fracturing Blows - *intermittently applies stacking dmg taken dot*
  - Fracture - *stacking dmg taken dot*
- Forgebound Mender (ID 2133380)
  - Restoring Metals - ***priority interrupt**, big enemy heal*
  - Alloy Bolt - *bait/low-priority interrupt*
- Forge Loader (ID 213343)
  - Lava Cannon - *frontal, dodge kamehameha*
  - Molten Mortar - *fire dmg burst with stacking, heavy fire dot*


carry-over mobs:

- Engine Speaker (ID 212764)
  - Concussive Smash - *stacking physical dot, slow, dispellable*. be aware if stacks are high
- Cursedheart Invader (ID 212389)
  - Arcing Void - *low-priority interrupt, spread 6+ yds to prevent dmg chain* (difficult in tight hallway and with Earth Infused Golem frontals)
  - Void Infection - *stacking dot, dispellable (decurse)*
- Repurposed Loaderbot (ID 222923)
  - Pulverizing Pounce - *don't stand in poop*


ui includes:

- Fracture stacks
- Molten Mortar stacks

# Master Machinists

[WH encounter journal](https://www.wowhead.com/beta/npc=213216/speaker-dorlita)

Priority will be to dodge mechanics while maintaining interrupts on Brokk's Molten Metal dmg/slow. All you have to do is play perfectly while ensuring you **always interrupt Molten Metal casts.** The slow this causes will complicate dodging of other mechanics, likely leading to wipes.

And be sure to **kill Brokk and Dorlita evenly**, on death the surviving Speaker begins pulsing dmg and gains a large dmg buff and they *do not share health* (Dorlita has a lot more health, too).


watch out for:

- When Brokk casts Scrap Song, he is about to jump to one of the sides to push the block (need to dodge) but then to keep casting Molten Metal, which needs to be range-interrupted.
- When Dorlita casts Blazing Crecendo, evacuate center for the safe vent to dodge incoming lava waves. Keep interrupts on Brokk's Molten Metal.
  - side comment: if caught away from safe vent during lava waves, there likely is a safe spot on or near the back of one of the blazing vents. just hold your breath and keep that gut in for this cheese.


core abilities:

- Speaker Brokk (caster)
  - Molten Metal - *priority interrupt (ranged after Scrap Song), groupwide dmg burst and heavy slow*
  - Scrap Song - *gonna jump away, push big block, and cast Molten Metal* 'bout to be a d\*ck'
  - Exhaust Vents - *run to safe vent*. three of four vents (in corners of encounter space) will channel fire beams, go to the one that doesn't
- Speaker Dorlita (bruilser, frontals)
  - Igneas Hammer - *tankbuster, physical dmg*
  - Blazing Crecendo - *get out of center/block path, go to safe spots **on vents***. pulls block to center, causing large proximity aoe and four large waves of lava


ui includes:

- ensure appropriate visuals for missed Molten Metal interrupts (which will never happen)


After boss kill, clear mobs blocking path to cart, then take cart back to the EDNA encounter room.

# Eirich Trash

mobs:

- Curseforge Honor Guard (ID 214264)
  - Stonebreaker Strike - *tankbuster, physical dmg*
  - Shield Stampede - *dodge charge* (direction of dark blue arrow, hard to see)
- Rock Smasher (ID 213954)
  - Granite Eruption - 
  - Smash Rock - *unavoidable aoe dmg with stacking dmg taken debuff*, stacking Smashed
- Curseforge Stoneshaper (ID 214066)
  - Stone Bolt - *low-priority interrupt*
  - Earth Burst Totem - *high priority kill totem*, large groupwide dmg burst if cast finishes. don't think spawning can be stopped, just need to burn totem on spawn


carry-over mobs:

- Forgebound Mender (ID 2133380)
  - Restoring Metals - ***priority interrupt**, big enemy heal*
  - Alloy Bolt - *bait/low-priority interrupt*


ui includes:

- Smashed stacks

# Eirich

[WH encounter journal](https://www.wowhead.com/beta/npc=213119/void-speaker-eirich)

Agree with party on general Void Corruption dot clear strat accounting for class squishiness. Just tap the puddle to clear stacks, believe will hurt if you actually step in. If tanky, can stack Entropic Reckoning puddle drops (don't believe overlapping poop dmg is addititive). Believe it'll ultimately be helpful to not drop poop in middle, but could take a while to catch on.


core abilities:

- Void Corruption - *ramping dot, stacking indefinitely until move within 15 yds of a Void Puddle*
- Entropic Reckoning - *spread, drop poop (Entropy, targeted on players)* try to avoid Void Puddle locations or "sectioning off" the room with bad drops. believe best to drop at perimeter
- Unbridled Void -  *dodge very large frontal* (kinda hard to see)


ui includes:

- Void Corruption stacks
