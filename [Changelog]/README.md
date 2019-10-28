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

## [1.0.0] - 2019-09-3
- Improve notify on jail time => showing total amount of 7 seconds
- Disabling seat shuffle => preparation for the pull out of vehicle => police system

## [1.0.0] - 2019-10-4
- Improve Prison system checker
- Improve Prison when player is sent => detach from every entity
- Uncuff player when player is sent to the jail => [ Prevent conflict ]

## [1.0.0] - 2019-10-6
- Increase length for rental lock and put player in venhicle
- Put player in vehicle with seat choice
- Pull player out of vehicle with bad chcker
- Improve pull player out now system is now dope
- Improve the checker logic and do the dialog significant if the player is in that seat > show red text
- Added Frisk System
- Added custom input to the frisk system
- Finish Bill system => complete implementation => [ Remain only pay method ]
- Done bill payment method
- Added a spot at the lspd
- Limit the range of Drag And Seat Crontrol system => prevent text happen from long range

## [1.0.0] - 2019-10-7
- Moved the notify on item-detecting to pick up from INVENTORY => awoken_core
- Removed the trash trace from weed job
- Change the Drop item to the new awoken_core system
- Added awoken_core system where objects are all synced with all player
- Commented the un-used old object in inventory resource


## [1.0.0] - 2019-10-8
- Added a true length of draw rect with text system [ Beautiful ]
- Added return vehicle system ( Support up to more than 1 points)
- Added Custom return money
- Change the spawning area of police point
- Adding a guild marker system on the rental vehicle that just got spawned
- Fix the pickLock to also SetVehicleLock to 1
- Prevent from entering the random spawned vehicle
- Added return point for doctor job

## [1.0.0] - 2019-10-9
- Added a category for inventory system
- Added a error handler when the object is bug / missing
- Improved the safe load object when the last saved object on hand is not exist in the system
- Change the name of all the tool / food and weapon to be compatible with the category system
- Change the name of the items that were changed also in the awoken_market_framework
- Replace the new calculated drawrect
- Changed all weed stuffs to compatible with the category system
- Extended the size of the font in the inventory system and also the holder of it self
- Change all the items that supposed to be a Material type to what it needs to be
- When rent the crop vehicle => suddently automatically attached the trailer to that Tractor vehicle
- Added clothes shop system
- Added a preview system for clothes shop
- Added some clothes to clothes shop
- Added on exit menu and restore previous clothes
- Ported the shop / weapon buying menu to use the lastest market framework
- Fixed the lockpick from check the old name without TOOL-

## [1.0.0] - 2019-10-10
- GetClosestPlayer is now filtering the not visible player out of the sight
- Added a naming tattoo system when try to append it ( later for removal )
- Added a removal tatoo depends on the name that player given before when trying to append the tattoo
- Added costing money when try to remove a tattoo
- Improve draw text with rect support with custom font-size and a dynamic width


## [1.0.0] - 2019-10-11
- Scale up the size of inventory 1.25x
- Added all 24/7 shop
- Changed strcutre of shop market
- Separate the shop type and made the itemList dynamically in the config file
- Added vehicle customization
- Added a point for each stop point of veh_cus
- Moved save_vehmod to awoken_vehicles ( old from awoken_vehicle_customization )
- Optimized awoken_core => object by showing what is on the floor and placeholder the amount that wanna pick

## [1.0.0] - 2019-10-12
- Vehicle recieve now will be checking based on the netId ( same old shiet xD ) [ Prevent Enumerating limitation ]
- Removing player from instance if trying to respawn at hospital inside the house
- Added checker for prey [ DRAG SYSTEM ] if the hunter is exist or not
- Added economy system
- Make market framework supported with GCBOURSE
- Add initialize when first run of gcphone => execute the initial event in market framework
- Improve economy system with stable phase and on price decrease
- Done economy system [ STAGE : 1.0.0 ]
- Comment the shift + x in the awoken_voice
- Change the non-network bed to settheentity pos instead of attached [ Prevent floating bug ]
- Change the animation of the player in laying down bed [ Prevent floating bug ]
- Added menu for wreck job
- Added wreck items to the market framework
- Added menu for fishing job
- Added menu for trash job
- Added a Antique Shop for => Trash job
- Make interact-core supported with the awoken_hospital[BED] by putting the variable into the temp data
- Added place player on the bed
- Added pick player from the bed
- Adjust the dead time to 600 second => ten minutes
- Disabled lifted player trying to lift other player
- Added lifting and enter/exit instance
- Disable house menu on lifted
- Disable using item on lifting or lifted

## [1.0.0] - 2019-10-13
- Added a eventHandler of using object in another resource [ NEWLY OBJECT FROM NOWHERE ]
- Added a python script that will generate a code for creating 1 item for us
- Added mask system
- Improve clothesData to be able to handle shared clothes [ GENDER NO MATTER ]
- Added mask shop
- Added left => holding item
- Make awoken_inventory => holding object phase be able to attach thee left hand side
- LATER WILL DO NEW LEFT DROP / GIVE  ANIMATION [ WILL DO !!!!!!!!!!!!!!!]
- Added barber Shop
- Added sit on the seat => playing with scenario
- Added 4 seat in Luxery barb
- Perweek [ in commit ]
- adjust scrollbar of awoken_menu to scroll-top when newly menu appended
- Added hotWire => will be using later

## [1.0.0] - 2019-10-14
- Added UI for crime-alert
- In progress [ doing the UI => crime alert ]
- Updated Hair to request for skin-changer to get the maximum value of possible hair
- Added safeload for chacracter creation => add while awk==nil => holder
- Added badge and adjust the img size to compatible with all size

## [1.0.0] - 2019-10-15
- Added skin-hair desc
- Remove empty css style
- FindClothesData now starting with the false => prevent from nil
- Change the css => crime_alert to absolute => first there was a problem but now it's gone lol
- Mapped all clothes-data
- Adjust card size

## [1.0.0] - 2019-10-16
- Changed from flash to another animation => [ Prevent conflict with the absolute => opcity 0]
- Added custom timer for awoken_game_text
- Added Location for crime alert
- Added a info on reached the crime point
- Added a treehold for a info-text after the reached_point game text was shown
- Moved the function into is player a cop
- Added AWK.IsPlayerACop() to the awoken base
- Prevent Dead player to use the inventory item ( To be held the item on the hand )
- Prevent Dead player from crafting the item
- Fixed the progress size of zeroloadinganimation
- Added return false of the dead checker before using item
- Added prevention from taking off the clothes
- Added AWK.IsPlayerADoctor() to the awoken base
- Added on press E when the time still going on in awoken_death
- Added a type of alert whereas 1 == police and 2 == doctor in the UI of crime alert
- Added condition to select whether which post data will be send to the Registered ui callback
- Added doctor Badge
- Added Emerge in progress functions & events
- Added a custom delay time per signal to the awoken_death
- Resetting the signal timer when the death is being initialized
- Added SAVE_DROP_TO_GROUND_IF_STILL_DEAD to the awoken_death system not including with the [ LOADED DEAD ]
- Change emerge signal key to [ H ] from E
- Added gender to gametext when reached to scene point
- Added AWK.IS_ON_DISABLED_TO_INVENTORY_ACTION() to awoken_base
- Applied AWK.IS_ON_DISABLED_TO_INVENTORY_ACTION() to the awoken_core when player tryna picking up item
- Fixed invalid or and condition of IS_ON_DISABLED_TO_INVENTORY_ACTION
- Show help-text to picking-up the item only when player is not IS_ON_DISABLED_TO_INVENTORY_ACTION
- Check on awoken:antiFallOff2 if Player is-Dead don't un-frozen player ( Prevent from loaded Death)
- Added clothes data for female in crime-alert
- Load shared resource first in   awoken:antiFallOff2 [ Forget lol ]
- Added shared_wait for awoken_death ( Prevent nil )
- MAPPING THE DESC and then passing to the server-side ( first we did it wrong lol )
- EXPORT MAPPING DESC for awoken_death to use => need to generate the player information first
- Fixed the biggest mistake of MAPPING DESC

## [1.0.0] - 2019-10-17
- Changed the old item-name with out the prefix to the prefix one => awoken_craft_table
- Awoken => status new design is progress => [ will be using the png progress bar => PRIORITY LATER ]
- Changed hat prop to cap
- Changed some set of png inventory
- Added z_adjust for core => currently 0.25
- Added pick-up range
- Inventory craft button => position absolute
- Added effect confetti on hit the craft button

## [1.0.0] - 2019-10-18
- Design final inventory UI

## [1.0.0] - 2019-10-19
- Apply the new inventory => (normal work normally) [ UNFINISHED-=> prox_obj => other section]
- Proximitely pickup done
- Dynamic itemsData for => awoken_inventory and awoken_market_framework
- Added mapping function [ Clonning ]
- Added eventlistener on js [ clonning between inv and market ]
- Added safe delay for javascript to be loaded first => 2000 is the current millisecond
- craft_table < Ignore for now >
- Items on hand box update_UI
- Category done
- Fixed missing .. split in HOLDING_UI
- Added AWK.GetWeightFromItemLists
- Added GetPlayerMaximumCarryWeight => default was 240.0
- Mapped the weight also in the MAP_ITEM_CONFIG_TO_JS
- Use toFixed to show 2 decimal places
- AddPlayerItem now will be return true or false if the capacity is ok or not
- KeepItemInPocket now check if the addPlayerItem is success or not => then clear the holding item if yes
- Added AWK.CanAddPlayerItem() to check if can add the item => logic just like the addplayeritem but only do return type


## [1.0.0] - 2019-10-20
- Added Beta weigHt
- Added AWK.CanAddPlayerItem() when player giving item
- Added AWK.CanAddPlayerItem() to the thread where prox_obj was being picking up
- awoken onFirstSpawn in awoken_account removed the line where setting the player location [ Hope it fix the instance bug ]
- AWK.CanAddPlayerItem() on player buy item from middle market
- Added clothes section and fixed the bug that i was using  Js language (!)
- Added refresh the section when newly openning again
- Moved the animation on pick-up to the main thread where the real use is => perfect timer 700f 700b
- Changed styles of custom input
- Added a trans style of inv_item_holder
- Done trunk N frisk but without capacity yet [UI_UPDATE_ITEM_ON_HAND(item.holding)] add to view trunk and other things
- Hide the other_inventory when the player is opening the inventory => and not !isupdate
- Weight on pick from trunk [ On -going ]
- Added check in the addplayerItem where the capacity is being calculate if the itemData is not exist in the config file return false and send the notification
- Added check weight for giveitem and house and trunk => ignore weight if only get 1 item
- CanAddPlayerItem check thread move down until the finalitemname is done generating
- On frisk check weight also
- updateInventory_UI() => remove if condition from it ( So it will be triggered everytimes ) => Prevent viewing the other_inv with the old value
- uodateInventory_UI() reverse back to the condition ( performance stuff )
- Added updateInventory_UI_FORCE() which will ignore the condition and use for everytime the other trunk was open
- On right click craft and then reverse back to the adjusted color ( transparent )
- Fixed pant but ( PANT pants => uppert not found ) => fix by manually added the pair table and pretend to create PANTS
- Added gta-iv minimap
- Added AWK.IS_ON_DISABLED_TO_INVENTORY_ACTION() to litter-N-Bed and also lifting
- Design MICRO INVENTORY UI ( NoPixel Style )
- MICRO INV UI EXPORT => 1 useful func
- Applied micro inv UI to awk.base
- Comment all old notification in awk.base
- Adjust the pic width to 88%
- Update the realistic set of PNG INVENTORY

## [1.0.0] - 2019-10-21
- Created new image progress bar plugin
- Applied new status_UI to the awoken_status
- Added red_money resources
- Added redCash [ Red money ]
- Adjust the top position of progress-bar
- Fixed mistaken trunk.lua in inventory
- Inventory make the cash => redCash priority to the first as second in the inventory
- Removed type and volume args from AWK.AddPlayerItem and replaced with keep => true or false
- Added MICRO_UI TYPE FOUR[4] for keep label
- Added condition in AddPlayerItem for keep or not and then SEND TYPE 2 or 4
- Added entrace system
- enter exit [ Normally working ]
- same re-useable place but with different instance [ on-going ]

## [1.0.0] - 2019-10-22
- Adjust all blips size to the appropiate one using [ CTRL + SHIFT + F ]
- Done entrance system with the re-useable flag
- Entrance system make the reuseAble type when at point 2 iterate all over the reuseable point and check if the hash is match then exit
- Added handler if entrance system can't find the data => set to the random exit point instead
- Added awoken shared inventory resource [ Will be very useful if it is finished ]
- Done shared inventory get keep open
- Made 3d_confirm custom function callback
- Export SHOW_INVENTORY may now can be recieve addition information about other
- Show information on opening ther inventory

## [1.0.0] - 2019-10-23
- Change structure of shared inv to be able to gain extra value
- Adjust some inv prox item and on hand styles
- Disabled on pressing E to pick up item => forcing them to view in F2 ( New window )
- Remove check from where the prox_ will get update
- Showother inventory now will be set display=true => to be able to get the prox item updated
- Added IS_INV_ACCESABLE to check if the inv is access able right now
- Added API-SERVER SIDED
- Added red_money on server side and triggered the api then do whatever i want
- Added sync_machine_data
- Added function for setting the machine data and then triggered all client event then set the data
- Added check on the main thread whereas we showing the label and also the control pressed method
- Added in - progress label
- Done awoken_red_money
- Added AWK.settimeout and cleartimeout on the awk_base_ server
- Applied to the red_money on cancle event
- Added awoken_synced_prop
- Added preview function
- Added export to the resource
- Added dynamic generate prop and all the data that needed
- Added press H to remove one of the closest prop
- Added create_item in the Config_prop_list
- Added prevention if the fetched object is already exist
- Added safe delay interval in the Config file
- Added invalid prop name handler [ 5 sec ]
- Added prop_list for hospital_system
- added AWK.IS_ON_DISABLED_TO_INVENTORY_ACTION_PREY() to the awoken_base [ got_lifted and dead only ] => vanilla [ lift included (HUNTER) ]
- Applied AWK.IS_ON_DISABLED_TO_INVENTORY_ACTION_PREY() to the entrace system where player doesn't has the ability to enter entrace

## [1.0.0] - 2019-10-24
- Added new MICRO_UI for knowledge type
- Timer duration are now set-able in the MICRO_UI new knowledge type
- Added DeadCause and DeadRelatedPlayer in the User Schema
- Trash job prevent help text from cached bin
- Added Locale for a prettier formatted
- Prevent double dead in the water by adding SetPedDiesInWater(ped,false) to the awoken_death
- Added awoken_disable_native_hotwire to disable the native hotwire
- Added 4 main red-money point
- Added med-take point for awoken_doctor

## [1.0.0] - 2019-10-25
- Added Diagnose items
- Skip the part in the add_item python script where the js take place ( skipped because now the system is more dynamic than that )
- Make custom_menu support title name
- Redesign of awoken_menu
- Make awoken_menu responsive to any screen_size
- Final desgin of awoken_menu
- Added label for garage menu and house menu
- Added enter_doubled prevention safe delay for awoken_menu
- Added delay after the enter being pressed [ 1 sec ]
- Adjust awoken chat to the right and change the font
- awkoen_menu now need to do with the scroll and pos vh to vw
- AWK_MENU THE SIZES ARE NOW FIXED
- Added HasCollisionLoadedAroundEntity in to awoken_useful => anitifalloff both 1 and 2



## [1.0.0] - 2019-10-26
- Added awoken vehicle core
- Added label to the closest trunk N hood
- Added find the owner_network of the vehicle and condition on do vouch task
- Added perfect range and smart detection for the awoken_vehicle_core
- Inventory view F2 to view the trunk
- vehicle_core now set the tempdata to point to the in-sight vehicle
- No more empty return from the open trunk send => {} instead for beautify
- Added dynamic label => open nor close condition
- Added condition to check when the 3d is confirmed => AWK.GetTempData().current_trunk == GetItemFromTrunk.Vehicle { check if the vehicle still in sight }
- Added additional text info == for vehicle trunk
- Dynamic timer check for the open_ratio after triggered the task => if successful then will show the help text => 1000ms
- Added Get the native lock status to prevent openning trunk/hood from locked npc car
- Disabled inventory_house on eye point to the pos => awoken_interact_menu
- Added label for house_inv and also the help text
- Added key left alt to open the house inventory
- Added addition info for house inv_text on other_info() will be rendered
- Disabled function on lookin at vehicle = > only pointing the eye contact png
- Radialmenu disable cycle type class => shift menu
- Replaced hood N trunk find closest car with local vehicle = GetClosestVehicle(GetEntityCoords(PlayerPedId()), 4.0, 0, 71) instead of getvehicle in direaction / infront because the precision of that calculation is really pretty bad
- Turn face to the veh before opening the hood/trunk
- Later will do on turn on house inv [ WILL DO ~~~!! ]
- Moved the inv_pos of default house inside of the cloest where the perfect heading will be occurs :P
- Turn ped face on house inv done
- Handler if can't find the exit point for the house
- Showing the house blips only for un-sold one
- When the house is bought remove the exist blip
- Removed the collision check from awoken_useful => anti_fall off both 1 and 2 ( useless )
- Added remove house command
- Added AWK.SendClientMessage and Added AWK.SendClientErrorMessage
- Set default color table ( r,g,b ) to light-green
- Added 2 useful house_interior
- Added tree and altstreet to optimized street for more realistic
- Added inv_data
- Awoken House get distance between coord now use the Z ,true <=  was passed
- Fix iteration when inside-the house and trying to fix [ Loop thru all exist house_inside first then . . . ]

## [1.0.0] - 2019-10-27
- Handler on instance==main but got inside to instance and can't find the way out
- Added AWK.Print3DText Mythic  syles
- Added handler on type invalid => create house commands
- Added new house type => 3
- Added bed for the house type => 3
- Change marker style to the final version
- Range change to the default of 8.0
- Added lock_picking core and all of the resource
- Lock_picking in stage [3] out of 5
- Will do awoken apartment system [ in - progress ]
- Added Apartment mongo - models
- Aps create - remove
- Make Aps system dynamic => with entrance system working together
- Added useful APIS for awoken_entrance
- Added awoken_js_util => [ In - progress ] => will be use for check if the time passed x day then eject the old owner

## [1.0.0] - 2019-10-28
- Added awk_audio [ In - progress ]
- AWK_AUDIO FINAL STAGE [ REMAIN ONLY IN APARTMENT VOICE / INSTANCE ]