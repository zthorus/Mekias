# Mekias
Mekias, Z80 assembler for the ZX Spectrum 

Mekias is a Z80 assembler for the ZX Spectrum. It uses the BASIC editor and allows to mix BASIC and assembly languages in the
same program file (as the Acorn BBC did). Assembly code is put in lines of REM. The compilation is done whenever the RUN key is pressed.
Mekias was written circa 1986. Unfortunately, I have lost its source code in BASIC (using POKE, READ and lots of DATA lines).
The .z80 snapshot file provided in this repository has been taken after the installation of Mekias at address 40000 (in decimal). A short
example of Z80 assembly program is provided. After dissassembly. I have recently tried to reverse-engineer what I wrote 32 years ago
(funny exercise !). I put my notes in an attached file. It is still incomplete, some of the parts have not been analyzed yet. The sad thing
is I spent time developing a tool that I have never used actually...

A quick Mekias manual:
* The assembly program must start with the character { followed by the address (ORG) of the program in decimal.
* The assembly program ends with the character } . 
* All numerical arguments od instructions are in decimal (because I hated hexadecimal).
More details are in the attached notes.
