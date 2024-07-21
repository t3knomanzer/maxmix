---
width: expand # Options: full, expand, small, xsmall
section: large

navbar:
  transparent: true
  transparent_color: light

header:
  layout: 1-1 # Options: left, center, 1-1, 1-2, 1-3 or 2-3. Left, right options display this pages title and subtitle. 1-1, 1-2, 1-3 or 2-3 options display content of block file/s.
  color: light # Content font color, Options: light, dark
  height: # Enable viewport height, Options: full
  header_size: large # Only if height disabled
  heading_size: medium # Title size, Options: small, medium, large
  parallax: false # Enable content parallax, Options: true
  container: small # Content width, Options: expand, small, xsmall
  content:
    block: build-header

  background_image: build/header.jpg
  background_overlay: 'linear-gradient(to left top,rgba(252, 97, 97, 0.8) 0%, rgba(69, 69, 69, 0.8) 80%)'

sidebar:
  right: build
  sticky: true
---

[part-power-bus-ae]:https://www.aliexpress.com/item/33007031908.html
[part-display-ae]:https://www.aliexpress.com/item/32861875681.html
[part-rotary-ae]:https://www.aliexpress.com/item/32790788377.html
[part-m2x5mm-ae]:https://www.aliexpress.us/item/3256807017181013.html
[part-m2x10mm-ae]:https://www.aliexpress.us/item/2251832856776732.html
[part-wires-ae]:https://www.aliexpress.us/item/3256806696233563.html
[part-bumpers-ae]:https://www.aliexpress.com/item/32289191938.html
[part-led-ring-ae]:https://www.aliexpress.com/item/32758176722.html
[part-conductive-glue-ae]:https://www.aliexpress.com/item/4000805311240.html

[part-power-bus-td]:https://www.tindie.com/products/maxmixproject/power-bus/
[part-display-am]:https://www.amazon.com/dp/B079BN2J8V/
[part-mcu-am]:https://www.amazon.com/dp/B09SG7D36R/
[part-rotary-am]:https://www.amazon.com/dp/B06XQTHDRR/
[part-m2x5mm-am]:https://www.amazon.com/dp/B076ZV44GN/
[part-m2x10mm-am]:https://www.amazon.com/dp/B01LJRPEXK/
[part-wires-am]:https://www.amazon.com/dp/B077N58HFK/
[part-bumpers-am]:https://www.amazon.com/dp/B07G86DL1L
[part-led-ring-am]:https://www.amazon.com/dp/B08PCPJSRF
[part-conductive-glue-am]:https://www.amazon.com/dp/B0992H9MQZ/

# Overview

The Maxmix controller has been designed to be easy and fun to build.
It uses a combination of 3D printed parts and off-the-shelf electronic components.
All parts can be easily found and ordered online!

The total cost of the parts is **~$25.00 USD** including the 3D printing and shipping. It takes around **25 minutes** to build.

Let's get started!

{% include_relative build-sections/parts.md %}
{% include_relative build-sections/soldering.md %}
{% include_relative build-sections/electronics.md %}
{% include_relative build-sections/wiring.md %}
{% include_relative build-sections/assembly.md %}
