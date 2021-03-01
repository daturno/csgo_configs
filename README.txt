# csgo_configs
READ ME by Daturno
Version 1.3
Date: Mar 1 2021

Contents
1. System Requirements
2. Deployment/Uninstalling
2.1. Deployment Instructions
2.2. Uninstalling
2.2.1. Deleting Daturno's Configs
2.2.2. Resetting Binds
2.2.3. Resetting Crosshair
2.2.4. [Optional] Restoring Backup "autoexec.cfg"
2.2.5. [Optional] Restoring Backup "config.cfg"
2.2.6. [Optional] Restoring Backup Crosshair Settings
3. Verifying CFGs Loaded
4. Notes on Deployment and CFGs
4.1. Notes on "Deployment Instructions"
4.2. Notes on "daturno_autoexec.cfg"
4.3. Notes on "daturno_config.cfg"
4.3.1. UBA
4.3.2. Q-Switch
4.3.3. Q-Drop
4.4. Notes on "daturno_ch.cfg"
5. Video and Audio Settings
5.1. Motion Blur OFF
5.2. Check Audio Device
5.3. Check Enable Voice
6. Changing In-Game Overlay Shortcut
7. Daturno's Steam Friend Code

-----------------------------------------------------------------------------------------------------------

1. System Requirements
- 6-core processor
- NVIDIA graphics
- NVIDIA GeForce Experience installed
- 60Hz monitor (5ms)
- 240Mbps download connection
- 90Mbps upload connection
- 5 button mouse with scroll wheel
- DPI @ 3200

-----------------------------------------------------------------------------------------------------------

2. Deployment/Uninstalling
Before deployment make sure to have a backup of your "autoexec.cfg", "config.cfg", current "launch options" and crosshair settings. Do not have backup files in your CS:GO CFG folder; change the directory of your current configs.
Note: you should save your current crosshair settings in ".cfg" format.

2.1. Deployment Instructions
Step 1. Save "daturno_autoexec.cfg", "daturno_ch.cfg" and "daturno_config.cfg" to your CS:GO CFG folder
Step 2. Go to Steam >> Library >> CS:GO >> Properties... >> General Tab
Step 3. Paste line below under "LAUNCH OPTIONS":

-novid -tickrate 64 -refresh 60 -freq 60 -nod3d9ex +exec daturno_autoexec

2.2. Uninstalling
In order to uninstall configs you have to delete Daturno's configs and reset/overwrite binds and crosshair.

2.2.1. Deleting Daturno's Configs
Step 1. Go to Steam >> Library >> CS:GO >> Properties... >> General Tab
Step 2. Delete or overwrite launch options. Make sure to delete or overwrite "+exec daturno_autoexec"
Step 3. Go to your CS:GO CFG folder and delete "daturno_autoexec.cfg", "daturno_ch.cfg" and "daturno.cfg"

2.2.2. Resetting Binds
Step 1. Open CS:GO 
Step 2. Settings Menu >> Keyboard / Mouse >> RESET

2.2.3. Resetting Crosshair
Step 1. Open CS:GO 
Step 2. Settings Menu >> Game >> Crosshair
Step 3. Select "Reset" (beside "Undo Changes")

2.2.4. [Optional] Restoring Backup "autoexec.cfg"
Step 1. Save your backup "autoexec.cfg" in your CS:GO CFG folder
Step 2. Go to Steam >> Library >> CS:GO >> Properties... >> General Tab
Step 3. Paste your original launch options and include "+exec autoexec"
Step 4. Press <Enter> for changes to take effect

2.2.5. [Optional] Restoring Backup "config.cfg"
Step 1. Save your backup "config.cfg" in your CS:GO CFG folder
Step 2. Open CS:GO
Step 3. Toggle console and write "exec config"
Step 4. Press <Enter> for changes to take effect

2.2.6. [Optional] Restoring Backup Crosshair Settings
These steps will only work if you have a backup of your crosshair in ".cfg" format.
Step 1. Save your backup "<crosshair-file-name>.cfg" in your CS:GO CFG folder
Step 2. Open CS:GO
Step 3. Toggle console and write "exec <crosshair-file-name>"
Step 4. Press <Enter> for changes to take effect

-----------------------------------------------------------------------------------------------------------

3. Verifying CFGs Loaded
Step 1. Open CS:GO
Step 2. Toggle console and verify the following messages:

Loading daturno_autoexec.cfg... 
Loading daturno_ch.cfg... 
daturno_ch.cfg Loaded! 
Loading daturno_config.cfg... 
daturno_config.cfg Loaded! 
daturno_autoexec.cfg Loaded! 

-----------------------------------------------------------------------------------------------------------

4. Notes on Deployment and CFGs
This section deals with what is embedded on the files.

4.1. Notes on "Deployment Instructions"
Removes CS:GO start video
Optimizes display frequency
Loads "daturno_autoexec.cfg"

4.2. Notes on "daturno_autoexec.cfg"
Removes FPS ceiling
Optimizes client interpolation settings
Optimizes client packets for tailored connection
Optimizes threads synchronization
Loads "daturno_ch.cfg"
Loads "daturno_config.cfg"

4.3. Notes on "daturno_config.cfg"
Sets eDPI @ 1152
Binds mouse and keyboard
Binds microphone to mouse "forward" button
Binds "player_ping" to mouse "backward" button
Features "Radio Binds Z, X, C, V."
Features "Utilities Bind Aliases [UBA]"
Features "Quickswitch [Q-Switch]"
Features "C4 Quickdrop [Q-Drop]"

4.3.1. UBA
Utilities are selected by scroll wheel directions. Up selects "damage" utilities (High Explosive, Incendiary and Molotov). Down selects "tactical" utilities (Flashbang, Smoke and Decoy). The aliases change the scroll wheel binds so you may need to activate more than once to select desired utility.

4.3.2. Q-Switch
Main usage is to unscope sniper. Switches between knife and primary weapon (if no primary then secondary). Applied on "MOUSE3" button (scroll wheel click). Able to "knife-run" by holding scroll wheel click.

4.3.3. Q-Drop
This feature is for when you spawn with the C4 and want to rush to bombsite without compromising the C4. Press "q" to drop C4 and switch to knife. Hold "q" to switch to C4 and release key to drop C4 then switch to knife.

4.4. Notes on "daturno_ch.cfg"
Features a static red "+" crosshair

-----------------------------------------------------------------------------------------------------------

5. Video and Audio Settings
Optimize video settings for your NVIDIA graphics card using NVIDIA GeForce Experience.
Step 1. Open NVIDIA GeForce Experience
Step 2. Hover mouse over CS:GO and click on "DETAILS"
Step 3. Click on the wrench icon ("Custom Settings") beside REVERT
Step 4. Optimize slider
Note: Performance increases FPS and Quality increases details. 

5.1. Motion Blur OFF
Step 1. Open CS:GO
Step 2. Settings Menu >> Video >> Advanced Video >> Motion Blur >> DISABLED

5.2. Check Audio Device
Step 1. Open CS:GO
Step 2. Settings Menu >> Audio >> Audio >> Audio Device >> [Select]

5.3. Check Enable Voice
Step 1. Open CS:GO
Step 2. Settings Menu >> Audio >> Audio >> Enable Voice >> PRESS TO USE MIC

-----------------------------------------------------------------------------------------------------------

6. Changing In-Game Overlay Shortcut
Step 1. Steam >> Steam >> Settings >> In-Game Tab
Step 2. Click under "Overlay shortcut keys"
Step 3. Press the key(s) that you would like to toggle overlay
Note: "Shift+Ctrl+Tab" works for me

-----------------------------------------------------------------------------------------------------------

7. Daturno's Steam Friend Code
1030594037
