# Home Assistant Add-on: Z-Wave JS UI Proxy

[![Docker Pulls]](https://hub.docker.com/r/priyantha1986/zwave-js-ui-proxy)

⚠️ This addon does not contain Z-Wave JS UI ⚠️

This addon acts as a proxy to an external running Z-Wave JS UI instance. 
The sole purpose of this addon is to add a Z-Wave JS UI icon to the sidebar of Home Assistant which will open the frontend of an external running Z-Wave JS UI instance.

## Options

- `server` (required): this should be the local URL on which the Z-Wave JS UI frontend is running, e.g. `http://192.168.2.43:8091`. Make sure there is no trailing slash!