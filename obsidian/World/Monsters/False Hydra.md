The false hydra was born in the Feywild out of [[Lunara]]'s emotion of betrayal and sorrow and hate. It consumes creatures and eliminates all living memories of them, while being able to mass charm witnesses into forgetting what they saw and/or using illusions to stay undetected through singing a magic song.

At the moment, it is guarding [[Lunara]]'s prison and hunts down all Heyholn citizens whose minds [[Lunara]] invades in hope of finding an escape. 
## False Hydra Song
False Hydra can emit a song with one of its heads when it is not fighting enemies. The song makes victims follow false hydra's commands and have no recollection of seeing the false hydra.

There are many ways to resist the false hydra's magic, such as
- Stuffing ears
- Using mirrors
- Casting silence
- Casting true sight
## Battle Encounter
False Hydra is a special type of creature, possessing multiple heads. The number can be regulated to fit the party, default is 7.

The body is very slow, whereas the heads can stretch to up to 480 feet and move relatively fast. The false hydra dies with its last head.

If players do not approach the false hydra stealthy, it will attempt an ambush.  To play this, the false hydra's stealth role should exceed PCs' passive perception.

The hydra cannot move fast, so it always chooses a place for battle where it can escape into the water. The terrain should be a swamp and considered **difficult**.
## Statblocks
Hydra's HP equals to sum of its heads HP. When all heads die, the Hydra dies as well. If PCs attack the torso, it is interpreted as all heads receive equal amount of damage.
### The False Hydra

```statblock
name: False Hydra
size: Huge
type: Fey
alignment: Chaotic Evil
ac: 10
hp: 700
speed: 5 ft., swim 80 ft.
stats: [20, 10, 20, 4, 19, 24]
saves:
  - intelligence: 2
  - wisdom: 9
  - charisma: 12
skillsaves:
  - stealth: 10
condition_immunities: charmed, prone, stunned, knocked unconscious
senses: Blindsight 120ft., Passive Perception 14
cr: 14
languages: Understands the language of its victims
spells:
  - "The false hydra's innate spellcasting ability is Intelligence (spell save DC 18). It can innately cast the following spells, requiring no components:"
  - At will: detect thoughts
  - 3/day: dominate monster
traits:
  - name: Legendary resistance (3/day)
    desc: If the false hydra fails a saving throw, it can choose to succeed instead.
  - name: Multiple heads
    desc: In addition to the torso, each False Hydra's heads have their own actions and reactions.
legendary_description: The false hydra can take 1 legendary actions, choosing from the options below. It can only take one legendary action at a time and only at the end of another creature's turn. The false hydra regains spent legendary actions at the start of its turn.
legendary_actions:
  - name: Sonic Pulse
    desc: The false hydra targets a creature within range of one of its heads and blasts a cone of noise. Creatures within a 10 foot cone take 12 (4d6) sonic damage.
```

## False Hydra's Head
Each head operates independently and has its own initiative.

```statblock
size: Medium
type: Fey, limb
alignment: Chaotic Evil
ac: 10
hp: 100
speed: fly 30 ft.
stats: [20, 10, 20, 4, 19, 24]
saves:
  - intelligence: 2
  - wisdom: 9
  - charisma: 12
skillsaves:
  - stealth: 10
condition_immunities: charmed, prone, stunned, knocked unconscious
senses: Blindsight 120ft., Passive Perception 14
cr: 0
languages: Understands the language of its victims
name: False Hydra's Head
traits:
  - name: Tight Grapple
    desc: If the target is Huge or smaller creature and is grappled, it takes 17 (3d8 + 5) constrict damage at the start of each of its turns until grapple ends. 
  - name: Growing Head Illusion
    desc: When a head dies, it emits gas that causes targets to believe new heads are growing. Other heads within 15 feet receive mirror image for 1 minute.
actions:
  - name: Bite
    desc: Melee Weapon Attack_ +11 to hit, one target. On successful hit deals 17 (2d12 + 5) bludgeoning/slashing/piercing damage.
  - name: Engulf
    desc: The false hydra's head engulfs a Large or smaller creature, grappled by it. The engulfed target is blinded, restrained, and unable to breathe, and it must succeed on a DC 25 Constitution saving throw at the start of each of the false hydra head's turns or take 30 (4d10+10) bludgeoning damage. If the false hydra's head moves, the engulfed target moves with it. The false hydra can only have one creature engulfed at a time. If the target's HP drops to 0 while engulfed, or dies, it is immediately consumed.
```
## Severed False Hydra's Head
```statblock
size: Medium
type: Fey, limb
alignment: Chaotic Evil
ac: 10
hp: 50
speed: fly 30 ft.
stats: [20, 10, 20, 4, 19, 24]
saves:
  - intelligence: 2
  - wisdom: 9
  - charisma: 12
skillsaves:
  - stealth: 10
condition_immunities: charmed, prone, stunned, knocked unconscious
senses: Blindsight 120ft., Passive Perception 14
cr: 0
languages: Understands the language of its victims
name: Severed False Hydra's Head
traits:
  - name: Tight Grapple
    desc: If the target is Huge or smaller creature and is grappled, it takes 17 (3d8 + 5) constrict damage at the start of each of its turns until grapple ends. 
actions:
  - name: Bite
    desc: Melee Weapon Attack_ +11 to hit, one target. On successful hit deals 17 (2d12 + 5) bludgeoning/slashing/piercing damage.
  - name: Engulf
    desc: The false hydra's head engulfs a Large or smaller creature, grappled by it. The engulfed target is blinded, restrained, and unable to breathe, and it must succeed on a DC 25 Constitution saving throw at the start of each of the false hydra head's turns or take 30 (4d10+10) bludgeoning damage. If the false hydra's head moves, the engulfed target moves with it. The false hydra can only have one creature engulfed at a time. If the target's HP drops to 0 while engulfed, or dies, it is immediately consumed.
```