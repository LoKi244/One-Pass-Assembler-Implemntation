Problem Statement:

To implement the design of a 1-pass assembler.
Assembler is system software which is used to convert an assembly language
program to its equivalent object code. The input to the assembler is a source
code written in assembly language (using mnemonics) and the output is the
object code. The design of an assembler depends upon the machine
architecture as the language used is mnemonic language.
A one pass assembler generates code and for any undefined symbols, leaves a
slot to be filled in, and remembers it in a table or other data structure. Then
where the symbol is defined, it fills in its value at the right place or places, using
the information from the table.

One-pass assemblers are used when

It is necessary or desirable to avoid a second pass over the source program, the
external storage for the intermediate file between two passes is slow or is
inconvenient to use.

