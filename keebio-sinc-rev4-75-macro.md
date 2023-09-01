# Keebio <em>Sinc Rev. 4</em> - 75% staggered split with XT-style function cluster

My first mechanical daily driver was the [Kinesis Freestyle RGB](https://gaming.kinesis-ergo.com/product/freestyle-edge/). While a very flexible, comfortable, and fun board, I never liked the bottom row layout with its non-standard 3.5u spacebars. Like many compact boards, it also lacked a third right modifier. 

I also prefer to silent switches to the Freestyle&rsquo;s soldered-in Cherry MX Browns.

[Keebio](https://keeb.io) to the rescue! I also own a couple version of the 65% ancestor of the Sinc: the [Quefrency](https://keeb.io/collections/quefrency-split-staggered-65-keyboard/products/quefrency-rev-5-pcbs-hotswap-65-65xt-split-staggered-keyboard).

I am  building a [Keebio Sinc Rev. 4 hotswap split keyboard](https://keeb.io/collections/sinc/products/sinc-rev-4-split-staggered-75-keyboard). It is a programmable with [QMK](https://qmk.fm/)/[VIA](https://usevia.app/) firmware, Eventually it will have two encoders soldered in the corners.

-----

Here is a picture of it with [Drop + biip MT3 Extended 2048](https://drop.com/buy/drop-biip-mt3-extended-custom-keycap-set) keycaps, with some color accents from [Drop + Zambumon MT3 Serika R2](https://drop.com/buy/drop-zambumon-mt3-serika-custom-keycap-set):

![Sinc Rev. 4 with MT3 Extended 2048 and MT3 Serika R2 keycaps](images/sinc-rev4-mt3-extended-serika.jpg)

-----

Thinking about getting this [NicePBT Type 6](https://cannonkeys.com/products/nicepbt-type-6) set from CannonKeys:

![Keebio Sinc Rev. 4](images/keebio-sinc-rev4-75-macro.png)

<http://www.keyboard-layout-editor.com/#/gists/176fb4b77b2ae1a718e536f923f7a414>

-----

A <strong>94-key QWERTY split staggered keyboard layout</strong>, inspired by Apple, IBM, and Sun keyboards.

* 2u <kbd>Backspace</kbd>
* 2.25u left <strong>SpaceFn</strong> key
* Split right space: convex 1.25u + 1.5u <kbd>Command</kbd> / <kbd>Win</kbd> / <kbd>◆</kbd> key
* Minimum mod width: 1.25u
* 0.5u blocker to left of arrow cluster
* F-row mimics macOS function keys
  * <kbd>Scroll Lock</kbd> / <kbd>F14</kbd> and <kbd>Pause</kbd> / <kbd>F15</kbd> in <kbd>F1</kbd> & <kbd>F2</kbd> position and handle screen brightness
  * Positions <kbd>F3</kbd> & <kbd>F4</kbd> are <kbd>F16</kbd> & <kbd>F17</kbd>
    * Via macOS System Preferences _Keyboard_ pane, I can assign these to:
      * _Show Notification Center_
        * Mission Control is better handled with <kbd>Control</kbd> + arrow keys
        * This key was used for Expose back in the day, anyway!
        * When modified with <kbd>Command</kbd>, it will _Show Desktop_
      * _Show Launchpad_
* Access to all keycodes found on a full-size US English Apple keyboard
  * Except a real <kbd>Fn</kbd> / “Globe” key
* Access to all Windows keys except <kbd>Menu</kbd>
  * Use <kbd>Shift</kbd> + <kbd>F10</kbd> instead
* Left-side: Navigation cluster on layer
* Right-side: Full Apple numeric keypad on layer
  * <kbd>Return</kbd> is <kbd>Enter</kbd>
  * <kbd>N</kbd> is <kbd>Clear</kbd> / <kbd>Num Lock</kbd>
  * <kbd>=</kbd> is Numpad <kbd>=</kbd>
* <kbd>Home</kbd> key in <kbd>F13</kbd> position
  * <kbd>Print Screen</kbd> / <kbd>F13</kbd> on layer
* <kbd>Escape</kbd> is <kbd>Eject</kbd> key on layer
* [ ] 2 rotary encoders soldered in corners


## Layout options

* 1.5u <kbd>Backspace</kbd>
* F-row <kbd>Escacpe</kbd> key replaced with <kbd>Help</kbd>, <kbd>Print Screen</kbd>, <kbd>⏻</kbd>, or blank keycap
* <kbd>Print Screen / SysReq</kbd> key in <kbd>F13</kbd> position
* <kbd>Scroll Lock</kbd> on <kbd>Fn</kbd>+ <kbd>F8</kbd>, seen as <kbd>F14</kbd> on macOS
* <kbd>Pause</kbd> on <kbd>Fn</kbd> + <kbd>Stop</kbd>, seen as <kbd>F15</kbd> on macOS
* <kbd>F16</kbd> … <kbd>F19</kbd> on <kbd>Fn</kbd> layer of left column macro keys
* <kbd>Delete</kbd> key to right of <kbd>Backspace</kbd>
* Key to right of <kbd>Up</kbd> is <kbd>End</kbd> on tap, and <kbd>Fn</kbd> on hold
* <kbd>`</kbd> key is <kbd>Escape</kbd> on layer
* F-row <kbd>Escacpe</kbd> key replaced with <kbd>Help</kbd>, <kbd>Print Screen</kbd>, <kbd>⏻</kbd>, or blank keycap
* [ ] 10 [Sun fun cluster](https://deskthority.net/wiki/Fun_cluster#Sun) layer on macro section:
  * <kbd>Stop</kbd> <kbd>Again</kbd>
  * <kbd>Props</kbd> <kbd>Undo</kbd>
  * <kbd>Front</kbd> <kbd>Copy</kbd>
  * <kbd>Open</kbd> <kbd>Paste</kbd>
  * <kbd>Find</kbd> <kbd>Cut</kbd>
  * <kbd>Help</kbd> key
* [ ] Hack firmware to spoof an Apple-manufactured board to access true <kbd>Fn</kbd> “Globe” key

------

## References

![Sun Compact 1 layout from _SPARCstation Voyager: Just the Facts_](images/Sun-Compact-1-layout.png)

![Photo of Sun Compact 1 keyboard with Unix layout](images/sun-compact-1-unix-layout-keyboard.jpg)

* _Deskthority Wiki_: [Sun Compact 1](https://deskthority.net/wiki/Sun_Compact_1).
* [_SPARCstation Voyager: Just the Facts_](https://janit.iki.fi/docs/SPARCstationVoyagerJTF.pdf). Sun Microsystems, March 1994.
* eBay listing: [Sun 320-1196 Compact 1 Keyboard, Mini-Din, US/UNIX Layout, Vintage Sun](https://www.ebay.com/itm/165992674326)
