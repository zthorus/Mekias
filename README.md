# Mekias
Mekias, Z80 assembler for the ZX Spectrum 

Mekias is a Z80 assembler for the ZX Spectrum. It uses the BASIC editor and allows to mix BASIC and assembly languages in the
same program file (as the Acorn BBC did). Assembly code is put in REM lines. The compilation starts whenever the RUN key is pressed.
Mekias was written circa 1986. Unfortunately, I have lost its source code written in BASIC (using POKE, READ and lots of DATA lines).
After dissassembly, I have tried in 2016 to reverse-engineer what I wrote 32 years ago (funny exercise !), then again in 2026 to clarify some details. I put my notes in an attached file.
The sad thing is I spent time during my teenage years to develop a tool that I eventually never used to develop software afterwards.

Files:

- Mekias_as_installed.z80: Example of assembly code within Basic REM lines, with Mekias installed in RAM. Typing RUN automatically triggers the
                         compilation of the assembly code (a beep is emitted when the compilation is done with no error). Note: this is an old .z80 file format, which seems not compatible with
                         the "FUSE" Spectrum emulator.
  
- Mekias_as_installed.sna: Same as before in sna (snapshot) format. This one works OK on FUSE.
                         
- 4_pix_hscroll_3.sna: Another example (4-pixel left-to-right scrolling routine).

- Mekias_code_detail.txt: Source code of Mekias, as disassembled from an old .z80 file, with comments.
