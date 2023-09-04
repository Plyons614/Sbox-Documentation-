# S&box MiniGame Server Specifications

##### S&box Game Links
> [Documentation Link](https://wiki.facepunch.com/sbox/)

##### Personal Main S&box File Links
> [Basics](https://github.com/Plyons614/Sbox-Documentation-/blob/main/s%26boxBasics.md)
> [Minigame General](https://github.com/Plyons614/Sbox-Documentation-/blob/main/s%26boxMiniGameServerInfo.md)

### Introduction

The server will be inspired by Mario Party, Pummel Party, Fall Guys, and most importantly Squid Game/Crab Game. 
- Planned to be played with 10-40+ people in it at any given time. Aimed to be chaotic fest with voice proximity chat and methods for users to mess with each other while the minigame is taking place. There will be 1 winner or survivor after each minigame is played and then move on to the next one with an overall scoreboard to show who is currently placed the highest. 
    - Might do normal generalized minigames or survival based minigames (avoid getting sucked up by a ufo, survive a tornado, etc.)
    - One big payout of premium currency is currently planned where normal gametime and winning smaller mini-games get users the free currency
    - Special minigames at the end of each rotation for special prizes
    - Uses a mix of maps, minigames, and modifiers to give more replayability                                       


### User Capabilities
- The user will have the standard movements brought by sandbox with simple jumping and sliding. The user will also be able to punch other people pushing them backward. There will be pickup-able items on the ground the user can use to their benefit or detriment as well as consumables bought in the shop to take into the next minigame with them.
- The user will be able to trade items with other people and also be able to earn points through playing the game and premium points through winning the minigames. MIGHT set up an auction style of trading where VIPs/Premium members can auction off their items for others to bid on. 
    - Focus primarily on customization for the user with points, more on the **PointShop** section
- Depending on the minigame and modifier there may be more controls for the player to use during that time
- There is also a GUI Menu User's can access for other controls and information listed in the [Basics](https://github.com/Plyons614/Sbox-Documentation-/blob/main/s%26boxBasics.md) document.


### Features

1. Minigame Listings
2. Modifiers
3. Consumables
4. Boosters
5. Point Shop
6. Tab Menu
7. Maps

### Minigames List

#### PRIORITY LIST

1. [Stepping Stones](https://github.com/Plyons614/Sbox-Documentation-/blob/main/SteppingStones.md)
    - Squid Game glass bridge
2. [UFO Survival](https://github.com/Plyons614/Sbox-Documentation-/blob/main/ufoSurvival.md)
    - Players spawn around map with a couple ufo's above tracking them and sucking them up with their beams
3. [Pool Table](https://github.com/Plyons614/Sbox-Documentation-/blob/main/PoolTable.md) 
    - Player is on a pool table and has to dodge other pool balls flung around the table 
4. [Sky fall](https://github.com/Plyons614/Sbox-Documentation-/blob/main/SkyFall.md)
    - Player dodges falling props that spawn in the sky and insta-kill
5. [Spinning bar Survival](https://github.com/Plyons614/Sbox-Documentation-/blob/main/SpinningBarSurvival.md)
    - Player on platform with a bar that rotates in a circle and knocks people off
6. [Red Light Green Light](https://github.com/Plyons614/Sbox-Documentation-/blob/main/RedLightGreenLight.md)
    - Players race to other side of the map or an item on the map without getting caught moving red mode
7. The Floor is Lava
    - Floor constantly changes between lava and normal 
8. Snake
    - Player gets a speed boost and can't stop while running around leaving a trail that is deadly

#### NON-PRIORITY LIST

9. Tornado Survival
    - Tornado(s) go through the map destroying it where the players try to survive
10. Jenga Tower
    - Players in a tower(s) where they start exploding and shifting to where the player has to run to other parts of the map
11. Titanic
    - Players on titanic as it breaks and steeps upward from both halves
12. Earthquake 
    - Whole ground and props/buildings move around with Players trying to avoid breaking buildings and props flying or falling into them
13. One in the Chamber
    - Players have a gun with 1 bullet to shoot each other with, instakilling them
14. Zombie Apocalypse
    - Spawn a bunch of zombie npcs to chase players around until all die except one
15. Infection
    - One infected player infects others until 1 survivor left
16. Hidden
    - Hidden gamemode from gmod (1 invisible man with a lot of health and a knife vs. everyone else with normal health and pistols)
17. Hot Potato
    - Player gets a bomb and has to pass it on before it explodes
18. Toilet Trouble 
    - Players inside a toilet bowl and gotta dodge shit
19. Flood 
    - Players have to reach stable high ground for the water rising
20. Blood for the Blood God
    - Players kill each other and have to toss bodies into an altar. The one who has most bodies entered wins
21. Dodgeball
    - AI dodgeballs that bounce off the walls and players have to dodge (slowly speeds up over time or spawn more balls over time)
22. NextBot Invasion 
    - Survive the nextbots
23. Black Hole
    - Spawn a black hole in a quarter of the map that gets bigger sucking people and props in

### Modifiers

#### PRIORITY LIST

1. Fog Mode (reduced visibility in distance)
2. Night Mode (flashlights for everyone)
3. Psychadelic Mode (Everythings rainbow)
4. Speed Mode (Everything has faster speed: Player, Props, NPCs)
5. Bomb Mode (Spawn bombs around the map that do no damage but push players from explosion)
6. Low Gravity Mode (Higher Jumps and slower fall speed)
7. Floor is Ice Mode (Users and Props slip on everything)
8. Gas Circle (Encloses from outside the map towards the center)
9. Noir Vision (Grayscale colors)

#### NON-PRIORITY LIST

10. Reversed Controls (wasd, mouse)
11. Flipped Vision (upside-down)
12. Walking Bomb (2 players touch, they knock each other back)
13. Lucky Blocks (Buffs and Debuffs)


### Consumables 

1. Bombs (Dropped by player and explodes after a few seconds pushing players away from center)
2. Bat (Stronger version of the punch any person can do but has limited use: multiple hits or disappears after current game round?)
3. Jump Potion (Increases jump height by 1.1x making the player be able to jump higher than most people and over smaller obstacles)
4. Russian Roulette (Gun that goes to your head and has 1 bullet in a 6 round chamber)
5. Air Horn (Ear rape)
6. Vape Pen (Smokescreen, can be colored)
7. Bass Cannon (What Mocho never implemented)

### Boosters

1. XP booster for player level
2. Point booster for free points to buy consumables, player models, etc.


### Point Shop

- The Point Shop will be organized into multiple section for better use for the user on specifications of each item.
    - The sections so far will be: Customization, Consumable, Premium
    - There may be more organization in the future and may limit slots (purchasable?)
    1. Customization Section:
        - This will be by far the largest section. The user will be able to get a few different types of items that they can use for customization to stand out from the normal crowd. 
        - Primarily there will be normal player models that they get with the normal points in the section and will be the biggest difference in telling each other apart
        - Along with that, hats will be another big customization item that users can equip. It is important to note that hats and models will **not affect** hit boxes whatsoever.
        - Finally, there will be a way to implement skins for consumable items such as different skins for the bomb like it being a party popper shooting out confetti or the bat turned into a candy cane earned from the Christmas event.
    2. Consumable Section:
        - A smaller section compared to the first but will contain a method to "equip" the consumable and only one consumable per minigame
        - Overall there will be different types of consumables: Ones they use inside the minigame and ones they use in the menu
            - An example of ones to be used in the menu will be a point consumable such as "use to get 1000 points" which can be given through a daily reward or another method
            - An example of one that can be used in the minigame would be a bomb mentioned above that can be dropped/thrown by the user
        - This will probably be the section with the most items and copies of those same items so it might be wise to setup an image of the item in the menu with a number at the corner showing how many of that consumable the user has.
        - There may or may not be premium consumables in the future but for now it will stick to non-altering items for the game


### Tab Menu

- Scoreboard shown with multiple features for the player
    - Show win streak next to player's name and their account level
    - Show Vip/Premium/Staff status
    - Show dead vs. alive players
    - Show ping to server
    - Show server IP
    - Show some of Player's personal data
        - Number of points
        - Number of wins
        - Winstreak
        - Player Model
        - Player Status

### Maps
