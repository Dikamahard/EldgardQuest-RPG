# EldgardQuest-RPG
<img src="https://views.whatilearened.today/views/github/dikamahard/EldgardQuest.svg" alt="View" />   

EldgardQuest is a classical text based RPG made with Java

This project is created just for fun and to implement my knowledege on OOP fundamentals.

CURRENTLY IN DEVELOPMENT (Using Java 8)

==========================================================


					===== PROJECT ELDGARD GRAND DESIGN =====

=> Brainstorming Grand Design of EldgardQuest RPG

- Text based RPG game using Java programming language
- Class system (mage, warrior, healer, ...)
- Level up system (increase stat point and xp cap, maybe you can choose your own stat point to increase, unlock new zone --> you can travel to a new area ,unlock new equipment, unlock new skill)
- Fight mechanism (roll the dice --> maybe multiply the dice for damage? or see who has higher dice roll, choosing skill, rock paper scissor, normal atk only)
- Exploring the game (1 click for random encounter, choose it your self with available area list, grind based on level to fight boss
- Graphics (ASCII art --> for enemies and area maybe)
- Stat (HP, Atk, Def, and maybe for more development --> pAtk; mAtk; mana)
- Skill (magical, physical, heal, run) --> damage increase based on equipment type (magic, physic)
- Inventory system (weapon, armor)
- Weapon type (staff for magical, sword for physical), for further development --> dagger for a chance of double pAtk, and orb for double mAtk but has a low damage, or just make so many weapon type for the races 
- equipment has a different stat based on equipment level type and rarity
- for further development (customize character race --> every race has a different stat and ability or skill and weaknesses and race is locked with some equipment type like dwarf only with axe, costumize stat --> hihger hp but lower atk or higher atk but lower hp) 
- Killing enemies (gain xp, and maybe gold, or maybe items like equipment)
- Shop for items (equipments)
- Save game to a txt file and load the game ofcourse
- Enemy types (every types has a different weaknesses)

==> Area & Mob
- Castle of Fantanir (dracula castle)
	- Alucard Van Gogh (B)
	- Dr Franken (M)
	- Mighty Dullahan (M)
	- Elder Lich (M)
	- Dark Warlock (M)
	- Vampire
	- Gargoyle
	- Mummy
	- Werewolf
	- Banshee
- Greimog Forest
	- Goblin
- Ruin of Asvangald
- Niddrulenn (elven)
- Etterfrost (snow)
- Beorggwnis (fire)

=========================================================
					==== USER INTERFACE PLANNING  ====

==> Menu Interface Start (When the game start and put some good ascii art for the title)
- New Game
- Load game

==> Menu Interface New Game (Character customization and intro to the game
* all of that customization (char name, race, class) + opening story for the intro

==> Menu Interface Game (THE MAIN MENU)
- Explore?
- Inventory (for further development)
- Character Info
- Shop (for further development)
- Save Game
- Exit

==> Menu Interface Explore (*maybe we can make south west north east choice for the zone?then see the list of the enemy) 
- Zone 1 (S W N E *maybe this can be implemented? after choosing the zone, we then choose the direction?)
- Zone 2
- Zone 3
- Zone ....
- Back

==> Menu Interface Zone
- Find Enemy (generate randomly encounter enemy)
- ?? What else??
- Back

=================================================

=> Phase 1 Development
- Basic fighting mechanic
- decreasing and increasing stat
- User interface


=> Phase 2
- Game exploring mechanic
- User interface
