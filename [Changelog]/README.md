### Changelog

## [1.0.0] - 2019-08-01
- Added a playGround resource to research N test whatever that i want to
- Created a project on github
- Made a backend for the server
- Removed old fivem_credential required ( not using steam:identifier anymore )

## [1.0.0] - 2019-08-02
- Added a map for the player to customizing the character
- Create a reuseable-style > performhttp request for further use
- Created the user model for registeration and login system
- Created a UI [HTML] for a player to be able to registering a user and loggingIn in the same page
- Made a script to be all shared-resource > ESX ALIKE <BUT NOT ESX LOL>

## [1.0.0] - 2019-08-03
- Added a skin based-framwork to be more conveniece doing with the stuffs
- Created MENU-FRAMEWORK for character registeration
- Added structure of the inventory system
- Created the inventory with the first version of UI
- Added Item-on-hand custom framework

## [1.0.0] - 2019-08-04
- Added Picking-up item system > interact with decor
- Added Dropping-down item system
- Sync all data of the object on the floor to the server-sided
- Fix bug>caused by fivem that the position of each object is not exact the same on every computer > fix by plotting the range [very small range differentation]
- Added a structure of the house system
- Added the command to create a house [ IN-GAME ]
- Added the lock attribute of each house and store in the server-side
- Added a key to lock-unlock house
- Added custom-instance system
- Started the first commit on the !!!!!!!GITHUB!!!!!!!!!

## [1.0.0] - 2019-08-05
- Fix the unknown-behavior bug of the instance system and may now working fine
- Prevent player from dropping an item in the house [ But still be able to hold it ]
- Design a UI for the custom notification system
- Added Custom Notification system with custom font!
- Update the inventory UI

## [1.0.0] - 2019-08-06
- Added the crafting system [ Dynamic ]
- Added custom menu [ with transistion ] - Dynamically
- Made the custom menu for a house menu > and can be reuseable
- Created a structure of the vehicle system
- Investigated about the lock/unlock glitch of the fivem_onesync bug behavior

## [1.0.0] - 2019-08-07
- Fixed the lockNunlock by .....SECRET TRICK
- Lock and unlock are now synced
- Added the first garage
- Add the function to itteration thru all the vehicles/objects
- Check if car is already exist somewhere on the map before requesting for a new one
- Added a menu for vehicle garage

## [1.0.0] - 2019-08-08
- Added a electric-car-remote and can be used by any player that own the key
- Added custom radial menu
- Design a little bit of radial menu
- Added engine system
- Added custom vehicle start/stop system
- Added custom realistic engine sound with realistic range
- Applied all the sound to use the realistic one instead
- Design a custom progress bar system [ Circular ]

## [1.0.0] - 2019-08-09
- Design a UI for a vehicle-shop
- Added the vehicle shop system
- Added a input to select a color when viewing the showroom-cars
- Fixed minor bugs of the vehicle system
- Some codes have been refactored
- Applied the custom progress bar to be used with the engine,lockHouse,lock:unlock vehicle

## [1.0.0] - 2019-08-10
- Added the coord saving command
- Optimized the beautify timer on player connect phase
- Added the safe-load event for using with the any warp system [ FROZE AFTER TELEPORTED ]

## [1.0.0] - 2019-08-11
- Added the lock system while in the vehicle > with radial menu
- Create a structure for a new inventory design [ The old one seems suck ]
- Adjust the position of the awoken_notification to use the transform only 1 axis
- Added a npc-reducer system
- Removed the old player interaction menu that based on 3d > because it doesn't support with thai fonts

## [1.0.0] - 2019-08-11
- Created the structure of the new interaction menu
- Fix huge conflict bugs with all other nui resource by the new interaction-menu
- Added a dynamic structure to be able to go to the sub menu of the menu it-self
- Adjust the ui of the interaction-menu
- Adjust the focus from crosshair to the eyes.png
- Added the transistion when there is no object/person in sight

## [1.0.0] - 2019-08-12
- Continue design the new inventory ui [ Continued from the date 11 ]
- Investigated the weird behavior of the voice system
- Change the structure of the inventory to be able to handle the specific object with the [ : > used for spliting the string ]
- Minor update of the crafting system
- Fix bug of the crafting system when passing the arguments to the GAME
- Crafting system is now finished
- Create the 3d menu for entering the amount and other things
- Added the give-item with synced animation with other player


## [1.0.0] - 2019-08-13
- New inventory UI design.
- Adjust the voice-chat range to be a realistic one.
- Change the clothesData to thai language and implement the inventory to support the format of the clothes data for more better format.
- Inventory menu now supported with wearing system [ On going ]

## [1.0.0] - 2019-08-14
- Clothing system added , with animation

## [1.0.0] - 2019-08-16
- Add the set and sync variable to the server-sided [ Still on progress ]
- Add the handler on the server backend when the data is sent as the object type of file
- Changed the structure of how the program stored a variable on client-side and server-side and backend
- Direct Update And Load value within client -> server -> client
- skins table are now saved
- New Vehicle Interact Menu [ OpenTrunk , View Inventory Truck] - JUST UI
- OpenTrunk is now functionable and required the door-lock status to be false
- CloseTrunk can be done by all player no matter what [ Realistic ]

## [1.0.0] - 2019-08-17
- Added HAT SYSTEM
- Prevent from wearing a different gender clothes
- Prevent from wearing clothes if already worn one
- Change the male and female to use the same anim [ Becasue the male one too buggy for it ]

## [1.0.0] - 2019-08-18
- Fixed open trunk sync problem by Call a request control on vehicle and Making a hold-wait until network is in controlled
- Add New "Other" current menu that supported with trunk/house store etc ...
- Change the structure of 3d_menu_confirm to be more dynamic > by sending the fucn [ Task ] to support a function
- Player may now picking item from TRUNK which can specifically the amount of how many to picking up
- Added the animation and the perfect timing wait
- All items are now can be saved into the trunk
- Vehicle plate on bought is now unique

## [1.0.0] - 2019-08-19
- Store the id of the user itself rather than the fullname one > fix the causing glitch if the player changed the name later
- Change the structure of the inventory in trunk to be supported for the checking if that vehicle is from the player or the npc vehicle
- Add checker for trunk inventory if it is a playerVehicle
- Change vehicle owner to store a object type id

## [1.0.0] - 2019-08-20
- Add the label for the Inventory of the house
- Add the key H to be able to open the house Inventory within the radius that was given
- Add the backend route for specifically load the housedata but getting only ('inventory' field)

## [1.0.0] - 2019-08-21
- Change the structure of the [Other menu] in inventory to be re-useable with any function that specific
- Add the inventoryHouse call-back on client-side and server-side [ On-going ]
- Add press H to open up the menu > trigger server event and then get the data as the trunk way
- House trunk system done > without saving to database yet

## [1.0.0] - 2019-08-22
- Interact menu on house store > more dynamic now > get the housestore data from the awoken_inventory hook

## [1.0.0] - 2019-08-23
- Crete the structure of the criminal record system
- Create the structure of the identity card of the player in the database

## [1.0.0] - 2019-08-24
- Create the crimnial record NUI

## [1.0.0] - 2019-08-25
- Added EJS for criminal Record NUI
- Modify the load-criminal api to fetch the name then get the _id then pass it to the criminal > do the rest . . .
- Add interval check for criminal-display if not in the police vehicle
- Add the F6 radial menu only when player's in the police type vehicle
- Add Job for the user model to be able to store a job data
- Add safe load function after the the whole plain table data from the database in > awoken_base:main.lua
- Add police resource which is currently show the blip
- Add locker system [ On - going ] currently has a markers which can be interacted by pressing the enter button to open up the menu for it

## [1.0.0] - 2019-08-26
- Set AWK.Players[Source] on quit successfully to nil
- Updated police clothes data
- Add menu handler to be able to borrow a police uniform which costs 250$(can be adjust later)
- Added new resource > awoken_admin which will act like a admin_commands that can set other player's data to anything that provided
- Add a command setPlayerJob

## [1.0.0] - 2019-08-27
- Add a access checker for awoken_admin
- Add a job checker menu - before open the menu for police-job > and can be also use for other jobs
- Create a main menu for police-job
- Add rentPoliceVehicle method
- Change the checker for carkey when tryna turning on the engine > to onHand of the returned function instead of using get current holding item

## [1.0.0] - 2019-08-28
- Add drag system [ On- going ] Remain > release N disable controller while dragging
- Detect if dragger is running or not , and change the animation up-on the speed
- Change the getSharedResource to the main.lua > server[folder] OF awoken_police resource
- Added Death system with perfect adjust
- Added Doctor Job
- Added IPL for doctor to open up the main-menu
- Added CPR by using the firstAid Item
- Added progress when performing the cpr
- Added Animation when cpr is done , and get up [ anim ]

## [1.0.0] - 2019-08-29
- Added Status UI
- Minor Performance fixed for random code

## [1.0.0] - 2019-08-30
- Added Stamina system
- Added Player Interactive - Progress bar system
- Added Set Voice range

## [1.0.0] - 2019-08-31
- Hide Map Hud But Show on car
- Updated the StatusBar UI [ More realistic ]
- Supported set voice range on StatusBar Ui
- Improved Status Bar > Added focusOut if player is idled
- Added ATM and interaction with 3dText [ On - going ]
- Added bank balance to database > user model
- Added restriction from saving [ Prevent from saving the databased sided only ]

## [1.0.0] - 2019-09-01
- Adjust stamina rate when running
- Added Handcuff [ Found trigging 2 animation at the same times :P ]
- Added point finger
- Create a structure of the backend for phone system
- Port from mysql to mongoDB [ On - going ] : Phone system

## [1.0.0] - 2019-09-02
- Phone system finished ( chat , screenshot , call > working RTC)

## [1.0.0] - 2019-09-03
- Created a framework of finding a volunteer to do specific task > like Creating the job object
- Improved on generating the wreck car to be more unique by random the entity-heading too
- Use find 3d groundZcoord instead of PlaceObjectOnGroundProperly : Proper placed object on ground


## [1.0.0] - 2019-09-04
- Finally created the car-wreck job
- Improved the current awoken_progress to be able to handle on success and onTick << Big update >>
- Created the particle fx when doing the animation to make it looks more realistic
- Applied the network to particle fx to be able to be seen by other's player
- Added 2 items ( car engine , metal part ) when player successfully grind the wreck part
- Added random method when grinded car wreck to give the player a random item

## [1.0.0] - 2019-09-05
- Added Crime notify with beautiful minimal Notification which will be appeared on the screen
- Added lockPick item
- Added LockPicking the car and then removed the item when lockpicking is success and Start the vehicle alarm also
- Added Lockpicking Progress

## [1.0.0] - 2019-09-06
- Added Middle market with Sweet UI
- Added hook when successfully sell item to make the UI updated up to date
- Added Economy variable on server which will be fetching the economy from the database and do some calc
- Added Checker when sell item if the data is really valid
- Passed the economy to the UI and do the task instead of the grocery list
- Added the config file where storing the Markets and else
- Added The open menu ability when standing in the right area
- Now UI can be exit when user press the ESC button

## [1.0.0] - 2019-09-07
- New loading screen
- Added the log N information of server
- Make the log box can be scrolled
- Added a custom cursor for loadingScreen
- Added music for loading screen
- Improved the market UI
- Make the UI re-useable with normal shop
- Added the config file for shops
- Added The open menu ability when standing in the right area
- Now UI can be exit when user press the ESC button
- Fixed the item with quantityLeft bugs when tryna dropping >> split the specific string
- Added sprite and chickenPie to the shop
- Food and Drink may now eatable/drinkable
- Moved the thread where keep/drop item to the same thread as the controller <<<< To prevent Keep/Drop while drink or eating glitch>>>>
- Added virtualization hunger and thirst
- Added a smooth transition when drink/eat

## [1.0.0] - 2019-09-08
- Weapon System Has Been Added
- Weapon system support with the hostler animation when pulling in and out
- Improved and optimized weapon system
- Move the thread the used to be a checker from inventory event to the thread of the weapon system
- Exports some useful function in order to be re-useable with other resource when comes to checking the weapon
- Change on drop player item which uses fixed var to set the objectRot > change to place object on ground proper or not
- Added 9mmPistol
- Added 9mmMagazine
- Added 9mmBullet
- Added Holster animation when pullin-in - out weapon
- Improved inventory name of the weapon whether to tell if the magazine is on or not

## [1.0.0] - 2019-09-09
- Created custom input with beautiful UI
- Added a addition method where user can be waited for the input
- Exported those 2 functions
- Replaced new input box with the old one where's using with the pick and drop
- Added bullets system where we can fill in the magazine
- Use custom UI when tryna fill
- Added weapon shop system with a beautiful category UI
- Added the close button to the WS UI
- Added the back button for the WS UI
- Adjust the magazine to be like ( when running out of it . Make it disappear)
- Removed/hide bullet section from the WS [ LOL ]

## [1.0.0] - 2019-09-10
- Design the vehicle UI [ Speedometer , loc , and more ] [ on - going ]
- Fixed the bug when tryna pull the Mag out when bullet meets 0
- Fixed the (withMag) shown with the items with .. ( forgot lol )

## [1.0.0] - 2019-09-11
- Finished the vehicle UI and it is ready to be used
- Added the event for updating the vehicle speed
- Added fuel to vehicle UI
- Added fuel system
- Get the vehicle max-speed and the current speed and calc it to be as KMH and the find the percentage and sent to the HOOK
- Added No-reticle which disabling the crosshair of any-weapon


## [1.0.0] - 2019-09-12
- Created the new version of custom-progress with minimal looking [AF]
- Found out that the crashes problem still detect even in the new JS
- Fixed the crash problem by removed the thread native [ BUGGED NATIVE WITH 1 SYNC]
- Improved the awoken_notification to make the screen look clearly by positioning it onto the right side of the screen
- Changed the font size of the text of awk_notification
- Align the text to right > add the width to the root which is (UL -> LI) to make the weird behavior bug gone
- Fixed the shooting problem caused by the skippednextreload which triggered every frame >> moved to the separated thread and then assign the WAIT to it

## [1.0.0] - 2019-09-13
- Creating vehicle customization
- Added sub-menu support
- Added sub-menu choice
- Added refresh menu on update
- Added Onbuy event
- Added preview event
- [ More part will coming ]
- Added tattoo system [ only preview ]

## [1.0.0] - 2019-09-14
- Vehicle customization may now saved and loaded [ ONLY PROBLEM IS WHEN PLAYER PUT THE VEHICLE BACK TO THE GARAGE AND TAKE IT OUT AGAIN ]
- doorlock system
- Added custom-map police doors  [ double door also ]
- Disable normal game dispatch


## [1.0.0] - 2019-09-15
- Added stunGun
- Added logic to weapon_system where some weapon doesn't has to be reloaded
- Improved weapon_system where people already hold the gun and tryna put another items out
- Added elegy to vehicle shop
- Change html background size to be sized-cover and position> center center
- Dead state will be triggered when player reconnect -> will automatically send to the thread where we virtualize the dead of the player
- Fixed tattoo disappeared after networkRecurrectLocalPlayer => Call the reload function again after all of the process is done
- Fixed LSPD hole by disable the lspd extended map
- Design a game-Text UI which will be support Thai language [ On-going ]
- Holding item can be loaded now with proper timer check

## [1.0.0] - 2019-09-16
- Added Dynamic Game Text With Color and Minimal-Border
- Disabled Old Hospital IPL in BOBIPL -> base
- Fixed mistaken UpdateHoldingItem
- Weapon on hand are now synced with bullets [ Interval-Update ]

## [1.0.0] - 2019-09-17
- Change the interact-menu to be always on - display when triggered the menu [ later check of each func by itself ]
- Added cuff system with animation
- Added progress for the cuff
- Added new car hud
- Done cuffing system
- Added a player Menu on F6 [ JUST UI ]
- Improved logic on inventory items on floor > [ Replace getclosestobject by DoesObjectOfTypeExistAtCoords]
- Check if visible and then show the crosshair [ INTERACT LOGIC IMPROVE ]
- Player may now lift other player with amazing code
- Improved Fuel to sync with passenger [ VEH HUD ]

## [1.0.0] - 2019-09-18
- Added a progress with an infinity loop
- Added an info graphic to show whether the action of the player is doing in that time
- Added function to clear the previous game text
- Added fishing system with an amazing control
- Added generate random fish

## [1.0.0] - 2019-09-19
- Improve AWOKEN_TRACE
- Redesign Loading UI
- Added global sync object and useful callbacks <  INCREDIBLE MOVE >
- Added Force-update
- Added respawn_timer interval for all synced objects
- Added more tree
- Added map icon
- Added prevention from update when away from point 300 radius

## [1.0.0] - 2019-09-20
- Added Miner jon
- Restructuring the tree job to be easily re-useable and more dynamic
- Added timer to the animation to prevent infinity anim
- Added safe interval update object rate to prevent lag
- Added random.seed to the random_thread > server-sided
- Added Trash-job
-- Added trashed_item
- Added Crop Job
- Added check on trailer touch the crop
- Added a menu for a job
- Added RENTAL_VEHICLE Resources > smart move
- Added Particle fx on harvest crop
- Fixed a random on global_object > server_sided [ Move random seed out of the loop ]
- Improved awoken_engine to allow a people with rent car can turn the engine on

## [1.0.0] - 2019-09-21
- Added new market framework with a very perfect UI [ unfinished ]
- Market framework included the picture of the item
- Market framework prices are now sync

## [1.0.0] - 2019-09-22
- Market framework is now ready to be used
- Added cow_job
- Added a respawning_sync timer for each round of a cow
- Added weed job
- Added a craft-table resource [ still in dev mode ]
- Added craftTable items

## [1.0.0] - 2019-09-23
- Improved craftable items logic and other [ still unfinished got a lot of thing to do => remained only the craft part ]
- Improved logic on the online playground [ Craft-table ]

## [1.0.0] - 2019-09-24
- Continued developing on the craft-table
- Finally done the craftable
- Added a progress for crafting
- Improved the craft_table by adding the interval_timer to support the custom timer of the craft time
- Added a crafting_progress which is the same type of the fishing system
- Improved a weed job to be able to sell weed[processed] to the npc[s] with a beautiful random phase and price

## [1.0.0] - 2019-09-25
- Try working on bed system [ Added a hostital_resource but got nothing to do with it yet]
- Added Rental Vehicle lock system to a playground command
- Improved a logic on manual_crafting to be more alike of the craft_table system


## [1.0.0] - 2019-09-26
- Improved rental_lock to be able to press L
- Added a custom progress to a rental_lock system [ normal vehicle re-used ]
- Use rental_veh instead of dummy veh-create of police system
- [ Be working with the criminal system ]
- Crimianl system was successfully done

## [1.0.0] - 2019-09-27
- Created the useful snippet
- Added prison map
- Saved the coords and preparing to use

## [1.0.0] - 2019-09-28
- Added prison_resource
- Jail system was done
- Added a coords check if player fall thru the map
- Added bill route
- Added bill database model
- Done bill route API's
- Added price attribute for bill [ forgot at first place lol ]
- Added view player bill in the police criminal menu > with history included
- Added extra self menu in F6 > radial menu
- Added view un-paid bills in the F6 menu
- Added UI identity system
- Added timeout after being shown
- Improved trash_job > wait for ped still then will be able to do an action

## [1.0.0] - 2019-09-29
- Added vehicle push system
- Made object global sync support a custom interval time and also random heading
- Improved particle to be sync or unsync choice => ex. wreck job and cowjob
- Improved remain check for all jobs that have to do with the remain
- Removed the old car wreck one and re-created the new one
- Added miner particle effect on hitting rock
- Added wooding particle effect on hitting the wood
- Added dymamic tree fall down [ Tree falling thru map because there's no real collision for that object ]
- Added hospital resource
- Added sleeping on the hospital's bed system
- Improved a check if the bed is taken or not [ Is - free ]
- Attached player to the bed instead of setting the position
- Added a table to store each bed configuration based on the bed hash

## [1.0.0] - 2019-09-30
- Added Moveable bed
- Added Pull the wheelup [ Prevent stuck ]
- Added place the bed in the amb
- Added a perfect spot of detection with marker
- Added checker if the bed is already exist in that amb
- Added get the bed out from the amb
- Request for control first before set the cow health to 0
- Use SQL for twitter [ Prevent the mess ]
- Added wallpapers for phone
- Added additional thai languages config
- Change the house owner from fullname to _id instead
- House inventory are now saved and sync
- Trunk inventory are now saved and sync
- Hunger Are now saved and sync
- Thirst are now saved and sync
- Added show_id in interaction_menu
- Added custom height check when player has been dropped from high ground level [ Will be use for death system too ]
- Fixed registeration bug => fix by InitialPlayerData likes when loaded after logging in
- Hide other player when registeration
- Added a clothes-off outfit when customization player
- Added cached entity when selling weed
- Manual craft system
- Fixed tattoo coords
- Doctor job may now rent the vehicle and rent the bed
- Disabled Jerry Can fuel [ Wait for custom coding ]
- Improve weed check if it's a player
- Removed retuurn car from police menu
- Give bill with notify [ But without animation yet ]
- Rent tazer gun for police job
- Remove motocycle from vehicle shop
- Added menu_ buy and market for MINER AND WOOD job
- Change inventory key to f2
- Change mobile phone key to [M]
- Limit the realistic cover of the phone
- Set no-shoe and no pant to be the default when first come to the character_customization screen