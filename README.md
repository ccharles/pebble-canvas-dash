# Dash watchface for Pebble #

## Introduction ##

Dash is a watchface for the [Pebble watch](https://getpebble.com/). It
requires
[Canvas for Pebble](https://play.google.com/store/apps/details?id=com.pennas.pebblecanvas)
version 1.4.6 or later. Canvas for Pebble is only available on Android.

All credit for this face should go to the Canvas developer. I just made a
background image, played around on my phone for a few minutes, and exported.

![Dash screenshot](https://github.com/ccharles/pebble-canvas-dash/raw/master/screenshot.png)

## Features ##

Dash was designed to pack as much useful information as possible into a face
while maintaining readability for frequently used information. I also wanted
to avoid the large, chunky icons that seem to be used on most Canvas faces
that show email, SMS, etc.

Most of these features can be easily modified using the Canvas interface, so
don't feel like you're stuck with any of my choices.

* Local day, date, month
* Local time (24 hour format)
* Sunrise, sunset
* Weather icon
* Location
* Temperature (Celsius)
* Weather
* Gmail unread message count
* SMS message count
* Missed call count
* Phone battery percentage
* Watch vibrates and shows a "!" icon when the Bluetooth connection is
  unexpectedly broken (e.g., if you walk too far away from your phone)

## A note on battery life ##

I have been having poor battery life on my watch since I started using this
face daily (2-3 days instead of 6-7). I have not done any kind of thorough
testing on this. YMMV.

## Installation ##

1. Install
   [Canvas for Pebble](https://play.google.com/store/apps/details?id=com.pennas.pebblecanvas)
1. On your phone, download the [latest `Dash.pcs` release](https://github.com/ccharles/pebble-canvas-dash/releases/download/1.0.0/Dash.pcs) from this repository
1. When prompted, open the file with Canvas
