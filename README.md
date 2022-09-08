# Sealcraft Changelog
**__08/09/22__**
- Removed "Rarity" from all crate rewards (except shiny) [(#14)](https://github.com/SansMe69/Sealcraft/issues/14)
- Migrated Test server to Live, ready for launch
- Set End worldborder at 2500
- Pregenned End by 2750 in each direction [(#36)](https://github.com/SansMe69/Sealcraft/issues/36)
- Redid pregen for Nether due to `allow-vanilla-mobs` being false
- Added custom join messages
- Banned Wither Skeleton Skull, End Crystal and Chorus Fruit in all worlds
- Removed `Explorer's Compass`
- Fixed incorrect text on RR kit [(#40)](https://github.com/SansMe69/Sealcraft/issues/40)
- Flight and /fly no longer work in Adventure [(#42)](https://github.com/SansMe69/Sealcraft/issues/42)


**__07/09/22__**
- Pregenned Azurite by 6250 in each direction [(#22)](https://github.com/SansMe69/Sealcraft/issues/22)
- Set Nether worldborder at 2500
- Pregenned Nether by 2750 in each direction
- Placed Dens all around Safari [(#28)](https://github.com/SansMe69/Sealcraft/issues/28)
- Set different biomes in Safari
- Removed any punctuation from unscramble
- Added 3 new Pokemon to unscramble
- Increased range of RTP
- Added `/warp EVs` [(#27)](https://github.com/SansMe69/Sealcraft/issues/27)
- Added map art for evacuation signs [(#29)](https://github.com/SansMe69/Sealcraft/issues/27)
- Added overworld "spawn" destination [(#35)](https://github.com/SansMe69/Sealcraft/issues/35)
- Prevented admins being changed to survival on world change and dying of fall damage :)
- Fixed datapack load order overwriting custom prices
- Added missing crate keys [(#37)](https://github.com/SansMe69/Sealcraft/issues/37)
- Added `/warp shrines` [(#26)](https://github.com/SansMe69/Sealcraft/issues/26)
- Pokemon no longer spawn in the overworld "spawn"


**__06/09/22__** (+5 days of backlog lol)
- Nerfed most Pixelmon loot items due to the increase in structures they can generate in:
	```
	relic copper - $5,000 -> $2,000
	relic silver - $10,000 -> $5,000
	relic gold - $20,000 -> $15,000
	relic vase - $50,000 -> $25000
	relic band - $100,000 -> $50,000
	relic statue - $300,000 -> $100,000
	relic crown - $300,000 -> $150,000
	nugget - $2,000 -> $1,400
	big nugget - $5,000 -> $3,500
	balm mushroom - $2,000 - > $1,200
	big mushroom - $1,500 -> $1,500
	big pearl - $5,000 -> $3,000
	comet shard - $5,000 -> $3,000
	pearl - $2,000 -> $1,000
	pearl string - $5,000 -> $3,000
	rare bone - $4,000 -> $2,000
	star piece - $2,000 -> $1,500
	stardust - $1,500 -> $1,000
	tiny mushroom - $1,000 -> $600
	```
- Tweaked Wondertrade pool size and layout [(#34)](https://github.com/SansMe69/Sealcraft/issues/34)
- Updated OS to Debian 11(?) to fix databases resetting [(#33)](https://github.com/SansMe69/Sealcraft/issues/33)
- Added Redeem Kits for every paid rank [(#25)](https://github.com/SansMe69/Sealcraft/issues/25)
- Recreated SQL Database [(#24)](https://github.com/SansMe69/Sealcraft/issues/24)
- Added all Dex Rewards [(#23)](https://github.com/SansMe69/Sealcraft/issues/23)
- Reset all playerdata from old test server [(#21)](https://github.com/SansMe69/Sealcraft/issues/21)
- Added all voteshop content [(#17)](https://github.com/SansMe69/Sealcraft/issues/17)
- Weighted all rewards in Legendary and Mythical crates [(#16)](https://github.com/SansMe69/Sealcraft/issues/16)
- Eevee no longer appears more commonly than every other Pokemon [(#15)](https://github.com/SansMe69/Sealcraft/issues/15)
+ Added Chess :)
+ Added Safari World
- Fixed Pokemon not spawning in the Safari World
- Set the Azurite worldborder to be 6000 in each direction, 12k x 12k for now.


**__01/09/22__**
- Breed and Hatch now have a 10 minute cooldown (it's scuffed but it works for now)
- Disabled `Grasp of Hadar` skill
- All modded logs and planks now give Woodcutting xp
- Ditto breeding eggs can now be Ultra Beasts


**__31/08/22__**
- Migrated Test Server to OVH, ready for transfer to Live
- Reduced Payday and G-Max Gold Rush payouts to match Live
- TRs are no longer reusable
- Dens are no longer breakable
- The "drop" button on reward screen now deletes instead of drops
- Re-added Auto Restarts every 6 hours
- Removed itemname access from Plasma
- Added itemname access to Galactic and above
- Itemname now works with colours and formatting


**__28/08/22__**
- Tweaked Store Permissions [(#4)](https://github.com/SansMe69/Sealcraft/issues/4)
+ Added **Repurposed Structures**
- Removed **Terraforged** (this corrupts every biome lol)
+ Added Adventure World
- Changed rarity of Mythical Crate rewards [(#16)](https://github.com/SansMe69/Sealcraft/issues/16)


**__27/08/22__**
+ Added Starter Kit [(#6)](https://github.com/SansMe69/Sealcraft/issues/6)
+ Added Agate Kit [(#6)](https://github.com/SansMe69/Sealcraft/issues/6)
- Rearranged Kits GUI
- Fixed Claimblocks transferring from old world [(#10)](https://github.com/SansMe69/Sealcraft/issues/10)
- Fixed all permission nodes for: [(#11)](https://github.com/SansMe69/Sealcraft/issues/11)
	- Checkspawns Legendary
	- Repair
	- Fly
	- Unlimited Homes
	- Feed
	- Workbench
	- Hat
	- Coloured Chat
	- Enderchest
	- Itemname
	- Coloured Msg
	- Nick
	- Warp Shrines
- Fixed Crates being broken [(#19)](https://github.com/SansMe69/Sealcraft/issues/19)
- Reduced rarity of Eevee from Shiny Crate [(#15)](https://github.com/SansMe69/Sealcraft/issues/15)


**__26/08/22__**
- Updated Arclight from `1.0.3` to Daniel's `1.0.4`
+ Added Bingo Rewards for single squares, lines, columns and full cards
- Tweaked Unscramble rewards, now rewards anywhere from `$300` to `$1000` with $100 increments [(#3)](https://github.com/SansMe69/Sealcraft/issues/3)
+ Added lots to the shop:
	- Buy Shop
		- Building Blocks Tab
			```
			+ Prismarine
			+ Prismarine Bricks
			+ Dark Prismarine
			+ End Stone
			+ Stone Bricks
			+ Terracotta
			+ Shulker Box
			+ All Logs
			``` 
		+ NEW: Agriculture Tab
			```
			+ Pomeg Berry
			+ Kelpsy Berry
			+ Qualot Berry
			+ Hondew Berry
			+ Grepa Berry
			+ Tamato Berry
			```
		+ NEW: Pixelmon Items Tab
			```
			+ PC
			+ Healer
			+ Trade Machine
			+ All Colours of Daycare
			+ Tumblestone
			+ Sky Tumblestone
			+ Black Tumblestone
			```
		+ NEW: Evolution Items Tab
			```
			+ Fire Stone
			+ Water Stone
			+ Thunder Stone
			+ Leaf Stone
			+ Sun Stone
			+ Dusk Stone
			+ Dawn Stone
			+ Shiny Stone
			+ Moon Stone
			+ Ice Stone
			+ Metal Coat
			+ Dubious Disc
			+ Up-Grade
			+ Protector
			+ King's Rock
			+ Magmarizer
			+ Electrizer
			+ Razor Claw
			+ Razer Fang
			+ Dragon Scale
			+ Reaper Cloth
			+ Prism Scale
			+ Chipped Pot
			+ Cracked Pot
			+ Galarica Cuff
			+ Deep Sea Scale
			+ Deep Sea Tooth
			+ Sweet Apple
			+ Tart Apple
			+ Whipped Dream
			+ Sachet
			+ Galarica Wreath
			```
	- Sell Shop
		```
		+ Rotten Flesh
		+ Bones
		+ String
		+ Gunpowder
		```