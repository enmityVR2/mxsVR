READ THIS!!!
This isnt a tutorial to fully setup alvr. This is a tutorial for it to work on mxs. 
Along with this, make sure your headset is here: https://github.com/alvr-org/ALVR. this should work on all of those listed on the github. but this has only been tested on a quest 2 and quest 3.

To download ALVR, follow the linux tar.gz tutorial at:  https://github.com/alvr-org/ALVR/wiki/Installation-guide

This will be updated when new fixes are found! if something breaks, scroll to the bottom, see if i updated this. if not, ping me in the maximumsettings server (@fatevr/enmity • VR) and I will try to find a fix!

Lastly, this should work on all tiers, but only tier 4 has been tested so far.

Requirements

———————————————————

ALVR on both the mxs pc, and your quest
Access to your router settings
Decently fast internet (100+ is reccomended for a good experience, but lower should still work)

Setup (router)

———————————————————

Open ALVR on your headset. You should see XXXX.client, and an IP address. You will need both of these

Now go to your routers settings (normally you can go there, by putting 192.168.1.1 in your browser, but this may be different for you!)

Look for port forwarding, and go to it.

Add your headset to it. Look for the IP that showed up in ALVR, that is your headset.

Specify the ports 9943 to 9944 for both UDP and TCP, and save it.


————————————————————


Setup (ALVR)

————————————————————

Open alvr on mxs, and setup as normal.

Now select "add client manually" and enter the XXXX.client that shows in your headset.

Now tap "Add New" and enter your IP (NOT THE ONE THAT IS IN YOUR HEADSET!!!) To find your IP go to a website like https://whatsmyip.com/

—————————————————————


Setup (SteamVR)

—————————————————————

Now you can login to steam, and get SteamVR.

Install it, and set the launch options to "~/.steam/debian-installation/steamapps/common/SteamVR/bin/vrmonitor.sh %command" (without the ")

Go back to ALVR and launch steamvr from the "Launch SteamVR" button.


——————————————————————


Finished!

——————————————————————

Now you can play! enjoy!!! if you have some issues, read below to see if i have already found a fix. if not, ping me on Discord! (@fatevr/enmity • VR)
——————————————————————


Workarounds/Fixes/Bugs

——————————————————————

Audio not in headset: Download pulseaudio, find the game you want, and change the audio source to the one at the top.

Hearing myself/Mic not working correctly: there are lots of versions of this bug, thus making this harder to explain, you will need pulseaudio aswell.
Try to mess around with the inputs and outputs in pulseaudio

Issue not here? Check https://github.com/alvr-org/ALVR/wiki/Troubleshooting!







This has not been updated yet. Read above to find your issue. if its not listed anywhere, please ping me on Discord (@fatevr/enmity • VR)
