# Wireless-Audio-Project

This is a college project, we tried to transmit audio to a lot devices ESP32 at the same time, we failed
because of the syncronization, it was very difficult to syncronize all the devices and we had very delays in 
our transmission, so we decided to adapt the project. 

We configured a shield called DFPlayer, it works similar to a MP3 player, we put this shield in all devices and
programmed to be controlled by the arduino IDE. So it worked well and then we used MQTT protocol to make some tests,
we built an APP to communicate with the devices, now when we send any message to the device via APP, all the
devices registered on the MQTT protocol that we configured, receive the message at the same time anywhere. That is, 
when we send a message to play an audio, all the devices receive the message at the same time and start to play, the
same happens with all the other messages we send: stop, previous, next, turn on the speaker, turn off the speaker,
turn up the volume, turn down the volume.

Link to watch the project running:
https://youtu.be/o2MXj6yLrms
