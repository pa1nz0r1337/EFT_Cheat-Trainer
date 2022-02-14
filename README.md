# EFT_Cheat-Trainer
Cheat trainer with love pasting &lt; 3

Screenshots  0-0

Wallhack
![138436846-9736fc13-ff23-43a3-853a-7ba3050999ed](https://user-images.githubusercontent.com/46020154/153920888-77689c9a-616b-40d0-be8d-f214a9a84577.png)
Wallhack
![138731215-d3ec58a6-38c5-49e4-9920-090c98fa79ef](https://user-images.githubusercontent.com/46020154/153921052-8efc089c-def4-4de0-9c02-89e90fc34a9f.png)
Wallhack loot
![135587083-938a3d9b-2082-4231-9fa8-e7807ad4a3d1](https://user-images.githubusercontent.com/46020154/153921128-c1864039-bb96-46e9-bf17-50480225fb71.png)
items
![135586489-c4214794-21c9-4493-9699-dcca6c3dd00e](https://user-images.githubusercontent.com/46020154/153921240-0d2a8fc5-de0b-46bd-aacc-b7708900c034.png)
Menu
![149630873-bf921e51-fb02-4249-bc7e-ddf2e8877fa0](https://user-images.githubusercontent.com/46020154/153921298-138c270b-786f-44a8-ae31-1e6ba5457497.png)

installation:
You can try to compile the code yourself (you will need a recent Visual Studio, because we are using CSharp 9). You can use a precompiled release as well.

Copy all files in your EFT directory like C:\Battlestate Games\EFT:

EscapeFromTarkov_Data\Managed\NLog.EFT.Trainer.dll (this is the compiled code for the trainer)
EscapeFromTarkov_Data\outline (this is the dedicated shader we use to outline players [wallhack])
If you are using the Live version (you should NOT do that, you'll be detected and banned):
Rename EscapeFromTarkov_Data\Managed\NLog.dll.nlog-live to NLog.dll.nlog

If you are using sptarkov (https://www.sp-tarkov.com):
Overwrite the existing EscapeFromTarkov_Data\Managed\NLog.dll.nlog using NLog.dll.nlog-sptarkov, or update the existing file accordingly. We must include the following <target name="EFTTarget" xsi:type="EFTTarget" /> in the targets section for the trainer to be loaded properly.

Sample trainer.ini configuration file
Please note that there is no need to create this file by yourself. If you want to customize settings, use save, edit what you want then use load. This file is located in %USERPROFILE%\Documents\Escape from Tarkov\trainer.ini.

[trainer.ini.txt](https://github.com/pa1nz0r1337/EFT_Cheat-Trainer/files/8063019/trainer.ini.txt)
