NXP LPC1114-school
------------------

### sandbox for experiments and learnings

- how about using existing 16 timer? is everything on same clock now?
- tried LUT for jitter, no effect. 
- Tried blocking interrupts, no go
- tried tuning frequency to just over 100HZ, no good.
- Is it the clock?

its not the LEDs; oothers do it. 
Its not the different timers because I've elimitated the systick and timer functions
Voltage or current related? not power supply; tried lipo w/ higher voltage.



MIDI Monitor with Python
------------------------
- sudo easy_install -U pyserial
- python miniterm.py --port /dev/tty.usbserial-A4016VJT -b 31250 -DDD

-DDD shows raw hex