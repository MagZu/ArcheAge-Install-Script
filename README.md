# ArcheAge-Install-Script
Lutris Install script for ArcheAge in DX11 by using DXVK

For some reason the install script I made for Lutris keeps getting removed or edited to a non working version.
So figured I would add my script here. Then atleast someone can give me pointers if anything is wrong in my script.

It have been very well tested on multiple linux machines and it does work.

The magic sauce in the script is adding d3dcompiler_42.dll to the gamedir bin32 folder.
This makes the game not give a black screen on startup in DX11.
