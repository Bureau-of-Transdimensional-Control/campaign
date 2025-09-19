Sometimes something just wants to tear you to pieces, and there's no point in talking to it. In this section, we'll discuss the combat system.

# Basics

The combat system in Call of Cthulhu is turn-based. A round is one turn for each participant in combat. On their turn, a participant can take one of the following actions:
- attack using a melee combat skill or firearms skill
- perform a fighting maneuver
- flee from combat
- cast spells
- perform other actions that require time and skill checks. For example, treating a wounded companion
It's worth noting that monsters can make more than 1 attack per turn.
A character can delay their turn, but not beyond the end of the round. If the end of the round is reached and no turn has been taken, it's considered skipped.

> [!Important]
> Combat rolls cannot be pushed.

# Turn Order Within a Round

Turn order is determined by DEX value from highest to lowest. However, those using firearms get +50 for determining turn order, since pulling a trigger is faster than striking with a hand or swinging a club.

> [!Example] 
> Three participants are in combat: Zombie (DEX 30), John with a club (DEX 60), Jane with a shotgun (DEX 50). The turn order in this case:  
> 1. Jane - 50 + 50 = 100
> 2. John - 60
> 3. Zombie - 30

# Melee Combat

When damage is dealt by hand or tentacle, regardless of whether there's anything in that appendage, melee combat rules apply.
1. The attacker declares intent to attack in melee combat
2. The defender chooses how to react:
    1. dodge
    2. counterattack
3. Both roll dice to determine the winner in the contest
4. Damage is calculated based on the roll results
Besides Brawl, there can be special melee weapon skills including swords, axes, spears, whips, garrotes, and even chainsaws. The Brawl skill is used when fighting with basic weapons that don't require special skills - bats, knives, chair legs, bottles, any improvised weapons.

## Dodging
The dodge skill allows you to take no damage from an attack if you achieve equal or greater success.

## Counterattack

If the target decides to strike back, the target's success must be higher than the attacker's success. Note that counterattacks cannot score critical hits. If both roll failures, this may mean both take damage.

## Determining Damage

If a skill check achieves a success or hard success, damage is determined by rolling damage dice.
If an extreme success (⅕ of Skill) or critical success (01 on d100) is achieved, critical damage is dealt:
- for blunt weapons, damage equals maximum weapon damage + maximum damage bonus
- for impaling weapons - maximum damage + additional damage roll. Firearms are considered impaling weapons

> [!Example] 
> John uses a knife and rolls an extreme success.  
> Knife damage is 1d4 + 2 + DB.  
> John's DB is 1d4.  
> Damage equals 4 + 2 + 4 + (1d4 + 2 + 1d4)  
> John rolled 2 and 3 on his d4s.  
> Result: 10 + 7 = 17 damage points  
> For reference, maximum HP of a human is 18, average is 13

## Outnumbered

When a target has made as many reactions as it can perform attacks, it enters an outnumbered state. In this state, melee attacks receive a bonus die on the attack roll.

## Fighting Maneuvers
If the goal of an attack is something other than dealing damage, then a fighting maneuver is used.
1. Determine the difference in Build
    1. If the target has a build 3 or more points higher, the maneuver is impossible
    2. If the target has a build 2 points higher, the attacker receives two penalty dice
    3. If the target has a build 1 point higher, the attacker receives one penalty die
    4. If the target has equal or lower Build, the maneuver is performed without modifiers
2. The attacker makes an attack roll, the target can:
    1. dodge, works the same way
    2. counterattack
    3. perform a responsive maneuver = counterattack
As a result of a successful maneuver, you can:
- disarm an opponent
- take an item
- escape a grapple
- grapple
- knock down
- push from height
In certain cases, a maneuver leads to gaining bonuses or imposing penalties on the opponent.

# Thrown weapons
Bows, slings, crossbows work the same way as firearms.  
Thrown weapons can be dodged.
Half of DB is applied to thrown weapons, bows and slings.

# Firearms
Basic mechanics for using firearms. Shooting gives +50 to DEX for determining turn order. The only possible reaction to gunfire is to dive for cover or fall prone, but this reaction removes the ability to attack on the next turn.

## TL;DR

| Difficulty level         | Bonus die             | Penalty die                 |
| ------------------------ | --------------------- | --------------------------- |
| Regular: normal range    | Aiming for 1 round    | Target diving for cover     |
| Hard: Long range         | Point blank           | Fast-moving target MOV 8+   |
| Extreme: Very long range | Large target Build 4+ | Partial concealment (50%+)  |
|                          |                       | Small target Build -2       |
|                          |                       | Multiple handgun shots      |
|                          |                       | Loading and firing one shot |
|                          |                       | Firing to melee             |

## Range
Depending on shooting range, different success levels may be required.
- Within base range - regular success
- Up to 2x base range - hard success
- Up to 4x base range - extreme success
For extreme success checks, impaling damage is only achieved on a roll of 01.

## Modifiers
### Dive for Cover (Penalty die)
The attack target dives to take cover behind an object, simply lies on the floor, or attempts to get below the barrel line. The target makes a dodge check, and on success adds 1 penalty die to the attacker's roll.
This target reaction cancels the next attack of whoever used it, regardless of whether the character has acted this round.
Nothing prevents using this reaction every turn.

### Cover and Concealment (Penalty die)
  Cover may not stop a bullet, but it definitely interferes with aimed fire.
If the target is hidden behind an object by at least half, this also gives at least 1 penalty die.
If a fully concealed character takes any action that allows at least part of the character to be seen, then that character can be targeted by shots this round.

### Aiming (Bonus die)
A character can spend their turn aiming. Next round, if the character took no damage and didn't move, the character gets a bonus die on the shot check.
Only one bonus can be gained from aiming.

### Fast-Moving Targets (Penalty die)
If a target with MOV 8+ is constantly moving, it's harder to hit.  

### Target Size (Bonus or Penalty die)
If target size is -2 and lower, it's harder to hit. Penalty die. If target size is 4 and higher, it's easier to hit. Bonus die.

### Reloading (Possible Penalty die)
Reloading takes time, usually 1 round.
However, it's possible to load exactly one cartridge and shoot with a penalty die.

### Multiple Shots from Pistols (Penalty die)
Most pistols can fire 2 or 3 times per attack.
For each shot in this case, the skill check is made separately with a penalty die.

### Shooting into Melee (Penalty die)
To avoid shotting an ally requires greater skill. One penalty die is added.
If the roll result is a fumble, the hit occurs on an ally. If there are multiple allies, the hit occurs on the one with the lowest Luck.

## Automatic Fire
There are three modes:

- Full-auto (fires the entire clip at once)
    - player declares the number of rounds to be fired
    - number of bullets is divided into volleys
    - volley size is up to Firearms SMG/MG divided by 10, rounded down
        - Firearms SMG 47 -> max volley size 4
    - each volley requires a fresh roll
    - first volley - usual rules
    - Nth volley - +(N-1) penalty dice
        - if there are more than 2 penalty dice, difficulty increases by one step
    - resolve
        - regular success - half the bullets (rounded down, min 1) deal damage
        - extreme success - all bullets in the volley deal damage, with the first half (rounded down, min 1) impaling
- Burst (fires several bullets per trigger pull, i.e. 2-3 bullets)
    - treated as a single volley
    - skill does not affect volley size
- Semi-automatic (fires one bullet at a time)
    - uses the same principle as handguns for firing multiple times

## Malfunctions
Firearms can jam or misfire. This occurs if a skill roll is higher than the malfunction score.
If the weapon is a revolver, break-open gun, or bolt-action rifle, the problem is just a dud round.
For lever-action rifles, a Mechanical Repair or Firearms skill check is required to fix a malfunction.