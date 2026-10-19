# vectests

A sandbox for learning to program the Vectrex, the 1982 vector-display home console, in 6809 assembly or C.

## What it does

Nothing yet: the repository was opened in 2020 to hold small Vectrex programming experiments, and no code has been committed to it.

## Status

Empty placeholder. No program, build script or test is in the repository.

## Getting started

There is nothing to build yet. When experiments land here, the intended loop is the usual one for Vectrex homebrew:

1. Assemble a cartridge image, for example with [asm6809](https://www.6809.org.uk/asm6809/): `asm6809 -B -o hello.bin hello.asm`. For C, [CMOC](http://perso.b2b2c.ca/~sarrazip/dev/cmoc.html) targets the Vectrex as well.
2. Run it in an emulator, for example [MAME](https://www.mamedev.org/): `mame vectrex -cart hello.bin` (MAME needs the Vectrex system ROM, which is not provided here).

[VIDE](http://vide.malban.de/), Malban's Vectrex IDE, bundles an assembler, a C compiler and an emulator in one tool.

## Configuration

None.

## Licence and credits

Released under the [MIT licence](LICENSE).
