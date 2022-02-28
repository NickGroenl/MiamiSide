# MiamiSide Updates (xylospeed developer)


# (Miamiside 0.2.9)
- Removed and redone the base of the house system
- Apartment type houses can now interact with their door with the Y key (to open or close it, the door will also move visually)
- Added a new type of dialog for lists or jobs with a large number of slots, such as backpacks
- Removed the anticheat and did it again
- work started on the damage system
- now the "cell phone" item is something personal, you can only have one of them and not throw it away
- the furniture system was remade


# (Miamiside 0.2.8)
- the command for the government body in which it consists is finished, in the locker of your department you can equip items such as cones, spikes or barriers in your inventory to load it on the mobile or a van
- the weather would change according to the role time on the server (time does not run the same way as outside your PC)
- the year cycle was added, miamiside will start in 1979 and will go up as time goes by
- now each daily payment adds +1 day to what would be the month (30 months = 1+ month, 12 months = +1 year)
- Started working in the government-type company
- fixed a bug in Miamiside Coins boxes

# (Miamiside 0.2.7)
- The Police type company was added
- Police, government or fire lockers have the option to take a tactical belt
- now the tactical belts (/ct) bring; in slot one and two the capacity of different weapons, slot 1 (9mm and desert-eagle), slot 2 (shotgun, m4, sniper)
- the /pmenu command is finished, in which you get a dialog if you are close to a player for the following options, arrest, join a patrol, search or confiscate an object
- Work began in another command on the construction of checkpoints in a dynamic and simple way for government bodies
- master account error with name variable set to 88
- now the commands /do, /me, /g, /s, /b and even when speaking, if you exceed the character limits then the double line method is applied
- now the inventory when selecting an item, it will be marked in purple
- fixed anticheat bugs


# (Miamiside 0.2.6)
- Modified the key to open/close vehicle (y + space)
- The company of type: Assembly of vehicles was finished
- The password hashing system (hash = security) was modified to the bcrypt method
- Vehicle system bugs fixed
- now in gear 5 it will not get stuck

# (Miamiside 0.2.5)
- fixed taxi company error
- visually modified the speedometer
- now company owners can add vehicles to their company (so members can use them)
- now companies can choose the id of the skin they want their employees to use
- now there is the /service command
- open and close vehicle with Y key
- now you can modify the position in which the /service command will be used
- now the engine will not turn off when in gear number 1
- fixed other bugs

# (Miamiside 0.2.4)
- Fixed hud bug
- Fixed login error and character menu
- Fixed anticheat bugs
- Now running out of bullets in your weapon will not make it disappear, but instead place it next to your hand as an item
- The first "Taxi" type company with its work as such was added
- Now the companies will have a work skin, when you start service you will get this skin and when you go out of service you will return to your original skin


# (Miamiside 0.2.3)
- Fixed vehicle system error
- Now when changing gear it will not throw you back to the vehicle
- Fixed bug that vehicles in gear number 2 catch fire
- Added radar in the top right corner
- Now the cell phone correctly lowers the battery
- Base of companies and businesses already finished
- Rent of automatic vehicles throughout the city
- First mission added for Pablo Escobar
- Visual fixes on the Vice City map
- Now when throwing an item from the inventory it will do it correctly
- Fixed mysql errors

# (MiamiSide 0.2.2)
- Fixed and finished the MiamiPhone system
- Solved problems of the trunk and accessories of the vehicle
- Base company system almost finished
- Started working on the business system and its NPC purchase system
- New types of notifications in the middle below Gta V style
- Fixed Hud bug
- First type of business finished "24/7"
- Now when you are in an entrance you will get the notification "Press Y to enter" "Press Y to exit"
- Character problem in mysql that caused an error fixed
- Now the include of the dialogs is per player and not global
- New skins added
- Now businesses can put/edit/buy furniture(Connected with business purchasing system)
- You can manage your online members who work in your company and everything with the /mycompany command
- Doors for companies editable
It is by the owner, automatic with the Y key



# (MiamiSide 0.2.1)
- The saving and loading of vehicles is finished
- Daily payment system
- Tax and other Government faction details
- Include for semi finished bars
- Working on an installer for all the files that miamiside will use
- New notifications(ThePez)
- Now with coins you can /buy boxes
- Command / help by pagination.


# (MiamiSide 0.2.0) preview 04/02/2020
- Work began on the cimenatica of the beginning and missions of Pablo Escobar and Ronald Reagan
- Modified the hud
- The inventory was modified
- Changed all logging/registration
- Working on our own progressbar
- New skins added

# (MiamiSide 0.1.9) preview 02/06/2020
- Most textdraw's were optimized
- now we will be using more attractive designs in the textdraw's (all will be remodeled)
- an .inc dialogs was created, adding our own dialogs, fully functional and dynamic
- The first fully nude skins have already been modeled to test the clothing system.

Compilation time 3.1s

# (MiamiSide 0.1.8) preview 01/14/2020
- Minor gear system bugs fixed
- Now when holding down 2 the clutch will not release, 2s after releasing 2 the clutch will release
- Accessories for vehicles were added (Still adding models)
- New textdraw for vehicle accessories
- Added commands /vmenu (inside the car to turn on/off engine and more) and /vtoys to see the accessories menu of your vehicle, all this with the vehicle key in hand.
- Added a function to duplicate the keys in the future
- Work began on the trunk of the vehicle

Compile time: 3.5s


# (MiamiSide 0.1.7) previews 01/10/2020
- Added icons to cell phone textdraw
- Added icons to hud bars
- Added cell functions, call, send messages, view contacts, all clickable and interactive
- Work began on the vehicle system
- Now the vehicles store, life of the car, battery, gasoline, water, oil and other factors
- Adapted a speedometer textdraw, with clickable functions
- Added a new manual gear system (N, 1, 2, 3, 4, 5, R)
"Key Y to go up, N to go down, 2 for the clutch, it is important to use the clutch to change gears, if you force the engine to reach its speed limit per gear, it will be damaged"

Compile time: 3.0s

# (MiamiSide 0.1.6) previews 01/08/2020
- Removed some things from the anticheat (they worked badly and will be done again)
- The basics of the company system were finished
- The company type "Production of clothes" was added with its respective interactive work
- Added some inventory functions
- A new object was added to the inventory "Cell phone" with its respective textdraw and functions, these cell phones have a battery, sim card and other things.

Compile time: 3.4s


# (MiamiSide 0.1.5) previews 01/01/2020
- Fixed an anticheat error that if you had no ammunition it would take away your weapon
- The furniture system was left aside for a while (to work on it better)
- The needs textdraws and the logo were totally changed
- Added a new hud (already working)
- The server was updated to version 0.3DL since now when spawning you will appear in the new parts of Miami

Compile time: 3.1s


# (MiamiSide 0.1.4) Previews 12/28/2019
- Fix in the anticheat that took your money
- Fixes in the administrator log
- A doubts channel was added for all users, if your rank is assistant or higher you will not have to wait 60s to speak
- Added 4 new objects: radio communicator (/fr, /r), hamburger, water, apple (used with right click) and their respective functions
- Started working on the company system (replacing the faction style)
- /invite and /eject commands
- Work began on the furniture system for companies
- Work began on the type of work that each company will give according to its type
- Now companies have a limit of 25 members
- New textdraw for the furniture menu.

Compile time: 3.1s


# (MiamiSide 0.1.3) Previews 12/26/2019
- General command fixes
- Logging fixes
- Now when picking up an object it will send you a notification
- Now admins can give items
- Each administrator command will be recorded in a log in the database, if it does not have approval it will start a countdown which will lead to a ban

Compile time: 3s

# (MiamiSide 0.1.2) Previews 12/21/2019
- Inventory can now be opened with the N key
- Fixed inventory bugs with the VIP
- Added new business type(Ammunation)
- The ammunation type business can now sell up to 5 types of weapons, only modifying the price-
- Added an automatic ban system
- Now when trying to use a weapon that is not in your inventory you will be banned automatically
- automatically (100% precision)
- Anticheat fixes

Compilation time: 3.2403 seconds.


# (MiamiSide 0.1.1) previews 12/20/2019
- Added 10 types of weapons to inventory, max handgun(1) :(9mm-common, 9mm-silenced, Desert-Eagle, Shotgun, Micro-Uzi, MP5, AK-47, M4, Rifle, Rifle- Sniper)
- Now when you enter you will have a gift from miamiside
- All the bugs that the server presented until now were fixed
- The anticheat was restructured so that it is %100 specific when it works, so that life, vest, money and weapons take less than 0.5s to reset it in case you use cheat
- fixed some textdraw's
- more admin commands
- Optimization of the code and the timers since they worked badly

Compilation time: 2.9059 seconds-

# (MiamiSide 0.1.0) previews 12/13/2019
- fixed a virtualworld error which took you out of the server
- Fixed bugs in logging
- new inventory system in textdraw with clickable items and the ability to throw/pick up
- items added to the inventory system: briefcase, ammo and deagle
- work is being done on the clothing system, with interaction with the inventory and its own textdraw
- added role commands
- added some admin commands

Compilation time: 3.0004 seconds.

# (MiamiSide 0.0.9) previews 12/08/2019
- Some big bugs were found which are being worked on
- New level system, with rewards and textdraw
- now receiving or losing money will send you a notification in textdraw
- Now when you use /changerpj you will get a clickable textdraw to change your character in just seconds
- New needs system(not finished)

Compilation time: 2.8049 seconds.


# (MiamiSide 0.0.8) previews 12/02/2019
- Work began on the map of Miami 0.3DL (soon images)
- Bank-type business finished (money transfer options and debit card, I'll save them for later)
- We are working on a new type of business (Stockbroker) more info in a txt that I will leave on the github
- The stock market system is finished, it needs to be adjusted to the TextDraw's
- The business system will be set aside for a time to work and address more important issues
- Improved some anticheat functions (already tested) Skin, money, life, vest.

Compilation time: 0.8980 seconds.

# (MiamiSide 0.0.7) Previews 11/29/2019
- Now you can buy/sell your business
- You enter/exit with the letter Y of the business
- The "Clothing Store" type business per level (MAX 3) is finished, what the level does is that you generate more income and give you access to sell more variety of skins, since level 1 limits you to 68 skins, to sell you will have to have merchandise (this is connected with a job that I will give information soon)
- added command /buy clothes, planning to pass it to the letter Y
- Started working in the stock market (buying and selling shares of a business) and the bank-type business.
- Optimization throughout the code and great bug fixes

Compilation time: 0.9876 seconds.


# (MiamiSide 0.0.6) Previews 11/27/2019
- Added textdraw's for business system(9)
- Work will be done on the interiors for the business system (each business will have a maximum of 50 pieces of furniture, VIP 100)
- the saving, loading and some functions of the business system are finished
- added a level function for the business system
- Anticheat redone and optimized
- Update to 0.3DL(for the map)

Compilation time: 1.1004 seconds.



# (MiamiSide 0.0.5) Previews 11/19/2019
- Updated all server textdraws to improve optimization for low-end PCs
- from 73 textdraws to 26, removed HUD functions to work on later
- Work began again on the map (finishing the port)
- Added a server logo
- Fixed errors that when selecting a character gave you a random skin

Compilation time: 0.9947 seconds.



# (MiamiSide 0.0.4) previews 11/12/2019
- Moved all logging/registration system to mysql-r41-4 with added string escape function
- HUD functions were modified (NOT VISUAL)
- Work on a new idea regarding all textdraw's (to help with low end PC's)
- Administrator commands began to be added

Compilation time: 0.8997 seconds.




 # (MiamiSide 0.0.3) previews 11/04/2019
- Logging and registration through textdraws are finished
- Character creation through textdraws is finished
- The character selection (3 slots, slot 3 VIP) through textdraws is finished
- A VIP system is being made
- The factions loader was eliminated to redo it later
- Optimized all the TextDraws of the server (for low-end PCs)
- The textdraws of the new HUD were created, only compatible with the GTA:SA hud
- All HUD functions are being added

Comm Timestacking: 0.8976 seconds.



 # (MiamiSide 0.0.2) previews 10/23/2019
- The master account login system is being recreated (textdraw)
- the character system is being recreated (textdraw)
- Now if the tables are not found in the database the system creates them automatically
- Fixed bugs with symbols #, @, Ñ, ´
- The spawn is being created (after creating your PJ) with an intuitive and fun GTA V-style mission

Compile time: 0.7986 seconds



 # (MiamiSide 0.0.1) Creation 10/13/2019
- The gamemode was created.
- The saving/loading/registration of the master account was created via textdraw and Mysql.
- The saving/loading/registration (working) of characters (max 2 characters) was created by master account.
- The gamemode is being worked on via modules to improve its optimization.
- Anticheat of money, life, vest, skin, level and some more.
- The saved/loaded/created IG (working) faction system was created.

Compile time: 0.4564 seconds
