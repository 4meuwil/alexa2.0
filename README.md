** updated using packages and added alexa temp/humidy sensor announements (set up routine to activate boolean)

# Alexa 2.0

This is what I call "alexa 2.0" and it works well for me. I have amazon prime music and use it almost solely. "media_content_id" could be adjusted for other services such as spotify, pandora, tunein etc.

This project requires ***Node Red*** and the ***"Alexa as a media player"*** script by Keaton Taylor successfully running....
Keaton's Github..... https://github.com/keatontaylor
Direct Link to Script... https://github.com/keatontaylor/custom_components/blob/master/media_player/alexa.py

The script alexa.py should be saved to your config/custom_components/media_player folder
and at minimum the media_player entry and options entered into configuration.yaml for it to work, restart!

Note: You may have to try a couple times to get the Captcha to work...just enter a few random letters and submit for a fresh photo.

**A Special Thank You! to Keaton Taylor for this amazing script, without it none of this would be possible.**

***If you haven't joined the DrZzs Home Automation and Tech Hacks facebook group and found this by other means...please join!***

Obviously...this is all dependent on device names....and what genres you want to have on hand.

Your input_select.which_device entry will need to be edited accordingly. After doing so, you'll need to edit names in the "big switch" as well as most of the function nodes for the devices. Take note of how it "flows" and add/subtract devices as needed.

For multiple speakers, go into your Alexa app and create a speaker group. It should show up in HA as media_player.groupname

For the genres, edit input_select.genre as you wish. I would suggest seeing how they are named in Prime Music i.e. "rock" played rap songs for me.

You can very quickly use this as a package or break out all the components to suite your needs....hope you like it!























