# Mendes' Mac-centric Ergodox EZ keymap

## Motivation

This is based off [@gabrielpoca][@gabrielpoca]'s changes to the Ergodox
EZ Keymap. Gabriel's changes make it really smooth to transition from the
default Mac keyboard to an Ergodox. However, I am also a vimmer and have
remapped my keys to allow `hjkl`-style navigation by changing the symbol layer
to use this.

This is Gabriel's original README. Jump to the end to see my changes:


Essentially, I wanted to switch to a layout that was less jarring than the default Ergodox EZ layout, and did not require finger gymnastics to perform common OS X shortcuts (most of which involve the CMD (LGui) key).

## How is it different from the default Ergodox EZ layout?

This layout more closely resembles that of the Mac keyboard, and has some other goodness baked in. Here is a rundown of what that means:

### Mac-like changes

- **The key to the left of "1" is "~" instead of "=".**
- **The key to the right of "0" is Backspace instead of "-"** (misleadingly labeled "delete" on the Mac's keyboard). There was no room to fit in "-" and "=" between "0" and Backspace, unfortunately.
- **The key to the left of "Q" is Tab instead of Delete.**
- **The rightmost big key on the left thumb is CMD (LGui) instead of Backspace.**

### Other changes

- **The button to the left of "A" is Ctrl/Esc instead of Backspace.** This is actually how I have the keyboard on my Macbook set up to be, since it's loads more convenient than a  CAPS LOCK key. This is the Ctrl key I find myself using most.
- **The key to the right of "5" and the key to left of "6" are "[" and "]", respectively, instead of Left and Right.** There is a more convenient set of Left and Right already present. Truth be told, I don't really use these keys, as they are a stretch to reach.
- **The Toggle L1 keys have been replaced by the otherwise displaced "-" and "=".** They are laid out, left-to-right, in the same order as on the Mac keyboard. Honestly, they are not terribly conveniently placed, and their placement might change in a later version. I found that I did not toggle L1 frequently at all, and found using the momentary keys to access L1 to fit my workflow better.
- **The "~"/L1 key in the bottom-left is now just momentary L1.** The "~" key was moved to the top-left as mentioned before, and I like to keep my multi-use keys to a minimum due to the latency for them to switch from "press" to "hold."
- **The Home and End buttons have been shifted up on the left thumb, and Shift inserted below them.** This makes doing Shift-5 and other such combinations less painful.
- **The Page Up and Page Down buttons have been shifted up on the right thumb, and Alt was moved from above them to below them.** I use Alt more than Page Up or Page Down (mostly in terminal applications), and thought that it deserved a more accessible location.

## Mendes' additions

- **The symbol layer has arrow keys where the `hjkl` keys are** - I'm a vimmer
  and I also never felt the need for a numpad style. So all the numbers in the
  symbol layer have been removed and replaced with vim-style navigation arrow
  keys.

**I'm always open to feedback and/or suggestions!**

[@gabrielpoca]: https://github.com/gabrielpoca/qmk_firmware/blob/0cdfdfb17e8706fbdf126d03cc82305d221ba632/keyboards/ergodox_ez/keymaps/gabrielpoca/readme.md
