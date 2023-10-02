# Predicting-CSGO-winner

## What is CSGO ?

Counter-Strike: Global Offensive (CS:GO) is a 2012 multiplayer tactical first-person shooter developed by Valve and Hidden Path Entertainment.The game pits two teams, Terrorists and Counter-Terrorists, against each other in different objective-based game modes. The most common game modes involve the Terrorists planting a bomb while Counter-Terrorists attempt to stop them, or Counter-Terrorists attempting to rescue hostages that the Terrorists have captured. There are nine official game modes, all of which have distinct characteristics specific to that mode. The game also has matchmaking support that allows players to play on dedicated Valve servers, in addition to community-hosted servers with custom maps and game modes.

## About Dataset

time_left The time left in the current round.

ct_score The current score of the Counter-Terrorist team.

t_score The current score of the Terrorist team.

map The map the round is being played on. E.g. de_dust2, de_inferno and de_overpass

bomb_planted If the bomb has been planted or not. False = No, True = Yes

ct_health The total health of all Counter-Terrorist players. Player health in range 0-100.

t_health The total health of all Terrorist players. Player health in range 0-100.

ct_armor The total armor of all Counter-Terrorist players.

t_armor The total armor of all Terrorist players.

ct_money The total bankroll of all Counter-Terrorist players. Amount in USD.

t_money The total bankroll of all Terrorist players. Amount in USD.

ct_helmets Number of helmets on the Counter-Terrorist team.

t_helmets Number of helmets on the Terrorist team.

ct_defuse_kits Number of defuse kits on the Counter-Terrorist team.

ct_players_alive Number of alive players on the Counter-Terrorist team. Range 0 to 5.

t_players_alive Number of alive players on the Terrorist team. Range 0 to 5.

ct_weapon_X Weapon X count on Counter-Terrorist team. E.g. Ak47, Deagle and UMP45.

t_weapon_X Weapon X count on Terrorist team. E.g. Ak47, Deagle and UMP45.

ct_grenade_X Grenade X count on Counter-Terrorist team. E.g. HeGrenade, Flashbang.

t_grenade_X Grenade X count on Terrorist team. E.g. HeGrenade, Flashbang.

round_winner Winner. CT = Counter-Terrorist, T = Terrorist
