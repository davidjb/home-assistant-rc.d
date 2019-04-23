# Home Assistant rc.d script

## Installation

Set up Home Assistant as per
https://www.home-assistant.io/docs/installation/freenas/ and then use this
script here as the `rc.d` script.

```bash
mkdir -p /usr/local/etc/rc.d
wget https://github.com/davidjb/home-assistant-rc.d/raw/master/homeassistant -O /usr/local/etc/rc.d/homeassistant
chmod +x !$
service homeassistant {start|stop|restart|configtest}
```
