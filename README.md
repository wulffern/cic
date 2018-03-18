# cic
cIc collection

# Introduction
cIcCreator was started as an exploritory effort to try and see if I could simplify how we make ICs. It's been 30 years of development, and we still draw
schematics, and do manual layout. We must find something better.

# Submodules

## ciccreator
The heart of cic is the ciccreator, it takes a JSON input file, a rule file and outputs layout in GDS or a CIC file.

## oscic - Open Source cIc
Building blocks that can be used for designing analog circuits

## cic2verilog
Reads the cic output file and outputs verilog wrappers that can be used in verilog simulations

