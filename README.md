Metar Bitbar Plugin
---

Metar provides a simple Bitbar item to watch aviation weather for a specific airport. At a glance you can see what the conditions of your home airport.

Metar uses the same NOAA METAR data used for aviationweather.gov and checks for updates every 5 minutes.

![/metar-vfr.png](/metar-vfr.png)

![/metar-ifr.png](/metar-ifr.png)

# Requirements

  * Ruby >= 2.3.1
  * [ruby gem] inifile
  * [ruby gem] metar-parser >= 1.3.2

# Setup

Inside the ~/.bitbarrc file is where you set the airport code you want to watch:

```
[metar]
airport=KDPA
```
