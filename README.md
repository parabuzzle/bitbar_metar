Metar Bitbar Plugin
---

Metar provides a simple Bitbar item to watch aviation weather for a specific airport. At a glance you can see what the conditions of your home airport.

Metar uses the same NOAA METAR data used for aviationweather.gov and checks for updates every 5 minutes.

![/metar-vfr.png](/metar-vfr.png)

![/metar-ifr.png](/metar-ifr.png)

# Requirements

  * Ruby >= 2.3.1
  * [ruby gem] inifile
  * [ruby gem] metar-parser (There's is a bug in the current version -- 1.3.1. This bug is fixed in my branch of the gem found here: https://github.com/parabuzzle/metar-parser/tree/fix_station_list_location)

# Setup

Inside the ~/.bitbarrc file is where you set the airport code you want to watch:

```
[metar]
airport=KDPA
```
