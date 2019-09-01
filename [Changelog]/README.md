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