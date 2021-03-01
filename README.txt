# csgo_configs
READ ME by Daturno
Version 1.1
Date: Feb 28 2021

Contents
1. System Requirements
2. Deployment Instructions
3. Verifying CFGs loaded
4. Notes on Deployment and CFGs
4.1. Notes on "Deployment Instructions"
4.2. Notes on "daturno_autoexec.cfg"
4.3. Notes on "daturno_config.cfg"
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
- 5 button mouse with mousewheel
- DPI @ 3200

-----------------------------------------------------------------------------------------------------------

2. Deployment Instructions
Step 1. Save "daturno_autoexec.cfg", "daturno_ch.cfg" and "daturno_config.cfg" to your CS:GO CFG folder
Step 2. Go to Steam >> Library >> CS:GO >> Properties... >> General Tab
Step 3. Paste line below under "LAUNCH OPTIONS":

-novid -tickrate 64 -refresh 60 -freq 60 -nod3d9ex +exec daturno_autoexec

-----------------------------------------------------------------------------------------------------------

3. Verifying CFGs loaded
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
Features "Utilities Bind Aliases [UBA]"
Features "Radio Binds Z, X, C, V."
Features "Quickswitch [Q-Switch]"

4.4. Notes on "daturno_ch.cfg"
Features a static red "+" crosshair

-----------------------------------------------------------------------------------------------------------

5. Video and Audio Settings
Optimize video settings for your NVIDIA graphics card using NVIDIA GeForce Experience
Step 1. Open NVIDIA GeForce Experience
Step 2. Hover mouse over CS:GO and click on "DETAILS"
Step 3. Click on the wrench icon ("Custom Settings") beside REVERT
Step 4. Optimize slider
Note: Performance increases FPS and Quality increases details. 

5.1. Motion Blur OFF
Step 1. Open CS:GO
Step 2. Settings >> Video >> Advanced Video >> Motion Blur >> DISABLED

5.2. Check Audio Device
Step 1. Open CS:GO
Step 2. Settings >> Audio >> Audio >> Audio Device >> [Select]

5.3. Check Enable Voice
Step 1. Open CS:GO
Step 2. Settings >> Audio >> Audio >> Enable Voice >> PRESS TO USE MIC

-----------------------------------------------------------------------------------------------------------

6. Changing In-Game Overlay Shortcut
Step 1. Steam >> Steam >> Settings >> In-Game Tab
Step 2. Click under "Overlay shortcut keys"
Step 3. Press the key(s) that you would like to toggle overlay
Note: "Shift+Ctrl+Tab" works for me

-----------------------------------------------------------------------------------------------------------

7. Daturno's Steam Friend Code
1030594037
