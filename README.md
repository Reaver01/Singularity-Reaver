# Singularity-Reaver  
Add on profile for the HCS Singularity BETA  
Please be aware that this is a PLUGIN, and is in no way shape or form necessary, or needed for your HCS profile. Also, I am in no way shape or form affiliated with the fine folks at HCS and am making this on my own for my own enjoyment. If you use this plugin, please be aware that it could cause unnecessary errors in your running profile, and if you believe you have found an issue with HCS' profiles, you should completely disable this plugin and attempt to recreate the error without it before bringing the bug to HCS support, as they do not have a responsibility to troubleshoot my plugin. 

## Current Features  

 - Auto jumping after each fuel scoop. (Make sure you don't let it hit 100% fuel, or it will try and jump wile your scoop is out and cook you. I can't do anything about this, it's just how the journal files are written) 
      If you are not near a scoopable star you will need to say the "initiate sequence" command after the "Enable auto jump" command to start the jump sequence. when you are finished jumping make sure you stop it with the "Sequence Complete" command.  
 - Pasting a system name into the Galmap and routing to it.  
      you can also use this with a list of systems in notepad, It will need to be in a file called "System Route.txt" and you will have to have it opened in Notepad.exe  
      the format is just system name on each line with end on the very last line  
 - "What mode am I in" uses TTS to tell you if you are in Open/Group/Solo in case you forget  
 - "Copy System Name" will copy the system you are currently in to the windows clipboard  
 - Mode switcher command will flip those pesky boards for you.
 - Music commands. These will work with any music player that recognises media keys. I use https://github.com/MarshallOfSound/Google-Play-Music-Desktop-Player-UNOFFICIAL-/releases which is why there are the thumps up/down ones **Thumbs up and down have changed to Ctrl + Alt + . and Ctrl + Alt + ,**


# How to use this add on  
First things first: YOU MUST OWN AN HCS VOICE PACK. If you don't own one, stop right now and don't bother. This is not a standalone VA Profile and it relies on a ton of things from HCS. Get Astra or something, that's the one I used to develop this.  
Next: YOU MUST BE USING THE SINGULARITY BETA. If you don't have this set up already, don't bother with this right now. Go set that up.  
Finally: I am making this as a side project. I will try my best to keep it updated. I may add requested features, but I already do tech support as a job, I don't want to do it during my gaming time.  

# Setup for real this time  
If you got past that first part, downloaded the add on and have everything setup without any pesky little errors or warnings we can now begin!  

1. Open VoiceAttack and make sure you are on your "Elite: Singularity" profile  
2. Click the edit button to open the command list  
3. Click "Import Commands" at the bottom on the left  
4. Select the "IMPORT INTO SINGULARITY AND OVERWRITE COMMANDS.vap" file and click "Open"  
  Before you ask: Yes, it is necissary to do this. I rely on a few Booleans from Journal events and they need to be in the main profile to work correctly.  
5. This is where you are going to be hesitant. I know, it's big red and scary, but make sure all 5 things are checked and click the "Import" button. I promise you won't explode, and in fact, this will not change anything with your "Elite: Singularity" Profile, it just gives me some true/false flags  
6. Click "Yes"  
7. We are done with that profile for now, so click "Done"  
8. Click the "+" button and "Import Profile"  
9. Select the "Singularity Reaver-Profile.vap" profile and "Open"  
10. No setup is required here, switch back to your "Elite: Singularity" profile  
11. Click on the edit button again  
12. Up top by the profile name there is a little checkmark button, press that  
13. in the "Include commands from other profiles:" section press the "..."  
14. Press the "+" and select the "Singularity: Reaver" profile from the dropdown  
15. Press both "OK" buttons to close those windows, and we are done here so press "Done"  
16. Bind "F6" in game to pitch down, or go into the "Singularity: Reaver" Profile and filter "F6" you can change that keybind there if you like. I have it set to that because I don't use F6 for anything else in game.  

That's it. Go play!  
