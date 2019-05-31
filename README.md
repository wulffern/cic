# cic
cIc collection

# Introduction
cIcCreator was started as an exploritory effort to try and see if I
could simplify how we make ICs. The industry has been making
integrated circuits for more than 30 years, and we still draw
schematics, and do manual layout. We must find something better.

# Submodules

## ciccreator - Beta software
The heart of cic is the ciccreator, it takes a JSON input file, a rule file and outputs layout in GDS or a CIC file.

## oscic - Open Source cIc - Alfa software
Building blocks that can be used for designing analog circuits

## cictools - Useful tools - Beta software
I discovered after writing ciccreator, and wanting to publish results that I needed some tools, so I made some
that could convert from the output file of cic to eps, png, tikz, show the layout and even minecraft

## cic2verilog - Alfa software
Reads the cic output file and outputs verilog wrappers that can be used in verilog simulations

