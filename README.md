# apex_dma_kvm_pub 3.0
 Apex Legends QEMU/KVM hack memflow

UnknownCheats thread: https://www.unknowncheats.me/forum/apex-legends/406426-kvm-vmread-apex-esp-aimbot.html

Bone IDs reference: https://www.unknowncheats.me/wiki/Apex_Legends_Bones_and_Hitboxes

Game version (Steam): v3.0.4.31

Removed build_libmemflow.zip.

Added script install_memflow.sh to install memflow-kvm & memflow-qemu at https://github.com/albatror/memflow if you still stuck at : 
- Init with qemu connector...
- Can't create qemu connector
- Init with kvm connector...
- Can't create kvm connector
    
(DONT FORGET TO UPDATE WITH YOUR PATH IN THE SCRIPT AT # Export PATH & # Define variables)

Working on Windows 10 20H1 (only)
1920/1080 (need to be changed manually)(default)
2560/1440 (default)

VISUALS :
 - ESP Box, XP Level, Line, Name, Distance
 - ESP Seer Health and Shield
 - Circle FOV
 - Players Glow (GREEN when visible, RED when not visible and YELLOW when knocked - Can be changed in the menu of the overlay)
 - Items Glow (complete disable)
 - Spectators count + Name List

FEATURES :
 - New function to read localPlayer with OFFSET_LOCAL_ENTITY_HANDLE //[Miscellaneous].LocalEntityHandle (seem more easy for new updates)
 - Press F1 (To Activate GloW, ESP Seer Health/Shield and Aimbot based on default conf)
 - Dynamic FOV/AIM/SMOOTH [70m by default] Process Updated & Optimized - Settings added in overlay
 - AutoSuperGlide (nothing to do, it do for you :) )
 - AutoWallJump updated (Slide then jump on a wall, dont touch anything else and it'll auto-walljump)
 - 1V1 (F9)

!!! WARNING !!!

 - If using Client.exe and Overlay.exe - obfuscate both files to avoid detection.
 - If using Client.exe and Overlay from NVIDIA - obfuscate both files to avoid detection.

 - You need to manually change the path on the client side at apex_guest/Client/Client/main.cpp - Change USERS to yours.
 -> #include "C:\Users\USERS\Documents\me\OKVM\apex_guest\Client\Client\imgui\imgui.h"

<img src="https://github.com/albatror/adkv/blob/master/demo/settingsS.png" style="display: block; margin: auto;" />
<img src="https://github.com/albatror/adkv/blob/master/demo/settingsS2.png" style="display: block; margin: auto;" />
<img src="https://github.com/albatror/adkv/blob/master/demo/Demo2.png" style="display: block; margin: auto;" />
<img src="https://github.com/albatror/adkv/blob/master/demo/settingsN2.png" style="display: block; margin: auto;" />
<img src="https://github.com/albatror/adkv/blob/master/demo/Demo4.png" style="display: block; margin: auto;" />
<img src="https://github.com/albatror/adkv/blob/master/demo/ingame1.png" style="display: block; margin: auto;" />
<img src="https://github.com/albatror/adkv/blob/master/demo/ingame2.png" style="display: block; margin: auto;" />
<img src="https://github.com/albatror/adkv/blob/master/demo/connected.png" style="display: block; margin: auto;" />
