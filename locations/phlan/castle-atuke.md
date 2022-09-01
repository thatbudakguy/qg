---
aliases: ["Castle Atuke"]
---
# Castle Atuke
## Appearance

> Castle Atuke was clearly once a grand seat of power, but several centuries' worth of neglect has reduced it to little more than a pile of stones shrouded in mist and quietly wasting away in the muck and mire of the Moonsea. Two tall circular towers dominate the rear of the stone structure, while a sprawling first floor has disintegrated in places, leaving once-opulent rooms open to the elements.
## Background
### House Stavenger
A noble house of Cormyr, the Stavengers migrated to the still-raw frontier of the Moonsea in the early 800s DR after being granted a barony by the crown. The house was known to employ legions of mercenaries with copious coin and dominated early Moonsea politics, such as they were. Baron Jaxyn Stavenger was a known Alchemist who sought the Chrysopoeia, attempting to transmute base substances into Gold. His wife Savenna was famous for her vanity and traveled with a personal guard of mercenaries at all times as a diplomatic envoy.
### The Doom of Atuke
After Jaxyn prayed for the knowledge of the Chrysopoeia, a being appeared to him in a dream cloaked in shadow, calling itself a great forest spirit. The spirit promised to grant his wish for knowledge if Jaxyn performed a ritual and offered his left hand as tribute. But the spirit was a nightwalker from the Plane of Shadow, and when it came from the forest it gave knowledge he could not refuse, bringing ruin on his mind and his house. The Stavengers and their servants became undead, haunting the remains of their new home in the Moonsea.
## Areas
The entire castle is desecrated by a permanent effect that imbues insanity for 1d4 hours if a DC 10 INT save is failed: an insane creature can't take actions, can't understand what other creatures say, can't read, and speaks only in gibberish. The DM controls its movement, which is erratic. The effect ends if the creature is targeted with a *calm emotions* spell.
### First floor
#### Armory
Inhabited largely by Mercenary Shadows. Ancient, rusting weapons are here.
#### Kitchen
Savenna ordered her Mercenaries to barricade an unfortunate party of four would-be tomb robbers in here decades ago. Their corpses have long since rotted away to bone, and the remains of one who attempted to make an escape are visible in the corridor beyond.
#### Chapel
There was once a shrine to Lathander in this room, but it's obvious to a cleric that any trace of holiness is long gone. In fact, it stinks of negative energy, and a DC 16 investigation check reveals a hidden compartment at the altar in which a mummified hand is collecting dust — Jaxyn's left hand, which he cut off as tribute to Vecna.
### Second floor
#### Laboratory
Jaxyn sometimes haunts this area, staring at his former instruments and whispering to himself about the consummation of his research. The rusting alchemical equipment here is no use to anyone anymore, but it was obviously quite high-quality. The pursuit of alchemy mostly died out on Faerun centuries ago.
#### Savenna's Chambers
Savenna is no longer able to travel to this room during the day, since its roof has partially collapsed and the daylight pains her. Most of its lavish furnishings have long since turned to dust. A DC 14 investigation check turns up a peridot necklace under a pile of stones and ceiling beams, worth 25gp.
### Third floor
The tower housing Jaxyn's laboratory had a third floor once, but nearly nothing remains of it — only a half-circle of enclosing wall and a rotting wooden floor. None of the ghosts of the castle come here, since it is somewhat exposed during the day. The Lord Sage is keeping a quiet vigil here, occasionally feeding Jaxyn pieces of arcane knowledge to keep him at bay.
## Inhabitants
### Jaxyn Stavenger
Jaxyn was transformed into an Allip by the Doom, his thirst for knowledge tying his spirit forever to the material plane in insanity. He wanders the castle babbling to himself about the nature of materiality and offers to enlighten any whose ear he can catch. If anyone voluntarily consents to listen to him, they too are transformed into an Allip.
```statblock
monster: Allip
name: Jaxyn Stavenger
languages: common
```
### Savenna Stavenger
Savenna was transformed into a Wraith by the Doom, her vanity the only part of her soul that remained as a blind rage against those still living. She orders the Shadows of her Mercenaries to attack on sight any non-undead visitor to Castle Atuke and transforms them into a Specter. Savenna can't leave the safety of the enclosed rooms at the rear of the first floor during the daytime, but roams freely at night.
```statblock
monster: Wraith
name: Savenna Stavenger
languages: common
```
### Mercenaries
The mercenaries in the employ of the Stavengers were slain instantly, leaving only a shadow of their spirits animating their former armor and weapons. They pervade the lower floors of the castle, but do not generally travel to any of the towers. They respond to verbal commands from any member of House Stavenger.
```statblock
name: Mercenary Shadow
size: Medium
type: construct
alignment: neutral evil
hp: 33
speed: 25 ft.
stats: [14, 11, 13, 1, 3, 1]
damage_immunities: necrotic, poison
condition_immunities: blinded, charmed, deafened, exhaustion, frightened, paralyzed, petrified, poisoned
senses: blindsight 60ft. (blind beyond this radius), passive Perception 6
cr: 1
languages: common
actions:
- name: Multiattack
  desc: The Shadow makes two melee attacks.
- name: Longsword
  desc: "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 6 (1d8+2) slashing damage."
- name: Heavy crossbow
  desc: "Ranged Weapon Attack: +2 to hit, range 100/400 ft., one target. Hit: 5 (1d10) piercing damage."
```
### Spectres
The would-be tomb robbers who starved to death in the kitchen were raised by Savenna as merciless Spectres, intent on killing anything with a soul that wanders onto the grounds of the castle.
```statblock
monster: Specter
```
