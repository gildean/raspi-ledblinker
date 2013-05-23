ledblinker
==========

Blink some leds and register interrupts from buttons on the raspi (or some other device with gpio pins).

![ledblinker in action](http://julkinen.salaliitto.com/misc/ledblinker.png "Ledblinker in action")

features
--------

You can set an arbitrary number of leds and buttons in the config, nothing is hardcoded to either the server or the frontend.

The changes made in the frontend are broadcast to all connected clients with websockets, so you'll see changes made on any client in real-time on other clients

usage
-----
Set your configs in `config.json`, install modules with `npm install` and then run the app with `./ledblinker`

license
-------
BSD
