Canon PowerShot A2200 1.00d settings
====================================

What is this?
-------------
This is a description of the Canon firmware settings I use with my Canon A2200 camera with firmware 1.00d.

I've more or less successfully used CHDK 1.0.0 r1825 build for the Canon A2200 1.00d (build date 2012/04/27), as found on the CHDK forums. Success means reliable remote shooting using lua shoot() commands over ptp using a combination of ptpcam and gphoto2. See test_keypedal.sh for a crude script that I hacked together to use with my book scanner.

The more recent CHDK 1.1.0 r19xx, build date 2012/07/02 seems to crash hard when trying to shoot remotely.

Turn your camera wheel to P mode and adjust to the settings below.

Capture settings
----------------
* AF Frame: center
* AF Frame size: normal
* Digital Zoom: off
* AF-Point zoom: off
* Servo AF: off
* AF-assist beam: off
* Flash settings:
 * Red-Eye Corr.: off
 * Red-Eye Lamp: off
* i-Contrast: off
* Review: off
* Blink Detection: off
* Disp. Overlay: off
* Date Stamp: off

General settings
----------------
* mute: off
* volume:
 * start-up vol.: max (you want some confirmation that it's working!)
 * operation vol.: max
 * selftimer vol.: max
 * shutter volume: max (you want some confirmation that it's working!)
* hints & tips: off
* LCD brightness: max (I have an AC adapter. If you don't, you might want to change this.)
* start-up image: none (might save a few extra bytes of camera memory?)
* file numbering: continuous (consistence when downloading)
* create folder: monthly (as little as possible)
* lens retract: 1 min. (as long as possible)
* power saving:
 * auto power down: off (I have an AC adapter. If you don't, you might want to change this.)
 * display off: 3 min. (as long as possible)

Various hints
-------------
* Make sure you have enough light when testing, or the camera might refuse to capture!
* If you want to override the autofocus distance, set the autofocus lock first, or the firmware will crash:
 * camera wheel -> P mode
 * focus
 * keep shutter button half pressed, press tulip button

See also
--------
* http://chdk.wikia.com/wiki/A2200 : CHDK on A2200 status page
* http://chdk.setepontos.com/index.php?topic=6254.0 : CHDK forum A2200 topic