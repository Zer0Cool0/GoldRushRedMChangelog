## Version 3.0.25 - 06/10/24

### Major Update (May - June)
### Revamp Graverobbing 
- We've given our grave robbing system a complete overhaul, recognizing it as one of the fundamental criminal activities. This revamp extends the process, encouraging more interaction between Criminals and Law counterparts.

### Revamped Wagon Scraping
- We've taken a fresh approach to the wagon scraping system, aiming to provide a more engaging experience for both criminals and their law enforcement adversaries.

### Revamped Mule Missions
- Our beloved Mule missions have undergone a significant transformation. Instead of quick one-stop completions, we've introduced multiple steps and increased the benefits for participants.

### Revamped Poaching Missions
- Responding to your feedback, we've made adjustments to promote better interactions between wardens and poachers, enhancing the overall experience for both sides.

### Revamped Waitress Script
- Improved the UI for a more user-friendly experience. Now, instead of scrolling through a list of food or drink options, it automatically filters and displays only the items available in your inventory. We have also added over 10+ new prop items thanks to @Dr. James Keates

### New: Side Quests
- Will you dare to embark on these intriguing side quests? Prepare to reap the rewards as you explore these additional adventures.

### New: Criminal Leveling System
- Our criminal content is now part of an overarching "Criminal" Leveling System, providing a comprehensive progression path for aspiring lawbreakers. Characters will encounter pivotal moments and must make significant decisions that tie into our leveling system. Going to prison or working for different individuals will affect your Reputation throughout the commonwealth.

### New: Criminal Progression System
- Many of our criminal scripts now feature a progression system. You start with one job and advance to the next, creating a dynamic and engaging experience

### New: Criminal Shop
- Gain access to exclusive items through our criminal leveling system, unlocking new possibilities and tools for your illicit activities.

### New: Drug Smuggling Mission
- Venture into the world of drug smuggling and deliver contraband for Mama and her associates throughout the Commonwealth, opening up new opportunities for lucrative ventures.

### New: Hunting Soft Skills & Reputation 
- Embark on a journey through eight distinct levels of hunting expertise, from Greenhorn to Master Hunter. As your hunting and skinning skills improve, your yield from each animal increases. Remember to manage your soft skills and maintain the precision required for successful hunting and skinning.

### New: Hunting License
- While currently optional for hunting, all certified trappers are now required to obtain a hunting license from the Game Warden's office. This license also serves as a tracker for your current level, ensuring compliance with hunting regulations.

### New: Hunting Violations and Strike System
- Game Wardens now have enhanced authority to enforce justice, issuing violations and strikes against the hunting permits of both hunters and poachers. Accumulating too many strikes will affect your poaching and hunting reputation. If you make a mistake, be sure to amend it with the Game Warden Command.

### New: Legal Hunter Shop
- Reels & Rifles is a new NPC/Shop that does things by the book, She is a respected hunter throughout the commonwealth, and dislikes poachers to the fullest. Her life mission is to provide equipment and tasks to respect hunters throughout the commonwealth. Upon reaching the appropriate hunting level, unlock access to the newly unveiled Hunter/Trapper Shop, where a diverse array of hunting essentials and equipment awaits.

### New: Backpacks & Bagtags
- Enhance your carrying capacity and streamline stash organization effortlessly. Note: Players can carry only one bag at a time, and dropping them on the ground is not permitted.

### New: Clothing Items
- Taking your clothes off will now turn them into items in your inventory. Meaning your clothes can be stolen and given by/to other players.

### Stables
- Fixed an exploit

### Gunsmithing
- Discover rare firearms by collecting specialized parts from heists and other criminal activities!

### Saloons & Restaurants
- Experience a revamped cooking and preparation system in saloons, designed to offer freshly made meals to customers as they arrive, rather than serving old food. :smug:

### Train Heist
- Gather your posse and prepare for the return of the thrilling train heist! Choo choo!

## Version 3.0.19 - 12/11/23

### Inventory
- Fixed a bug where an animation will play if you use the hotkey buttons. If you had a revolver equipped, and hit "1" it would still start playing the unholster animation for revolvers even if your revolver was not in that hotbar slot.
- Fixed a bug where the weapon would appear immediately in your hand with no animation. This is a fundamental issue with how the game engine handle weapons and inventory natively.
- Note that if you are on a horse, it will still immediately put it in your hands
- Fixed the logic for applying gun customizations.
- Fixed a bug with the oil prospecting tool not being usable.
- Fan from general store now works
- Chewing tobacco now works

### Gun Modifications
- Completely rewritten
- The rewrite fixed: wood tints and issues with applying the data to customized guns.
- If you have trouble with tints sticking, try using the first grip option
- Note the way the data saves is different. I wrote conversions for the data so your existing firearms that have been customized SHOULD still work.

### Clothing Wheel
- Added image for gunbelt accessories
- Added image for hair accessories

### Trains
- Completely new script
- Requires Coal to run
- Miscellaneous Jobs
- Storage

### First Person Overhaul
- Return of the 2.0 first person script.
- You can enter this mode by holding BACKSPACE and hitting P

### Butchershop
- Price balances

## Version 3.0.18 - 12/08/23

### Bee Keeping
- Fixed stashes
- Fixed inability to harvest honey
- Improved some functionality

### Clothing Wheel
- Added Hair Accessories & Command (/hairaccs)
- Fixed eyewear & added Command (/eyewear)
- Fixed gun belt accessories & added Command (/gunbeltaccs)

### Wagons
- Added proper slots / weight per wagon type

### Banking
- Fixed taxes. Your money at the bank will now be taxed properly.

### Doctor Job
- Fixed some bugs with the med bag, stackable in stashes again.
- Added the ability to request a doctor at the NPC doctor.

### Saint Denis
- Mapping changes
- Collision fixes

### New Wagon Scrapping
- Venture into the unknown as you uncover fresh wagon scrapping sites scattered across the vast Commonwealth. Brace yourself for thrilling adventures and stay vigilant, as encounters with the law add an extra layer of excitement to your journey.

### New Veterinarian Clinic
- Veterinarians take charge of their own clinic in Valentine, where they embark on a quest to discover and treat sick and wounded animals before situations escalate. This exciting new feature boasts over 60 distinct scenarios for treating a variety of animals. Get ready for a rewarding and challenging experience in the world of veterinary care.

## Version 3.0.17 - 12/06/23

- Fixed an issue especially with the badge menu where the inventory could be opened with an ox_lib menu open
- Fixed an issue where the annesburg saw mill 3rd eye would double up each time you left and came back
- Fixed an issue with the Tumbleweed bank where you could see and access the prompt to plant a bomb on the vault through the outside wall
- Fixed an issue with boats script that caused them to not move to the harbor they were parked at
- Fixed an issue with the plainview boat depot (teleported you to another town)
- Fixed an issue where tamed horses were assigned the wrong gender
- Fixed an edge case that locked players in stable when they decline the price of horse tack
- Fixed glass job crafting items having the same label ('Jar' for a lot of stuff)
- Added missing annesburg sawmill blip (it was still in stdenis doubling up on the original)
- You can now pick up arrows off the ground and it will replenish the bow in your hand or the first bow in your inventory
- You can now pick up tomahawks and throwing knives off of the ground

## Version 3.0.16 - 12/05/23

### Flasks
- Both flasks and canteens restore 50% less thirst.
Note: This will likely continue to be balanced

### Character Creation
- Minimum height has been upped by to 160cm from 150cm.

### Government Jobs (Lawyers, etc)
- Moved clock in / out in St Denis to the government building.

### Police Job
- Moved the coach spawn position in Annesburg.

### Farming
- Fixed a bug with shovel durability, allowed you to plant, but would eat the seed and not actually plant the crop.

### Cooking / Crafting
- Added cooking pot to Annesburg

### Train Conductors
- Added the ability to clock in and out.

### Stables
- Player horses now kick much less
- Added horse courage system. Horses gain more courage as they are exposed to threats
- Pressing CTRL + SPACE on a horse will make it rear. If the horse level is only 1 or 2, (exp under half max) you will fall off.

### Wagons
- Improved spawning / despawning logic
- Moved cart parking to radial menu (context based when in parking pos. parking position same as spawn position)
- Added cart transfer option to third eye

### Housing
- Key holders now have access to the stash / wardrobe / cooking

## Version 3.0.15 - 12/04/23

### Farming
- Added more optimization to third eye. Hoping this fixes some of the intense lag experienced by players who are farming for extended periods of time.

### Doctor Job
- Fixed bug with MDT where reports were not readable
- Fixed a bug with MDT where reports would not load when going to that page.
- MDT Access moved to correct building in Rhodes
- MDT Access added to guarma
- Moved Armadillo storage thirdeye
- Fix bugs with med bag, has uses instead of durability. Cancellable (will not use a usage)
- Removed the focus "G" to visit. Its been moved to the radial (It was there just not working properly)
- Removed an unnecessary command that alerted doctors
- NPC doctor no longer counts assistant doctors (rank 1)
- Treatment bed added to Rhodes
- Treatment bed added to vanhorn
- Beds now work at all offices

### Injuries
- Bleeding no longer causes a ragdoll when sprinting
- Snake bites no longer causes a ragdoll when sprinting

### Crafting
- Splint added to doctor + public crafting

### Mapping
- Various collision fixes
- Removed Saint Denis Court house to determine if its contributing to crashes.  (Recommended to clear cache)

### Slaughterhouse
- Slaughterhouse for ranching items now operational
- Job locked to ranch roles

## Version 3.0.14 - 12/03/23

### Weapon Repair
- Initial release. (12/01/23)
- Ability to clean weapons (12/01/23)
- Does not cost money, but costs parts (12/01/23)
- Fixed two bugs that require a relog (inventory busy & cannot move)

### Police Job
- MDT penal code updated (12/01/23)

### Pianos
- Third eye pianos to play, not the seat (12/3/23)

### Horse Training / Stables
- Fixed a bug where wild horses could be sold for an exorbitant amount
- Fixed an unintended feature where a non-horse trainer could break a horse, bring it to a trainer to then tame.

### Emotes
- More dance emotes added to F6 key

### Weather
- The month of December will feature snowy weather

### Knockout
- Script has been put in to be tested, good for fights and horse kicks
- Feedback and bug reports very much welcomed

### Crafting
- Numerous balances to recipes
- Cooking pot added to Saint Denis docks

## Version 3.0.13 - 11/30/23

### Train Conductors
- Bossmenus added to train stations

### Blacksmithing/Gunsmithing
- Balance tweaks
- Output issue fixed on grindstone
- Missing knife model added (Trader Knife)

### Blackmarket
- Gold bar item fixed

### Stashes/Inventories
- Changes implemented to prevent item loss issues

### Horse Training Grounds
- XP buffs balanced more
- Horse leading can only gain XP if they are young

### Camps/Properties
- Wardrobe is now functioning properly for both properties & camps
- Fixed camps not taking upkeep. Now it is 1 camp supplies per 6 hrs.

### Drug Sales
- Balances made
- Offset the radius of law alerts (more than they already were)

### Camps
- Camp cooking thirdeye fixed

## Version 3.0.12 - 11/29/23

### Processing Plant
- Animal feed added
- Butter added

### Mining
- Output balances on cracking

### Blacksmithing
- Fixed Macfarlanes forge

### Scenes
- Fixed bug with text scenes (could not place them)

### Government Jobs
- Added clock-in ability for gov jobs (lawyers, DA, etc)

### Police / Doctor Job
- Fixed bug where if you scroll in first person to aim down sights it would show the last five alerts

### Poker
- Fixed some bugs with some functions

### Roulette
- Lowered chip limit

### Drug Sales
- Fixed % chance to alert law

### Scenarios
- Added some missing scenarios (standcoffee / standsmoke)
- Added "notes" which already existed as "notebook", just allows either or now

### Notebook
- Fixed setting an image breaking the NUI, this has been confirmed working with discord image links

### Butcher
- Added butcher to Paraiso

### Camps
- Fixed a bug where you were unable to move a previously placed prop
- Fixed a bug with cooking props not working
- The prop list at camps is now sorted in alphabetical order
- Removed a bugged prop (tipi 2) and replaced it with a different model
- Increased range at which you can see camps

### Government Jobs
- Fixed the in-ability to clock in at all location

### Gun Crafting
- Fixed the in-ability to craft any gun

### Horse Training Grounds
- Western training grounds added to MacFarlanes Ranch
- Eastern training grounds added near Emerald Ranch

## Version 3.0.11 - 11/28/23

### Stables
- Tweaks to horse spawning
- Added Mask Tack option
- Added Bridle Tack option
- Added horse training areas system

### Appearance
- Fixed /loadskin health issue
- Added mullet hair option to both male and female peds
- Fixed strawberry barber

### Fishing
- Fixed empty bags being dropped

### Doctor
- Change keys of doctor revive prompt (I instead of E)

### Mapping
- Removed some MLOs from Blackwater to test RAGE crash issues

### Blacksmithing/Gunsmithing
- Changes will come to balance things accordingly, nothing is set in stone and will be adjusted now that we have seen output/mining rates etc
- Please provide quality feedback in your business tickets and we will get issues sorted

### Telegrams
- Fixed directory search feature
- Added the ability to create physical copies of telegrams and view those copies anywhere

### Spawn
- Moved the respawn timer / press e text on screen way down to get it out of the way

### Police Job / Doctor Job / Misc Jobs
- Disabled ledgers until we can figure out why they are not saving
- Police / Doctor job alerts now show location

### Scenes
- You will no longer attack someone while placing a scene
- Removed "E" to inspect, you now do this action through the radial menu when you are close enough to a scene

### Blacksmithing
- Typos fixed on recipes
- Some balancing done, more to come
- Parts bench & tool bench should now function properly
- As always please report any issue/feedback

### Ciudad Paraiso
- Telegram office fixed
- Street lights added by request

### Housing
- Wardrobe, stash, and cooking prompts fixed

### Farming
- A few old farm spots that weren't rotated from 2.0 have been moved

### Logging
- New logging camp added in Ambarino
- Fixed an exploit that allowed a double drop from trees
- Rebalanced wood weights (they were invalid)

## Version 3.0.10 - 11/27/23

### Barber / Appearance
- Fixed issue with female character peds not syncing properly (Body Types, Facial Features, etc)
- Barber has been completely rewritten, all features should work and work properly (Without changing your skin tone)
- Third eye on the chairs in: Blackwater, Armadillo, Valentine, Saint Denis
- Camera Controls: Q: Rotate Character Left | E: Rotate Character Right | W: Zoom In | S: Zoom Out | Z: Camera Down, X: Camera Up
  
[NOTE: MAKE SURE YOU HIT SAVE NOT EXIT]

### Character Select / Spawn
- Fixed for 4k resolutions

### Camps
- Camp Stashes are now shared

### Stashes
- Fix implemented to resolve loss of items in stashes

### Story Missions
- Lowered volume of speech
- If you get instanced during a mission, it now cancels

### Loans
- Added creditor to Saint Denis
- Added creditor to Valentine

### Police Job
- Fixed an issue where command was unable to hire
- Fixed a bossmenu promotion bug

### Targets
- Super important; you can now pet cats

## Version 3.0.9 - 11/26/23

### Inventory / Crafting / Shops
- Possible fix implemented to prevent "edge case" errors when equipping a weapon too fast
- Fixed bug where weapons with no durability were usable on horseback & presumably wagons & boats.
- Added Tin ore icon
- Added Tin bar icon
- Fixed Tin bar label (was "Tib" Bar)
- Added Tin bar as a smeltable item at the forge.
- Fixed a crafting issue with doctor's venom elixir
- Fixed a bug where you could craft food from horseback

### Warehouses
- Increased base slot count to 100 (11/25/23)
- Increased base weight to 250KG (11/25/23)

### Appearance / Clothes wheel
- Fixed a Bug where if you would change clothes without saving and outfit it would not apply properly.
- Fixed a small logic bug where an error would occur if you did not have that clothing item on and used a clothing command
- Fixed a bug where if you changed clothes / outfits it would not reset the clothing wheel.
- Fixed a bug where armor was not removable from the clothing wheel. Subsequently, /armor now works.
- Added the ability to tuck pants into boots into the radial and a slash command (/tuck)
- Added Skirts as a togglable option
- Added /sleeves (toggle sleeves up / down)
- Added /collar (toggle collar buttoned / unbuttoned)
- Added /bandana (toggle bandana up / down)
- Added /bandanat (toggle bandana on / off)

### Flasks
- Fixed health not going down enough when drinking dirty water
- Change notify depending on drink status (dirty / clean)
- Nerfed dirty water thirst. Basically its 2x better to use a clean flask.

### Games / Entertainment
- Fixed issue with being unable to close Ouija NUI (Its the ESC key)
- Fixed grammar error in ludo game (thingking -> thinking)

## Version 3.0.8 - 11/24/23

### Appearance / Clothing Store / Character Creator
- Added the ability to delete outfits
- Fixed a bug where if you equipped an outfit, then loaded your skin it would not persist
- Fixed teeth hashes (They were incorrect so no matter what you choose - they never changed from default)
- When selecting teeth in creator, you characters mouth now opens for a better visual.
- The character ped now is FORCED to look right at the camera, no longer while they look around
- Moved "face" camera in creator closer to face so you have a better visual on what you are doing
- Fixed the height of the camera for different character heights, should all be in frame now
- Added Flat price for finishing buying clothes and saving new outfits
- Added a cap on outfits (more slots will be add later)

### Law MDT
- Fixed year mismatch (whoops)

### Farming
- Lowered the radius in which the third eye registers on the plant targets from 15 to 5, hopefully solving some FPS drops and improving overall optimization

### Butcher / Blackmarket Butcher / Produce Shops
- Switch the stash checking from server id to character citizen id. Purpose of this is to allow persistency in the event of a client crash. Items will now be there upon return, so long as you rejoined within 20 minutes.

## Version 3.0.7 - 11/24/23

### Inventory / Crafting / Shops
- Fixed the inability to crouch with a bow.

### Drug Selling
- Can no longer move while progress bar is active during selling (Note: You can still cancel this)
- Added animations and props to the selling action
- Removed SOUND effect from law man alert per feedback from law

### Blacksmithing
- Fixed durability bug with hammers

### Farming
- Fixed durability bug with buckets / shovel
- Re-upped limit on individual farmlands
- Adjusted some outputs
- Removed a hidden farmland (the one moved last time), was causing an issue with some players camps

### Lumberjack
- Fixed durability bug with wood axe and milling saw

### Doctors
- Changed blip style
- NPC doctor now works properly (the heal function that is), costs some money, and takes a little bit of time (not instant)

### Blackmarket Butcher
- New audio and ped models to differentiate from the regular butcher

### Stagecoach Job
- Moved Rhodes location to Emerald Ranch in an attempt to fix networking and ped issues
- New pickup and drop off locations

## Version 3.0.6 - 11/23/23

#### Inventory / Craft / Shops
- Moved the Item used / added / removed / holster / unholster notification down and decreased size by about 50% ⁠remove

#### Drug Selling
- Fixed the ability to steal your drugs back from a hogtied, unconscious, or dead local instead of just fully dead (but for real this time)
- Removed the ability to sell at Sisika (like come on really...)
- Added proper police alerts

#### Graverobbing
- Tweaks to progress bar time
- Locks player position until progress bar completes (Note that you can still cancel this bar)
- Added proper police alerts

#### Camps
- Removed the ability to name camps, sorry, was abused by some heinous folks. Might see a return at some point

#### Smoking
- Swamp herb joint should now be smokable.

#### Farming
- Moved a hidden farmland

#### Shop Robberies
- Added proper police alerts

#### Random Events
- Fixed exploit with rewards

## Version 3.0.5 - 11/22/23

#### Drug Selling
- Fixed drug selling third eye being blocked
- Fixed locals on horses can make you an offer/rob you while drug selling
- Fixed interaction peds being able to make you an offer while drug selling
- Made the notifications for offers/being robbed much more obvious & stick around longer
- Taking your drugs back from the ped who robbed you can now be done if they are hogtied or dead, instead of only dead
- Added missing crouch inspect scenario to retrieving your drugs back from the local who robbed you

#### Stables
- Fixed getting stuck in stable menu when buying horse tack
- Fixed horses location occasionally not updating on flee
- Fixed selling horses not giving money back
- The preview horse entity now deletes on sell

#### Blackmarket
- Removed waterfall Andy. I thought it was a cool inconspicuous position (Long pause) I was wrong.

#### Blackmarket Butcher
- Price balance (went up)

#### Gathering / Ecology
- [Gathering] restored missing items, enabling you to conveniently pick them up once again
- [Ecology] tuned and missing items have been added back

#### Mama
- Introducing a new mission out west for mama, while concurrently fine-tuning the balance of the existing two missions

#### Stagecoach job
- The stagecoach job in Blackwater has been relocated out west to address the current issues with player count and networking.

#### Ice Fishing
- Huts have been added.

## Version 3.0.4 - 11/21/23

#### Inventory / Crafting / Shops
- Fixed cooking spices recipe
- Moved progress circle for ALL crafting to the bottom middle instead of center of screen
- Added a cooking station to Guarma
- Moved Guarma warehouse

#### Doctors / Respawn
- Added option to alert doctors when you are down
- Doctors will receive the alert at the top right corner. Check map after.

#### Doors
- 1 dead door fixed in Valentine
- 3 dead door fixed in Rhodes
- 1 dead door fixed in Strawberry
- 1 dead door fixed in Blackwater
- 1 dead door fixed at Flatneck Station
- Fixed a door in the Rhodes bank that needed to be locked

#### Clothing
- Added slash commands back for clothing.
(This is synced properly with the clothing wheel)

#### Lumberjack
- Added sticks to loot table.

#### Interact Command
- Lowered radius to prevent teleporting.

#### Peds
- Optimized ped spawns, resulting in a lower GamePool for Peds, Hopefully improves syncing, ie the disappearing markets, and brings back some wildlife

#### Hunting
- Re-enabled the pickup / skin prompts for dead animals to allow picking up / skinning in water/snow (third eye can still be used)
(Note that you still need to have a knife equipped (In holster.))

## Version 3.0.3 - 11/21/23

#### Appearance
- Fixed Skin issues
- Fixed Hair issues
- You can now be bald
- (Males) you can have no beard
- Added admin creator command to allow players to be put into the character creator.
- Loadskin can no longer be used while dead

THIS HOTFIX FOR SKINS SHOULD NOT MESS UP ANY EXISTING SKINS
THIS HOTFIX FOR SKINS SHOULD FIX ANY EXISTING ISSUE WITH SKINS (FACE/HAIR/SKIN TONE)

(We will work the next few days on the issues with the barber and missing features there)
(We are also working on missing hairstyles, like the mullet)

#### Jobs
- Fixed some job permissions related to doorlocks

#### Pausemenu
- Now checks if the radial is open. If it is, it will not open the pause menu

#### Stables
- Fixed issue with breeding timer
- Re-added job check

#### Job Center
- Some balance tweaks

 #### Criminal Land
- Rebalance of mule missions

## Version 3.0.2 - 11/20/2023

#### Inventory / Crafting / Shops
- Fixed issues with opening cooking crafting and it closing immediately if you are not close enough
- Fixed cooked venision in public cooking table

#### Mapping
- Fixed a rendering / LOD (level of detail) around blackwater, flat iron lake, limpany

#### Banking
- Fixed exploit

#### Doors
- Fixed a dead door in tumbleweed sheriff's office
- Fixed 6 dead doors in Blackwater
- Fixed a dead door in Strawberry

#### Pausemenu
- Fixed a bug if you have a specific menu type open it gets stuck if you hit ESC

#### Butcher / Produce shop
- Fixed a display bug for the offer amount, no more repeating decimals.

#### SaltyChat
- Reverted toggle range key back to J.

#### Gold Panning
- Fixed bug with the label of the prompt taking on drawn text on screen

## Version 3.0.1 - 11/19/2023

#### Telegrams
- Telegrams can now be Deleted
- Fixed style so recived telegrams are readable

#### Chat
- Removed blur when open

#### Doctor Script
- You should no longer respawn with diseases
- Temporarily increased the minimum amount of doctors needed to stop the local doctor from healing / reviving
- Lowered cold tempature for getting sick (Hopefully fixes issues with getting sick while wearing bulky clothing)

#### Hunting/Fishing
- Adjusted animal population density in an attempt to have more wildlife spawning

#### Mining
- Fixed mining being broken for all female characters

#### Farming
- Temporarily disable weather effects from crops to help narrow down source of mass crash

#### Inventory / Crafting / Shops
- Added Cooked Venison to public cooking table.
- Added Cooked Stringy Meat to public cooking table.
- Soap can now be purchased from General store

#### Doorlocks
- Fixed a door in the BW sheriff's office that had the wrong yaw axis
- Perma locked a "dead door" in Armadillo Saloon (IE went to the abyss)
- Perma locked a "dead door" at Manzanita

#### Job Center
(Note that some of this changes are possibly temporary as we continue to find a balance)
- Removed Garbage Job temporarily due to culling issues
- Added skill checks to the Handyman and Electrician Job
- Increased Cooldown on Job Centers

#### Butchers
- Added missing pelts to normal and black market butcher shops.

#### Gathering
- Added missing herbs

#### Mama
- Fixed a money check

## Version 3.0.0 - 11/19/2023
- RELEASE!
