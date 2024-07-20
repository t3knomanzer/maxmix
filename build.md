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

[part-power-bus-ae]: https://www.aliexpress.com/item/33007031908.html?spm=a2g0s.9042311.0.0.5ea74c4dZSeJCA
[part-display-ae]: https://www.aliexpress.com/item/32861875681.html?spm=a2g0o.productlist.0.0.40103137cSuJWL&algo_pvid=72a2cf65-9a42-4ea4-acc1-12d0c207044d&algo_expid=72a2cf65-9a42-4ea4-acc1-12d0c207044d-3&btsid=0ab6d59515893349825181599eeff5&ws_ab_test=searchweb0_0,searchweb201602_,searchweb201603_
[part-mcu-ae]: https://www.aliexpress.com/item/32856118319.html?spm=a2g0s.9042311.0.0.5ea74c4dZSeJCA
[part-rotary-ae]: https://www.aliexpress.com/item/32790788377.html?spm=a2g0s.9042311.0.0.3f0b4c4dAi0mJO
[part-m2x5mm-ae]: https://www.aliexpress.com/item/32975410255.html?spm=a2g0o.detail.0.0.496572dbSutw9Y&gps-id=pcDetailCartBuyAlsoBuy&scm=1007.12908.131176.0&scm_id=1007.12908.131176.0&scm-url=1007.12908.131176.0&pvid=ff23c9a7-d73c-454f-a4c6-322a121bd814&_t=gps-id:pcDetailCartBuyAlsoBuy,scm-url:1007.12908.131176.0,pvid:ff23c9a7-d73c-454f-a4c6-322a121bd814,tpp_buckets:668%230%23131923%2319_668%23808%235965%23251_668%23888%233325%2311_668%232846%238111%23466_668%232717%237566%23817
[part-m2x10mm-ae]: https://www.aliexpress.com/item/33043091484.html?spm=a2g0o.productlist.0.0.767f4a08gAx7Oc&s=p&ad_pvid=2020051218463417005721656175370016165454_11&algo_pvid=9e1a1b86-9322-441f-b087-ef567c376f63&algo_expid=9e1a1b86-9322-441f-b087-ef567c376f63-10&btsid=0ab6d69f15893343947923488e699c&ws_ab_test=searchweb0_0,searchweb201602_,searchweb201603_
[part-wires-ae]: https://www.aliexpress.com/item/33007698478.html?spm=a2g0o.productlist.0.0.44b248d7kcLfV9&algo_pvid=b0a90a38-c903-4828-9cf3-0073b86684ae&algo_expid=b0a90a38-c903-4828-9cf3-0073b86684ae-6&btsid=0ab6d67915893355772902177e0543&ws_ab_test=searchweb0_0,searchweb201602_,searchweb201603_
[part-bumpers-ae]: https://www.aliexpress.com/item/32289191938.html?spm=a2g0o.productlist.0.0.20513e1cJD6rV0&s=p&ad_pvid=2020051219254812188693811548200016292927_1&algo_pvid=f58a6173-19a8-4de7-9dbb-819984df4870&algo_expid=f58a6173-19a8-4de7-9dbb-819984df4870-0&btsid=0ab50f6115893367485698071ebd11&ws_ab_test=searchweb0_0,searchweb201602_,searchweb201603_

[part-led-ring-ae]: https://www.aliexpress.com/item/32758176722.html
[part-power-bus-td]: https://www.tindie.com/products/maxmixproject/power-bus/
[part-display-am]: https://www.amazon.com/MakerFocus-Display-SSD1306-3-3V-5V-Arduino/dp/B079BN2J8V/
[part-mcu-am]: https://www.amazon.com/ELEGOO-Arduino-ATmega328P-Without-Compatible/dp/B0713XK923
[part-rotary-am]: https://www.amazon.com/gp/product/B06XQTHDRR/
[part-m2x5mm-am]: https://www.amazon.com/gp/product/B076ZV44GN/
[part-m2x10mm-am]: https://www.amazon.com/gp/product/B01LJRPEXK/
[part-wires-am]: https://www.amazon.com/gp/product/B077N58HFK/
[part-bumpers-am]: https://www.amazon.com/gp/product/B073ZKDMM3
[part-led-ring-am]: https://www.amazon.com/gp/product/B081B9QWP6/

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
