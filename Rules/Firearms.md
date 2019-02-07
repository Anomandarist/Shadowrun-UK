---
title: Firearms
---

## Firing Modes

- Firearms come in a variety of firing modes which are listed on the weapon’s stat block
- If a weapon has more than one firing mode, switching between modes is a simple action or a free action if the weapon is wirelessly active and the shooter has a DNI
- The different firing modes are listed below along with the actions available when firing in each mode

### Single Shot
- Simple action - Fires a single round

### Semi-automatic
- Simple action - Fires a single round
- Complex action - Semi-automatic Burst: Fires 3 rounds, -2 penalty to dodge
- Complex action - Double tap: Fires 2 rounds, no penalty to dodge, +1DV

### Burst Fire
- Simple action - Fires 3 rounds, -2 penalty to dodge
- Complex action - Long burst: Fires 6 rounds, -5 penalty to dodge
- Complex action - Aimed burst: Fires 3 rounds, no penalty to dodge, +1 DV

### Fully automatic
- Simple action - Fires 6 rounds, -5 penalty to dodge
- Complex action - Fires 10 rounds, -9 penalty to dodge
- Complex action - Brain Blaster: Fires 6 rounds, +2 DV


## Suppressing Fire
- Takes a complex action
- Uses 20 rounds of ammunition
- Suppress a cone area at a distance of the shooters choice up to the range of the weapon
- The cone is 10m wide and 2m high at its end
- Make a (Weapon Skill) + AGI [Acc] test and record the hits
- Suppressive fire lasts until the end of the combat turn as long as the firer does not move or make another action
- Anyone in or immediately adjacent to the zone takes a dice pool penalty to all actions equal to the shooter’s hits (unless they are completely unaware of the suppression)
- Any character in the suppressed area who is not prone or behind cover must make a REA + EDG (+Full defence if they choose) test with a threshold equal to the shooter’s hits.  If they fail they are hit and take the base DV of the weapon/ammunition
- Characters may spend their free action to go prone and avoid making the roll
- Characters with no available free action may use the [Hit the Dirt](InterruptActions.md) interrupt action if they have the initiative to spend
- If multiple suppressive fire actions overlap only the highest dice pool penalty counts but REA + EDG tests must be made against all overlapping zones.  These tests are subject to the -1 penalty for each subsequent defence

### Enhanced Suppression
- Complex action
- This narrows the area of suppression but increases it vertically
- The cone width is reduced to 5m across at the far end
- Characters within this zone may not use the Drop Prone free action to avoid the fire
- They may still use the Lucky Cover Edge action to avoid the roll

### Flechette Suppression
- May only be performed with weapons firing flechette ammunition
- Prevent targets from using the drop prone action to avoid being hit
- Effects are dependent on the choke setting of the weapon
- Narrow choke confers the effects of enhanced suppression

### Medium choke

| Range   | DV  | ACC | Defence | Extra width |
| ------- |:---:|:---:|:-------:|:-----------:|
| Short   | -1  |  -  |   -3    |     4m      |
| Medium  | -3  |  -  |   -3    |     8m      |
| Long    | -5  | -1  |   -3    |     12m     |
| Extreme | -7  | -1  |   -3    |     16m     |

### Wide choke

| Range   | DV  | ACC | Defence | Extra width |
| ------- |:---:|:---:|:-------:|:-----------:|
| Short   | -3  |  -  |   -5    |     6m      |
| Medium  | -5  |  -  |   -5    |     12m     |
| Long    | -7  | -1  |   -5    |     18m     |
| Extreme | -9  | -1  |   -5    |     24m     |

## Shotguns
- Flechette ammunition fired by shotguns has a spread
- The spread is controlled by the choke
- Changing the choke setting is a simple action, or a free action on a smartlinked weapon
- At medium and wide choke settings multiple targets within a specified spread can be targeted with the same attack roll without splitting the dice pool
- Called shots cannot be made with weapons set to medium or wide choke

### Narrow Choke
- Target receives a -1 penalty to defence tests at all ranges

### Medium Choke

| Range   | DV  | ACC | Defence | Spread | Number of Targets |
| ------- |:---:|:---:|:-------:|:------:|:-----------------:|
| Short   | -1  |  -  |   -3    |   2m   |         2         |
| Medium  | -3  |  -  |   -3    |   4m   |         3         |
| Long    | -5  | -1  |   -3    |   6m   |         4         |
| Extreme | -7  | -1  |   -3    |   8m   |         6         |

### Wide Choke

| Range   | DV  | ACC | Defence | Spread | Number of Targets |
| ------- |:---:|:---:|:-------:|:------:|:-----------------:|
| Short   | -3  |  -  |   -5    |   3m   |         2         |
| Medium  | -5  |  -  |    5    |   6m   |         3         |
| Long    | -7  | -1  |   -5    |   9m   |         4         |
| Extreme | -9  | -1  |   -5    |  12m   |         6         |

## Recoil
- All firearms exert recoil on the shooter
- If a shooter is wielding two firearms at the same time the recoil is combined
- Recoil compensation helps to control the first few shots the weapon fires
- Recoil compensation = 1 + STR/3(Rounded up) + RC of the weapon
- Recoil is equal to the number of bullets fired and is cumulative across every action phase and combat turn until the shooter takes a simple or complex action that does not involve shooting.  This resets the characters recoil to zero
- Recoil is cumulative to the shooter, not the weapon being fired
- Single Shot weapons do not exert cumulative recoil

- Once the cumulative recoil exceeds the characters recoil compensation the excess recoil is applied as a penalty to the characters dice pool for attacks made with firearms

- Vehicle and drone mounted weapons have recoil compensation equal to the body of the vehicle + RC of the weapon
