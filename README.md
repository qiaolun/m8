m8
==

A bootloader of ATmega8L with external 8MHz crystal.



fuse
----

> $ avrdude -p m8 -c usbasp -vvvv

> $ avrdude -p m8 -c usbasp -b 19200 -e -U lfuse:w:0xdf:m -U hfuse:w:0xca:m


upload
------

TX led will blink three times after upload button clicked. Release the reset button when TX led blicks.


