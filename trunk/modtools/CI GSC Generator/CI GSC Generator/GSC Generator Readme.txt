GSC Generator

-------------------

This is the old version of GSC Generator which is used in combination with GSC Viewer.
A newer version is available wich combines both these tools in one : GSC Utility


----------------------------------------------------------------------------------------------------------

Original Readme:

------------------

This tool was designed to help all those would-be modders out there, for the great game Cossacks : Back to War. 

Requirements:
VB6 Runtime Library (you may have this installed on your system already, if not it can be downloaded from Microsoft Web Site)
Windows (tested on Win ME, Win NT and Win XP but should work also on Win 95 + 98)
More than 64MB system memory
Due to inherent limitation, you must have MODS01 (by Baddog + Stefan) and ofcourse Back to War installed on your system first. 

I will try to explain this:

Cossacks game engine looks for files of .GSC and .GS1 types on starting up. In the original game, there are ALL.GSC and PATCH02.GS1 files.
It is highly NOT advisable that you modify/change these files as the game WILL crash. These files are like archive files, containing numerous other
files such as the graphic and text files. They are needed to load the games. These smaller files, within the archives, are unfortunately encrypted/compressed. 
The algorithm unfortunately is currently not known. (You can extract these files using the GSC file viewer, by Roy Luo, available for download at
cossacks.heavengames.com but you will not be able to readily read them as they will be in binary).

With the release of MODS01, two more GS1 files were added. They are MODS01.GS1 and MODS.GS1. The small files contained within these 2 are not 
encrypted. They can be extracted (text files with unit and nation parameters are in mods01.gs1, and graphic files are in mods.gs1), and the text files are
readily modifiable to change unit/nation parameters. Another source for modifiable text files would be the downloadable demos from GSC. After you have
done your modifications, this tool will come in handy. You use it to combine the little files to make a new MODS01.GS1 files. It is recommended that you
extract the original files from the original MODS01.GS1 file (using the above mentioned GSC file viewer) and include them in the new MODS01.GS1 to 
retain the units made by Baddog and Stefan.

Another important thing to note is that you can not just add any files into a MODS01.GS1 file. As I mention before, Cossacks game engine looks into the
.GSC and .GS1 files on loading up. The smaller files contained within these are all tagged with what I believe to be unique identification number for each
files. Therefore you cannot just make a file with a new name and chuck it into these .GSC and .GS1 files. You have to use files that are already there .
You can only modify them and then recombine them using GSC File Generator tool. When Stefan and Baddog made the mods, the excutable had to be
modify to accomodate the new files that they created. This is way beyond the scope of GSC File Generator. What this means is that you can not add
new units or nation at this stage, just modify or replace the existing ones.

How to use the tool:

Quite simple actually -

Extract the content of the ZIP file. Start up GSC File Generator by double-clicking on file called GSC_Gen.exe.

Just select a whole bunch of files that you have modified and drag/drop them into the empty box of the tool. You can delete individual files from the box by
double-clicking in it. The button called Generate will then become active.
Click and wait (depending on how many files you put in), until you get the message File generation completed. You will find a file in the same directory as 
GSC_Gen.exe called MODS01.GS1. You then copy this file to your Cossacks : Back to War directory and voila, you can play the game with the stats that 
you wanted. It is recommended that you back up the original MODS01.GS1 by renaming it to MODS01.BAK or something like that.

Just a few things you should note:

1. This tool will crash if you drop a folder into it. Only drop files into the empty box.
2. If you have included files that are not supported by the Cossacks game engine, you will get a message telling you so. The created MODS01.GS1 file will be unusable.
3. Be careful of duplicate files (adding files of same name) as this has unpredictable results.
4. Files that are meant to be in a folder within Cossacks directory eg: ..\text\mods_text.txt should be named text+mod_txt.text before dropping into the GSC File
Generator box (as it will not accept a folder).
5. The included tool called File Renamer is useful for just this purpose - you can put a whole bunch of files (eg. ai.txt, mod_text.txt) into the box. In the text box below, you can type in
eg: text+ and it will rename all of the files in the box to text+ai.txt, text+mod_text.txt

Thanks to GSC for a great game, CDV for distributing this great game, Stefan + Baddog for a great mods, Roy Luo for GSC Viewer, all those at 
www.planet-source-code.com for code snipets, and anyone else who deserves credit.

Give it a swirl and let me know of any troubles.
I hope to see a few new mods soon!.
I can be contacted at ckphan@bigpond.com

