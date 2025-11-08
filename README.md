# ESPHome firmwares

This repo holds the source of various firmwares used for installing ESPHome onto devices with [esphome/esp-web-tools](https://github.com/esphome/esp-web-tools).

modified to allow remote tts playback on other media players, as well as added a conversational mode that will continue listening for further imput after responding and time out after 15 seconds of no input resetting the loop. 

currently it will start listening for input durning response when playing tts back remotely triggering it to respond to itself. 
 
Working out how to set up a boolean in home assistant that can be turned on and off based on the tts playback state that can trigger listening to avoid this. this should also allow the response window to be triggered by tts playback finishing as well, preventing longer responses from being cut off and allowing the user to configure shorter (or longer) input windows as well.

Also trying to figure out the best way to get a wake sound implimented, but nothing fuctional as of yet.
