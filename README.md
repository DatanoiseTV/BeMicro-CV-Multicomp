BeMicro-CV-Multicomp
====================

Pick-and-mix to create your own custom microcomputer on the BeMicro CV FPGA Board.


Credits
=======
Original credits to Multicomp go to Grant Searle, who initiated the project
in order to make a low-cost computer prototyping solution for the EP2C5T144C8N
FPGA board. I ported it to the BeMicro-CV to allow the concept to grow bigger.

Roadmap
=======
I am planning to add more than the currently available 4K of internal SRAM.
Eventually, I will make a DDR3 Interface, which will behave like SRAM, so
the full 1GiB of the Board could be theoretically used.

Memory Map
==========
* E000-FFFF: Basic ROM for 6502
* FFD0-FFD1: UART Interface
* FFD2-FFD3: Graphics Interface
* FFD8-FFDF: SD-Card
