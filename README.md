# MPRS8
A Rust compiler for the 8-bit family of Microchip PIC microcontrollers.

Rust is being heralded as the language that might finally beat C out of the embedded systems market, and yet it still isn't available for the PIC devices, one of the most popular line of hobbyist microchip processors. This compiler would be an alternative to the XC8 compiler provided by Microchip (or the third-party HI_TEC compiler), allowing developers to write Rust code instead of C code for the PIC. If this exploration is successful, it would branch into the 16-bit family and 32-bit family of microcontrollers as well.

For now, this repo is just a reminder to myserlf to explore this possibility. Does Rust generate intermediate assembly? Using the include files provided with MPASM, it might not be too difficult to modify the instruction set it generates.
