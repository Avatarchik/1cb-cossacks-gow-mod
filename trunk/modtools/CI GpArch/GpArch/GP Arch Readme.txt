Cossacks I - American Conquest Gp Arch
--------------------------------------

The whole GpArch folder must be installed in the root of your C: drive !!!


For viewing, extracting Cossacks I files, change the 0 & 1 folder with the one's contained in the subfolder ' For Cossacks'.
For viewing , extracting American Conquest files, change the 0 & 1 folder with the one's contained in the subfolder ' for AC'.

Use GpViewer for viewing & extracting .gp file's
Use MegaPack to create new .gp file's

Additional tools are GSC Unpack which is a dos programm , but does the same thing as the newer GSC Utility and GSCArch with is a dos programm that allows you to pack gsc files, but does the same thing as the newer GSC Utility.






Original Readme:
==========================================================
!!!Mod tool must be installed in the root of drive C:\ !!! 
==========================================================
1. All animation files are in *.gp format. 
2. To create *.gp files make use of the *.bmp and *.lst files you have previously prepared. They must be stored in the same folder! See example folder!
3. Use MegaPack.exe utility to transform *.bmp and *.lst files into *.gp format. Firstly, you "Add List of BMP's" and indicate the path to *.lst file
4. In the "Convertion properties":
a) Image type and packing - use Simple packing image to pack *.bmp files
b) Packing quality - select (3) for walking animations, (1) for other (attack, death, shot, etc.)
c) Scaling - unit must have 48 pixels for American Conquest and 45 for Cossacks. This option is used to obtain the best possible quality of anti-aliasing.
d) GP-file name - output file.
   Tick "Anti-aliasing" to switch on anti-aliasing. We do not reccomend it for death and walking animations.
5. Output directory. By defalut it is C:\GParch\gp\. You can change it to whatever you want.
6. Use Palette 0 for AC and Palette 1 for Cossacks.
7. Save your project by pressing "Save project". 
8. Press "Convert All" or "Convert selected" to convert *.bmp into *.gp
9. To view *.gp file type in the command line "C:\GpArch\GPView.exe" where "C:\GpArch\gp\myproject.gp" is a path to your *.gp file



================================================
!!!gscunpack.exe utility unpacks ALL.gsc file!!!
================================================
This utility must be stored in a separate folder.
It is also recommended to store ALL.gsc file in the same folder.
Type in the command line "c:\!yourfolder!\gscunpack.exe c:\!yourfolder!\all.gsc" to unpack all.gsc



============================================================
!!!GSCarch.exe utility packs up the modified ALL.gsc file!!!
============================================================
You have to modify do_mod.bat file which must be stored in the same folder as GSCArch.exe file
do_mod.bat file has the following structure: 
GSCarch !where_to_create_file "mods01.gs1" or "mods.gs1"! !what_to_archive! and then you have to add this string
" -.gp +.grd +.pal +.xlt +.set +.dat +.lst +.rsr +.bpx +.rlc +.dat +.bmp +.msk +.gpi +.set +.msp +.smp +.sty +.pix +.ads +.cd +.nds +.txt +.md +.lnk +.terr +.cml"
For example, GSCarch C:\AMERICANCONQUEST_RC_1_10pack\Mods.GS1 C:\AMERICANCONQUEST_RC_1_10pack\_BAT\MODS\ -.gp +.grd +.pal +.xlt +.set +.dat +.lst +.rsr +.bpx +.rlc +.dat +.bmp +.msk +.gpi +.set +.msp +.smp +.sty +.pix +.ads +.cd +.nds +.txt +.md +.lnk +.terr +.cml


Make use of GSCarch.exe to archive all large files that were changed (all files but *.md and *.nds and *.lst *.ads *.txt *.rsr *.dat)
For example, GSCArch C:\AMERICANCONQUEST_RC_1_10pack\Mods.GS1 C:\AMERICANCONQUEST_RC_1_10pack\_BAT\MODS\ -.gp +.grd +.pal +.xlt +.set +.bpx +.rlc +.bmp +.msk +.gpi +.set +.msp +.smp +.sty +.pix +.cd +.lnk +.terr +.cml
into file mods.gs1
and all *.md and *.nds and *.lst *.ads *.txt *.rsr *.dat into mods01.gs1


Make sure you understand the structure of the files *.md and *.nds!
*.md file contains all the unit info. There is no unit without this file (sort of)! It links the *.gp file to the unit, parameters (attack, defence, etc.) and particularities. 
*.nds file links a unit to a nation.
nations.lst file contains the list of the nations.

If you add new nation you will also have to add it into AI.dat file
File mdlist.txt contains the names of the units.
nmlist.lst file contains the list of *.md files that are used.

To add new unit you have to indicate it in mdlist.txt, nmlist.lst, and *.nds


It is recommended you:
1. Copy ALL.gsc file into a new folder;
2. Unpack it;
3. Delete ALL.gsc and gscunpack.exe from that folder;
4. Copy all these two files into another new folder;
5. Modify the files from the second folder;
6. Compare two folders and copy all new files into another new folder;
7. Archive the files from the third folder with GSCarch.exe into mods.gs1 and mods01.gs1 files;
8. Do not delete ALL.gsc file from your game! Copy mods.gs1 and mods01.gs1 files into the root folder of the game;
9. Start the game. 


Good luck and may the force be with you!:)))