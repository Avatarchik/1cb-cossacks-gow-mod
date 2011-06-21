GSC Utility v1.11
------------------

-       Run the Gsc Utility. Read the included original read me below file for basic information.
If you get a missing component error : comdlg32.ocx or comctl32.ocx then you should use the Library_Components.Rar included with this tool and place them in your Windows/System32 folder. 
Next go to run ( XP) or cmd (Vista/Windows 7) and type :

regsvr32 comdlg32.ocx       (note the space)  

It should tell you that the component has been succesfully installed)

-       Select File Extractor, and tick extract as “+” if you want all the files not to appear in subfolders. This will make it easier to put the files back

-       Alternate decrypting algorithm: default. 

-       Select Open File and select your all.gsc file from your cossacks directory. Files will appear in the list. 

-       Press Select all. (or select only a few files if you know what you are looking for).

-       Press Extract. This might take some time as there are many files to extract depending on the game version




------------------


Original Readme

------------------

GSC Utility v1.0
This tool is designed to extract files contained within GSC files of the 
game Cossacks for editing, and then recombine them together to make
another GSC format file. This can be used to alter various unit and 
nation statistics as you see fit.

Requirements:
Windows (tested on WinNT4, Win98SE, WinME and WinXP)
More than 64MB of system memory with a fast CPU
VB6 Run-Time Library (this can be downloaded at 
http://download.microsoft.com/download/vba6/Utility/1/WIN98/EN-US/vbrun60sp3.EXE)

How to use:
This tool has two main modes, file extraction and file generation.
File generation mode is only available if you have the game Cossacks: EW
installed on your machine. 

FILE EXTRACTION MODE:
This is used to look into files like All.gsc and patch01.gs1/patch02.gs1
files in Cossacks installation directory, and extract the files within.
Use the FILE menu at the top to open a particular GSC file. Once opened,
a list will be presented in the big box below with all the files contained
in the GSC file. The ones with "*" are encrypted files. Choose some of them 
and click the EXTRACT button. The files will be extracted to the default 
folder called "extracted", or you can name another folder by typing into 
the text box "Extract to folder:"

Double clicking on the file name will give you information about the file
size in the status bar.

The DECRYPT option (recommended), chosen by default, will decrypt the file to its 
original format before the file is extracted. This however may take a bit of 
time, especially with larger files like picture files.

The EXTRACT AS "+" option, when chosen, will extract the file as FOLDER+FILENAME
rather than a file within a folder. This will make it easier when you re-add the
file for GSC file generation (see below in FILE GENERATION MODE, to make more
sense of this).

A lot of these files are text files, and can be manually edited using notepad
or wordpad. For example, TKP.MD is the control file for the Winged Hussar. Extracting
this, you can then open it to edit unit parameters such as strength, armor,
attacks, etc.. AUSTRIA.NDS is the control file for Austrian nation.

.MD = unit parameters
.NDS = nation parameters

How do you put all these files back in the game to make it work?. See below...

FILE GENERATION MODE:
This is not available unless you have the game Cossacks installed already on your 
machine. This is used to recombine all the files that you have extracted and edited
into a "usable" file by Cossacks game engine. If you have only Cossacks:EW,
the file you should make is PATCH01.GS1. If you have AoW, you should make 
PATCH02.GS1. If you have MODS1, you should make MODS01.GS1 file.

Depending on which version of Cossacks you have installed, the different options
are available on the combo box on the top right hand side of the GSC Utility. Choosing
the appropriate mode will allow you to make a suitable .GS1 file for that game. This
is because each of the files within the GSC file seems to be tagged with a unique ID number. 
As such, if you add a file that has not already existed in that game (eg. adding file
BAVARIA.NDS to Cossacks:EW) will give you a warning and no file will be generated.

To add the files to combine for .GS1 file generation, you simply drag and drop them into the
box. To remove files, double click on the filename in the box. Note that you must NOT
drop a folder into the box. This will cause the utility to crash. This is a known bug.

Please note that if a file you want to add is nested within a folder inside the Cossacks
installation directory, you must change the name of that file to FOLDER+FILENAME format.
Eg. AGEW_1.PAL file is nested within a folder called 0. You should name this file
0+AGEW_1.PAL before adding it to the box. This can easily be done if you have extracted
the file with the EXTRACT AS "+" option chosen.

Also, if you were to make patch01.gs1 or patch02.gs1 files, it is highly advisable that
you rename the original file to something like patch01.bak. It is also important that
you extract the files within these files first and recombine them later with your edited
files.

-----------------------------------------------------------------------------------------------------------------------------------

What's new in version 1.03

1. Added option for naming your path name to Cossacks installtion directory. This is only
   needed if your Cossacks installation was not detected by the utility. You can check if
   it finds your installation by switching to File generator mode and using the top box on the
   right hand corner to see the options available.
2. Added decryption scheme for those who finds their version of Cossacks did not extract
  and decrypt properly.

----------------------------------------------------------------------------------------------------------------------------------

Version 1.10

This version has support for all files and does not require any installation of Cossacks on user's
computer for the generator to work.

---------------------------------------------------------------------------------------------------------------------------------

Version 1.11

This is a minor update to include added functionality including a Select All button (for the 
extractor module) and Find/Find next menu (under Edit) for easier navigation through larger files
(eg. ALL.GSC). Removal of GAME MODE choice as this option is no longer needed.

----------------------------------------------------------------------------------------------------------------------------------

Give it a spin.

Let me know of any queries or questions at ckphan@bigpond.com
Visit me at http://members.optusnet.com.au/~congthuyphan