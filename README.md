# Home Assistant Add-on: Z-Wave JS UI Proxy

⚠️ This addon does not contain Z-Wave JS UI ⚠️

This addon acts as a proxy to an external running Z-Wave JS UI instance. 
The sole purpose of this addon is to add a Z-Wave JS UI icon to the sidebar of Home Assistant which will open the frontend of an external running Z-Wave JS UI instance.

I do NOT have a working docker image, or something else like a 'normal' installation method because simply I am not capable of doing so, I am no coder.
So you can only install this the 'manual' way.

You can do this like this:
1. Git clone this project into your local (for example '/usr/share/hassio/addons/local' this is in my supervised install the folder) add-ons folder
2. chmod the file entrypoint.sh to 755 by using 'chmod 755 entrypoint.sh' as command.


## Options

- `server` (required): this should be the local URL on which the Z-Wave JS UI frontend is running, e.g. `http://192.168.2.43:8091`. Make sure there is no trailing slash!