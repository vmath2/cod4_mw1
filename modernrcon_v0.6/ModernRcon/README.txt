Application:  ModernRcon
Author: Josh "JD" Olin
Version: 0.6
Date: 2/23/08

Website: http://www.CoDHQ.com

Overview:

This is a program designed to allow Call of Duty 4: Modern Warfare server 
admins the ability to monitor and control their CoD4 servers remotely, 
without having to be in-game playing.

Requirements:

Java
- latest version recommended
- www.java.com

Usage:

Just run the ModernRcon executable in any Windows environment.

IMPORTANT: Vista users, you may have to run ModernRcon as Administrator if you have the 
"User Account Control" enabled. Right-click ModernRcon and choose "Run as Administrator."

Current Release Features:
    * Save servers to a server list.
    * Realtime in-game chat monitoring! (PBUCON)
    * View server information (gametype, map, name, players, etc).
    * Kick, Ban, TempBan, Message, Private Message, and monitor players.
    * Kick, Ban, Screenshot, and more via PunkBuster controls.
    * Restart Map, FastRestart Map, Load next map.
    * Load a selected map from a list of maps.
    * Load custom maps!
    * Set a new gametype when loading a map from a list.
    * Configure all basic settings, including Hardcore mode, Autobalance, Friendly Fire, etc.
    * Set or remove server passwords!
    * Manually enter commands into the console and read responses. 
    * Configure all aspects of all supported gametypes.
    * View / modify map rotation settings. Easy tools like Rotation Builder exist!
    * Send messages to the server.
    * Send messages to individual players.
    * Setup rotating messages to display to the server on an interval.
    * Save message rotations.
    * Auto-update player list for easy server monitoring.

Future Releases:
    * Additional DVAR controls: airstrikes, UAV, helo, etc.
    * Offline "Config Builder" tool for writing config files.
    * Auto-kick feature for Chat Monitoring.
    * Rcon Limiter (for granting lesser access to clan members).
    

Release History:
2/23/08 - ModernRcon v0.6
    Added:
    	- Password field in Basic Settings panel for managing the server password.
    	- "Custom Map" field in the Maps tab for loading custom maps.
    
    Foxes:
    	- scr_oldschool_mw problem fixed for real this time...
    	- Fixed PBUCON's ú character issue. No more error 106 about not being authenticated!
    	- Spelled "Version" properly.
    	- Fixed issues with Windows XP truncating the status text at the bottom.
    	- Map rotation tab now uses sv_mapRotation DVAR instead of mapRotationCurrent.
    	- Players with negative score will now show in player list!
    	- Loading a message rotation, in previous versions you could not double-click the 
    		second entry in the list. Fixed that.
    		
    	Code Count: 6560
    	
    	
1/6/08 - ModernRcon v0.5
    Added:
    	- Auto-refresh for player list.
    	- Refresh List button for quicker refreshing of player list.
    	- Global Refresh button for refreshing all server DVAR's.
    	- Support for mp_crash_show map.
    	- PunkBuster tab for listing players' GUID's.
    	- PB controls for: screenshots, kicking, banning, etc.
    	- Kick and Ban messages for PB kicking and banning.
    	- All new master server functionality for notifications of updates.
    		* This feature is the ground works for auto-updating.
    	- Disconnect button for closing PBUCON.
    	- Saving the list of players on either the Players or the PB tab has changed.
    		* Now it will save to respective folders as timestamps for filenames.
    
    Fixes:
    	- Fixed the oldschool_mw issue.
    	- Fixed some rare issues that cause the program to hang.
    	- Fixed the progress bar from popping up in center of the screen.
    		* Now it pops up in the center of the program you ran it from.
    	
    	Code Count: 6,407 lines of Java code
    	
    	
12/15/07 - ModernRcon v0.4
    Added:
    	- Realtime in-game chat monitoring!!!
    	- Basic Settings tab for configuring additional DVAR's.
    	- Progress bar for notifying users that the server is being queried.
    	
    Fixes:
    	- More hanging issues when bad UDP packets are received.
    	- DLL file for arbitrary incompatibility issues.
    	
    Authors Notes:
    	- Brought on a new part-time developer, Alberto Rosano aka "Ros".
    	- Ros made the Basic Settings tab.
    	- This was one of our "smallest" updates in terms of fixes and 
    	  feature count, but it added the most lines of code.
    	- The realtime in-game chat monitoring is a HUGE system. You 
    	  probably will never appreciate how challenging that was :-P
    	
    	Code Count: 4,981 lines of Java code
    	

12/8/07 - ModernRcon v0.3
    Added:
    	- Server list for browsing previously saved servers.
    	- Message rotation saving / loading for easy management of message schedules.
    	- Encryption algorithm for Rcon passwords (ground works for future releases).
    	- Warning prompts + error messages.
    	
    Fixes:
    	- Server hanging when connecting without entering a password.
    	- Server hanging when poor UDP responses are received.
    	- Map preview image not updating when using keyboard to navigate list.
    	
    Code Count: 3,122 lines of Java code
    

11/18/07 - ModernRcon v0.2
    Added:
        - Gametypes tab for modifying gametype settings.
        - Map Rotation tab for viewing / modifying rotation settings.
        - Messages tab for sending + scheduling server messages.
        - Maps tab - Added a preview to the to-be-loaded map.
        - Maps tab - Added the ability to specify a gametype to load.
        - Players tab - Added a button for sending private messages.
        
    Fixes:
        - Fixed the header, a bug where with long server names all the text got jumbled.
        - Fixed a crash when server stopped responding, handled with a dialog box.
        - Modified the Console tab giving the ability to clear the console.
        - Added confirm dialogs on powerful functions like Ban Player and Kick All.
        
    Code Count: 2,450 lines of Java code
        

11/11/07 - ModernRcon v0.1
    * View server information (gametype, map, name, players, etc).
    * Kick, Ban, TempBan, and monitor players.
    * Restart Map, FastRestart Map, Load next map.
    * Load a selected map from a list of maps.
    * Manually enter commands into the console and read responses. 
    
    Code Count: 988 lines of Java code
    
 
Please visit www.CoDHQ.com for all your Call of Duty 4 needs!
