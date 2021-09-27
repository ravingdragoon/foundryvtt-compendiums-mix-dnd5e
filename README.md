
![](https://img.shields.io/badge/Foundry-v0.8.9-informational)

# FoundryVTT Compendiums Mix DnD5e
  
This is a collection of some public projects compendiums:

- [Kobold Press OGL Compendium](http://kpogl.wdfiles.com/local--files/home:home/module.json) version 0.26
- [Kobold Press OGL Compendium with images](Personal compendium with some images form the OGL Kobold Press Site)
- [Summoner](https://github.com/Jonwh25/summoner) version 1.0.18
- [Supplemental Bestiary Pack](https://github.com/sparkcity/fvtt-supplementalbestiary) version 2.2.0
- [FoundryVTT Lingering Injuries](https://gitlab.com/p4535992/foundryvtt-lingering-injuries) version 1.0.2
- [Innocenti Looting](https://github.com/rinnocenti/innocenti-looting) version 0.3.1
- [1001 Fish](https://github.com/cswendrowski/FoundryVTT-1000-Fish) version 1.1.0
- [FoundryVTT-FantasyPlants](https://github.com/KyleBishop/FoundryVTT-FantasyPlants) version 1.0.0
- [Grim Hollow Weapon Properties](https://github.com/TheDraggo/GrimHollowWeaponProperties) version 0.2
- [Draggos Mod](https://github.com/TheDraggo/DraggosMods) version 0.1
- [Sly Flourish' 1d20 Lists for D&D Adventure Inspiration](https://gitlab.com/fohswe/sf-adventure-inspiration) version 0.1.0
- [Modular Trains](https://www.reddit.com/r/FoundryVTT/comments/mgc1m6/modular_trains_module_just_a_simple_few_tokens_to/)
- [Copper Dragon's Hoard](https://github.com/copperdragongames/copperdragonhoard) version 0.1.4
- [Flirtatious Foundry Maps 1.1.1](https://github.com/FlirtatiousMule/flirtatiousfoundry) version 1.1.1
- [Dragon Flagon Architect](https://github.com/flamewave000/dragonflagon-arch) version 2.1.2
- [DnD5 Cheatsheet](https://github.com/pchouzenoux/foundryvtt-dnd5-cheatsheet) version 0.0.6
- [IW] version Commits on Jul 31, 2021

**this is just a "personal" use module because some of these projects seem abbandoned or not maintained (or i just need the compendium without all the other features) and foundryvtt 0.8.X is annoying with all the warnings, but be free to use if you find useful**

**If any author of the original projects does not agree to use their projects on this, feel free to contact me or open an issue and I will remove the references and the code as soon as possible**

The only work of this module is to import the compendium and colored the title of the compendium.

## Installation

It's always easiest to install modules from the in game add-on browser.

To install this module manually:
1.  Inside the Foundry "Configuration and Setup" screen, click "Add-on Modules"
2.  Click "Install Module"
3.  In the "Manifest URL" field, paste the following url:
`https://github.com/ravingdragoon/foundryvtt-compendiums-mix-dnd5e/releases/latest/download/module.json`
4.  Click 'Install' and wait for installation to complete
5.  Don't forget to enable the module in game using the "Manage Module" button

## [Kobold Press OGL Compendium](http://kpogl.wdfiles.com/local--files/home:home/module.json)

## [Summoner](https://github.com/Jonwh25/summoner)

DnD5e compendium for spells like Find Familiar

This FoundryVTT Module adds a simple compendium pack to help with DnD5e spells that summon creatures.
It is nothing fancy. My players were casting find familiar and I tried to use the npc creatures that
are in the DnD5e system and it wasn't working.  So all I did was create actor/player types for each 
creature they could summon.

Hope this saves you some time.  

Right now this only supports the following spells:
* Find Familiar
* Unseen Servant

### Updated

* Added new find familiar macro. You can find it in the macro compendium.

### How to Use It

* Go to the compendium tab and you will find the Summoner compendium.
* Select the creature that the player wants to summon and right click it and select import
* Finally, assign permissions to the player so they can interact with the token.

## [Supplemental Bestiary Pack](https://github.com/sparkcity/fvtt-supplementalbestiary)

A module that adds homebrew creatures to your D&D 5e game.

### Description

This module contains additional homebrewed monsters for D&D 5E to be used in Foundry VTT.
* Current Count: 45

## [FoundryVTT Lingering Injuries](https://gitlab.com/p4535992/foundryvtt-lingering-injuries)

Lingering Injuries by Damage Type

#### A compendium for use the Lingering Injuries by Damage Type, based on the article (http://farlandworld.com/injuries.html)

It's up to you to decide when to check for a lingering injury. A creature might sustain a lingering injury under the following circumstances:

- When it takes a critical hit.
- When it drops to 0 hit points but isn't killed outright.
- When it fails a death saving throw by 5 or more.

To determine the nature of the injury, determine the type of damage that triggered the injury and roll on the appropriate table below that corresponds to the damage type. If multiple types of damage caused the injury, use the type that dealt the majority of damage, or randomly determine the damage type to use when you roll for the lingering injury. 

These tables assume a typical humanoid physiology, but you can adapt the results for creatures with different body types. If you choose, you can also allow injuries that require regeneration or other high level magic to heal naturally, given a substantial amount of time.

The damages types are:

##### Acid

|||
|--- |--- |
|d20|Lingering Injury|
|1|Blindness. Your eyes are destroyed; you gain the blinded condition. Magic such as the regenerate spell can restore your sight.|
|2|Partial Blindness. Your eyes are damaged; you have disadvantage on Wisdom (Perception) checks that rely on sight and on ranged attack rolls. Magic such as the regenerate spell can heal the damage to your eyes. If you have already suffered partial blindness, you're blinded.|
|3|Destroyed Hand. You can no longer hold anything with two hands, and you can hold only a single object at a time. Magic such as the regenerate spell can restore the lost appendage.|
|4|Destroyed Foot or Leg. Your speed on foot is halved, and you must use a crutch or cane to move. You fall prone after using the Dash action. You have disadvantage on Dexterity checks made to balance. Magic such as the regenerate spell can restore the damaged appendage.|
|5-7|Major Neuralgia. You are in constant pain from nerve damage. Whenever you attempt an action in combat, you must make a DC 15 Constitution saving throw. On a failed save, you lose your action and can't use reactions until the start of your next turn.Magical healing of 6th level or higher, such as heal and regenerate, cures the neuralgia, or if you spend twenty days doing nothing but resting it resolves on its own.|
|8-10|Minor Neuralgia. This has the same effect as Major Neuralgia above, except that the save DC is 10, and it only takes ten days to resolve on its own.|
|11-13|Horrible Disfigurement. You have acid burns to the extent that the scars can't be easily concealed. You have disadvantage on Charisma (Persuasion) checks and advantage on Charisma (Intimidation) checks. Magical healing of 6th level or higher, such as heal and regenerate, removes the acid burn scar.|
|14-16|Blisters. You have severe blisters. You have disadvantage on Dexterity checks. The blisters heal if you receive magical healing. Alternatively, someone can tend to the blisters and make a DC 15 Wisdom (Medicine) check once every 24 hours. After seven successes, the blisters heal.|
|17-20|Minor Disfigurement. You have acid burn scars, but they don’t have any adverse effect. Magical healing of 6th level or higher, such as heal and regenerate, removes the acid burn scars.|

##### Bludgeoning

|||
|--- |--- |
|d20|Lingering Injury|
|1|Brain Injury. You have suffered a brain injury. You have disadvantage on Intelligence, Wisdom, and Charisma checks, as well as Intelligence, Wisdom, and Charisma saving throws. If you fail a saving throw against bludgeoning damage, force damage, or psychic damage, you are also stunned until the end of your next turn. Magic such as the regenerate spell can restore your full brain function.|
|2|Broken leg. Your speed on foot is halved, and you must use a cane or crutch to move. You fall prone after using the Dash action. You have disadvantage on Dexterity checks made to balance. If your leg is splinted with a successful DC 15 Wisdom (Medicine) check, then magical healing of 6th level or higher, such as heal and regenerate, mends the broken leg , or it will heal naturally in 8 weeks. If it is not splinted before it's healed or allowed to heal, the effects remain until it is rebroken and splinted.|
|3|Broken arm. You can no longer hold anything with two hands, and you can hold only a single object at a time. If your arm is splinted with a successful DC 15 Wisdom (Medicine) check, then magical healing of 6th level or higher, such as heal and regenerate, mends the broken leg, or it will heal naturally in 8 weeks. If it is not splinted before it's healed or allowed to heal, the effects remain until it is rebroken and splinted.|
|4|Internal Injury. Whenever you attempt an action in combat, you must make a DC 15 Constitution saving throw. On a failed save, you lose your action and can't use reactions until the start of your next turn. Magical healing of 6th level or higher, such as heal and regenerate, cure the injury, or if you spend ten days doing nothing but resting, it will heal naturally.|
|5-7|Broken Ribs. This has the same effect as Internal Injury above, except that the save DC is 10.|
|8-10|Major Concussion. You have disadvantage on Intelligence checks, Wisdom checks, and Charisma checks, as well as Constitution saving throws to maintain concentration. Magical healing of 6th level or higher, such as heal and regenerate, cures the concussion. Alternately, it heals on its own in four weeks.|
|11-13|Minor Concussion. You have disadvantage on Intelligence checks. The concussion heals if you receive any magical healing; alternately it heals on its own in two weeks. If you already have a minor concussion, you suffer a major concussion.|
|14-16|Severe bruising. You suffer severe bruising over an extensive portion of your anatomy. Anytime you suffer bludgeoning or force damage, you suffer an additional point of bludgeoning or force damage. The bruising heals if you receive magical healing. Alternately, it heals on its own in 2 week.|
|17-20|Broken Nose. Your broken nose is painful but doesn't have any adverse effect. Any magical healing mends your nose, although it may heal crooked if it is crooked when the healing is applied.|

##### Cold

|||
|--- |--- |
|d20|Lingering Injury|
|1|Ocular Damage. One of your corneas is damaged from frostbite. You have disadvantage on Wisdom (Perception) checks that rely on sight and on ranged attack rolls. Magic such as the regenerate spell can restore the damaged cornea. If you have no corneas that remain undamaged after sustaining this injury, you're blinded.|
|2|Systemic Damage from Frostbite. You have disadvantage on Strength, Dexterity, and Constitution ability checks and Strength, Dexterity, and Constitution saving throws. Magic such as the regenerate spell cures this damage.|
|3|Gangrene of the Hand. You can no longer hold anything with two hands, and you can hold only a single object at a time. Magic such as the regenerate spell can restore the crushed appendage.|
|4|Gangrene of the Foot. Your speed on foot is halved, and you must use a cane or crutch to move. You fall prone after using the Dash action. You have disadvantage on Dexterity checks made to balance. Magic such as the regenerate spell can restore the crushed appendage.|
|5-7|Major Neuralgia. You have constant, painful nerve damage over a large portion of your body. Whenever you attempt an action in combat, you must make a DC 15 Constitution saving throw. On a failed save, you lose your action and can't use reactions until the start of your next turn. Magical healing of 6th level or higher, such as heal and regenerate, cures the neuralgia, or if you spend twenty days doing nothing but resting it resolves on its own.|
|8-10|Frostbitten Foot. Your speed on foot is reduced by 5 feet. You must make a DC 10 Dexterity saving throw after using the Dash action. If you fail the save, you fall prone. Magical healing cures the frostbite. Alternately, your foot can be treated with a successful DC 15 Wisdom (Medicine) check, in which case it will heal naturally in 2 weeks.|
|11-13|Frostbitten hand. Randomly determine which hand has been frostbitten. In order to grasp or manipulate an object with that hand, you must succeed at a DC 15 Dexterity check. Magical healing cures the frostbite. Alternately, your hand can be treated with a successful DC 15 Wisdom (Medicine) check, in which case it will heal naturally in 2 weeks.|
|14-16|Minor Neuralgia. This has the same effect as Major Neuralgia above, except that the save DC is 10 and it only takes ten days to resolve on its own.|
|17-20|Anosmia. You lose your sense of smell and taste. You automatically fail any ability checks that involve your sense of smell or taste. The condition heals if you receive any magical healing.|

##### Fire

|||
|--- |--- |
|d20|Lingering Injury|
|1|Lose an Eye. You have disadvantage on Wisdom (Perception) checks that rely on sight and on ranged attack rolls. Magic such as the regenerate spell can restore the lost eye. If you have no eyes left after sustaining this injury, you're blinded.|
|2|Fourth Degree Burns. You have disadvantage on ability checks and Strength, Dexterity, and Constitution saving throws. If you fail a saving throw against an effect that causes fire damage, you also gain the stunned condition until the end of your next turn. Magic such as the regenerate spell cures this damage. If you already have fourth degree burns, you must succeed at a DC 15 Constitution saving throw or die.|
|3|Third Degree Burns. You have disadvantage on ability checks and Constitution saving throws. If you fail a saving throw against an effect that causes fire damage, you also gain the stunned condition until the end of your next turn. Magic such as the regenerate spell cures this damage. Alternatively, someone can tend to the burns and make a DC 15 Wisdom (Medicine) check once every week. After ten successes, the burns heal. If you already have third degree burns, you instead suffer fourth degree burns.|
|4|Second Degree Burns. You have disadvantage on Strength, Dexterity, and Constitution checks. Magic such as the regenerate spell cures this damage. Alternately, they will heal on their own in 4 weeks. If you already have second degree burns, you instead suffer third degree burns.|
|5-7|Major Neuralgia. You have constant, painful nerve damage over a large portion of your body. Whenever you attempt an action in combat, you must make a DC 15 Constitution saving throw. On a failed save, you lose your action and can't use reactions until the start of your next turn. Magical healing of 6th level or higher, such as heal and regenerate, cures the neuralgia, or if you spend twenty days doing nothing but resting, it resolves on its own.|
|8-10|Minor Neuralgia. This has the same effect as Major Neuralgia above, except that the save DC is 10, and it will resolve on its own in ten days.|
|11-13|Horrible Disfigurement. You have burn scars to the extent that can't be easily concealed. You have disadvantage on Charisma (Persuasion) checks and advantage on Charisma (Intimidation) checks. Magical healing of 6th level or higher, such as heal and regenerate, removes the burn scars.|
|14-16|Blisters. You have severe blisters. You have disadvantage on Dexterity checks. The blisters heal if you receive magical healing. Alternatively, someone can tend to the blisters and make a DC 15 Wisdom (Medicine) check once every 24 hours. After seven successes, the blisters heal.|
|17-20|First Degree Burns. You have superficial but painful burns. Whenever you take fire damage, you take an additional 1 point of damage. Magical healing cures the burns; alternately, they will heal on their own in 2 weeks. If you already have first degree burns, you instead suffer second degree burns.|


##### Force

|||
|--- |--- |
|d20|Lingering Injury|
|1|Brain Injury. You have suffered a brain injury. You have disadvantage on Intelligence, Wisdom, and Charisma checks, as well as Intelligence, Wisdom, and Charisma saving throws. If you fail a saving throw against bludgeoning damage, force damage, or psychic damage, you are also stunned until the end of your next turn. Magic such as the regenerate spell can restore your full brain function.|
|2|Broken leg. Your speed on foot is halved, and you must use a cane or crutch to move. You fall prone after using the Dash action. You have disadvantage on Dexterity checks made to balance. If your leg is splinted with a successful DC 15 Wisdom (Medicine) check, then magical healing of 6th level or higher, such as heal and regenerate, mends the broken leg , or it will heal naturally in 8 weeks. If it is not splinted before it's healed or allowed to heal, the effects remain until it is rebroken and splinted.|
|3|Broken arm. You can no longer hold anything with two hands, and you can hold only a single object at a time. If your arm is splinted with a successful DC 15 Wisdom (Medicine) check, then magical healing of 6th level or higher, such as heal and regenerate, mends the broken leg, or it will heal naturally in 8 weeks. If it is not splinted before it's healed or allowed to heal, the effects remain until it is rebroken and splinted.|
|4|Internal Injury. Whenever you attempt an action in combat, you must make a DC 15 Constitution saving throw. On a failed save, you lose your action and can't use reactions until the start of your next turn. Magical healing of 6th level or higher, such as heal and regenerate, cure the injury, or if you spend ten days doing nothing but resting, it will heal naturally.|
|5-7|Broken Ribs. This has the same effect as Internal Injury above, except that the save DC is 10.|
|8-10|Major Concussion. You have disadvantage on Intelligence checks, Wisdom checks, and Charisma checks, as well as Constitution saving throws to maintain concentration. Magical healing of 6th level or higher, such as heal and regenerate, cures the concussion. Alternately, it heals on its own in four weeks.|
|11-13|Minor Concussion. You have disadvantage on Intelligence checks. The concussion heals if you receive any magical healing; alternately it heals on its own in two weeks. If you already have a minor concussion, you suffer a major concussion.|
|14-16|Severe bruising. You suffer severe bruising over an extensive portion of your anatomy. Anytime you suffer bludgeoning or force damage, you suffer an additional point of bludgeoning or force damage. The bruising heals if you receive magical healing. Alternately, it heals on its own in 2 week.|
|17-20|Broken Nose. Your broken nose is painful but doesn't have any adverse effect. Any magical healing mends your nose, although it may heal crooked if it is crooked when the healing is applied.|

##### Lightning

|||
|--- |--- |
|d20|Lingering Injury|
|1|Brain Injury. You have suffered a brain injury. You have disadvantage on Intelligence, Wisdom, and Charisma checks, as well as Intelligence, Wisdom, and Charisma saving throws. If you fail a saving throw against bludgeoning damage, force damage, or psychic damage, you are also stunned until the end of your next turn. Magic such as the regenerate spell can restore your full brain function.|
|2|Explosive Grounding of the Hand. You lose a hand. You can no longer hold anything with two hands, and you can hold only a single object at a time. Magic such as the regenerate spell can restore the lost appendage.|
|3|Explosive Grounding of the Foot. You lose a foot. Your speed on foot is halved, and you must use a cane or crutch to move unless you have a peg leg or other prosthesis. You fall prone after using the Dash action. You have disadvantage on Dexterity checks made to balance. Magic such as the regenerate spell can restore the lost appendage.|
|4|Kidney Failure. When you complete a long rest, you must succeed at a Constitution saving throw DC 15 or gain the poisoned condition until you complete a long rest. Magic such as the regenerate spell can cure your kidney failure. Alternatively, someone can tend to the kidney failure and make a DC 15 Wisdom (Medicine) check once every week. After ten successes, the kidney failure is resolved.|
|5-7|Arc Flash. Roll on the fire table.|
|8-10|Cardiac Injury. You gain a level of exhaustion which cannot be removed by normal means. If you fail a saving throw against fear or fear effects, you gain another level of exhaustion that can be removed by normal means. Magic such as the regenerate spell can heal your cardiac damage.|
|11-13|Skeletal Muscle Breakdown. You have disadvantage on Strength checks and Strength saving throws. Magic such as the regenerate spell can cure your muscle breakdown. Alternatively, it will resolve on its own in 6 weeks.|
|14-16|Muscle Spasms. You have disadvantage on Dexterity checks. Magical healing cures your muscle spasms. Alternatively, they will resolve on their own in 2 weeks.|
|17-20|Flash Burns. You have superficial burns. You turn red as a lobster, but otherwise suffer no mechanical effects. Magical healing cures your flash burns. Alternatively, they will heal on their own in 2 weeks.|

##### Necrotic

|||
|--- |--- |
|d20|Lingering Injury|
|1|Spiritual Injury. You are afflicted with intense apathy and depression. You have disadvantage on Intelligence, Wisdom, and Charisma ability checks and Intelligence, Wisdom, and Charisma saving throws. Magic such as the heal or regenerate spell can resolve your spiritual injury, but such spells must be cast by a cleric, druid, or other class that uses divine magic.|
|2|Withered Hand. You lose a hand. You can no longer hold anything with two hands, and you can hold only a single object at a time. Magic such as the regenerate spell can restore the lost appendage.|
|3|Withered Foot. Your speed on foot is halved, and you must use a cane or crutch to move. You fall prone after using the Dash action. You have disadvantage on Dexterity checks made to balance. Magic such as the regenerate spell can restore the lost appendage.|
|4|Major Organ Necrosis. Whenever you attempt an action in combat, you must make a DC 15 Constitution saving throw. On a failed save, you lose your action and can't use reactions until the start of your next turn. Magical healing of 6th level or higher, such as heal and regenerate, cures the Major Organ Necrosis.|
|5-7|Minor Organ Necrosis. This has the same effect as Major Organ Necrosis above, except that the save DC is 10.|
|8-10|Necrotic Stench. You smell like rotting flesh. You have disadvantage on Charisma (Persuasion) checks. Magical healing of 6th level or higher, such as heal and regenerate, removes the smell.|
|11-13|Necrotizing Wound. Your hit point maximum is reduced by 1 every 24 hours the wound persists. If your hit point maximum drops to 0, you die. The wound heals if you receive magical healing. Alternatively, someone can tend to the wound and make a DC 15 Wisdom (Medicine) check once every 24 hours. After ten successes, the wound heals.|
|14-16|Inflammation. Your muscles are irritated and inflamed. You have disadvantage on strength checks. Magical healing resolves the inflammation. Alternately, it will resolve on its own in two weeks.|
|17-20|Necrotic Discoloration. You get white and gray spots on your cheeks. The spots don't have any adverse effect. Magical healing of 6th level or higher, such as heal and regenerate, removes the spots.|

##### Piercing

|||
|--- |--- |
|d20|Lingering Injury|
|1|Lose an Eye. You have disadvantage on Wisdom (Perception) checks that rely on sight and on ranged attack rolls. Magic such as the regenerate spell can restore the lost eye. If you have no eyes left after sustaining this injury, you're blinded.|
|2|Throat Injury. You gain a level of exhaustion which cannot be removed by normal means. You also have disadvantage on constitution checks. Magic such as the regenerate spell can heal your throat injury.|
|3|Groin Injury. Your speed on foot is halved, and you must use a cane or crutch to move. You cannot take the Dash action. You are also sterile. Magic such as the regenerate spell can heal the groin injury.|
|4|Cardiac Injury. You gain a level of exhaustion which cannot be removed by normal means. If you fail a saving throw against fear or fear effects, you gain another level of exhaustion that can be removed by normal means. Magic such as the regenerate spell can heal your cardiac damage.|
|5-7|Organ Damage. Whenever you attempt an action in combat, you must make a DC 15 Constitution saving throw. On a failed save, you lose your action and can't use reactions until the start of your next turn. Magic such as the regenerate spell can cure your organ damage. Alternatively, someone can tend to the organ damage and make a DC 15 Wisdom (Medicine) check once every day. After ten successes, the organ damage is resolved.|
|8-10|Pierced Stomach. When you complete a long rest, you must succeed at a Constitution saving throw DC 10 or gain the poisoned condition until you complete a long rest. Magical healing of 6th level or higher, such as heal and regenerate, heals the pierced stomach, or if you spend ten days doing nothing but resting, it heals on its own.|
|11-13|Horrible Scar. You are disfigured to the extent that the wound can't be easily concealed . You have disadvantage on Charisma (Persuasion) checks and advantage on Charisma (Intimidation) checks. Magical healing of 6th level or higher, such as heal and regenerate, removes the scar.|
|14-16|Festering Wound. Your hit point maximum is reduced by 1 every 24 hours the wound persists. If your hit point maximum drops to 0, you die. The wound heals if you receive any magical healing. Alternatively, someone can tend to the wound and make a DC 15 Wisdom (Medicine) check once every 24 hours. After ten successes, the wound heals.|
|17-20|Minor Scar. The scar doesn't have any adverse effect. Magical healing of 6th level or higher, such as heal and regenerate, removes the scar.|

##### Poison

|||
|--- |--- |
|d20|Lingering Injury|
|1|Systemic Damage. You have disadvantage on Strength, Dexterity, and Constitution ability checks and Strength, Dexterity, and Constitution saving throws. Magic such as the regenerate spell cures this damage.|
|2|Major Liver Damage. When you complete a long rest, you must succeed at a Constitution saving throw DC 15 or gain the poisoned condition until you complete a long rest. Additionally, whenever you take poison damage, you take an additional 3 (1d6) poison damage. Anytime you drink alcohol or take another drug, you take 3 (1d6) poison damage. Magic such as the regenerate spell can cure your liver failure.|
|3|Minor Liver Damage. When you complete a long rest, you must succeed at a Constitution saving throw DC 10 or gain the poisoned condition until you complete a long rest. Additionally, whenever you take poison damage, you take an additional 2 (1d4) poison damage. Anytime you drink alcohol or take another drug, you take 2 (1d4) poison damage. Magic such as the regenerate spell can cure your liver failure.|
|4|Major Kidney Failure. When you complete a long rest, you must succeed at a Constitution saving throw DC 15 or gain the poisoned condition until you complete a long rest. Magic such as the regenerate spell can cure your kidney failure. Alternatively, someone can tend to the kidney failure and make a DC 15 Wisdom (Medicine) check once every week. After ten successes, the kidney failure is resolved.|
|5-7|Minor Kidney Failure. This has the same effect as Major Kidney Failure above, except that the save DC is 10 and only six Wisdom (Medicine) check successes are needed to resolve the Kidney Failure.|
|8-10|Cardiac Injury. You gain a level of exhaustion which cannot be removed by normal means. If you fail a saving throw against fear or fear effects, you gain another level of exhaustion that can be removed by normal means. Magic such as the regenerate spell can heal your cardiac damage.|
|11-13|Vertigo. You have disadvantage on Dexterity checks. Magic such as the regenerate spell can cure your vertigo. Alternatively, it will resolve on its own in 8 weeks.|
|14-16|Nausea. You have disadvantage on Constitution checks. Magical healing cures your nausea. Alternatively, it will resolve on its own in 4 weeks.|
|17-20|Minor nausea. You must succeed at a DC 10 Constitution saving throw before you can consume food. Magical healing cures your nausea. Alternatively, it will resolve on its own in 1 week.|

##### Psychic

|||
|--- |--- |
|d20|Lingering Injury|
|1|Brain Injury. You have suffered a brain injury. You have disadvantage on Intelligence, Wisdom, and Charisma checks, as well as Intelligence, Wisdom, and Charisma saving throws. If you fail a saving throw against bludgeoning damage, force damage, or psychic damage, you are also stunned until the end of your next turn. Magic such as the regenerate spell can restore your full brain function.|
|2|Indefinite Madness. Roll on the Indefinite Madness table in the Dungeon Masters Guide.|
|3|Severe headaches. You have disadvantage on Wisdom checks and Wisdom saving throws. If you fail a saving throw against bludgeoning damage, force damage, or psychic damage, you are also stunned until the end of your next turn. Magic such as the regenerate spell can cure your severe headaches.|
|4|Phobia. You develop a debilitating fear of something in the situation from which you gained your injury. For example, if you were damaged by a mind flayer, you might have a fear of octopuses. The DM will decide. When you are confronted with your phobia, you have disadvantage on all ability checks and saving throws. Magic such as the regenerate spell can cure your phobia.|
|5-7|Long-term Madness. Roll on the Long-term Madness table in the Dungeon Masters Guide. Your madness lasts twice as long.|
|8-10|Weak Persona. You have suffered damage to your sense of self. You have disadvantage on Charisma checks. Magic such as the regenerate spell can heal your weak persona. Alternately, it will heal on its own in four weeks.|
|11-13|Minor headaches. You have disadvantage on Wisdom checks. Magical healing cures your minor headaches. Alternately, they will resolve on their own in two weeks.|
|14-16|Inappropriate Volume. You can’t regulate your volume. You shout when you intend to whisper, and whisper when you intend to shout. Magical healing cures your inappropriate volume.|
|17-20|Short-term Madness. Roll on the Short-term Madness table in the Dungeon Masters Guide. Your madness lasts twice as long.|

##### Radiant

|||
|--- |--- |
|d20|Lingering Injury|
|1|Blindness. Your eyes are destroyed; you gain the blinded condition. Magic such as the regenerate spell can restore your sight.|
|2|Partial Blindness. Your retinas are damaged; you have disadvantage on Wisdom (Perception) checks that rely on sight and on ranged attack rolls. Magic such as the regenerate spell can restore the lost eye. If you have already suffered partial blindness, you're blinded.|
|3|Third Degree Burns. You have disadvantage on ability checks and Constitution saving throws. If you fail a saving throw against an effect that causes fire damage, you also gain the stunned condition until the end of your next turn. Magic such as the regenerate spell cures this damage. Alternatively, someone can tend to the burns and make a DC 15 Wisdom (Medicine) check once every week. After ten successes, the burns heal. If you already have third degree burns, you instead suffer fourth degree burns as per the Fire chart.|
|4|Second Degree Burns. You have disadvantage on Strength, Dexterity, and Constitution checks. Magic such as the regenerate spell cures this damage. Alternately, they will heal on their own in 4 weeks. If you already have second degree burns, you instead suffer third degree burns.|
|5-7|Large Skin Tumors. You develop several large, painful skin tumors. You have disadvantage on Charisma and Wisdom checks. Magic such as the regenerate spell cures your large skin tumors. If your large skin tumors are not cured within six months, you develop Systemic Damage as per the poison table.|
|8-10|Small Skin Tumors. You develop several small, painless skin tumor. You have disadvantage on Charisma checks. Magic such as the regenerate spell cures your small skin tumors. If your small skin tumors are not cured within one year, you develop Large Skin Tumors.|
|11-13|Blisters. You have severe blisters. You have disadvantage on Dexterity checks. The blisters heal if you receive magical healing. Alternatively, someone can tend to the blisters and make a DC 15 Wisdom (Medicine) check once every 24 hours. After seven successes, the blisters heal.|
|14-16|First Degree Burns. You have superficial but painful burns. Whenever you take fire damage, you take an additional 1 point of damage. Magical healing cures the burns; alternately, they will heal on their own in 2 weeks. If you already have first degree burns, you instead suffer second degree burns.|
|17-20|Hair Loss and Cosmetic Damage. Visible hair on your body burns away but will grow back as normal. If you have any exposed tattoos, they fade as if exposed to 10 years of sunlight.|

##### Slashing

|||
|--- |--- |
|d20|Lingering Injury|
|1|Lose an Eye. You have disadvantage on Wisdom (Perception) checks that rely on sight and on ranged attack rolls. Magic such as the regenerate spell can restore the lost eye. If you have no eyes left after sustaining this injury, you're blinded.|
|2|Lose an Arm or a Hand. You can no longer hold anything with two hands, and you can hold only a single object at a time. Magic such as the regenerate spell can restore the lost appendage.|
|3|Lose a Foot or Leg. Your speed on foot is halved, and you must use a cane or crutch to move unless you have a peg leg or other prosthesis. You fall prone after using the Dash action. You have disadvantage on Dexterity checks made to balance. Magic such as the regenerate spell can restore the lost appendage.|
|4|Hamstrung. Your speed on foot is reduced by 5 feet. You must make a DC 10 Dexterity saving throw after using the Dash action. If you fail the save, you fall prone. Magic such as the regenerate spell can cure your severed hamstring tendons.|
|5-7|Major Internal Injury. Whenever you attempt an action in combat, you must make a DC 15 Constitution saving throw. On a failed save, you lose your action and can't use reactions until the start of your next turn. Magical healing of 6th level or higher, such as heal and regenerate, heals the internal injury; alternately, if you spend ten days doing nothing but resting, it heals on its own.|
|8-10|Minor Internal Injury. This has the same effect as Major Internal Injury above, except that the save DC is 10.|
|11-13|Horrible Scar. You are disfigured to the extent that the wound can't be easily concealed. You have disadvantage on Charisma (Persuasion) checks and advantage on Charisma (Intimidation) checks. Magical healing of 6th level or higher, such as heal and regenerate, removes the scar.|
|14-16|Festering Wound. Your hit point maximum is reduced by 1 every 24 hours the wound persists. If your hit point maximum drops to 0, you die. The wound heals if you receive magical healing. Alternatively, someone can tend to the wound and make a DC 15 Wisdom (Medicine) check once every 24 hours. After ten successes, the wound heals.|
|17-20|Minor Scar. The scar doesn't have any adverse effect. Magical healing of 6th level or higher, such as heal and regenerate, removes the scar.|

##### Thunder

|||
|--- |--- |
|d20|Lingering Injury|
|1|Brain Injury. You have suffered a brain injury. You have disadvantage on Intelligence, Wisdom, and Charisma checks, as well as Intelligence, Wisdom, and Charisma saving throws. If you fail a saving throw against bludgeoning damage, force damage, or psychic damage, you are also stunned until the end of your next turn. Magic such as the regenerate spell can restore your full brain function.|
|2|Deafness. Your eardrums have been destroyed; you gain the deafened condition. Magic such as the regenerate spell can restore your hearing.|
|3|Partial Deafness. Your eardrums have been damaged; you are hard of hearing. You have disadvantage on any ability check that requires hearing. Magic such as the regenerate spell can restore your hearing.|
|4|Severe Headaches. You have disadvantage on Wisdom checks and Wisdom saving throws. If you fail a saving throw against bludgeoning damage, force damage, or psychic damage, you are also stunned until the end of your next turn. Magic such as the regenerate spell can cure your severe headaches.|
|5-7|Internal Injury. Whenever you attempt an action in combat, you must make a DC 15 Constitution saving throw. On a failed save, you lose your action and can't use reactions until the start of your next turn. Magical healing of 6th level or higher, such as heal and regenerate, cures the internal injury, or if you spend ten days doing nothing but resting, it heals on its own.|
|8-10|Major Concussion. You have disadvantage on Intelligence checks, Wisdom checks, and Charisma checks, as well as Constitution saving throws to maintain concentration. Magical healing of 6th level or higher, such as heal and regenerate, cures the concussion. Alternately, it heals on its own in four weeks.|
|11-13|Minor Concussion. You have disadvantage on Intelligence checks. The concussion heals if you receive any magical healing; alternately it heals on its own in two weeks. If you already have a minor concussion, you suffer a major concussion.|
|14-16|Minor headaches. You have disadvantage on Wisdom checks. Magical healing of 6th level or higher, such as heal and regenerate, cures the headaches. Alternately, they will resolve on their own in two weeks.|
|17-20|Severe bruising. You suffer severe bruising over an extensive portion of your anatomy. Anytime you suffer bludgeoning or force damage, you suffer an additional point of bludgeoning or force damage. The bruising heals if you receive magical healing. Alternately, it heals on its own in 2 week.|

## [Innocenti Looting](https://github.com/rinnocenti/innocenti-looting)

## [1001 Fish](https://github.com/cswendrowski/FoundryVTT-1000-Fish)

A rollable table of 1001 fish, created by burkenhare #4761 (Discord) 

"Typical use:
PC wants to roll for a survival check, after the party makes camp alongside a river. The GM makes them roll on the d1000 fish table to determine what kind of fish they catch (thank god there is such a thing, or else it would be trout every time!) .  They roll a 210, why, it's a cownose ray! But every adventurer knows that the cownose ray is a saltwater animal, that could only mean one thing.... FLOOD!
So you see, it can be used in many ways to contribute to the plot." - Burkenhare

## [SRD heros et dragons](https://gitlab.com/lemaire.erw/srd-heros-et-dragons)

## [Ultramodern OGL/SRD (UM5) by Dias Ex Machina Games](https://github.com/MrBrentRogers/UM5-Ultramodern5-OGL)

Provides support for the UM5 SRD by extending the dnd5e system. UM5 is a SRD extension for 5e created by Dias Ex Machina Games, https://www.drivethrurpg.com/product/196905/Ultramodern5SRD-OGL-5th-Edition

Ultramodern OGL adds modern and future tech, including a new variant human, classes, skills, and equipment to the D&D5e system.

This module is wholly unaffiliated with Dias Ex Machina Games.

### Compendiums:
- UM5 Ch.1: Skills, Proficiencies, & Feats
- UM5 Ch.2: Backgrounds
- UM5 Ch.2: Lifepath & Life Events
- UM5 Ch.3: Ladders
- UM5 Ch.4: Classes
- UM5 Ch.5: Archetypes
- UM5 Ch.6: New Rules Summary
- UM5 Ch.6: New Weapon Properties
- UM5 Ch.6: Equipment
- UM5 Ch.6: Vehicles
- UM5 Ch.6: Exo-Armor (Mechs)
- UM5 Ch.7: Antagonists & Enemies
- UM5 Ch.7: Antagonist Traits
- UM5 Modern Locations

## [fvtt-me5e (Mass Effect 5e)](https://github.com/sparkcity/fvtt-me5e)

A module to add support for ME5e, a futuristic sci-fi setting, to your 5e world. Includes most compendium content from ME5e excluding that which would infringe on copyright.

## [FoundryVTT-FantasyPlants](https://github.com/KyleBishop/FoundryVTT-FantasyPlants)

https://www.reddit.com/r/DnD/comments/83oupp/brodericks_compendium_plants_and_fungi_across_the/ ). I did not create any of the plants. This addon includes rolltables for the following regions as per the source material: 
* Arctic 
* City 
* Coastal 
* Desert 
* Forest
* Jungle 
* Mountain 
* Ocean 
* Plains 
* River 
* Swamp 
* Underdark/Cave

Roll tables and plants are included as compendiums. Open up the roll table and select the region type your party is searching in. Results will be added to a "Found Plants" loot actor for distribution to the players.

### Suggested Use
I currently use this in my campaign to allow players to forage. If you use the included roll tables for the region(s) they are in, you can select the Generate Loot button on the table, it will create a new instance of the item on the Actor "Found Plants" in the Actors tab (it will create that loot actor if you don't have it already). 

I also have Forien's Unidentified Items add-on and right click the new plant and mystify before letting the players see it/access it. You can save a copy to your items for reference if you want.

## [Sly Flourish' 1d20 Lists for D&D Adventure Inspiration](https://gitlab.com/fohswe/sf-adventure-inspiration)

This is an implementation of the [Sly Flourish' 1d20 Lists for D&D Adventure Inspiration](https://slyflourish_content.s3.us-east-1.amazonaws.com/1d20_lists.pdf).

Shared on Twitter and adapted with permission.

## [Weather Effects 5e](https://github.com/orangetruth/weather-effects-5e )

This FoundryVTT module contains rollable tables with seasonal weather effects for 5e based on homebrew by KibblesTasty (https://www.gmbinder.com/share/-M6xAC_2zw4BzpByxO-c). You can find more homebrew by KibblesTasty at https://www.patreon.com/KibblesTasty.

This module contains 3 compendiums:

1. Weather Actors
* A single Weather Effects actor with each weather condition added as a Feature. This allows weather effects to be easily clicked on and the description sent to chat. Each description has links to related weather effects, as well as buttons to roll damage and saving throws where applicable. 
![image](https://user-images.githubusercontent.com/76987378/109440451-95a9a600-79ef-11eb-9588-55f790478a63.png)

2. Weather Effects
* An item for each weather effect, complete with links to related effects and buttons to roll damage and saving throws:
![image](https://user-images.githubusercontent.com/76987378/109440608-19fc2900-79f0-11eb-9a91-5ba7742f233e.png)

3. Weather Roll Tables
* Rollable tables for all four seasons:
![image](https://user-images.githubusercontent.com/76987378/109449280-440c1600-7a05-11eb-923d-8869b7a089b1.png)

## [Modular Trains](https://www.reddit.com/r/FoundryVTT/comments/mgc1m6/modular_trains_module_just_a_simple_few_tokens_to/)

## [Copper Dragon's Hoard](https://github.com/copperdragongames/copperdragonhoard)

This is a collection of homebrew options for D&D 5e, ready to be added to your D&D 5e games on Foundry Virtual Tabletop. The content available in this addon can also be found on DriveThruRPG, and my patrons on Patreon get access to a much more detailed version of this addon.

## [Flirtatious Foundry Maps 1.1.1](https://github.com/FlirtatiousMule/flirtatiousfoundry)

A map pack using DungeonDraft, and Foundry VTT.  Featuring animated assets.  Made using FX Master, Dynamic Illumination, and Community Lighting modules.

Flirtatious Notes:
New maps are being made with FX Master, Community Lighting, and Dynamic Illumination modules if you're interested in a more immersive scene I'd recommend using them in conjunction with our maps.

# Weapon Properties

## [Draggos Mod](https://github.com/TheDraggo/DraggosMods)

**Armor Piercing**

**Blackpowder**

**Brutal**

**Cumbersome**

**Defending**

**Disarming**

**Double**

**Entangling**

**Guard**

**Hafted**

**Magazine**

**Momentum**

**Precise**

**Repeater**

**Restraining**

**Returning**

**Scatter**

**Set**

**Strong-Draw**

**Swift**

**Tripping**

## Home brew

**Spiked**

When hit by a weapon with the spiked property the target gains {@dice +1} damage.

## Beginner Baubles

**Aquatic**
Some weapons are as aquadynamic as they are aerodynamic. The wielder doesn't have disadvantage on melee weapon attacks or ranged weapon attacks within normal range when using a weapon that has this property.

**Concealed**
Some weapons are designed to be easily concealed. The wielder has advantage on Dexterity or Charisma checks made to hide or coneal a weapon that has this property.

**Dexterous**
Some weapons require precision to wield effectively. When attacking with a weapon that has this property, the wielder uses their Dexterity modifier for their attack and damage rolls, in place of Strength.

**Disguised (basic)**
Some weapons are best hidden in plain sight. Such implements are designed to resemble common, everyday objects and can be easily mistaken as such. Identifying the true intent of a weapon that has this property requires a close inspection and a DC 10 Intelligence (investigation) or Wisdom (perception) check; or at least an hour spent in close proximity to it and a passive Perception score of 15 or higher.

**Disguised (elaborate)**
Some weapons are best hidden in plain sight. Such implements are designed to resemble common, everyday objects and can be easily mistaken as such. Identifying the true intent of a weapon that has this property requires a close inspection and a DC 15 Intelligence (investigation) or Wisdom (perception) check; or at least an hour spent in close proximity to it and a passive Perception score of 20 or higher.

**Disguised (intricate)**
Some weapons are best hidden in plain sight. Such implements are designed to resemble common, everyday objects and can be easily mistaken as such. Identifying the true intent of a weapon that has this property requires a close inspection and a DC 20 Intelligence (investigation) or Wisdom (perception) check; or at least an hour spent in close proximity to it and a passive Perception score of 25 or higher.

**Lethal**
Some weapons are unusually dangerous and difficult to handle with care. The wielder can choose to deal non-lethal damage with a weapon that has this property, however they have disadvantage on attack rolls made to do so.

**Monastic**
Some weapons favored by martial combatants are still choice implements of monks and their kind. A martial weapon that has this property counts as a monk weapon.

**Non-lethal**
Some weapons are ill-suited to inflicting mortal wounds. The wielder can choose to deal lethal damage with a weapon that has this property, however they have disadvantage on attack rolls made to do so.

**Parrying**
Some weapons are ideally suited to bolster their wielder's defence. If a creature is wielding one or more weapons with this property and does not use them to make an attack on their turn in combat, their armor class increases by 1 against melee attacks until the start of their next turn.

## Item and Equipment Properties

**Partial Armor**

Partial armor only grants its AC bonus if you are wearing light or no armor. If you are wearing only one piece of partial armor, you are still considered to be wearing your base armor type (e.g. no armor or light armor). If you are wearing two pieces of partial armor, you are considered to be wearing the heaviest type among the armor pieces you are wearing (e.g. medium or heavy armor). You cannot benefit from wearing three or more pieces of partial armor.

## [Changelog](./changelog.md)

## Issues

Any issues, bugs, or feature requests are always welcome to be reported directly to the [Issue Tracker](https://github.com/p4535992/foundryvtt-compendiums-mix-dnd5e/issues ), or using the [Bug Reporter Module](https://foundryvtt.com/packages/bug-reporter/).

## Credit

Thanks to anyone who helps me with this code! I appreciate the user community's feedback on this project!

- [Kobold Press OGL Compendium](http://kpogl.wdfiles.com/local--files/home:home/module.json)
- [Kobold Press OGL Compendium with images](Personal compendium with some images form the OGL Kobold Press Site)
- [Summoner](https://github.com/Jonwh25/summoner)
- [Supplemental Bestiary Pack](https://github.com/sparkcity/fvtt-supplementalbestiary)
- [FoundryVTT Lingering Injuries](https://gitlab.com/p4535992/foundryvtt-lingering-injuries)
- [Innocenti Looting](https://github.com/rinnocenti/innocenti-looting)
- [1001 Fish](https://github.com/cswendrowski/FoundryVTT-1000-Fish)
- [SRD heros et dragons](https://gitlab.com/lemaire.erw/srd-heros-et-dragons)
- [Ultramodern OGL/SRD (UM5) by Dias Ex Machina Games](https://github.com/MrBrentRogers/UM5-Ultramodern5-OGL)
- [fvtt-me5e (Mass Effect 5e)](https://github.com/sparkcity/fvtt-me5e)
- [FoundryVTT-FantasyPlants](https://github.com/KyleBishop/FoundryVTT-FantasyPlants)
- [Grim Hollow Weapon Properties](https://github.com/TheDraggo/GrimHollowWeaponProperties)
- [Draggos Mod](https://github.com/TheDraggo/DraggosMods)
- [Sly Flourish' 1d20 Lists for D&D Adventure Inspiration](https://gitlab.com/fohswe/sf-adventure-inspiration)
- [Weather Effects 5e](https://github.com/orangetruth/weather-effects-5e )
- [Modular Trains](https://www.reddit.com/r/FoundryVTT/comments/mgc1m6/modular_trains_module_just_a_simple_few_tokens_to/)
- [Copper Dragon's Hoard](https://github.com/copperdragongames/copperdragonhoard)
- [Flirtatious Foundry Maps 1.1.1](https://github.com/FlirtatiousMule/flirtatiousfoundry)
- [Dragon Flagon Architect](https://github.com/flamewave000/dragonflagon-arch)

## License

This package is under an [MIT license](LICENSE) and the [Foundry Virtual Tabletop Limited License Agreement for module development](https://foundryvtt.com/article/license/).

## Acknowledgements

Bootstrapped with League of Extraordinary FoundryVTT Developers  [foundry-vtt-types](https://github.com/League-of-Foundry-Developers/foundry-vtt-types).

Mad props to the 'League of Extraordinary FoundryVTT Developers' community which helped me figure out a lot.
