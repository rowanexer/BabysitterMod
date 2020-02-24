BABYSITTER 1.1

REQUIREMENTS
- SMAPI
- Content Patcher
- Child To NPC
- Custom NPC Fixes

FEATURES
- General dialogue (same for all children)
- Dialogue for babysitters (same for all children)
- Dialogue for no babysitter (different for all children)
- Schedule for no babysitter (different for all children)
- Schedule for babysitters Alex, Maru, and Sebastian (one child for one babysitter only)
- Likes and dialogue for gifts

CONFIGURATION
Load the game with the mod for the first time to generate the config file. It should look like this:

{
  "FirstBabysitter": "None",
  "SecondBabysitter": "None"
}

You can change the babysitter for the first born and second born child like so:

{
  "FirstBabysitter": "Sebastian",
  "SecondBabysitter": "Maru"
}

Make sure to use quotation marks "" and leave the first comma where it is.

KNOWN ISSUES
- If your child has the same name as another NPC in the game then this mod will affect the adult's schedule
and not your child. You will need to change your child's name for the mod to work.
- Sometimes children will refuse to leave the house even when they have a schedule. 
Closing the game and reopening should solve this problem.