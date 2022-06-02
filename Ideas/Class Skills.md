## Artificer - Adept Analysis
You can immediately identify any spell you can percieve being cast, unless cast using Metamagic.  Gain a maximum number of Comprehension Points equal to your Proficiency Bonus, which are restored after a short or long rest.  When you identify a spell in this way, you may choose to fix that spell in your mind and learn it temporarily.  You may choose to cast that spell using Comprehension Points, instead of spell slots, where the required number of Comprehension Points is equal to the level of the spell slot you would like to use, allowing for higher level versions of spells to be cast in this way.  Only one spell may be fixed in your mind at a time.

## Barbarian - Improvised Fighting
When using any improvised weapon that bears no resemblance to a weapon, attacks may be rolled instead as 1d6 + Strength Modifier.  While the barbarian has one hand free, they may use a bonus action to pick up and make a ranged attack with a nearby rock or stone, if one is available.  While the barbarian has one hand free, they may use a bonus action to make an unarmed strike dealing 1d4 damage.

## Barbarian (Alternate) - Wild Strength
When using any melee weapon which adds damage based on the Strength modifier, you may choose to ignore the value of the weapon's base damage roll, which is generally Piercing, Bludgeoning, or Slashing damage.  If you do, instead roll Xd4 + your Proficiency Bonus of the same damage type as the weapon, where X is equal to your Strength modifier, plus one if wielded with two hands.  Any additional damage that is added by magical effects is still added.  If this is done with an improvised or weakened weapon, that weapon breaks and becomes unusable after dealing damage.

## Bard - Battle Song
As a bonus action, you may expend two uses of Bardic Inspiration to begin a prolonged song or chant of battle.  This song requires you to maintain concentration and is ended if you are no longer able to speak, lose concentration, or after 30 seconds.  While sustaining the song, Bardic Inspiration may be without expending uses, and when the song begins you may immediately use Bardic Inspiration.

## Cleric - Favored Art
After a long rest, select one 1st-level spell you know.  You may cast that spell as a cantrip a number of times equal to your Proficiency Bonus until your next long rest.

## Druid - Animal Adaptation
As a bonus action while using Wild Shape, you may select another creature to assume the shape of without first reverting to your normal form.  Doing so does not require an additional use of Wild Shape, but you do not regain any hit points.  If your current hit points are less than the new maximum, they are reduced to the new maximum.  Additionally, at 14th level the Max CR is increased to 2.

## Druid (Alternative) - Sprout
After a long rest, the Druid may create a single Sprout Seed.  A single Druid may have created up to 3 of these seeds at any time, with the oldest seed being destroyed when attempting to create a new one.  To create a seed, the Druid must expend a single spell slot, which determines the type of seed that is created.  Seeds may be used by an sentient creature, even while in Wild Shape.
| Spell Slot Level | Seed Type |
| ---------------- | --------- |
| 1st - 3th        | Creeper   |
| 4th - 6th        | Bramble   |
| 7th - 9th        | Fly Trap  |

```statblock
traits:
 - name: Creeper
   desc: You may use this seed only as a Reaction to missing with a melee attack against a Large or smaller creature.  The target must make a Dexterity saving throw against your Spell Save DC.  Upon failure, the target is restrained by rapidly growing vines that sprout from the seed.  At the start of each of their turns, they may make a Strength Saving Throw against your Spell Save DC, ending the effect upon success.  While restrained, the target cannot cast spells that require a somatic component.
 - name: Bramble
   desc: As a bonus action, this seed sprouts within the wielder's hand into a bramble whip.  The whip lasts for 1 minute and has the same stats as a Whip + 3.  Upon a successful hit with the whip, the number of thorns stuck in the creature is doubled, to a minimum of 1 or maximum of 16.  A creature takes 1 magical piercing damage at the start of their turn for each thorn.  All thorns disappear when the whip disappears.
 - name: Fly Trap
   desc: You may throw this seed to any point on the ground or in the water, then will it to activate.  Once activated, if any water source touches the seed it will immediately sprout into a large fly trap.  Creatures that are Large or smaller within a 20ft. radius must make a Dexterity saving throw against your Spell Save DC.  Upon failure, they are forcibly pulled toward the spot where the seed was thrown as the fly trap closes around them.  Any creature which starts its turn within the fly trap takes 1d4 Acid damage and cannot cast spells which require a somatic component.  The fly trap is a creature with maximum hit points equal to 4 times your Druid level, and releases all trapped creatures when killed.
```

## Fighter - Signature Move
All fighters at level 1 and 11 get to select a Signature Move, which may only be used during combat.  This can be any maneuver from the Battle Master’s list.  The maneuver may be performed without expending the superiority die.  If you do so, you perform the maneuver without rolling the superiority die, unless the maneuver would have no effect without rolling the die, in which case you roll 1d4.  If the maneuver requires or affects an attack, the attack roll suffers a 1d4 penalty.   The fighter gets one Superiority Die at level 1 and another at level 11.

## Monk - Unlock Limits
As your action, perform all possible unarmed attacks, including Extra Attack and Martial Arts, that do not require spending ki points targeting yourself.  After taking damage from these attacks, increase your movement speed by 10ft, AC by 1, and gain an additional Extra Attack for 1 minute.  You may not use this feature again until after a long rest.

## Monk (Alternative) - Martial Spirit
Consuming any potion that restores health also restores 1d4 Ki Points.  As a Bonus Action, the Monk may expend 1 Ki Point to increase the range of their Unarmed Attack to 30ft and select any other damage type for the attacks to deal, until the end of their turn.  Attacks made using Flurry of Blows do not gain this benefit.  The monk may spend 2 Ki Points to emit a thread of Divine Sense.

```statblock
columns: 2
name: Divine Sense
size: Tiny
type: spirit
ac: 10
hp: 10
hit_dice: 10
speed: 5ft flying per Monk level
senses: blindsight 10ft.  hearing 30ft.
damage_immunities: Bludgeoning, Piercing, or Slashing damage from Non-Magical Weapons
traits:
 - name: Invisible
   desc: The thread of Divine Sense is always invisible.
 - name: Intangible
   desc: Creatures pass through the thread of Divine Sense without contacting it.  It has a diameter of 1in. for the purposes of movement through the environment.
 - name: Ceaseless
   desc: The thread of Divine Sense must move its maximum speed every turn.  Once it has traveled a distance of 50ft per Monk level, it must retract back to the monk.
 - name: Soul Link
   desc: As a part of your soul, the monk sees, hears, and feels everything the thread of Divine Sense does.  If destroyed, the monk suffers 1d10 damage and loses half their remaining Ki Points.  While the Divine Sense exists, the monk is Unconscious.
```

A monk can sit down and spend 2 Ki Points render themselves unconscious to send out a thread of Divine Sense.  This invisible, physically intangible thread can be detected by Detect Magic, cannot pass through solid objects, is approximately 1 inch in diameter, and travels constantly at a rate of 5 feet for every point of Wisdom the monk has to a maximum traveled distance of 50 feet for every point of Wisdom the monk has.  The entire length of the thread can transmits sound and sight back to the monk and blind sight to 10 feet.  Once it reaches its maximum length, the thread begins retracting along the same path.  Creatures that detect the thread may destroy it using magical weapons or spells



## Monk (Alternative) - Martial Techniques
Gain the following martial techniques as your level increases:
```statblock
traits:
 - name: Lightning Step (3rd Level)
   desc: Expend 1 Ki Point to move 10 feet without provoking Opportunity Attacks.
 - name: Soul Strike (6th Level)
   desc: Upon hitting with an Unarmed attack or a Monk weapon, expend 1 Ki Point to deal an additional 1d8 Psychic damage
 - name: Wind Step (9th Level)
   desc: Expend 1 Ki Point to move 10 feet in any direction, even if not currently on the ground.
 - name: Wave Projection Fist (12th Level)
   desc: Expend 2 Ki points to increase your Unarmed attack reach by 25ft until the start of your next turn.
 - name: Ki Guard (15th Level)
   desc: As a Reaction to being targeted with an attack, you may expend 1 Ki Point to increase your AC by 2 until the start of your next turn.
 - name: Martial Domain (18th Level)
   desc: As a Bonus Action, expend 4 Ki Points to create a Martial Domain with a radius of 20ft centered on your current location.  While inside this domain, you gain advantage on Unarmed attacks and attacks with a Monk weapon.  The domain lasts for 60 seconds and may be ended early as a Free Action.  When the domain ends, it collapses on itself to deal 1d8 Force damage to all creatures within, except you.
```

## Monk Subclass - Tempered Body
### Way of the Tempered Body
Monks of the Way of the Tempered Body have trained their physical body to withstand immense damage without yielding.  This strength and durability have surpassed the limits of normal beings.

### Kinetic Accumulation
When the Monk is hit with an attack that would deal Bludgeoning damage, they store 2 points of Kinetic Energy.  Additionally, the monk gains points of Kinetic Energy equal to any damage they take from non-spell attacks.  10 points of Kinetic Energy may be used in place of a Ki Point.  At the end of the Monk's turn, they lose all Kinetic Energy.

### Brace Stance
As a reaction to taking damage, you may expend 1 Ki Point to reduce the damage taken by half, but also reduce your movement speed by half during your next turn.  At 15th level, if the attack was a non-spell attack, you may choose to roll an unarmed attack and deflect up to that much damage from the resisted amount to another valid target within range of the original attack.

### Recoil Burst
For every 5 points of Kinetic Energy you expend, gain 5 feet of movement this turn.  Movement done in this way does not provoke Opportunity Attacks.

### Golden Body
As a bonus action, you may expend 2 Ki Points to emit a golden light from your body for 20 seconds (2 rounds after the current one).  You shed bright light for a radius of 15 feet, and dim light for an additional 15 feet.  While emitting that light, your melee attacks deal an additional 1d4 Radiant damage.

## Paladin - Lightbringer
Gain proficiency in Persuasion and add an additional +3 to all rolls for Persuasion.  A favorable status within society means you will immediately have good standing and more clout in any town or city you visit where you're known or recognized as a Paladin.  It's not unusual for lords and nobles to offer you food, lodging, work, or information as they attempt to curry favor with you.

You know Charm Person and may cast it without using a spell slot when targeting non-hostile creatures.  You know Compelled Duel and may cast it without using a spell slot.  Gain +2 to attack rolls against Undead creatures.  Gain +2 to attack rolls against Frightened creatures.

## Ranger - Wilderness Training
Rangers all know True Strike and Speak with Animals, and they don’t count against their known spells.  At 5th level, the ranger may cast True Strike upon their attacker as a reaction to being targeted with an attack.  At 11th level, the ranger may cast True Strike as a Bonus Action against any target that they did not attack this turn.  At 15th level, True Strike no longer requires concentration.

Rangers gain +3 to all Nature, Survival, and Animal Handling rolls.  While using their Primeval Awareness, Rangers gain an accurate and detailed understanding of the terrain and pathways within range.

## Rogue - Toolkit
Rogues are able to craft a large number of tools for use in their trade.  Each tool has its own construction time, cost, weight, and usage.
```statblock
traits:
 - name: Flashbomb
   desc: 0.5lbs, 5gp, 1 hour.  As an action, you can throw this up to 30 feet, exploding on impact.  Each creature within 15 feet must make either a DC 15 Constitution saving throw or become Deafened for 2 turns.  Each creature within 60 feet with line of sight toward the explosion must make a DC 13 Dexterity saving throw or become Blinded for 2 turns.  If the creature has Sunlight Sensitivity, they immediately fail the Dexterity saving throw.  The burst can be heard up to 1000 feet away.
 - name: Glowbolt
   desc: 0.1lbs, 5sp, 15 minutes.  This bolt may be fired from any crossbow.  It glows bright for the duration of its flight, losing its glow 6 seconds after impacting a target.  An invisible creature struck with this bolt may be attacked by sighted creatures without imposing disadvantage until the glow fades.
 - name: Material Scope
   desc: 7lbs, 200gp, 8 hours.  When building this scope, you must select either Wood, Stone, or Metal.  Using the scope, you may spend 10 minutes of careful inspection of a surface or object constructed of the chosen material to observe inside or beyond it.  The scope can see through 1 foot of wood, 6 inches of stone, and 1 inch of metal.  If observation reveals a lock or trap, you gain advantage on attempts to pick or disarm.
 - name: Needle Sleeve
   desc: 3lbs, 12gp, 4 hours.  You cannot wear any additional gloves while this sleeve is equipped.  The sleeve contains 12 throwing needles sewn carefully as to not inhibit movement.  As a bonus action, you may draw and throw a needle as an attack against a target within a range of 20/60ft. for 1d4 piercing damage.  Upon a successful hit, the target must make a Constitution saving throw with a DC equal to 10 + your Proficiency Bonus or be Poisoned for 2 turns.
```

## Sorcerer - Font of Magic
You may use Sorcery Points to restore spell slots to other creatures.  When doing so, you may reduce the spell slot restored by 1 level to target an additional creature other than yourself.  For example, by paying the cost to restore a 3rd Level spell slot, you may restore a 2nd Level spell slot to 2 creatures or a 1st Level spell slot to 3 different creatures.  Instead of restoring a spell slot, you may restore 1d8 + your Proficiency Bonus Hit Points per level of the spell slot that would have been restored.

## Sorcerer (Alternative) - Blood Magic
As an action, you may restore any number of Sorcery Points.  For each Sorcery Point restored, gain a point of Blood Curse.  For each point of Blood Curse, reduce your Max Hit Points by 2.  If knocked Unconcious with any points of Blood Curse, immediately fail one Death Saving Throw.  If knocked Unconscious with more than 10 points of Blood Curse, immediately fail a second Death Saving Throw.  If Remove Curse is used to remove the Blood Curse, increase Exhaustion to 4 points if less than 4 points.

## Warlock - Servant of Many Masters
You no longer select a single Pact Boon as a Warlock, but have all of them.  However, you may only have one active Boon at a time, and may change which boon is active as a Bonus Action.  When you do, any items or creatures associated with the previous Boon are banished to another plane.  When changing to a previously active Boon, the items or creatures assocated with that Boon are returned from banishment to their previous wielder, or a valid location within 30 feet.  Duration timers still continue while any creatures or items are banished.  Any Eldritch Invocations which require a certain Pact Boon will only be usable while that is your active Boon.

## Wizard - A Thousand Words
The wizard may, as an Action, expend a spell slot to transform any item or willing creature they touch into text within their spellbook.  This does not act as a pocket dimension, like Bag of Holding or Portable Hole. The target's every detail is accurately and immutably transcribed within the spellbook and is used to reconstitute them later. While within the spellbook, a creature may only interact with the world by causing new words to appear within the pages, but still retains their perception.  The wizard may expend a spell slot to restore any transcribed target exactly as they were when they entered the book, materializing at any visible space within 30 feet.  A number of creatures or items equal to your Proficiency Bonus may be transcribed at any one time, and they are all destroyed if the book is destroyed.

## Wizard (Alternative) - Protracted Casting
For any spell that may be cast using a higher level spell slot, you may willingly extend the casting time of that spell to span multiple turns, known as a Protracted Casting.  If you do, you must maintain concentration on the spell until the time that it is finally cast.  At the start of any turn where you have a Protracted Casting, you must decide whether to release the spell or to sustain your concentration.  If you release the spell, it does not require your action but is still considered as a leveled spell cast during this turn, so you may only cast Cantrips for the remainder of the turn.  If you wish to sustain the spell, you must expend a spell slot of any level.  The level of the spell slot expended is added to the total number of levels in the Protracted Casting, allowing higher level spells than you might normally be able to cast.  In this way, you may cast spells up to 12th Level or the natural limit of the spell, whichever is lower.
