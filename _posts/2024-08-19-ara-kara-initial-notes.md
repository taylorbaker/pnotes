---
title: Ara-Kara Initial Notes
layout: post
date: 2024-08-19
headerImage: false
description: Instance overview of Ara-Kara for the first season of the War Within
author: phunkp
tag:
- The War Within
- Mythic+
category: blog
---

last updated: 9/4/24

Poison cleanse is BiS this dungeon.

vods:

[The Bible - Quazzi Ara-Kara Masterclass](https://youtu.be/yMeiIG-z2xw?si=tsz3nbrykoYd032L)

# Avanoxx Trash

Need to kill three named mobs (sureki attendants: Ixin, Nakt, and Atik) prior to pulling boss. They are spread around starting area and have a pulsing white visual over them at dungeon start. Seems meta to go left to right.

mobs:

- Ixin (ID 217531) , Nakt (ID 218324) , and Atik (ID 217533) 
  - need to clear mobs to make room for spray cone and fear fail
  - Web Spray - *tank face toward open space*: large frontal on tank that leaves poop
    - saw yoda face in open space (even at group) for poop spread
    - believe facing away/off ledge is what causes mass poop on named mob, causing melee super sad
  - Web Bolt - *don't interrupt*: (baits wasted interrupts)
  - Ixin only (left-most) - Horrifying Shrill - ***mandatory interrupt***: interruptable group-wide fear
  - Nakt only (middle) - Call of the Brood - *tank taunt/gather summoned adds*: pulsing aoe physical dmg and enrages nearby Web Crawlers
  - Atik only (right-most) - Poisonous Cloud - *move out*: telegraphed poison aoe dealing high dmg
- Trill Attendant (ID 216293)
  - Resonant Barrage - *interrupt*: pulsing aoe physical dmg to entire group
  - Web Bolt - *don't interrupt*: (baits wasted interrupts)
- Engorged Crawler (ID 214840)
  - Toxic Rupture - *move out*: low-health suicide ability with telegraphed green aoe around mob
- Jabbing Flyer (ID 216341)
  - Bleeding Jab - *bleed dispel at high stacks (should track stacks)*: applies stacking bleed dot

ui includes:

- Bleeding Jab stacks
- mark Assistants for interrupts?

# Avanoxx

[wh encounter journal](https://www.wowhead.com/npc=213179/avanoxx)

Four eggs will spawn with boss (including prior to pull) indicating add (Starved Crawler) spawn points (on Alerting Shrill). Clear any remaining adds near egg spawn points prior to pull, or pull with boss. Poop spawns on players during Gossamer Onslaught and will slow players and adds alike. Players should not camp in poop, builds a stacking slow (Vile Webbing) that incaps at 10 stacks. Conserve space as poop does not despawn until boss dies, acting as a soft enrage.

Adds gain a stacking dmg buff the longer they're alive.

core abilities:

- Insatiable - *huge dmg buff if adds reach boss*
- Alerting Shrill - *wakes adds and large pulsing group-wide physical dmg*
- Gossamer Onslaught - *large pulsing nature dmg leaving poop at players' feet*
  - poop can be used to slow adds, but also builds a stacking slow (Vile Webbing) that will incap at 10 stacks (Web Wrap)
  - don't camp in poop, but do drop around eggs (indicating add spawn points)
- Voracious Bite - ***tank buster** (physical) with following dmg taken debuff, be alone for splash (unconfirmed)*: boss leaps on primary target for 3 consecutive attacks. final hit increases dmg taken for 10 secs

ui includes:

- Vile Webbing stacks
- Voracious Bite debuff

Old Prog Strat: "Eat two, kill two"

[kill clip (yoda)](https://youtu.be/gNrfmK7Gyw8?si=WPwUhSUHzvXuzWBE&t=302) (posted 7/31/24)

At one point in the beta, eggs spawned in pairs, allowing for the option of letting boss consume two adds while the other two get burned/slowed by group. Tank would communicate this by pulling boss to one pair of eggs on spawn, indicating dps should drop Gossamer Onslaught poop near other set and prepare for burn.

Now, seems like eggs all spawn together, making it mandatory they all be killed on prog keys.

# Anub'zekt Trash

Work across NW bridge through mobs (seems best to take right/top path after bridge). Clear until pack with two Stagshells and a Webmage casting on a webbed door, blocking progress. Once this pack is cleared, continue through door (mountable throughout) to final trash pack before boss.

Typically, pull to next Bloodguard, chaining so that as one dies the next is engaged. You will need to learn with experience where you can pause for breaks here, if needed. Easy to chain pull packs out of control with charges, alerting mechanics, and channeled Bloodguard spawns.

mobs:

- Bloodworker (ID 216337)
  - Charge - *dodge, targets player direction* don't point at friends!
- Bloodstained Assistant (ID 216333)
  - Extraction Strike - *medium-priority focus mob (before gets too strong) purge?*: physical dmg on primary target with leeching effect. also applies stacking dmg and healing received throughput buff per cast
- Bloodstained Webmage (ID 223253)
  - Revolting Volley - *priority interrupt*: heavy nature damage tick and heal absorb on all
  - Web Bolt - *don't interrupt*: (baits wasted interrupts)
- Hulking Bloodguard (ID 216338)
  - Slam - *unavoidable aoe group dmg* (nature)
  - Impale - *don't stand in large, telegraphed frontal* - deals physical dmg and knockback to failures
- Sentry Stagshell (ID 216340)
  - Alarm Shrill - *stop long cast* - will spawn a Bloodguard and taunt nearby mobs on cast finish

ui includes:

- mark Webmages for Revolting Volley interrupts?
- mark Stagshells for stops?

# Anub'zekt

On pull, tank boss roughly off-center, don't stand in tornadoes, and tank face boss away from group to bait frontals. Ranged stack at a moderate distance to bait Burrow Charges. Do not be in the path of boss or in proximity of the targeted spot. On each Burrow Charge, Bloodstained Webmage(s) are spawned and should be picked up by tank.

After set time (seemingly), boss will enter Eye of the Swarm, creating a battle-royale-style safe zone players need to get within. Standing in storm will accrue Ceaseless Swarm, a stacking nature dmg dot resulting in a potentially lethal combo with any remaining Webmage Silken Restraints casts. Tank should position boss on edge of safe zone and still face Impale away (as tangential to safe zone as possible). Believe once Eye of the Swarm starts, it lasts until end of fight.

core abilities:

- Impale - *avoid large frontal* dealing physical dmg
- Burrow Charge - *targets random player location, move out of path and target location. if targeted player is far enough away from boss on cast, dmg can be avoided*
- Eye of the Swarm - *stand in battle-royale-style safe zone. tank still aim boss away from group for Impale and* ***ranged priority interrupt any remaining Webmages***
- Ceaseless Swarm - *stacking nature dmg for standing in storm*

mobs:

- Bloodstained Webmage (ID 220599)
  - Silken Restraints - *interrupt, immobilizes and stacks debuff on friendlies*

ui includes:

- Ceaseless Swarm stacks

# Ki'Katal the Harvester Trash

Travel across new accessway (watch them holes), aggro the Overseer and stay as central as possible to avoid pulling the lining Reinforced Drones while maintaining interrupts on the Overseer's Venom Volley. On first damaging the patrolling Winged Carriers, each will drop a Black Blood aoe that will CC any players hit (similar to the upcoming boss mechanic). CC'd players will be consumed by a channeling Blood add. These can be removed with any CC of our own or any immobilization removal (e.g. Hand of Freedom). 

Should the Drones get pulled, they too drop Black Blood when first receiving dmg, but they also apply a stacking slow with Grasping Slash within 10 yds. This is another nasty combo with the Overseer's Erupting Webs.

Make your way to the Nerubian Hauler, who just needs to be burned before his Intensity stacks cause Massive Slam to overwhelm the group. Ideally clear the Hauler before pulling the double Overseer group prior to boss. Don't believe these mobs can be stunned or aoe-stopped, making coordinated interrupts of Venom Volleys a high-value play.

mobs:

- Blood Overseer (ID 216364)
  - Venom Volley - ***high priority interrupt*** dealing high group nature damage and applying a nature dot
  - Erupting Webs - *don't stand in poop, look out for opportunities to save teammates immobilized by Black Blood with immobilization removal or cc'ing the channeling blood add on afflicted players*
- Winged Carrier (ID 216365)
  - Black Blood - *on first dmg, drops blood puddles*
  - Dashing Strike - *deals physical dmg at player location*, believe can be dodged
- Nerubian Hauler (ID 217039)
  - Massive Slam - *group-wide unavoidable nature dmg pulse with 1 sec stun*
  - Intensity - *stacking dmg buff, kill before Massive Slam becomes lethal*
- Reinforced Drone (ID 216363)
  - Black Blood - *on first dmg, drops blood puddles*
  - Grasping Slash - *inflicts physical dmg and applies stacking slow*
- Bloods - *CC to free players hit with Black Blood, dmg sponges afterwards*

ui includes:

- Blood-channeled players indication
- Grasping Slash stacks
- mark double Overseer pack for Venom Volley interrupts

# Ki'Katal the Harvester

Fight constantly rotates between spreading/killing Bloods in favorable positions and CC'ing yourselves for Cosmic Singularity casts. During spread phase, wait to kill Bloods until they are in medium range to boss. This is to taste, as players will need a spread selection of Blood puddles within range for each Cosmic Singularity cast (while reducing splash damage from Cultivated Poisons). **Each puddle is consumed on player entry. Each player will need their own puddle.** If possible, early signal "your" puddle by standing near it ahead of time.

The Bloodworker mobs are insta-killed, so its tempting to kill all immediately around the perimeter, requiring large group movement for the next Cosmic Singularity or, more likely, a wipe. This will be a stressful fight on the healer, so playing to that player's comfort level will likely be a safer bet.

After Cosmic Singularity, Blood adds are countered same as trash. Any CC will free players (Typhoon, Hand of Justice, Blessing of Freedom), but the adds will need to be killed. Help your buddies. Or don't and laugh.

mobs:

- Bloodworker - *instantly-killable, drops Black Blood on death, kill in favorable locations*
- Bloods - *CC to free players hit with Black Blood, dmg sponges afterwards*

core abilities:

- Erupting Webs - *don't stand in poop* or get stunned
- Cosmic Singularity - *large group grip countered by going in Black Blood and being rooted* (after ability, CC your mob to be freed)
- Cultivated Poisons - *poison dot debuff (nature dmg) that ejects waves on removal*, struck players will also take heavy nature dmg
- Faded - *players hit by Cosmic Singularity are debuffed with increased dmg taken and reduced throughput*

ui includes:

- Cultivated Poisons debuff
- Faded debuff