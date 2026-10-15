# gadgets-complex

Complex for the gadgets of [polpo](https://github.com/polpo-system/polpo): an example of how to
program a model gadget of your own, a complex number with the attributes Real and Imag that visual
gadgets can show and change. It is meant to be read: src/Complex.Mod.

```
portia.Install gadgets-complex
```

## Using

    Gadgets.Insert TextField Complex.New ~    a text field showing a new complex number

## What is here

    src/Complex.Mod         the example
    tools/Complex.Tool
    test/ComplexTest.Mod

The source comes from ETH Linux Oberon (OLR, 2017-06-18), converted from an Oberon text to plain
text; the first commit has it unchanged. It compiles unchanged with all five of polpo's compilers
(x86, ARM, ARMv7, RISC-V, MIPS).

## Tests

    ComplexTest.Run      1 check: the model made; it needs the desktop's display

The license is GPL-3 (`LICENSE`); the code comes from ETH Oberon, whose license (`LICENSE.ETH`)
asks to keep its copyright notice and conditions, which `LICENSE.ETH` does.
