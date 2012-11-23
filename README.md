MIPS-datapath
=============
Author: Peihsun (Ben) Yeh

A MIPS datapath with 5 stage pipeline complete with branching and forwarding

This was written in VHDL, and can be run in a HDL simulation program such as Modelsim. 

The instructions being simulation is in IFETCH.VHD. The current instructions are

and $4 $3 $1

or $8 $1 $4

sub $3 $4 $4

add $5 $4 $3 

and $1 $6 $7

These instructions are intended to show forwarding behavior. 

Included in the repository are two .png showing the correct datapath behavior for the program above as well as another program intended to exhibit branching. 
