# UNK

<a href="https://github.com/qmk/qmk_firmware/"><img width="200" src="https://qmk.131719.xyz/assets/images/badge-dark.svg"></a>

UNK stands for Ultimate Ngoprek Keyboard, my own version of <a href="https://ultimatehackingkeyboard.com/">UHK</a>. You can read the build log <a href="https://github.com/herpiko/unk#build-logs">here</a>.

I still want the original UHK but can't afford it for now. It's an expensive keyboard, the shipping cost alone is crazy 🙈. If you like this project and you want to <a href="https://karyakarsa.com/herpiko">buy me a coffe</a>, I'll be glad 😉.

If you are building one yourself and encountered any issue, feel free to open an issue in this GitHub repository. I'll respond ASAP.

I love building things. If you want this keyboard and  have resources (e.g. money) but don't have time to deal with tin, cables and failures, I can help you to build one. By doing this, you're supporting me to iterate the UNK into a better version. Please to reach me at herpiko@gmail.com.

<img src="/images/unkrev1.jpg">

## Goals

- Cheap 👎
- As thin as possible (thinner than Vortex Core) ✅
- Fully programmable (QMK) ✅
- Almost zero learning curve (horizontally staggered, ~ortholinear~, ~symbols through modifier/layer~) ✅
- Ergonomic as UHK (splitted) ✅
- Generic size of keycaps (combinations from 104 keycaps set should be fitted) ✅
- Interchangeable middle modules (trackpoint, ~touchpad, trackball, smartphone dock~) ✅

## Layout (rev2)

This is rev2 layout. I revised it to make it compatible with common 104 keycaps set. If you're looking for the original UNK layout (as seen on the photo above and in the build logs, which is not 100% compatible with 104 keycaps set), <a href="https://github.com/herpiko/unk/blob/master/unk-plate-layout.rev1.1.svg">you can grab it here</a>.

http://www.keyboard-layout-editor.com/#/gists/457787e3b1938c4cbe9d65c7b7bd31ef

<img src="/images/unk-layout-rev2.png">

## Plate (rev2)

Download:
- <a href="https://github.com/herpiko/unk/raw/master/unk-plate-layout.rev2.svg">SVG (Inkscape)</a>

The SVG file is fragmented to few locked layers:
- Components
- SandwichCase
- TopPlate
- BottomPlate

<img src="/images/plate-layout-rev-2.png">

## Anatomy

<img src="/images/component-anatomy.png" width="400">

The greens are on the top plate. The oranges are on the bottom.

1. USB-C female to Micro USB male converter
2. Pro Micro clone
3. Tactile switch
4. TRRS jack
5. Neodymium magnets

## Parts

| Item  | Price (rupiah) |
| ------------- | -------------: |
| I'm using existing DSA keycaps set from my <a href="https://www.google.com/search?q=vortex+tab+75&source=lnms&tbm=isch">Vortex Tab 75 keyboard</a>.<br/><br/>104 keycaps set is now supported. | 0 |
| <a href="https://www.tokopedia.com/vortexseries/ks-9-gateron-brown-switch-tactile-plate-mounted">Gateron Brown switches</a>, 80 @ Rp 2.400 | 192.000 |
| <a href="https://www.tokopedia.com/tokopuwei/dioda-in4148-1n-4148-in-4148-dip-diode-1n4148-do35-ac85-harga-1-pcs">IN4148 diodes</a>, 200 @ Rp 100 | 20.000 |
| <a href="https://www.tokopedia.com/solarperfect/pro-micro-promicro-atmega32u4-16mhz-5v-arduino-module">Pro micro ATMEGA32U4 16Mhz 5V</a>, 2 @ Rp 52.800 | 105.600 |
| Stainless steel plates + laser cutting service at <a href="https://www.instagram.com/laserindonesia/">Laser Indonesia</a>, 1.5mm top plate + 2.0mm bottom plate | 463.000 |
| ~~<a href="https://www.tokopedia.com/pixlup/genuine-cherry-pcb-mount-stabilizer-stabilizers-fullsize">Cherry switch stabilizers (1x6u, 6x2u)</a>~~  *<-- WRONG PART.* <a href="https://www.tokopedia.com/pixlup/genuine-cherry-plate-mount-stabilizers-stabilizer">The right one is the plate mount version.</a> | 210.000 |
| <a href="https://www.tokopedia.com/hpasesoris/m3x6mm-m3-6-black-nylon-hex-nut-m3-thread-female-standoff-spacer-aq21">M3 x 6mm female to female spacer</a>, 30 @ Rp 1.200 | 36.000 |
| <a href="https://www.tokopedia.com/pcmjakarta/kabel-tunggal-mini-tembaga-0-5mm-40meter">Single copper wire 0.5mm</a>, 40 meter | 30.000 |
| <a href="https://www.tokopedia.com/stickerkacafilm/stikerstickermotormobilstiker-karboncarbon3d-hitam-dof">Carbon vinyl sticker 30 meter</a> | 45.000 |
| <a href="https://www.tokopedia.com/kiddiesworld123/magnet-super-neodymium-kepingan-persegi-kotak-ndfeb-20-x-10-x-2-mm">Neodymium super magnet 20 x 10 x 2mm</a>, 16 @ Rp 3.700 | 59.200 |
| <a href="https://www.tokopedia.com/adelioberkah/baut-screw-kecil-m3x3-laptop-hp-toshiba-dell-samsung-asus-acer-lenovo">M3x3mm screw for top plate</a>, 20 @ Rp 3.000 | 60.000 |
| <a href="https://www.tokopedia.com/crd/m3-x-5mm-button-head-hex-screw-1pcs-baut-hex-m3x5mm-1pcs">M3x5mm hex screw for bottom plate</a>, 30 @ Rp 1.500 | 45.000 |
| <a href="https://www.bukalapak.com/p/komputer/aksesoris-226/keyboard/6ere8e-jual-wood-wrist-rest-for-tenkeyless-size-mechanical-keyboard-brown">Wood wrist rest for TKL size mechanical keyboard (36cm)</a> | 100.000 |
| <a href="https://www.tokopedia.com/qacc/type-c-to-microusb-adapter-converter-otg-adaptor-type-c-to-micro-usb">Type C USB to micro USB adapter</a>, 2 @ Rp 15.000 | 30.000 |
| <a href="https://www.bukalapak.com/p/elektronik/komponen-elektronik/zzdmgd-jual-tactile-switch-push-button-saklar-tekan-6x6x10-mm-arduino-elektronika-bread-board-pcb?product_sku=2181000539">Tactile switch push button 6 x 6 x 10mm</a>, 2 @ Rp 2.800 | 5.600 |
| <a href="https://www.tokopedia.com/myofficialstore0/trrs-pcb-3-5mm-breakout-jack-headset-headphone-earphone-socket-diy-merah">TRRS PCB 3.5mm jack socket</a>, 2 @ Rp 12.000 | 24.000 |
| <a href="https://www.tokopedia.com/herzhz/35mm-trrs-4-pole-for-hifiman-balanced-male-plug-jack-35">3.5mm TRRS 4 pins male plug</a>, 2 @ Rp 12.500 | 25.000 |
| <a href="https://www.tokopedia.com/optimuspri/joyseus-2-in-1-coiled-data-cable-1-m-micro-usb-type-c">Joyseus 2 in 1 coiled data cable 1M (micro USB & type C)</a> | 45.000 |
| <a href="https://www.tokopedia.com/3mtapes/3m-sj-5306-bumpon-clear">3M SJ-5306 Bumpon Clear</a> | 18.000 |
| <a href="https://www.tokopedia.com/isee/new-091-091-inch-inchi-128x32-oled-white-display-lcd-module-slim">128x32 pixel OLED white display</a> | 35.000 |

*The list is excluding shipping cost and wrong parts those I purchased. Some items were purchased more than the need for spare/stockpile. If the whole things counted, it reached almost 2 million rupiahs.*

## Firmware

UNK firmware code is now registered under QMK's handwired section.

### Preparation
```
$ git clone https://github.com/qmk/qmk_firmware.git
$ ./util/qmk_install.sh
```

### Compile
```
$ make handwired/unk/rev1:default
```

### Flashing the left half

Press the reset button twice and fast, then:
```
$ sudo avrdude -p atmega32u4 -c avr109 -U ./.build/handwired_unk_rev1_default.hex -P /dev/ttyACM0

```

### Flashing the right half

Uncomment the line that state `#define MASTER_LEFT` in `keyboards/handwired/unk/rev1/config.h`, then:

```
$ make handwired/unk/rev1:default
```

Press the reset button twice and fast, then:

```
$ sudo avrdude -p atmega32u4 -c avr109 -U ./.build/handwired_unk_rev1_default.hex -P /dev/ttyACM0
```
## Usage

- `LOWER` + `Home` to switch to Qwerty layout
- `LOWER` + `End` to switch to Colemak layout

## Useful links

The sources I read and inspired me for building this keyboard:

- Keyboard layout editor, http://www.keyboard-layout-editor.com/
- Plate builder, http://builder.swillkb.com/
- Laser cutting service, https://lasergist.com/shop/lasergist/
- Acrylic laser cutting service, https://www.tokopedia.com/kencanagrafikama/akrilik-acrylic-3mm-potongan-custom-putih-susu
- Pro micro official guides/FAQ, https://learn.sparkfun.com/tutorials/pro-micro--fio-v3-hookup-guide/troubleshooting-and-faq
- Promethium51, https://priyadi.smugmug.com/Mechanical-Keyboard/Promethium-Keyboard/Build-Log/n-4fFNQC
- Handwiring split guide based on lets_split, https://johannes-jansson.github.io/projects/2018/07/23/hand-wiring-lets-split.html
- Handwiring guide, https://geekhack.org/index.php?topic=87689.0
- https://www.reddit.com/r/olkb/comments/5s8q76/help_pro_micro_pinout_for_qmk/
- Thinkpad trackpoint,
  - https://electronics.stackexchange.com/questions/189790/determining-trackpoint-pinout
  - https://github.com/qmk/qmk_firmware/tree/master/keyboards/handwired/trackpoint
  - https://github.com/alonswartz/trackpoint
  - https://github.com/alonswartz/trackpoint#tmk-firmware-changes-and-tweaks
  - https://docs.qmk.fm/#/feature_ps2_mouse
  - https://deskthority.net/wiki/TrackPoint_Hardware#ThinkPad_R61_TrackPoint
  - https://community.keyboard.io/t/trackpoint-mod-ii-a-new-guide/3663
- Pro micro built-in LEDs, https://www.electronicsweekly.com/blogs/engineer-in-wonderland/arduino-micro-direct-access-board-leds-2017-08/
- TRRS in  Pro Micro + QMK, https://beta.docs.qmk.fm/using-qmk/hardware-features/feature_split_keyboard
- Blackberry trackpad, https://vlukash.com/2019/01/15/trackpad-in-keycap-corne-crkbd-keyboard/
- Adding layers, https://thomasbaart.nl/2018/12/06/qmk-basics-how-to-add-a-layer-to-your-keymap/
- Layers, https://jayliu50.github.io/qmk-cheatsheet/
- VIA configurator, https://gist.github.com/nooges/5878b2648b6daeefb5c44d4ec16bf912


## Build Logs

### 20200612

The wish was occured a loooooong time ago but I began to (seriously) design the keyboard from this date. I also started to purchase the parts that I need to build the keyboard.

### 20200615

Pro micro clones arrived. Small important things.

<img width="650" src="/images/promicro.png">

### 20200617

The plates arrived. The top plate's thickness is 1.5mm and the bottom plate is 2mm. I'm a bit surprissed that these plates were quite heavy. Heavy (p)unk keyboard!

<img width="650" src="/images/plate-1.jpg">
<img width="650" src="/images/plate-3.jpg">

### 20200619

I put carbon-like sticker on the inner side of bottom plate to avoid shorting from the wiring.

<img width="650" src="/images/split-magnet.png">

Also there were four strong neodymium magnets to help the two parts stick together.

<img width="650" src="/images/split-magnet.gif">

### 20200620

Handwired. Pardon my mediocre soldering skill.

<img width="650" src="/images/handwired.png">

<img width="650" src="/images/pro-micro-testing.jpg">

### 20200622

Fully working left half. I was still playing and learn how to work with QMK firmware code.

<img width="650" src="/images/left-half-test-on-game.gif">

<img width="650" src="/images/writedown.jpg">


### 20200623

DO NOT USE SUPER GLUE TO GLUE YOUR SWITCHES TO THE PLATE.

Oh boy, just don't. I'm a big fan of super glue as it's very versatile, strong adhesive, and quick-drying. Super glue has this kind of vapor that makes white mark around the surface that you glued on. My super glue is the strong one. This marks got into my switches' housing, contaminated the copper contacts, and makes it unusable!

Because of my stupidity, I've to unplugged all the switches. I've to redo all the works that has been done on switches: matrix soldering and gluing. Plentiful of switches become the victims. Huft!

<img width="650" src="/images/unplugged-switches.jpg">

Use hot glue instead. Hot glue is quite strong to hold your switches but very easy to remove in case that you want to change some bad switches.

I'll use super glue only to things that need strong hold on the plate like USB-C port. reset tactile switch,  TRRS jack.

I've seen some videos of making handwired keyboard and got some idea for better handwiring. I'll be using ~~0.35mm magnet coil wire~~ single core copper wire.

### 20200624

Need to cut out the height of the switches and stabilizer so I can push the  thickness limit. It'll be using 6mm spacer. The original uncut version is on the left. The middle is the common cut. The right one was forced to be cut like that to make more room for the neodymium magnet.

<img width="650" src="/images/switch-cut.jpg">

I noticed lately that I purchased the wrong stabilizer. I should use the plate mount version instead of PCB mount.

<img width="650" src="/images/stabilizer-cut.jpg">


I reglued the switches back into the plate using hot glue. Quite easy but messy. Note that you have to clean the "spider web" things from the hot glue. If this thing makes it way into your switch housing or the stabilizer, it'll makes it feels terrible.

<img width="650" src="/images/hot-glue.png">

### 20299625

While waiting for the wire to be arrived, I made a pair of wrist rest from an unused one.

<img width="650" src="/images/wrist-rest-1.jpg">
<img width="650" src="/images/wrist-rest-2.jpg">
<img width="650" src="/images/wrist-rest-3.jpg">

The TRRS cable was also being made.

<img width="650" src="/images/trrs-1.png">

Turned out that the TRRS jack is too thick for 6mm spacer. I need to set apart the jack port from the PCB.

<img width="650" src="/images/components.png">

### 20200627

Fully handwired.

<img width="650" src="/images/fully-handwired.jpg">

Components placement. Glued with super glue (except for the Pro micros).

<img width="650" src="/images/components-2.jpg">

Bumpons added as rubber foot. Also another neodymium magnet to force the wrist rest stick with the board.

<img width="650" src="/images/bumpon.jpg">

Multimeter tool is a must here. Need to check the entire wiring carefully.

<img width="650" src="/images/multimeter-testing.png">

I found an inverted diode and fixed it.

<img width="650" src="/images/inverted-diode.jpg">

Forgot that the neodymium magnet's coating is conductive so I put the sticker on these too.

<img width="650" src="/images/magnet-shorted.png">

Entering programming phase. QMK is fun. I'm using deltasplit75 as the base.

<img width="650" src="/images/firmware-testing.gif">

Side views. You can see that the reset button is easy to reach with your nail.

<img width="650" src="/images/side-view.jpg">
<img width="650" src="/images/side-view-2.jpg">


All the keys has been tested.

<img width="650" src="/images/keyboard-checker.png">

Finished!

<img width="650" src="/images/finished.png">

### 20200629

My first day using UNK at work, https://www.youtube.com/watch?v=z-LAlFVbLv8. This is the first time ever I typed on split keyboard for long hours.

<img width="650" src="/images/satisfied.jpg">

I also send <a href="https://github.com/qmk/qmk_firmware/pull/9571">pull request</a> to QMK to register UNK under handwired section.


### 20200630

<a href="https://github.com/qmk/qmk_firmware/commit/6d6340a82b3ed61f5dd2a40dac78712d7bd736fd">My pull request has been merged.</a> I think the first iteration of UNK is done for now. Thanks!

### 20200704

I've updated the layout and plate design. UNK is now supporting 104 keycaps set by resizing its space keys to 2u. `+` and `Ent` keys from the numpad can be used here. On the other hand left `Fn` and `Del` keys got bigger. DSA profile is preferred for best suitability.

### 20200706

UNK is now having mini OLED display so I'll know which layer is on. Just like UHK, eh?

<img width="650" src="/images/oled1.png">

<img width="650" src="/images/oled2.png">

### 202007018

I made a trackpoint module for the UNK. The trackpoint sensor was taken from a dead Thinkpad X201 keyboard.

<img width="650" src="/images/trackpoint1.jpg">

<img width="650" src="/images/trackpoint2.jpg">

It has two attached mode:

#### By using your index finger

<img width="650" src="/images/trackpoint3.jpg">

#### By using your thumb

<img width="650" src="/images/trackpoint4.jpg">

### 20230318

After two years of extensive use, the switches eventually fail because of dust. I got tempted to replace the troubled switches but found that it's not easy to remove the hot glue. The original hole is 14.1mm and it's too loose for the switches. That is why hot glue came in. After thinking about it for a while, I decided to start over and revise the hole size to 13.7mm so it will be stiff enough to hold the switches.

You can find the revised SVG here https://github.com/herpiko/unk/blob/master/unk-plate-layout.rev1.1.svg.

I also replaced the Cherry MX Brown switches with Kailh Box which is have some advantages over the previous one:
- Less tactile, which is my preference
- IP56 water and dust proof. The protection is done by two brilliant solutions:
  - The boxy keycap stem prevents dust coming into the switch.
  - The gold crosspoint part got surrounded by a plastic box and exposing only the tiny part that will be touched by keycap stem.
- The bottom housing is shorter and fit nicely under 6mm space between the two plates. I don't have to cut the bottom part anymore.

## Disclaimer

I'm not responsible for the inaccuracy of the build that based on my design. I've tested it but your mileage may vary.

## License

All images and SVG file that I produced are under CC-BY-SA. QMK related code is under GPL. The QMK Firmware logo is a trademark of QMK.
