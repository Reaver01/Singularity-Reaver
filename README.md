# Singularity-Reaver  
Add on profile for the HCS Singularity BETA  

## Current Features  

 - Auto jumping after each fuel scoop. (Make sure you don't let it hit 100% fuel, or it will try and jump wile your scoop is out and cook you. I can't do anything about this, it's just how the journal files are written) 
      If you are not near a scoopable star you will need to say the "initiate sequence" command after the "Enable auto jump" command to start the jump sequence. when you are finished jumping make sure you stop it with the "Sequence Complete" command.  
 - Pasting a system name into the Galmap and routing to it.  
      you can also use this with a list of systems in notepad, It will need to be in a file called "System Route.txt" and you will have to have it opened in Notepad.exe  
      the format is just system name on each line with end on the very last line  
 - "What mode am I in" uses TTS to tell you if you are in Open/Group/Solo in case you forget  
 - "Copy System Name" will copy the system you are currently in to the windows clipboard  
 - Mode switcher command will flip those pesky boards for you.
 - Music commands. These will work with any music player that recognises media keys. I use https://github.com/MarshallOfSound/Google-Play-Music-Desktop-Player-UNOFFICIAL-/releases which is why there are the thumps up/down ones


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

# I don't have sounds from your profile other than a few TTS things!!!  
I am using some R2D2 sounds that I found on the Internet.  
You can find them here: http://www.android.net/forum/android-audio/58434-star-wars-sound-files-you-r2-d2-many-more-ringtones-notifications.html  
you will have to put them in the sound folder yourself.  
I have them in the following directories:  

R2_D2\S1  
  QR2_D2S1.WAV  
  QR2_D2S2.WAV  
  QR2_D2S3.WAV  
  
R2_D2\S2  
  QR2_D2W1.WAV  
  QR2_D2W2.WAV  
  QR2_D2W3.WAV  
  
R2_D2\S3  
  QSNTNC1.WAV  
  QSNTNC2.WAV  
  QSNTNC4.WAV  
  QSNTNC6.WAV  
  QSNTNC7.WAV  
  QSNTNC8.WAV  
  QSNTNC9.WAV  
  QSNTNC10.WAV  
  QSNTNC13.WAV  
  QSNTNC16.WAV  
  QSNTNC18.WAV  
  QSNTNC20.WAV  
  
R2_D2\S4  
  QWORD1.WAV  
  QWORD4.WAV  
  QWORD8.WAV  
  QWORD9.WAV  
  QWORD16.WAV  
  QWORD22.WAV  
  
Mixed  
  ~~Various sounds I wanted to play during FSD Jump. Just pick and choose your favorite lines!~~  
  Current version does not use these.
  
