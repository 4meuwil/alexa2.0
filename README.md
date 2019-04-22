*** updated 4/22/19 using two lovelace files optimized for my desktop/mobile as well as a mini media player custom component.

** updated using packages and added alexa temp/humidy sensor announements (set up routine to activate boolean)

# Alexa 2.0

This is what I call "alexa 2.0" and it works well for me. I have amazon prime music and use it almost solely. "media_content_id" could be adjusted for other services such as spotify, pandora, tunein etc.

This project requires ***Node Red***, ***"mini media player"*** custom component, and the ***"Alexa as a media player"*** custom component by Keaton Taylor successfully running....

**A Special Thank You! to Keaton Taylor for this amazing script, without it none of this would be possible.**

***If you haven't joined the DrZzs Home Automation and Tech Hacks facebook group and found this by other means...please join!***

Obviously...this is all dependent on device names....and what genres you want to have on hand.

Your input_select.which_device entry will need to be edited accordingly. After doing so, you'll need to edit names in the "big switch" as well as most of the function nodes for the devices. Take note of how it "flows" and add/subtract devices as needed.

For multiple speakers, go into your Alexa app and create a speaker group. It should show up in HA as media_player.groupname

For the genres, I would suggest seeing how they are named in Prime Music i.e. "rock" played rap songs for me.

You can very quickly use this as a package or break out all the components to suite your needs....hope you like it!























