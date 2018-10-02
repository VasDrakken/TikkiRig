# TikkiRig
Mel based Rig system for automating rig and painting weights

I was at full sail university taking a class on rigging when the question of automaticing the process came up in class. 
The teacher said that he used to work for idustrial light and magic and wanted to learn coding to duplicate the system
they had but did not understand the code. So he got permission to create the class but told me if I wanted to take the class I
would have to fail the one I was in. I laughed and accidently submited the wrong file at the end of the class.
So I eneded up the scripted rig class. The teacher had six lab assistants writing code and most of it did not work at all because
they did not understand how to use functions and had varibles undeclared and it was a mess. I used the psudo code to rewrite
it and it tooks hundreds of hours, I did do much beside write and rewrite the code breaking functions of the inline coding and
storing them and external functions and limiting the overhead and cross talk between varibles.
The painting weights function was beyond the scope of the class, and it took until this version to get the gui and all the extra
bits working. It is written in mel on maya 2008, which was the current version when the class was created. Everyone ended up
passing the class as it was too advanced for what they taught before the class. Hopefully with the teacchers being replaced with
professors they have much better program but the long and short the rig that is being released under the MIT license should
work in 2018, but if it does not hopefully I can get autodesk to find the dependecies that changed and re-write that part of the
code.

The gui is loaded with BS_setupRigGui.mel and the rest of the scripts have to be in the documents folder were maya loads them at
run time. The default path is ..\Documents\maya\2018\scripts

