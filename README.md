# Mekias
Mekias, Z80 assembler for the ZX Spectrum 

Mekias is a Z80 assembler for the ZX Spectrum. It uses the BASIC editor and allows to mix BASIC and assembly languages in the
same program file (as the Acorn BBC did). Assembly code is put in REM lines. The compilation starts whenever the RUN key is pressed.
Mekias was written circa 1986. Unfortunately, I have lost its source code in BASIC (using POKE, READ and lots of DATA lines).
After dissassembly. I have recently tried to reverse-engineer what I wrote 32 years ago (funny exercise !). I put my notes in an attached file.
It is still incomplete, some of the parts have not been analyzed yet. The sad thing is I spent time developing a tool that I have never used actually...

Files:
======

Mekias_as_installed.z80: Example of assembly code within Basic REM lines, with Mekias installed in RAM. Typing RUN automatically triggers the
                         compilation of the assembly code. Note: this is an old .z80 file format, which seems not compatible with
                         the "FUSE" Spectrum emulator.
                         
4_pix_hscroll_3.sna: Another example (4-pixel left-to-right scrolling routine).

Mekias_code_detail.txt: Source code of Mekias, as disassembled from an old .z80 file, with comments. Everything is not commented yet, and
                        some parts of the Mekias code are missing ; in particular the interrupt routine that is triggered whenever the RUN
                        command is typed. This routine initializes the variable and starts the compilation
