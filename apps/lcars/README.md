# LCARS clock

A simple LCARS inspired clock.
To show weather data such as temperature, humidity or window you BangleJS must be connected
with Gadgetbride and the weather app must be installed. To use the timer
the "sched" app must be installed on your device.

## Control
 * Tap left / right to change between screens.
 * Tap top / bottom to control the current screen.

## Features
 * LCARS Style watch face.
 * Enable or disable fullscreen mode (widgets are always loaded, but hidden if fullscreen).
 * Tab on left/right to switch between different screens.
 * Cusomizable data that is shown on screen 1 (steps, weather etc.)
 * Shows random and real images of planets.
 * Tap on top/bottom of screen 1 to activate an alarm. Depends on widtmr.
 * The lower orange line indicates the battery level.
 * Display graphs (day or month) for steps + hrm on the second screen.
 * Customizable theming colors in the settings menu of the app.
 * Enable or disable the alarm feature.
 * Enable or disbale the graphs for steps + hrm.
 * Has an optional setting to use the clock_info modules for the three data displaying areas.

## Data that can be configured
 * Steps - Steps loaded via the wpedom app.
 * Battery - Current battery level in %
 * VREF - Voltage of battery
 * HRM - Last measured HRM
 * Temp - Weather temperature loaded via the weather module + gadgetbridge
 * Humidity - Humidity loaded via the weather module + gadgetbridge
 * Wind - Wind loaded via the weather module + gadgetbridge. Set kph / mph in the settings.
 * Altitude - Shows the altitude in m.
 * CoreT - Temperature of device
 * You can also change the data with any of the clock info modules if enabled in the settings window.

## Multiple screens support
Access different screens via tap on the left/ right side of the screen

![](screenshot_1.png)
![](screenshot_2.png)

## Clock Info Module Support
Access diffrent data with the clock info module if enabled in the app settings.

## Creator
- [David Peer](https://github.com/peerdavid)

## Contributors
- [Adam Schmalhofer](https://github.com/adamschmalhofer)
- [Jon Warrington](https://github.com/BartokW)
- [Ronin Stegner](https://github.com/Ronin0000)
