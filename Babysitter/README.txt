BABYSITTER 1.7.0


REQUIREMENTS
- SMAPI
- Content Patcher
- Child To NPC
- Custom NPC Fixes


FEATURES
- Two personality types (outgoing and shy)
- General dialogue (different for each personality)
- Dialogue during babysitting (same for all children)
- Schedule for babysitters Alex, Maru, Sebastian, Abigail, Shane, Emily, Linus, Sam and Elliott (one child for one babysitter only)
- Dialogue for no babysitter (different for all children)
- Schedule for no babysitter (different for all children)
- Likes and dialogue for gifts
- Movie dialogue
- Portuguese translation
- Chinese translation


CONFIGURATION
Load the game with the mod for the first time to generate the config file. It should look like this:

{
  "FirstBabysitter": "None",
  "SecondBabysitter": "None",
  "FirstPersonality": "Outgoing",
  "SecondPersonality": "Shy"
}

You can change the babysitter for the first born and second born child like so:

{
  "FirstBabysitter": "Sebastian",
  "SecondBabysitter": "Maru"
}

You can also change the children's personalities.

Make sure to use quotation marks "" and leave the first comma where it is.

By default Babysitter starts working 1 month after the baby turned into a toddler. If you want it to start working earlier then open the Child to NPC config file, and change the AgeWhenKidsAreModified to 55. 

You can also change other settings in the Child to NPC config file such as curfew time. 



KNOWN ISSUES
- If your child has the same name as another NPC in the game then this mod will affect the adult's schedule and not your child. You will need to change your child's name for the mod to work.
- Sometimes children will refuse to leave the house even when they have a schedule. 
Closing the game and reopening should solve this problem.