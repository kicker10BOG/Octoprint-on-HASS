# Octoprint-on-HASS

This is the relevant configuration settings, sensors, and groups 
I used for setting up a tab in my Home-Assistant site to monitor 
my Creality Ender 3 from anywhere. 

I have two Pi 3 B+s. One runs OctoPi and the other runs Hassio 
(home-assistant), which I use to control all my IoT stuff, like 
Hue lights or smart plugs. The Pi running Hassio is online; I 
can check it anywhere. The OctoPi is not, mostly because there's 
other ways to control it without exposing it too much.

Hassio has an Octoprint plugin that lets you monitor temps, 
status, time, and the camera, so I have it setup to do so. I 
also have a smart plug for the printer and a home made hue light 
strip in the enclosure (that I hope the printer is going into 
this weekend) that I can control from there. some extra work went 
into making the data display this way, with days, hours, minute, 
and seconds as well as Celsius instead of Fahrenheit, but I think 
it's pretty amazing as a monitoring system.

configuration.yaml is an exceprt from my own Configuration.yaml

ender3sensors.yaml is from my sensors.yaml

ender3groups.yaml is it's own file in my setup. 

![screenshot](https://raw.githubusercontent.com/kicker10BOG/Octoprint-on-HASS/master/Home%20Assistant.png)
