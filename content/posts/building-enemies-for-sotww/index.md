---
title: "Building Enemies for Shadow of the Weird Wizard"
date: 2024-12-18T23:11:10Z
description: >
  Let's build enemies and foes for Shadow of the Weird Wizard! It's almost
  OSR-like!
tags:
  - SotWW
  - Role-Playing
  - TTRPGs
draft: false
---
In the **Secrets of the Weird Wizard** in the _Bestiary_, there are some rough breakdowns of what a monster is, how they're listed, and how the challenge system works. After typing a lot of these up, I saw some patterns emerge.

## How I got here...

So, this going to be a stretch of connections, but hang with me. Looking at the DIFFICULTY number, knowing that Rob Schwalb worked on older versions of the most known role-playing game, I equated DIFFICULTY with LEVEL, because some where higher that PCs and did more damage. Damage is generally tied to (level)d6. Knave 2e and Shadowdark use Level as well, but Knave 2e is the only one to make the relation in text to matching HIT DICE. For some reason I kept thinking about Basic Roleplaying and how magic is bought d6 per level. It worked in my head. Then I used some instincts from Whitehack 4e and The Black Hack 2e on how a single number like HD provides a ton of information given the formula in the books. Worlds Without Number also equates HD as a sort of challenge rating or Difficulty number as well. Hit Dice Budgets from Scarlet Heroes.

Now, let's get into actually building enemies!

## Building an Enemy

Let's take a look at the Enemy/Foe Stat Block first. This is displayed in **Secrets of the Weird Wizard** _Bestiary_ page 96-98, so I won't dive too far into what each field means, but I'll discuss my choices for each blank.

- NAME - DIFF#
    - Description Tags
    - Defense - Health
    - Stats - Strength, Agility, Intellect, WIllpower
    - Size - Speed
    - Traits
        - Senses
        - Immunities
        - Fury
        - Special Traits & Talents
    - Actions
        - Melee Attack(s)
        - Ranged Attack(s)
        - Special Attack(s)
    - Reactions
    - End-of-Round Actions

Let's create a traditional fantasy style creature of extreme weirdness, something like...a giant gorilla! My gorilla will be going against a group of 4 PCs that are of Novice Tier and I want this to be an Average Difficulty. So, this gives me 8 Difficulty to work with. My giant gorilla will be a solo enemy, so we're gonna give it a few attacks since it is DIFFICULTY 8. Health is generally DIFFICULTY x 10, plus or minus 10 to 20 points for a stronger or weaker foe, respectively. For attacks, a Slam area of effect, a Hug and Throw 2 stage attack, and a single target Punch. We'll make the Punch the standard attack, the Slam a secondary when surrounded, and the Hug and Throw our big attack. Punch should do 2d6 Damage, Slam should do 4d6 Damage, Save to take half, and the H&T will do 2d6, followed by a Save with 2 Banes to get out, then throw 10 yards/size/squares away if the target is still held. Let's give the gorilla a Strength of 18, an Agility of 12, an Intellect of 10, and a Willpower of 15. Our gorilla will have a tough outer hide, so a defense of 14.  We're ready to make our Stat Block.

- **Giant Gorilla** - Beast - DIFFICULTY 8
    - Defense: 14, Health: 80
    - Strength: 18, Agility: 12, Intellect: 10, Willpower: 15
    - Size: 4, Speed 5
    - Traits
        - Languages: Sign
        - Immunities: None
        - Fury: Raging Slam: forgo Hug & Throw and combine Slam each round for 6d6.
        - Special Traits or Talents: None
    - Actions
        - **Punch** (Melee): Strength (+8), Damage 2d6
        - **Slam** (Melee): Area of Effect, Strength (+8), Damage 4d6, PCs save for half-damage, failure also knocks prone.
        - **Hug & Throw** (Melee): Strength (+8), Gorilla hugs the PC with a successful contested Strength Test. Failure is grappled for one round. The PC may attempt to resist again, and upon failure results in being thrown taking 2d6 Damage.
    - Reactions
        - None
    - End-of-Round
        - **Relocate**: The Giant Gorilla will attempt to reposition so it gets out of range, and use verticality to its advantage.

Alright, so we've made a Giant Gorilla. As with any enemy, foe or monster, even officially created ones, gauge your table, and make sure you're telegraphing the danger. Running away and retreating should always be an option, unless it is telegraphed that there isn't a way out.

## TL;DR - gimme the brief

- HP = DIFFICULTY x10
    - +10-20 for stronger enemies.
    - -10-20 for weaker enemies.
- Damage = DIFFICULTY x d6
    - Spread out between all attacks.
    - DIFF 1 = 1d6, DIFF 4 = 4d6, ...
- Defense = 11 + Armor
    - Natural or Made/Forged.
- DIFF 4 or higher enemies have 2-4 attacks.
    - This must make sense in the fiction of the foe.
        - Two arms, one carrying a sword, and a shield, 1 or two attacks.
        - Four arms, maybe 4 attacks.
- Damage Threshold = Rage = when Injured
    - perform an action or ability.
- DIFF 4 or higher enemies can inflict a Status Effect when achieving a Critical Hit.
- Enemies have Reactions which generally do not inflict damage.
    - These Reactions must fit the narrative.
- Stats and Bonuses are what makes sense.
    - Use a "Cloud Rating"
        - Use Tags to raise/lower Stats from the Clout Rating.
- Enemies can have End-of-Round actions.
    - Generally boosting themselves or hindering the PCs.

These are the highlight bullet points of what I have reverse engineered from Secrets of the Weird Wizard.

## Using a Clout Rating

A wut?

A **Clout Rating** is something I got from the **Eclectic Gamemaster's Toolkit for Genesys RPG**. Essentially almost every game has a "power level". In this, I will say I have a Clout Rating 8 Enemy. This is how well renown they are or their species is. So, CR 8 is going to be a DIFFICULTY 18 Enemy, taking the CR and adding 10 to it. Then, we'll give the enemy some tags or aspects to modify our other numbers. If we're going to stat out our gorilla again, it'd be CR 8, and a tag of "Strong" for +2 to STR and WILL Stats. "Fears Fire", would give it a -2 to INT and maybe a Vulnerability to fire. "Tough" would raise our Defense +2, and probably our STR +2.  Lastly, I'll say "Big Ol' Dude", and give it another STR +2 to make it 18, so we match our earlier example. Then from this, I can extrapolate most of the other information I need.

Hopefully that's a neat method to build a Foe as well that would be usable in any system, not just Shadow of the Weird Wizard. Of course, Mythic Role Playing's Scaling Boxes make that real easy too.
