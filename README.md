Exile Territory Codes
=====
Exile Territory Codes allows for Moderators of territories to be able to unlock abstract constructions (doors/gates etc) without having to enter a code each time. 

Installing 
---
Simply place the included files into your existing overwrites folder. Hop into config.cpp, scroll to class ExileCustomCode, and add in these lines of code (Dont forget to change the path of the file if it is different for you!):
	ExileClient_object_lock_toggle = "overwrites\ExileClient_object_lock_toggle.sqf";
	ExileServer_object_lock_network_lockToggle = "overwrites\ExileServer_object_lock_network_lockToggle.sqf";
