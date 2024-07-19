---
width:                    expand        # Options: full, expand, small, xsmall
section:                  large

navbar:
    transparent:          true
    transparent_color:    light

header:
  layout:             1-1            # Options: left, center, 1-1, 1-2, 1-3 or 2-3. Left, right options display this pages title and subtitle. 1-1, 1-2, 1-3 or 2-3 options display content of block file/s.
  color:              light             # Content font color, Options: light, dark
  height:                               # Enable viewport height, Options: full
  header_size:        large            # Only if height disabled
  heading_size:       medium            # Title size, Options: small, medium, large
  parallax:           false              # Enable content parallax, Options: true
  container:          small             # Content width, Options: expand, small, xsmall
  content:
    block:            build-header

  background_image:   build/header.jpg
  background_overlay: "linear-gradient(to left top,rgba(252, 97, 97, 0.8) 0%, rgba(69, 69, 69, 0.8) 80%)"

sidebar:
    right:            build
---

[part-power-bus-ae]:https://www.aliexpress.com/item/33007031908.html
[part-display-ae]:https://www.aliexpress.com/item/32861875681.html
[part-rotary-ae]:https://www.aliexpress.com/item/32790788377.html
[part-m2x5mm-ae]:https://www.aliexpress.com/item/32975410255.html
[part-m2x10mm-ae]:https://www.aliexpress.us/item/2251832856776732.html
[part-wires-ae]:https://www.aliexpress.com/item/33007698478.html
[part-bumpers-ae]:https://www.aliexpress.com/item/32289191938.html
[part-led-ring-ae]:https://www.aliexpress.com/item/32758176722.html

[part-power-bus-td]:https://www.tindie.com/products/maxmixproject/power-bus/
[part-display-am]:https://www.amazon.com/MakerFocus-Display-SSD1306-3-3V-5V-Arduino/dp/B079BN2J8V/
[part-mcu-am]:https://www.amazon.com/ELEGOO-Arduino-ATmega328P-Without-Compatible/dp/B0713XK923
[part-rotary-am]:https://www.amazon.com/gp/product/B06XQTHDRR/
[part-m2x5mm-am]:https://www.amazon.com/gp/product/B076ZV44GN/
[part-m2x10mm-am]:https://www.amazon.com/gp/product/B01LJRPEXK/
[part-wires-am]:https://www.amazon.com/gp/product/B077N58HFK/
[part-bumpers-am]:https://www.amazon.com/gp/product/B073ZKDMM3
[part-led-ring-am]:https://www.amazon.com/gp/product/B081B9QWP6/

# Parts

All parts for the maxmix controller can be found and purchased online.
Links to the parts are provided below but feel free to purchase them elsewhere.
When looking for alternatives, just make sure the part specifications match to avoid any issues.

## 3D Print

The enclosure for the controller is made of a couple of 3D printed parts and can be downloaded from [Prusaprinters.org](https://www.prusaprinters.org/prints/31336-maxmix).

If you don't have a 3D printer, I recommend using a community printing service such as [Treatstock](https://www.treatstock.com/), it is the most cost effective method.

{% include gallery.html
  gallery="build/parts/enclosure/"
  grid="1-4"
  gutter="small"
  caption="false"
  lightbox="true"
%}

## Hardware

Below are the rest of parts needed to complete the project.
\* **Due to DOA reports on Arduinos ordered from AliExpress, we've decided to not provide a link.**

|Part                                     |Count   |Ali-Express                 |Amazon (US)                            |
|-----------------------------------------|--------|----------------------------|---------------------------------------|
|M2 10mm Countersink screws               |4       |[Link][part-m2x10mm-ae]     |[Link][part-m2x10mm-am]                |
|M2 5mm Screws                            |6       |[Link][part-m2x5mm-ae]      |[Link][part-m2x5mm-am]                 |
|Silicon bumper 2x8mm                     |4       |[Link][part-bumpers-ae]     |[Link][part-bumpers-am]                |
|Arduino Nano 328P CH340                  |1       |*                           |[Link][part-mcu-am]                    |
|128x32 I2C OLED display                  |1       |[Link][part-display-ae]     |[Link][part-display-am]                |
|Rotary encoder                           |1       |[Link][part-rotary-ae]      |[Link][part-rotary-am]                 |
|Power bus                                |1       |[Link][part-power-bus-ae]   |[Link (Tindie)][part-power-bus-td]     |
|10cm Female to female jumper wires       |11      |[Link][part-wires-ae]       |[Link][part-wires-am]                  |
|WS2812 5050 LED Ring 8-bit (Optional)    |1       |[Link][part-led-ring-ae]    |[Link][part-led-ring-am]               |

{% include gallery.html
  gallery="build/parts/hardware/"
  grid="1-4"
  gutter="small"
  caption="false"
  lightbox="true"
%}

## Tools

Here are the tools you are going to need.

- Small philips screwdriver
- Soldering iron (or alternative such as conductive silver epoxy)
- Needle nose pliers
- Wire cutting pliers
- Wire stripper (Optional)
- Third hand (Optional)

{% include gallery.html
  gallery="build/parts/tools/"
  grid="1-4"
  gutter="small"
  caption="false"
  lightbox="true"
%}
