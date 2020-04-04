# AlyxCheats
Cheat configuration file for Half-Life: Alyx

This config file eases the experience of Half-Life: Alyx. Please be aware that this will ruin the excellent game balancing Valve has provided and make it far too easy. This is only for the run and gun experience.



This cfg file has the following features:

God Mode
Infinite Ammo
One Hit Kill
Increased rate of fire
Makes the puzzles easy and shows the solution
increases the multitool scan range to save on bending and stretching.

Bindable cheat keys, bound to the Joypad buttons are as below but these can be edited in the CFG file:

JOY1	Spawns a Grenade (only use on later levels or an ERROR is spawned)

JOY2	Look in a direction and press a button and this will create a sound object that Jeff will follow, only use this on the Jeff level as an error is produced on any other level.

JOY3	Notarget – Makes you invisible to most enemies (Except Jeff, he’s a scamp!)

JOY4	Gives all weapons

JOY5	Upgrades all weapons to max. 



Features especially for Jeff who scares the bejesus out of me:

Coughing turned off

Lower sniff time

Jeff is less aggressive

JOY2 distracts Jeff


Enabling Cheats and the Console:

Go to your Steam Library, right click Half-Life: Alyx and choose Properties.
Click Set Launch Options and paste the following line into the text box:

-console -vconsole -sv_cheats 1 -novid

Once done, click OK, and then close. This will then give you access to the console by pressing the ` key.



Temporary installation:
Find your Half-Life: Alyx Directory which should be in your steam folder:
Steam\steamapps\common\Half-Life Alyx

Navigate to the cfg folder:
Steam\steamapps\common\Half-Life Alyx\game\hlvr\cfg

extract the Jam.zip file to:
Steam\steamapps\common\Half-Life Alyx\game\hlvr\cfg

To activate the cheats on a one time only basis, when running the game, press ` on the keyboard to bring up the Console and type:

Exec Jam.cfg

This will activate the options described above.




To make this permanent, edit the skill_manifest.cfg and add this line to the bottom of the text
exec Jam.cfg, the file should look like this


exec skill.cfg

exec skill_episodic.cfg

exec skill_hlvr.cfg

exec Jam.cfg


This will enable the options permanently, to undo this, remove the exec Jam.cfg line from the bottom.

Editing the Jam.cfg file:

The options in jam.cfg are all annotated so that you can tweak/remove the setting to best suit you.

Enjoy!

