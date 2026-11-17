Ancestral Talents

Attribute Increases
Dynastic Scion Increase any two Secondary Attribute Modifiers by +1. (implement custom attribute modifier) - done
Quicksilver Innards When you are Stressed, temporarily add +5% to all Primary Attributes for 1 hour. If Frightened, for 2 hours. If Terrified, for 3 hours. These effects aren't cumulative.

Agility - done
Undefoot Permanently adjust your [AB] by +1.
Deadly Aim Permanently adjust your [AB] by +1.

Brawn - done
"Mountain Among Men" Permanently adjust your [BB] by +1
"Inhuman Strength" Permanently adjust your [BB] by +1
"Big Folk" Permanently adjust your [BB] by +1
"Monstrous Body" Permanently adjust your [BB] by +1,

Combat - done
"Combat Prowess" Permanently adjust your [CB] by +1.

Skills
"Jack of All Trades" (Ancestral Talent When using a Skill you don't possess Skill Ranks in, add +5%.)
if "Jack of All Trades"|lower in talent_ancestral and  if skill_[skill_name] == 0
then skill +5
"Winter King's Embrace" +5% melee
"Razor-sharp Claws" Gain +5% to attack with Melee
"Mighty Thews" Gain +5% to attack with Melee
"Horrific Claws" Gain +5% to attack with Melee
"Fieldwarden" Gain +5% to attack with Ranged
"Cloak & Dagger" Gain +5% to attack with Melee
Blue-blooded Gain +5% to attack with Ranged
Saber-toothed Gain +5% to attack with Melee

Peril Threshold
"Servant of the Steward" When you aren't Stressed, Frightened, or Terrified, add +2 to Peril Thresholds  (  variables.peril_stress == "None")
    label: "peril stress"
    input: select
    options:
      none: None
      stressed: stressed
      frightened: frightened
      terrified: terrified))
"Ironclad" When wearing armor, adjust your Peril Thresholds by +2. (variables.armor_name is not empty)
"Saltborne" Adjust your Peril Thresholds by +3, but this does not stack with other Talents.
Broad-bellied When you aren't Starving, add +2 to Peril Thresholds. (variables.starving_toggle == false)

Damage Threshold
"Hide of Scales" When unarmored, add +2 to Damage Thresholds.
"Leathery Skin" When unarmored, add +2 to Damage Thresholds.
"Bend Like a Reed" Reference [BB] or [FB] to determine your Damage Thresholds
"Seal Skin" Permanently add +1 to all Damage Thresholds.
"Upper Crust" Reference [BB] or [FB] to determine your Damage Thresholds.
Warg-blooded When you are Seriously Wounded, Grievously Wounded, or Dying!, add+3 to Damage Thresholds.
(Professional) Spiritual Defense Effect: Permanently modify your Damage Thresholds by the number of Scars you have (e.g., 2 Scars equals +2 to Damage Thresholds). You cannot wear armor with the Heavy Quality while taking advantage of Spiritual Defense. (add customization - scars)

Initiative Modifier
Steam-powered When you are at -5% To Skill Tests on the Peril Condition Track, increase your Initiative Modifier by +1. If at -10%, add +2. If at -15%, add +3. These effects aren't cumulative.
(General) Supernatural Paranoia Effect: When Stressed, Frightened, or Terrified, =temporarily add +3 to your Initiative value

Tools and Burden
"Strength of the Mountain" You can carry up to 6 weapons and 6 tools (instead of the normal limitation of 3).
"Prehensile Tail" You don't have to use Action Points to swap tools or weapons in a fight
scene. You can carry 1 additional weapon or tool.
(Profiessional) Fair Share Effect: When you successfully use Persuasion to bargain for pay, increase it by three times your [FB]. You also gain 2 additional weapon and tool slots.
(Profiessional) Call To Arms Reference your [CB] for Supply Rating limits instead of the normal [IB]. Once per day, spend 1 Fortune Coin to increase your Supply Rating of one type of ammunition by 1.


Professional
Stand & Deliver Effect: At your option, substitute Persuasion instead of Melee for Attack Actions. You can also reference [FB] in place of [AB] or [CB] for Damage. (not used)


Genral