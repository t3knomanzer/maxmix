# Soldering

Soldering has been kept down to a minimum but some is required.
If you are unable to solder, you can try alternative methods such as [conductive glue](part-conductive-glue).

## MCU

1. Locate the side that has pins D13 through VIN.
2. Insert a row of pins them from the top so shorter ends are poking through the back.
3. Solder the pins from below.
4. Use the needle nose pliers top break apart 5 pins from the remaining row.
5. Insert them in the MCU between pins D12 and D8.
6. Solder them from below.

{% include gallery.html
  gallery="build/soldering/mcu/"
  grid="1-4"
  gutter="small"
  caption="false"
  lightbox="true"
%}

## LED Ring (Optional)

1. Grab 3 of the jumper wires.
2. Using the wire cutters, cut the connectors from one end and strip the wires.
3. Use the soldering iron to tin the stripped ends.
4. Tin the pcb connections of the LED ring labeled **DI**, **5V** and **GND**.
5. Solder the wires to the pcb.

{% include gallery.html
  gallery="build/soldering/led-ring/"
  grid="1-4"
  gutter="small"
  caption="false"
  lightbox="true"
%}
