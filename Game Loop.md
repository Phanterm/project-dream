## Game Loop
1. (Host Only) Configure the settings for the game in the lobby.
2. Once all players are standing in the ready zone in the lobby, a countdown begins. Valid players will be teleported. The rest are spectators who watch from the lobby. (Or idk are invisible PHANTOMS on the map wow)
3. The next stage is mode-dependent:
	1. Deathmatch - 2v2 Free For All (Use Player Decks)
	2. Quick - 2v2 Free For All (Random Deck For All Players)
	3. Team Quick - 2v2 Team (Random Deck For All Players)
	4. Team Deathmatch - 2v2 Team (Use Player Decks)
4. Players will spawn into the map according to the game mode.
5. Instanced pickups called Draw Zones will appear where each player spawns. These spawns can only be accessed by that player, and provide "cards" containing assignable skills from that player's deck.
6. Players must level up their mana before they may use the majority of their spells and going on the offensive. This puts the game into multiple stages:
### Early-Game: Base Forming
1. When the game begins, players will start at level 0, meaning they can only use level 0 skills until they draw more mana.
2. Using mana skills consumes them and increases your maximum level by 1. Level will slowly regenerate on its own.
3. It is possible to use skills that can snipe and attack opponents from long range at this phase. However, at some point, the players begin attacking one another more often.
### Mid-Game: Base Storming
1. During the middle of the match, a storm will begin forming over a distant spot on the map. 
2. After a short period of time after the storm appears, lightning will strike, creating 4 spawn zones at a location.
3. While one team occupies this territory, they have access to 4 extra Draw Zones (2 per teammate), giving them the opportunity to comfortably apply pressure from multiple locations on the map.
4. Should a team manage to hold it for long enough while uncontested, the territory will be permanently claimed. Additionally, this will provide a large bonus to the team who claimed it.
## Late-Game
1. By this point in the game, both teams should have their loadout and game plan defined. If the storm was claimed, then that team pushes their advantage. If not, teams will continue fighting while threatening to take that territory.
2. The game ends once both players have lost all of their HP, or the timer runs out.
3. (!) *If the timer runs out, healing is disabled, all stats equalized, all players set to 1 HP, and all players only have a barrier skill, and a basic projectile. Sudden Death Mode.*
4. (!) *After 2 minutes, everyone loses if both teams are still standing.*
(!) *out of scope for this version of the project. instead, calculate damage done between teams. most damage dealt to enemies wins (friendly fire doesn't count lol)

![[Game Loop 1.png]]![[Game Loop 2.png]]