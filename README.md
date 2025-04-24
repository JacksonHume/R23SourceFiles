# R23
1.02+ R23 source files for reference. Assets may be used but credit would be appreciated.
This cannot be compiled as a standalone mod as it does not contain all of the 1.02+ files, only the ones I have modified or added over the years.

R23 Patch Notes (Draft)

 Will not be implemented, but may be tested.
 Implemented

General Changes
Crane cost reduced from 1500$ to 1200$.
Tweaks made to harvesters to increase health bar size have been made.
AI code will be revised to check for inconsistencies (desyncs were reported online vs Nod/GDI faction AIs).
Repair drone speed reduced from 100 to 75 (as it was in vanilla).
Outpost unpack duration decreased from 20s to 15s. Outpost speed increased by 10%.
Locomotors reverted to 1.02 statistics besides the Scorpion Tank, Scrin MCV, V35 ox , Carryall Transport for testing purposes, keep in mind the clamptangent attribute causes movement bugs.
	

GDI
Fix shatterers being unable to kill allies husks.
Increased the cooldown of Adaptive Armour from 10s to 15s so that players may have the opportunity to EMP enemy units once the effect wears off.
Change the “Can Enter” filter on the Heavy Harvester to prevent units from garrisoning it while docking.
Watchtowers with AP Ammo now deal 25% less damage vs vehicles.
The MARV now benefits from AP Ammo, increasing attack damage from 35 to 47 per shot (a 35% increase).
 MARV grenade launcher damage vs structures increased by 25%.
The MARV Zone Trooper turret while railgun accelerated and grenadier turret now rotate towards the enemy whilst engaged.
MARV sniper range increased from 450 to 470, reload time reduced by 10%.

Nod
Venoms sometimes don't work with beam venom, adjust reload time on exploit workaround.
The damage dealt to husks from the Tiberium Trooper Redeemer hardpoint has been increased from 75 to 100.
Tiberium Trooper damage against structures increased by 33%.
Fix Specter Artillery randomly un deploying  (using jugg deploy and weapon code and changing min range in the weapon), a fake weapon has been added to prevent the unit from un deploying within its 250 minimum range.
Reckoners, after given an attack command will now reacquire targets if the target moves out of range.
Tiberium Trooper Redeemer hardpoint damage to structures increased from 75 to 100.
Charged/Supercharged shredders now deal 25% less damage vs vehicles.
The Redeemer now benefits from Charged Particle Beam and Super Charged Particle Beam upgrade, dealing 80 damage per shot. The Super Charged Particle Beam also benefits from a 25% bonus against vehicles.
Redeemer rocket garrison damage against vehicles and structures increased by 35%.

Scrin
Cultist capture range reduced from 250 to 235 (6% reduction).
Infestation hive hp increased by 60%, rocket armor doubled, survivability against gun damage decreased by 50% compared to the pre hp buff.
Infestation hive cost increased from 800$ to 1000$.
Shock Trooper speed increased by 10% (Advanced Articulators unaffected).
Ravager speed increased by 10% (Advanced Articulators unaffected).
Mastermind/Prodigy garrisons now scale for a cooldown reduction.
1 Mastermind provides a 30s cooldown.
2 Masterminds provides a 17s cooldown.
3 Masterminds provides a 10s cooldown.

Neutral
Viceroid veterancy added.
