
# Virtual Pinball Machine

This repo contains information about building a virtual pinball machine.

# Cabinet & Backbox

Original WPC style cabinet sketchup plans can be found [here](https://github.com/jonaskello/wpc-cabinet). In order to work as a virtual cabinet these plans will have to be customized. These items will affect the cabinet woodwork so they need to be determined before cutting the wood:

* Screens
* Buttons & External Connections
* Plunger
* Ventilation
* Speakers

http://www.space-eight.com/Downloads.html

# Screens

The screens are the most important parts because they are only avialble in certain fixed sizes. So the cabinet need to built to fit the screens which means we need to select screens before building the cabinet. In order to fit screens they may have to be decased, which means the outer plastic is removed. Some screens cannot be decased because they have no internal metal holding the screen together. So make sure your model can be decased.

In order to fully simulate a WPC pinball machine three screens are needed; Playfield, Backglass, DMD.

## Screen Considerations 

### Playfield Screen

* Low input lag.
* Good viewing angle.
* Inner width of a standard cabinet with 3/4" plywood is **20-1/2"** (22" - 2 * 3/4").
* Inner width of a standard cabinet with 18 mm plywood is **522,8 mm** (22 * 25,4 - 2 * 18).
* With a slide-in groove of 12 mm width becomes **546,8 mm** (522,8 + 12 * 2).

If the playfield screen do not fit in the cabinet you have these options:

* Decase the screen. If not enough, can be combined with the below options.

* Route a groove on each cabinet side and slide in the screen from the back.
    * PRO: Genuine/authentic size.
    * PRO: Standard lockdown bar.
    * PRO: Standard playfield glass.
    * PRO: Covers the edges of the screen.
    * CON: Hard to remove monitor for service.

* Build the cabinet wider than standard and get a [custom lockdown bar](http://virtuapin.net/index.php?main_page=product_info&cPath=3&products_id=34).
    * PRO: Easy to remove monitor for service (can make it foldable like a regular playfield).
    * CON: Not genuine/authentic size.
    * CON: Custom lockdown bar.
    * CON: Custom playfield glass.
    * CON: Need to cover the edges of the screen (black borders on the side).

See [this page](http://mjrnet.org/pinscape/BuildGuideV2/BuildGuide.php?sid=playfieldTV) for more discussion about these options.

### Backglass Screen

* Static image displayed from front so input lag or viewing angle is not that important.
* Make sure it has VESA mounting.
* The inner width of a standard backbox with 3/4" plywood is **27-1/4"** (28-3/4" - 2 * 3/4").
* The inner width of a standard backbox with 18 mm plywood is **694,25 mm** (28-3/4" * 25,4 - 2 * 18).
* With a slide-in groove of 12 mm width becomes **718,25 mm** (694,25 + 12 * 2).
* The inner height of a standard backbox with 3/4" plywood is **27"** (28-1/2" - 2 * 3/4").
* The inner height of a standard backbox with 18 mm plywood is **687,9 mm** (28,5 * 25,4 - 2 * 18).
* The speaker panel including it's top H bracket covers 8-1/4" (209,55 mm) of the backbox's inner height which leaves 17-3/4" (450,85 mm) to be covered by the backglass screen and additional spacing.

If the backglass screen do not fit in the backbox you have these options:

* Decase the screen. If not enough, can be combined with the below options.
* Route a groove on each backbox side and slide in the screen from the top.
* Build the backbox wider than standard.

Ideas for covering the height not covered by the backglass monitor:

* Build speaker panel width non standard height, see example in this [thread](http://vpinball.com/forums/topic/new-build-complete/).
* Put a glass (acrylic or regular tempered) in front with black borders, mounted as a backglass on a regular machine.
* Put some plywood over and under the screen?

### DMD Screen

* Either use a real DMD such as [pindmd](http://www.pindmd.com/) or a monitor. 
* Ideally a special size monitor would be used but may be hard to find?
* TODO: Size of DMD viwable area.

## Screen Models

| Screen    | Model             | Inch    | Viewable (mm)  | Case (mm) | Case fit (mm) | Decased (mm) | Resolution       | Link    |
|:--------- |:----------------- |:--------|:-------------- |:----------|:------------- |:------------ |:---------------- |:------- |
| Playfield | Philips BDM4350UC | 42.51"  | 941.2 x 529.4  | 968 x 562 | -39,2         | Unknown      | 4K (3840 x 2160) | [Link](http://download.p4c.philips.com/files/b/bdm4350uc_00/bdm4350uc_00_pss_engph.pdf) |
| Playfield | PROLITE X4071UHSU-B1 | 40.0"  | 879.5 x 487.0  | 906.5 x 520.5 | +2,3         | Unknown      | 4K (3840 x 2160) | [Link](https://iiyama.com/gl_en/products/prolite-x4071uhsu-b1/) |
| Backglass | Philips 323E7QDAB | 31.5"   | 698.4 x 392.85 | 703 x 431 | -8,75         | Unknown      | 1920 x 1080      | [Link](https://www.philips.co.uk/c-p/323E7QDAB_00/lcd-display/specifications) |


# Buttons & External Connections

## Types of buttons

* Flipper buttons
* Start buttons

## Cabinet Side

* Left Flipper Buttons
* Right Flipper Button
* Left Magna Save Buttons
* Right Magna Save Buttons

## Cabinet Front

* Start
* Coin
* Exit 
* Credits?
* Instructions?
* Launch ball

## Cabinet Bottom

* On/Off power switch
* USB connection to connect a keyboard easily.
* Headphones?

## Cabinet Back

* External power connector.

## References

http://www.davesclassicarcade.com/vpinball/vpinball6.html#buttons

# Plunger

TODO!

# Ventilation

Fans in the cabinet bottom at the front to take in air, and fans at the cabinet back to exhaust air. 

# Speakers

Some really nice information about pinball speaker replacement can be found [here](http://dziedzic.us/wpc_speaker_replacement.html).

For games with a wooden display panel with a dot matrix display purchase a pair of 5-1/4 inch coaxial speakers. Back box speakers should be 4 ohm impedance and be rated to handle at least 25 watts RMS power.

 Go with woofer that has the best low-end response. Look for a low frequency response of at least 35 Hz; a smaller number is better here. Purchase a woofer rated to handle at least 25 watts RMS. 

Since we're replacing the existing "wide range" cabinet speaker with a woofer we'll want to ensure that only low frequency sounds are sent to the cabinet speaker. Pre-assembled subwoofer crossover.

# Speaker Panel

As mentioned [here](https://nickpinball.wordpress.com/tag/virtual-cabinet/), to get an authentic feel, purchase a Williams original speaker panel as avaialble [here](http://www.ministryofpinball.com/en/wpc95-speaker-panel-with-chrome-williams-logo.html).

To mount the speaker panel we need:

* Bottom bracket
* Top H bracket
* Mounting brackets in the backbox

# Internal Power Connectors

* Surge Protector

# PC

## Case

For mounting the PC we don't need a full case. An open "test bench case" as used [here](http://thingsnotleftunsaid.blogspot.se/2015/06/virtual-pinball-machine-build_30.html) will be enough and maybe better from a cooling standpoint. Some examples:

* [QDIY-PC-JMK6](
https://www.aliexpress.com/item/QDIY-PC-JMK6-ATX-Aluminum-Alloy-Horizontal-Full-Open-Computer-Case-Chassis/32360817006.html)

* [QDIY PC-D60](https://www.aliexpress.com/item/QDIY-PC-D60-On-Sale-Personalized-Transparent-Acrylic-Water-cooled-Wide-Open-Standard-ATX-Chassis-Nude/1783227644.html)

* [L-101 Multi-Function](https://www.aliexpress.com/item/L-101-Multi-Function-263-470-130-mm-Centralized-Computer-Cases-Towers-Biggest-Support-For-Main/32743197755.html)

* [DIYPC Alpha-DB6](https://www.newegg.com/Product/Product.aspx?Item=N82E16811353001)

# Keyboard controller

TODO!

# Nudge

TODO!

# Tactile drivers

TODO!

# References

http://thingsnotleftunsaid.blogspot.se/2015/06/virtual-pinball-machine-build_30.html

# Trim & brackets

## Cabinet

TODO!

## Backbox

TODO!
