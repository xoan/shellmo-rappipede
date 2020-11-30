# Rappipede for Shellmo

RepRap printable version of [Micropede][mpdoc] motor module for [Shellmo][spweb].

[mpdoc]: http://shellmo.org/making-micropede.html
[spweb]: http://shellmo.org/

## Printing

All the parts can be printed without support.

Recommended settings for Slic3r 1.2.1:

* layer height: 0.25mm
* infill: 30%
* extrusion width: 0.5mm

## Assembly ([in pictures][mpagp])

* M3x8mm screw **x24**
* M3x10mm screw **x4** (for motor cover)
* M3 nut **x28**

Please, refer to `src/chassis.fcstd` to see the pin-leg connection and to
figure out how to assembly the whole thing. You must put all the pins before
to assembly the ribs, and also before this you must put the captive nuts.

Shaft is a tricky part. Try to fit all the shaft parts without glue and
without play, and insert in the ribs before put the rear one.

The rest is the same in [Micropede documentation][mpdoc].

The compatible motor cover is the one you can find in the [RepWalker][rwdoc].

[mpagp]: https://photos.app.goo.gl/5GXLVykhWVXsJaY36
[rwdoc]: http://shellmo.org/making-repwalker.html
