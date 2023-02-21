# Individual Scripts

These scripts are all standalone. 

# Incineration
A script that when someone says a specific word, changes their nickname from <x> to be 'INCINERATED <x>'. If they're already been incinerated <y> times, names them 'INCINERATEDx<y+1> <x>'. It will also react to the triggering message with a fire emoji.

## How to install
1. Create a Custom Command, and paste the contents of the Incineration file in it.
2. Set Trigger Type to Contains
3. Enter a name for the command to remind you in the future what word gets incinerated
4. In the 'Trigger' box, put in the word you want to trigger incineration. Set Case Sensitive to whatever you would prefer 
(Optional) You can use Regex instead, if you set the Trigger type to Regex and insert some valid Regex.

# BONE FLESH TEETH
A script that does Call and Response based on a combination of the three words Bone, Flesh, and Teeth.

## How to install
1. Create a Custom Command, and past the contents of the BoneFleshTeeth file into it.
2. Set the Trigger Type to Regex
3. Set the name to Bone Flesh Teeth (for your own sanity).
4. Insert the following regex as the Trigger:

^([Tt][Ee]+[Tt][Hh])*([Ff][Ll][Ee][Ss][Hh])*([bB][Oo][Nn][Ee][sS]*)* ([Tt][Ee]+[Tt][Hh])*([Ff][Ll][Ee][Ss][Hh])*([bB][Oo][Nn][Ee][sS]*)* ([Tt][Ee]+[Tt][Hh])*([Ff][Ll][Ee][Ss][Hh])*([bB][Oo][Nn][Ee][sS]*)*$