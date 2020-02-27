# deceit-N3K0.cc
cryengine is amzing engine

if hack did not work copy dlls in deceit-N3K0.cc-master/x64/fixed  then paste them to YourGamefolder/bin/win_x64 folder
good luck

# how to use (i guess)
https://imgur.com/a/rZPskbm <br>
fixes file (i can't directly upload to github due to unknowcheat-rules) <br>
FW1FontWrapper.dll https://github.com/gamelaster/FW1FontWrapper <br>
MinHook.dll https://github.com/TsudaKageyu/minhook <br>
# keybind
V + ALT -> teleport you to closet player (depent on sort mode) <br>
numpad 7 -> change player sort mode to the closet player <br>
numpad 8 -> change player sort mode to the closet crosshair <br>
delete -> unload module <br>
<br>
# ps
infinity ammo , esp and rapifire is enable by default (you can't disable it in game) <br>

# offsets
* pGameFramework
  * offset : 0x1B468D0
  * pattern : 48 8B 0D ? ? ? ? 48 8B 01 FF 90 ? ? ? ? 48 8B 54 24 ? 4C 8D 0D ? ? ? ? + 1
* pEntitySystem
  * offset : 0x1B468E0
  * pattern : 48 8B 0D ? ? ? ? 48 8B 01 8B 93 ? ? ? ?  + 1
* pRender
  * offset : 0x1B46930
  * pattern : 48 83 3D ? ? ? ? ? 0F 84 ? ? ? ? 48 89 B4 24 ? ? ? ?  + 1
* pPhysicalWorld
  * offset : 0x1B46870
  * pattern : 48 8B 3D ? ? ? ? 48 8D 4C 24 ? 33 D2  + 1
* pConsole
  * offset : 0x1B468E8
  * pattern : 48 8B 1D ? ? ? ? 48 8D 15 ? ? ? ? 48 8B F9  + 1
* pLog
  * offset : 0x1B468F8
  * pattern : E8 ? ? ? ? 83 7B 10 0D  + 1
