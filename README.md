PS3 Voice and Graphics Patch
-----------------------------------------------------------------------------------------
For Higurashi No Naku Koro Ni - Chapter 1 Onikakushi, Steam Version

This patch aims to combine the efforts of the ps3 voice patch and the ps3 sprites/background patch,
and fill in missing voice files not covered by the original voice patch.

Releases
-----------------------------------------------------------------------------------------
https://github.com/higurashi-mod/scripts/releases/

Installation:
-----------------------------------------------------------------------------------------

Install both folders into streamingassets folder.
If prompted to overwrite current files, overwrite them.
You backed up your files, right?

Grab HigurashiPS3-Voices01.zip: https://mega.co.nz/#F!SRt1DTKI!0vSWMtBLaa2VO0bDgfzb7A

Place s01, s19, s20 folders into streamingassets/SE folder

For the Graphics patch, pick your pack of choice from here: https://www.mediafire.com/folder/xq4ncmss3yiwr/Higurashi_Steam_Modding

Troubleshooting:
-----------------------------------------------------------------------------------------
- "There's a missing voice in this scene!"

Check the Known Issues section of this readme.
If it's not in there, report it. 

- "Why aren't the voices playing?"

Make sure the FULL voice pack is installed.
Make sure your directory is as follows:

..SteamApps\common\Higurashi When They Cry\HigurashiEp01_Data\StreamingAssets\SE\

..SteamApps\common\Higurashi When They Cry\HigurashiEp01_Data\StreamingAssets\Update

- "It's still not playing/I'm not getting the afternoon/night backgrounds."

Go to ..common\Higurashi When They Cry\HigurashiEp01_Data\StreamingAssets\CompiledScripts

Make a copy of the Complied Scripts folder.
Delete onik_000.mg -> onik_15_03.mg and onik_op.mg
This will force the game to read the new files.

If this stops the game from working properly, go to
..common\Higurashi When They Cry\HigurashiEp01_Data\
And open output_log.txt ; This will tell you which script txt file has the syntax error.

Known Issues:
-----------------------------------------------------------------------------------------
- Generic -
*Sometimes the lines don't last long enough for a voice file to play fully. 
This is most evident when auto is left on.
*BGM is too loud / BGM volume mutes BGM and Voices
Unavoidable, since the voices aren't their own thing
*More than one sound effect cannot be played at the same time.
So if a voice and sound effect is supposed to play at the same time, only one of them will play.
This is why combine.ogg was made (originally 5 voices were supposed to play at the same time).

- Chapter 1 - 
Voices not properly aligned during the talk about Keichii's dick scene. 
There are too many voice files for Keichii for this scene, 
probably the scene is extended in the ps3 version.
Since I don't know japanese, I can't tell which voices are actually used.

- Chapter 2 - 
Missing Voice for Satako during the picnic scene,
when she says ""Aaah! The last meatbaaaaaaaaall!!!"
Following the numbers of her voice files, 
it should be 990400040.ogg but this seems to be missing.

- Chapter 4 - 
Sound effects in the zombie scene stop some voices from playing.

Changelog:
-----------------------------------------------------------------------------------------
v. 0.0
Test patch of prologue and chapter 1

v. 0.1
Chapter 1 finished
Combined all edits of ps3 graphics patch and voice patch

v. 0.2
Chapter 2 finished
Fixed folder structure of patch archive
Added in Extras folder with watermark-less window

v 0.3
Chapter 3 finished
Fixed an error in Mion's dialogue in which PlaySE showed up
Changed bg_045 to bg_044 in scene when Keichii mentions Tomitake while he walks to the dump site

v 0.4
Chapter 4 finished
Fixed Satako's voice during the Old Bachelor Scene in Chapter 3

Credits:
-----------------------------------------------------------------------------------------
- TheGuraGuraMan - For making the Sprite/BGM Patch.

- Anon - For providing the PS3 voices and patch.

- Another Anon - For providing the watermark-less window.
