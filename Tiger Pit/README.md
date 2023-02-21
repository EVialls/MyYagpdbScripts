# The Tiger Pit
A set of scripts that creates a minigame about collecting marbles from The Tiger Pit, with a risk of being eaten by the tigers, dropping marbles, and there always being a cost for taking marbles. There is very little interaction beyond activating the scripts, and is an entertaining randomiser for people who are hanging in a discord.

# Recommended Installation
1. Create a Custom Command Group named 'The Tigerpit'. This allows adjusting the usage of the commands all as one unit rather than having to sort each one individually
2. Paste the contents of each non-readme file into a new command.
   a) For each command, set Trigger Type to 'Commmand (mention/cmd prefix)'
   b) In the 'Trigger' text box, put in the name of the command - The recommended names are the names of the files, and leaving it as not case sensitive

It is highly recommended to restrict the commands to be used in a dedicated discord channel only, as there is a lot of text that comes from these that would get in the way of conversation.

# The flow
A new user who uses either the Marbles or Tigerpit command for the first time will get assigned in the database as having '0 marbles'. 

The Tiger Pit command is the main command that does action. The player uses Tigerpit, and the command rolls the successes and failures, as well as generating a very basic narrative. The results are either the player gaining marbles, losing marbles, losing all their marbles, or being eaten for having no marbles. The player can use Tigerpit as many times as they like.

Each time the player succeeds at collecting marbles, the database notes down a 'sacrifice' that the player left in the pit, which gets recorded alongside their name. When a player uses the tigerpit command, alongside the marbles they get a chance of the number of a 'sacrifice' going down in the pit and them having 'gained' one - while only marbles gets recorded, this can sometimes result in a player picking up one of the sacrifices they left behind, or picking up someone else's sacrifice.

The rest of the commands are about listing how many marbles/sacrifices are in the pit, and an option for players to give marbles to other players.