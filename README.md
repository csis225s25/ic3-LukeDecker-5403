# In Class Problem Set 3

I used ComboBoxDemo.java a few years ago.  It used to compile cleanly.  Even though the code has not changed, it now  will not compile without throwing warnings.

Doing everything from a command prompt or Git Bash (no IDEs allowed), your mission is to debug the code and find out why it stopped compiling cleanly.  When you have figured it out,  note what you changed and why it stopped working in the README.md file.


**Changes to code**

Using nano, I added the missing identifier to JComboBox in its initialization on line 21, and its declaration on line 43. Without the String identifier, JComboBox was using its raw datatype. 

**What caused it to stop working?**

This code stopped working due to it being outdated. Compiling it on new versions of java doesn't work because in recent updates a datatype is needed to match what's being passed in. Otherwise, it uses the raw datatype.
