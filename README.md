OctoRGB Plugin
===============

This is a plugin for displaying [OctoPrint](http://octoprint.org/) status on a connected RGB LED.

Requirements
------------
* Raspberry Pi
* Common-cathode RGB LED or LED strip
* OctoPi 1.2.0+

Acknowledgements
----------------
OctoGlow uses Jason Barnett's [PiGlow Python module](https://github.com/Boeeerb/PiGlow)


Moving to OctoPrint 1.2.0
-------------------------
Follow the process in [the OctoPrint FAQ](https://github.com/foosel/OctoPrint/wiki/FAQ#how-can-i-switch-the-branch-of-the-octoprint-installation-on-my-octopi-image) to move to the development branch

Installing the Plugin
---------------------
Install the plugin like you would install any regular Python package from source:

``` bash
pip install https://github.com/Liftyee/OctoPrint-OctoGlow/archive/master.zip
```

Make sure you use the same Python environment that you installed OctoPrint under, otherwise the plugin won't be able to satisfy its dependencies.

