# TESQ2

A melee & spellcasting mod for Quake 2.

## Deliverables

* **Player Attributes & Growth**
  * Magicka & Stamina
    * *Totals - Gain points by using spells / swinging weapons.*
    * *Regen - Increases by 1 point per second for every 50 points gained to respective total stat.*
* **Five spells to learn**
  * Heal
    * *Restore 10 health in exchange for 20 magicka.*
  * Replenish
    * *Restore 10 stamina in exchange for 20 magicka.*
  * Haste
    * *Gain 2x movespeed; 15 magicka cost, -5 stamina per second while active.*
  * Fireball
    * *Launch an explosive projectile; 25 magicka cost, 25 damage, 25 AoE damage*
  * Charm
    * *Fire a Charm beam; 50 magicka cost, enemies hit will attack others and no longer target you.*
  * Invisibility
    * *Enemies cannot spot you; -5 magicka drain per second while active.*
* **10 Melee weapons**
  * Sword 1
    * *15 Damage, 45 Range, 10 Stamina Cost*
  * Sword 2
    * *22 Damage, 48 Range, 15 Stamina Cost*
  * Sword 3
    * *30 Damage, 51 Range, 20 Stamina Cost*
  * Sword 4
    * *37 Damage, 54 Range, 25 Stamina Cost*
  * Sword (Knife) 5
    * *40 Damage, 45 Range, 15 Stamina Cost*
  * Special Sword 6
    * *30 Damage, 50 Range, 20 Stamina Cost*
    * ***Swings cause explosions***
  * Special Sword 7
    * *15 Damage, 50 Range, 10 Stamina Cost*
    * ***Swings launch a fireball***
  * Special Sword 8
    * *30 Damage, 50 Range, 30 Stamina Cost*
    * ***Swings launch a charm beam***
  * Special Sword (Knife) 9
    * *30 Damage, 45 Range, 10 Stamina Cost*
    * ***Succesful attacks steal attributes (15 mag, 15 stam)***
  * Special Sword 10
    * *15 Damage, 45 Range, 10 Stamina Cost*
    * ***Succesful attacks launch enemies very far, very fast.***
* **Loot drops**
  * Special swords 6-10 randomly drop from soldiers.
  
## Usage / Additional Info

* Spells are linked to commands
  * SpellHeal
  * SpellReplenish
  * SpellHaste
  * SpellAttack
  * SpellCharm
  * SpellInvis
* Attacking with insufficient stamina will do 1/2 damage, and will not level your total stamina.
* Magicka & Stamina regen & degen are handled separately; technically, you can reach a point where invis and haste can be on permanently, albeit with slowed regeneration.
* Magicka & Stamina regen scales infinitely.
