Mission Scripting Tools
=====================

Mission Scripting Tools for Digital Combat Simulator

Authors: Grimes (mrSkortch), Speed

Forum Thread: http://forums.eagle.ru/showthread.php?t=98616

Documentation
====
Can be found here: http://wiki.hoggit.us/view/Mission_Scripting_Tools_Documentation

Description
===
MIssion Scripting Tools (Mist) is a collection of Lua functions and databases that is intended to be a supplement to the standard Lua functions included in the simulator scripting engine. Mist functions and databases provide ready-made solutions to many common scripting tasks and challenges, enabling easier scripting and saving mission scripters time. The table mist.flagFuncs contains a set of Lua functions (that are similar to Slmod functions) that do not require detailed Lua knowledge to use. However, the majority of Mist does require knowledge of the Lua language, and, if you are going to utilize these components of Mist, it is necessary that you read the Simulator Scripting Engine guide on the official ED wiki

Contribution Guide
===
Contributions can be made with a standard github pull request model.  Code developed for the next release should be requested to be pulled into the "develop" branch.
Pull requests not targetted for "develop" will be denied.  For hotfixes please open a ticket describing the problem and ideally a fix and your changes will be attributed in the relevant commit message.  It's done like this because unfortunately github provides no tools to target to a new hotfix branch, and github tools are exclusively used in the administration of this repository and we wish to minimize the amount of unvetted code into master.
