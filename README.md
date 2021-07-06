This is a fork of
https://github.com/adafruit/Adafruit-GFX-Library/tree/master/fontconvert
I've added the option to specify a set of glyphs to include in
addition to the existing options of ending character number or
character range. It's invoked by
>     fontconvert fontfile size -s stringofglyphstoinclude
This generates the bitmaps for only the glyphs in that string
(duplicates are ignored) and outputs the minimal range of glyphs that
includes all the glyphs in the string.
