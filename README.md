# kid
6hp trianlge-core vco

No transistor matching, tune it in the same way as you would every other expo converter of this style. There's lots of info on how to tune an analogue oscillator that's better written than I will ever do.

Trim the sine by ear, or use a signal analyser to trim out the 3rd harmonic with R27. R29 has minimal effect, so don't drive yourself mad with it.

The saw trims trim out the bump in the saw, plug it into a scope and trim until you're happy.

Seat the tempco in contact with the sot363-6 transistor pair and stick some thermal paste on top of them.

This is largely an adaptation of the stroh pico vco with some changes to the expo converter.
