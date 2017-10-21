Don't feel disparaged if you can't get it working with this alone a lot of people can't when they're first starting messing with these things.

I'll give you a link to my discord, ( https://discord.gg/gRHYA2X ) and/or you can connect with me through a messenger (They're linked to my FFXIAH account.)
If you're relatively computer savvy, it shouldn't be too hard, if not, I'm happy to help explain more or answer questions even if you do get it working.

1.) Go to my dropbox ( https://www.dropbox.com/sh/20vy32liub3glxz/AAAiIVHAasFdwCK1SZdZz7d_a?dl=0 ) and download my entire gearswap folder as a zip file.

2.) Go to your Windower4 folder, if you don't know where it is, you can right click your windower icon and click "Open file location".

3.) In your windower4\scripts folder replace your init.txt with the one you downloaded, this step is skippable, if you don't want to use any of the non-official addons
	I have found/wrote and don't care about my custom keybinds and aliases.

4.) Completely delete your windower4\addons\Gearswap\libs folder, just the "libs" folder itself in there and replace it with the libs folder you downloaded from my dropbox.

5.) Completely delete your windower4\addons\Gearswap\data folder, just the "data" folder itself in there and replace it with the data folder you downloaded from my dropbox.

6.) Inside your data folder, change the folder named Selindrile to your character's name, then open that folder, and replace ALL instances of the name Selindrile to your
	character's name, if you have multiple characters, copy this whole folder, and then rename it and everything inside to another character's name, rinse repeat.

7.) You can review my other addons, some of which I wrote and some of which are collected throughout the internet and download whichever appeal to you and put them in your
	gearswap\addons folder, some of them automatically load (the ones I use) if you replaced your init.txt file, it's easy to add/remove more there.

8.) Edit your gear, the only files you want to edit are the ones inside your "Character" folder, the ones that I named Selindrile, that you changed, those are the equipment
	and settings specific to that character, if you have any trouble understanding those, feel free to ask me, preferably through discord or a messenger, if you use
	FFXIAH or Email, replies will be very slow but you're welcome to do so, but PLEASE DO NOT MESSAGE ME ABOUT ANYTHING THIRD PARTY IN GAME, I will not respond.

9.) I update my gearswap files frequently, to receive updates without destroying your gear settings, repeat steps 3, 4, and instead of 5, just replace the 22 Job.lua
	files, such as Blm.lua, Blu.lua, etc, do not delete or modify anything inside your character's folders.
	
10.)For full functionality my gearswap and init files do depend on a few other addons that can be found in your launcher, I'll list them here: 
	Addons: Shortcuts, Cancel, Itemizer.    Plugins: Timers, Run
	
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ Macros and More ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

[Ctrl+F8]	= Toggle auto-stun mode, will attempt to automatically stun a list of moves in your
			  Windower4\addons\GearSwap\libs\Sel-MonsterAbilities.lua file.
:Macro:		/console gs c toggle AutoStunMode

[Alt+F8]	= Toggle auto-defense mode, will attempt to automatically swap into and out of defensive sets for
			the specific move, listed in your Name-Globals file.

:Macro:		/console gs c toggle AutoDefenseMode

[Win+F8]	= Turns on auto nuking on some jobs.

:Macro:		/console gs c toggle AutoNukeMode

[F9]		= Change offense mode. (Usually Engaged, accuracy modes) Fodder (Trash Mobs) sets generally
				have more Dual Wield/Multiattack because they don't have to worry about Acc/Atk.
				
:Macro:		/console gs c cycle OffenseMode


[Ctrl+F9]	= Change hybrid engaged mode. (Usually defensive modes such as PDT or Evasion, combines with
				offense mode to create an engaged with both options if you created it in gearswap.

:Macro:		/console gs c cycle HybridMode


[Alt+F9]	= Change Weasponskill mode. (Usually accuracy sets to depend on targets.)

:Macro:		/console gs c cycle WeaponskillMode


[Win+F9]	= Change ranged mode. (Again usually accuracy sets for target's evasion.) This doesn't affect
				ranged WS, that's the above.
				
:Macro:		/console gs c cycle RangedMode


[F10]		= Somewhat "Lock" a Physical defense set in, only changes some gear for spells and abilities
				generally an "OH Shit Button" to be used in response to physical abilites.

:Macro:		/console gs c set DefenseMode Physical


[Ctrl+F10]	= Change the current Physical defense set, generally things like PDT, Evasion, PDTTwilight
				that the above command locks in place.
				
:Macro:		/console gs c cycle PhysicalDefenseMode


[Alt+F10]	= Toggle kiting mode. Makes your movement speed items stay in place when in idle/defensive idle
				sets, and should also have it likely overwrite any movementspeed reducing slots.

:Macro:		/console gs c toggle Kiting
		
		
[Win+F7]	= Automatic ranged attacks, right now only set up for RNG and COR, this uses a different internal
			  "clock" from other automatic modes, so they aren't completely friendly, to change what weaponskill
			  it uses automatically you can edit the files in libs or use: gs rh set "Weaponskill Name"
			  
:Macro:		/console gs rh toggle
		
[Win+F10]	= Toggle job specific modes, different depending on jobs some examples:
				Also sometimes Ctrl/Alt/Win + Grave/Tilde (` or ~) or even Backspace, Backslash, Delete, Dash or Equals.

:Macro:
Thf:		/console gs c toggle AmbushMode		(Equips Ambush gear on TP and non SA/TA WS)
Blu:		/console gs c toggle LearningMode	(Locks learning gear in at all times.)
Pld:		/console gs c toggle EquipShield	(Allows Weapon/Shield to swap with F10/F11)
Brd:		/console gs c cycle ExtraSongsMode   (Your next song plays as a dummy song.) [Ctrl+~]
Blm:		/console gs c cycle RecoverMode		(Nukes in converts elemental damage to MP gear)
Blm2:		/console gs c cycle MagicBurstMode	(Single makes your next spell burst, while lock keeps it bursting until you toggle again.) [Win+~]


[F11]		= Somewhat "Lock" a Magical defense set in, only changes some gear for spells and abilities
				generally an "OH Shit Button" to be used in response to magical abilites.

:Macro:		/console gs c set DefenseMode Magical

[Ctrl+F11]	= Change the current Magical defense set, generally things like MDT, MagicEvasion, MDTTwilight
				that the above command locks in place.

:Macro:		/console gs c cycle MagicalDefenseMode



[Alt+F11]	= Extra job specific modes, Pld gets extra defense modes, other melee generally get extra
				melee modes.

:Macro:
Pld:		/console gs c cycle ExtraDefenseMode
Melees:		/console gs c cycle ExtraMeleeMode

[Win+F11]	= Casting modes, such as resistant, and fodder mobs, and sets for proccing (Low damage, low recast).

:Macro:		/console gs c cycle CastingMode

[F12]	= Somewhat "Lock" a resistance set in, only changes some gear for spells and abilities
				generally an "OH Shit Button" to be used in response to certain abilites.

:Macro:		/console gs c set DefenseMode Resist

[Ctrl+F12]	= Change the current resistdefense set, generally things like MEVA, Charm, Death
				that the above command locks in place.
				
:Macro:		/console gs c cycle ResistDefenseMode

[Win+F12]	= Changes the current idle set, from refresh, regen, PDT, etc.

:Macro:		/console gs c cycle IdleMode

[Alt+F12]	= Unlocks current defense mode.

:Macro:		/console gs c reset DefenseMode

[Pause/Break]		= Displays most current modes and reequips gear appropriate to your status.

:Macro:		/console gs c update user

[Ctrl+Alt+Win+F12]	= Reloads gearswap to reset all the current modes or update changes quickly.

:Macro:		/console gs reload

[Ctrl+Alt+Win+F1] = Toggles windower lighting setttings.
				
:Macro:		/console gs c cycle MagicalDefenseMode

[Ctrl+Alt+Win+Pause/Break]	= Runs Organizer to obtain your curren't job's gear as listed in your gearswap file.

:Macro:		/console gs org

--- Non F-Key combinations. ---

[Ctrl+T]	= Change treasurehunter mode, Tag: Equips TH gear for one hit, Fulltime keeps it on always, SATA for Sneak/Trick Attack.

:Macro:		/console gs c cycle treasuremode

[Alt+T]		= Target battle target. (Red mob claimed by party.)

:Macro:		/target <bt>

[Ctrl+O]	= Toggle fillmode. (See through walls/ceiling/floors.)

:Macro:		/console fillmode

[Alt+P]		= Equip Cure-Potency-Recieved gear for maximizing incoming cures reactively.

:Macro:		/console gs equip sets.Self_Healing

[Win+P]		= Equip Sheltered equipment for maximizing incoming Protects and Shells.

:Macro:		/console gs equip sets.Sheltered

[Win+Pause/Break]	= Toggles AutoBuffMode which automatically buffs.

:Macro:		/console gs c toggle AutoBuffMode
SubCommand Examples to change options:
//gs c autoindi Focus
//gs c autogeo Malaise
Can change default options in the gearswap job_character_gear file with:
autoindi = 'Focus'
autogeo = 'Malaise'

[Ctrl+Win+Alt+F7]	= Toggles AutoWSMode for automatic WS.

:Macro:		/console gs c toggle AutoWSMode
SubCommand Examples to change options:
//gs c autows Savage Blade
//gs c autows tp 1250
Can change default options in the gearswap job_character_gear file with:
autows = 'Savage Blade'
autowstp = 1250

[Alt+F8]	= Toggles AutoDefenseMode, automatically pushes your F10-F12 keys for defense.
			  Edit options in your Windower4\addons\GearSwap\libs\Sel-MonsterAbilities.lua file.

:Macro:		/console gs c toggle AutoDefenseMode
			
--- Addon and Plugin related combinations. These are in init, but they can be moved elsewhere. ---

[Ctrl+Alt+Win+?]	= Load or reload the Addon or Plugin, the ? is the key specific to the related Addon or Plugin.
[Win+?]				= Unload the Addon or Plugin, the ? is the key specific to the related Addon or Plugin (With the exception of Gearswap).

[G]					= Anchor (Prevents you from being knocked back by monster TP moves.)
[Q]					= AllSeeingEye (Allows you to see things usually invisible to players.)
[O]					= Dressup (Prevents players from blinking with the proper setup.)
[T]					= Zonetimer (Keeps track of the amount of time you've spent in a zone, or since you loaded the timer.)
[I]					= Gametime (Tracks days of the week and current time at the top of the screen.)
[R]					= Treasury (Automatically lots and passes or drops certain items you set.)
[F12]				= Gearswap (Reloads to reset all the current modes or update changes quickly.)

My scripts\init.txt loads Request, which is an addon that can be used to answer player's requests, use it with the Shortcuts addon.
It also loads a few other addons which I've written or found from other sources.
Non-Official addon mentioned here can be downloaded from: https://www.dropbox.com/sh/qz5rb5je202cbu3/AAAxozfBv_8agarM0NCnPTiZa?dl=0

--- Item related combinations. These are defaults, can be changed in Character-Globals.lua ---

[Ctrl+Alt+Win+?]	= Obtain the item linked to the ? key from your satchel. (Requires the Itemizer Addon)
[Ctrl+?]			= Equip (and usually lock) the item in place.
[Alt+?]				= Use the item. (if usable)
[Ctrl+Alt+?]		= Unlock, unequip the item, and stow it in satchel. (Requires the Itemizer Addon)

[H]					= Warp Ring.
[N]					= Nexus Cape.
[Z]					= Capacity Cape.
[Y]					= Capacity Ring.
[[]					= Trizek Ring.
[]]					= Echad Ring.
[K]					= Facility Ring.
[U]					= Reraise Earring.

[Control + Z] Capacity Mode
Will automatically use capacity items and keep capacity cape on, for this to work it
seems you must keep your capacity items in your inventory or satchel, not in any wardrobe locations.
In the wardrobe they seem to report the wrong times to the function that checks them, don't know why.

--- Auto Commands ---
Some of my job gearswaps have automatic functions, like auto-enmity for Pld, auto-buffing and auto nuking, often they are
windows +f8 or windows +Pause/Break - These can mostly be changed in Character-Globals.lua.

:Macro:		/console gs c toggle AutoNukeMode
:Macro:		/console gs c toggle AutoBuffMode
:Macro:		/console gs c toggle AutoTankMode
:Macro:		/console gs c toggle AutoReadyMode
:Macro:		/console gs c toggle AutoNukeMode
:Macro:		/console gs c toggle AutoSubMode

You may reset some of the choices for automatic modes with commands like the following.

//gs c autonuke fire5
//gs c autows Savage Blade
//gs c autows tp 1250
//gs c autofood Soy Ramen

Export Command for editing gearswap.

//gs export lua    OR    /console gs export lua

Creates a file in Gearswap\Data\Export with your current set detailed as a file, useful for
getting specific augments labelled just right in gearswap, either for putting job specific items
at the top of your job_gear lua or for all jobs in your items.lua.

----- Elemental handling commands for mages.
:Macro:		/console gs c cycle ElementalMode
:Macro:		/console gs c elemental [COMMAND]

Commands:
nuke - Highest Nuke
smallnuke - Tier 2 or 1 nuke.
helix - Elemental Helix
weather - Scholar Weather
skillchain1 - Tier 1 skillchain
skillchain2 - Tier 2 skillchain
skillchain4 - 4 Step skillchain for popping Perfidion
skillchain6 - 6 Step Skillchain for popping Pluton (Requires you have a strategem up and 5 strategem charges to start)
wsskillchain - Attempts to start skillchain with a weaponskill and finish with a spell (for conserving stratagems).
endskillchain - Attempts to end a skillchain with the current element.
tier1 - Casts a tier 1 spell of that element.
tier2 - Casts a tier 2 spell of that element.
tier3 - Casts a tier 3 spell of that element.
tier4 - Casts a tier 4 spell of that element.
tier5 - Casts a tier 5 spell of that element.
tier6 - Casts a tier 6 spell of that element.
aga - Casts highest available aja/aga spell of that element.
aga1 - Tier 1 aga
aga2 - Tier 2 aga
aga3 - Tier 3 aga
aja - Aja spell
ancientmagic - Burst/Flood/Etc
ancientmagic2 - Burst2/Flood2/Etc
enfeeble - Elemental enfeeble of that element.
bardsong - Threnody of that element (for aby proccing)
ara - Highest ara spell of that element
ara1 - Tier 1 ara
ara2 - Tier 2 ara
ara3 - Tier 3 ara
