---
title: Security Devices
---

# Landscaping

- Make it difficult for unauthorised people to enter without being spotted, trapped, intercepted, or killed
- Prevent intruder from escaping easily
- Trees, dense brush, and hedges can provide cover for sensors, wires, cameras, tiger pits, secret entrances or exits, or automated gun systems
- Ponds and lakes
- Dense brush and ground cover difficult to bypass without creating noise and may be paired with acoustic sensors
- Foliage affects Matrix Noise

# Barriers

- Prevent entry, escaping, deter surveillance, deter terrorist attacks
- Climbing past fencetop wiring: Climbing + AGI (3) Test, otherwise take damage
- Damage resisted by BOD + Armour
- Perception Test to spot the fence is non-standard

| Fence       | Perception Threshold | Damage |
| ----------- |:--------------------:|:------:|
| Barbed      |          1           |   4P   |
| Concertina  |          1           |   5P   |
| Monowire    |          3           |   8P   |
| Electrified |          2           |   6S   |

# Doors, Windows and Locks

## Doors and Windows

- Windows tend to be mirrored (prevents outside spellcasting)
	- Tinting is often voice or wireless controlled
- Transparent concrete

## Key Locks

- Not very common (private safes or low-end businesses)
- Locksmith + AGI [Physical] (Lock Rating, 1 Combat Turn) Extended Test
- Autopickers add their Rating
	- Or use their Rating in place of the skill

## Transponder-Embedded Keys

- Calibrated resistor that completes a circuit in the lock
- Additional test to general the appropriate electrical characteristics
- Requires an electronics kit
- Hardware + LOG [Mental] (Lock Rating, 1 minute) Extended Test
- If it is the same character picking the lock and calibrating the electrical feed, -2 to both tests

## Maglocks

- Widespread
- “Keys” can be:
	- Physical (keypad, swipe card, proximity card, memory string)
	- Biometric
	- Or any combination thereof
	- See below for details
- Often accessible via local network
- May be monitored by security hacker/rigger
- Usually log all usages (time, date, identity of user)
- Remove case: Locksmith + AGI [Physical] (Maglock Rating ×2, 1 Combat Turn) Extended Test
- Break case: Barrier Rating = Maglock Rating
- Overzealous attempts may harm electronics inside
- Re-assembling case requires the same test
- Anti-tamper systems: Rating 1-4, Locksmith + AGI [Physical] (Anti-tamper System Rating)
	- Failing triggers and alarm

### Keypads

- Access code (often different ones for different users)
- Rewiring circuits: Locksmith + AGI [Physical] (Maglock Rating ×2, 1 Combat Turn)
- Maglock sequencer can be used
	- Opposed Test by Sequencer vs Maglock Rating
	- Wireless: +1 Rating bonus

### Cardreaders

- Swipe cards or RFID proximity cards
- Can also be defeated using Maglock passkeys
	- Opposed Test by Passkey Rating vs Maglock Rating
	- Wireless: +1 Rating bonus
- Can also copy a keycard using a keycard copier
	- Copies in seconds
	- New keycard can be manufactured with a Hardware kit, about ten minutes
	- Hardware + LOG [Mental] (2) Test
	- Opposed Test by Forged Keycard Rating ×2 vs Maglock Rating ×2
	- Wireless: +1 dice pool bonus
	- Note: Some systems will record unusual usage of duplicate keys

### Print Scanners

- Fingerprints, palm prints, retinal prints, pattern of blood vessels in face/palm
- Synthetic print glove-like membrane (a “sleeve”) can be manufactured for fingerprints and thumbprints using a cellular glove molder
	- Opposed Test by Duplicate Rating vs Maglock Rating
- Retinal duplication cybereye accessory
	- Opposed Test by Duplicate Rating vs Maglock Rating

### Voice Recognition

- Vocal response from an approved user’s voice within a set time
- If note, alarm is sounded
- Recording, simulation can also be used
	- Opposed Test by Equipment Used Rating vs Voice Recognition System

### Breath, Cellular, and DNA Scanners

- Sample of user’s cells (off finger/palm, hair suction, exhaled particles)
- Sample required, preserved in specially formulated enzyme bath
- Enzyme bath can be synthesised in a chemistry shop using Chemistry + Logic (5, 1 hour) Extended Test

### Facial Recognition

- Opposed Test by Disguise + INT [Mental] vs Device Rating
- +2 dice pool modifier if system is picking character out of a crowd

# Sensors and Scanners

## Lighting

- Usually controlled via wireless
- Activate at pre-determined times or events
- Indoor lighting can be manually controlled with switch or programmed
- Switches subverted with Hardware + LOG [Mental] (5, 1 Combat Turn) Extended Test
- Occasionally, gas-discharge lighting is used for high-wattage exterior lighting - takes 5 minutes to warm up

## Alarms

- Alerts guards, security hackers/riggers, or remote monitoring services
- May be silent or loud
- Many based on electrical circuits
- Hardware + LOG [Mental] (5, 1 minute) Extended Test
	- Though depending on design, may be more difficult

## Wire

- Triggers alarm
- Monowire wires for damage
- Perception Test required to spot

| Wire        | Perception Threshold | Damage |
| ----------- |:--------------------:|:------:|
| Barbed      |          1           |   4P   |
| Concertina  |          1           |   5P   |
| Monowire    |          3           |   8P   |
| Electrified |          2           |   6S   |

## Trip Beams

- Perimeter or across entrances
- Laser emitters (visible or infrared), mirrors, and laser detectors
- Noticing: Perception + INT [Mental] Test
	- Threshold 2 for visible
	- Threshold 3 for infrared
- Smoke or aerosol spray reduces threshold by 1
- Squeezing past: Escape Artist + AGI [Physical] Test vs GM Threshold
- Can also simultaneously lining up proxy laser emitters of the proper wattage into each detector
	- Escape Artist + AGI [Physical] Test
- Can also use calibrated system of mirrors to re-arrange the trip beam pattern

## Pressure Pads, Pressure Mesh

- React to any amount of weight, or too much weight beyond a pre-programmed amount (2-5kg heavier than the heaviest authorised individual)
- Mesh mainly used outdoors, but less sensitive
- Noticing: Perception Test
	- Threshold 3 for pads
	- Threshold 4 for mesh
- If stepped on, a second Perception Test should be rolled to attempt to react
	- Threshold 1 for pads
	- Threshold 3 for mesh
- Can remove weight before triggering
	- REA + INT - BOD (3) Test

## Motion Sensors

- Ultrasonic field
- Can be detected using an ultrasonic sensor set to passive mode within 5m
- Move <=0.5m/Combat Turn
- And also succeed on Sneaking + AGI - extra Initiative Dice [Physical] (3) Test

## Proximity Wire

- aka capacitance wire
- Detects electrical discharge of metahuman body (or animal) within 2m
- Often used around building’s perimeter fencing, on secure entranceways, or on special objects
- Triggers alarm or turns on security cameras/measures
- May be used in conjunction with motion sensors

## Sound/Vibration Detectors

- Sensitive microphones
- Can be programmed with pattern recognition algorithms to ignore some sounds/vibrations
- Sneaking + AGI [Physical] (3) Test
	- Spells that aid can also be used
- Triangulating the sound’s origin can be achieved with multiple detectors

## Cameras

- Standard visual to low-light, infrared, and ultraviolet
- Have reflective infrared surfaces for infrared cameras to pick up on body heat around corners
- Low-light cameras can be overpowered by bright light
- Typical cameras on fixed or pivoting mounts can be easily seen if characters are looking for them
- Smaller micro-cameras have threshold 3 on Perception test

## Olfactory/Pheromone Scanners

- aka chemical detection systems, chemsniffers
- Roll chemsniffer’s Rating dice pool with threshold 2
	- Threshold 3 if hermetically sealed
- Uncommonly, can be used to detect pheromones from metahumans
	- Can distinguish metahuman/animal and gender
- Rolls Device Rating, threshold 3
	- Threshold 2 for characters with tailored pheromone bioware

| Situation                                   | Modifier |
| ------------------------------------------- |:--------:|
| Every 10 rounds of ammunition               |    +1    |
| Every grenade                               |    +1    |
| Every 30 grams of (non-plastique) explosive |    +1    |
| Every 100 grams of plastique                |    +1    |
| Item contained in plastic                   |    -1    |

## Magnetic Anomaly Detectors (MADs)

- Detects metallic substances
- Rolls Device Rating, threshold 1

## Millimetre Wave Detection (Cyberware Scanners)

- aka cyberware scanners
- Process video taken in millimetre wave spectrum
- To identify the energy signature of cyberware and concealed items (specifically weapons)
- Rolls Device Rating, threshold in tables below
- Can detect any non-biological item by its shape and composition, assuming the item is listed in the device’s database
- If detected, the scanner notes general locations and type
	- Additional hits provide more detail

| Item                        | Threshold |
| --------------------------- |:---------:|
| Standard cyberware, weapons |     1     |
| Alphaware, other items      |     2     |
| Betaware                    |     3     |
| Deltaware                   |    5+     |

| Situation          | Modifier |
| ------------------ |:--------:|
| 2-3 implants/items |    +1    |
| 4-5 implants/items |    +2    |
| 6+ implants/items  |    +3    |

# Automated Defences

## Automated Gun Systems

- On fixed locations (180° arc) or on slide-mounted track systems
- Typically loaded with basic sensors and Targeting autosofts
- Follow standard rules for drones

## Containment Systems

- Trap mechanism
	- e.g. shutters, doors lock, sliding walls or gates
	- May include laser or monowire mazes and radio jamming

## Gas Delivery Systems

- Can be insidious, dispersing in a potentially undetectable way
- Fill an area of 30 cubic metres in one Combat Turn
- GM may conduct Perception Tests
	- Threshold based on how noticeable the gas is (many gases are colourless and odourless)
- Characters with olfactory scanners may be alerted by their gear

## Marking Systems

- Tag intruders with a discreet mark
	- e.g. ultraviolet dye, RFID tags, DNA-encoded material, nanite tags
- Typically sprayed unobtrusively over exits and other traffic areas
