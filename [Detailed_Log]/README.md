This project is created and implemented by [Thiti Mahawannakit](https://www.facebook.com/n.o.m.o.r.e.1.2.8.0.2)

#### Note: The lists below here are the framework used
`FIVEM`

#### Note: The lists below here are the languages and libraries used
`LUA`
`JS`
`HTML`
`CSS`
`Jquery`

#### Note: The lists below here are all of the backends
`Nodejs`
`Mongodb`

#### Current-Features
- [x] Registeration system , Login System
- [x] Save player last position , also if inside instance
- [x] Custom character creation system , Custom NUI V1
- [x] Inventory system
- [x] Items are all unique not just visual
- [x] Dropable item , and useable while on hand
- [x] Custom menu V2
- [x] House system , with key and lock and knocking
- [x] Custom instance system which stored on server-side
- [x] Custom notification system with animated
- [x] Vehicle system , save - load from garage > also check if car is exist on the map
- [x] Remote car key to lock and unlock car
- [x] Realistic sound range with custom calculation
- [x] Vehicle shop with custom PERFECT nui , color is selectable
- [x] Custom vehicle interaction radial menu
- [x] Custom progress - bar [ Circular Styled ] with amazing hook
- [x] Custom vehicle engine system , Start with sound , and stop
- [x] New Interaction MENU with player
- [x] New Confirm menu with amount design
- [x] Give - item with animation
- [x] Clothing system , TAKING-OFF , WEARING-IN with animation
- [x] HAT system > can be taken off and on
- [x] House Inventory system [ Not saved yet ]
- [x] Trunk inventory system
- [x] Death System [ With perfect Synced ]
- [x] Police system [ On-going ]
- [x] Criminal Database System
- [x] Doctor system [ On-going ]
- [x] ATM system
- [x] Status System > Perfect UI
- [x] Custom stamina system
- [x] Queue System
- [ ] Phone System [ On-going ]

#### BIGFIX - CUSTOM FIX
- [x] Sync the vehicle lock or unlock
- [x] Instace system with custom voicechannel that generated the hash from string

#### Incoming-Improvement [ Don't Forget ]
- [ ] Go to all TaskPlayAnim and set the duration for each anim > Prevent casuing Infinite Loop
- [ ] all clothes should have it own name , not just like - Uniform of .....
- [ ] check if holding object in the different instance causing conflict or not?
- [ ] Prevent player from needing to enter the amount when player only had 1 object / also from houseinventory / trunk
- [x] make the awoken_interact_menu triggerEvent when player was loaded and get the information of the list of house inventory > to be more dynamic
- [ ] Save the house inventory to the database with anyway that i like :P
- [ ] When someone is on a driver seat > make it can't open trunk [ Prevent network id request ] > [ Or i have to call to the host for it]
- [ ] Make the hat prop always attached to player [ NOT IMPORTANT ]
- [x] Check if already wear a clothes when tryna put on clothes
- [x] Check for the matching gender when tryna use clothes
- [x] Avoid store a car,house owner as an full string , just store an id of it [ Relation ]
- [ ] AddEventHandler to listen whenever wanting to close all the NUI [ Prevent Conflict ]
- [ ] Check for existing FirstName and LastName on registeration
- [x] Show label if inventory has no item ( Blank box instead )
- [ ] Add prevention from recieving items from different people at the same time
- [x] When buying vehicle > check the plate on the DB first if exist make another one
- [ ] Make crafting system remove the item in the array  >  Prepare for real use
- [ ] Hide other players when registering
- [ ] Cost player money when buy a vehicle
- [ ] Disabled motocycle lock > More realistic
- [x] Save clothes values on changing [ Send to the server-side ]

#### Incoming-Features
- [ ] Seatbeat system ( Minor priority because it is easy )
- [ ] Police system with animation on cuff ( Minor priority because it is easy )
- [ ] ID card system , making and more . . .
- [ ] JOBS , AND ECONOMY SYSTEM
- [ ] Weapon system ( Minor priority because i will be having to be done with the job framework first )

#### Challenging - Features  [ Require extra money > HARD SYSTEM!! > Needed to be Discussed ]
- [ ] Wakie Talkie without using in-game voice channel , and tokovoip [ Using SimpleWebRTC ]

#### Currently working-on
- [ ] Phone system

#### Known-Issue
- [x] FIXED : SOLUTION > AddDelay to wait for control Trunk only can control by host ID
- [x] FIXED : >RELATED TO SERVER PROBLEM [NEED VPS!!!] Instance system not working properly with people more than 2 person in the house
- [x] FIXED SOLUTION VEH_01> Vehicle not sync , even the decor
- [x] HALF_FIXED: >RELATED TO SERVER PROBLEM [NEED VPS!!!] Sometimes Player got instanced when joining the server  [ require hard restart server only ]


<p align="center">
  <b>: Contact me By :</b><br>
  <a href="https://www.facebook.com/thiti.developer">Facebook</a> |
  <a href="https://www.instagram.com/thiti.mwk/">Instagram</a> |
  <a href="https://www.linkedin.com/in/thiti-mahawannakit-558791183/">LinkedIn</a>
  <br><br>
  <img src="https://media.giphy.com/media/h1u6yvxlVKmfLiSryA/giphy.gif" width="250" height="220">
</p>

