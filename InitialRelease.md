# Introduction #

Just did the initial release and we just rushed this out so we could use it.

It's fully functional but there are some things that could be improved.

We used it AS-IS to import 500 Mantis tickets+ into our FogBugz installation.

# Running It #

[Download](http://code.google.com/p/mantibugz/downloads/list) the zip file from the Downloads area and unzip it to a folder.

You should be able to execute the mantibugz.jar file inside the lib folder simply by clicking on it in most operating systems or you could try modifying and executing the run.sh file for your installation (i.e. rename it it to run.bat on Windows).

The screen should be fairly self explanatory, click go after you've connected to both sides of your transaction.

MAKE SURE TO PICK SOURCE AND DESTINATION PROJECTS ACCORDINGLY.

The issues listed in the bottom half of the screen are for preview or verification purposes only (i.e. no selection supported).

# Known Issues #

Source code has some IntelliJ idiosyncrasies (need to convert .form files to pure Java Swing (JFormDesigner can do this I think), will update code ASAP.

No validation (i.e. for valid connections) when initiating import.

Does not translate areas/categories, users, priorities, or versions on import, these get defaulted by FogBugz.

Does not import attachments.