# Awesome Hardware Description Languages [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of amazingly awesome hardware description language projects.

# Hardware developement

## HDL doc

* Verilog [IEEE Std 1364-2001](https://inst.eecs.berkeley.edu/~cs150/fa06/Labs/verilog-ieee.pdf), [Quick Ref Guide](http://sutherland-hdl.com/pdfs/verilog_2001_ref_guide.pdf), [SystemVerilog 3.1a](http://www.ece.uah.edu/~gaede/cpe526/SystemVerilog_3.1a.pdf), [Synthesizing SystemVerilog Busting the Myth that SystemVerilog is only for Verification](http://sutherland-hdl.com/papers/2013-SNUG-SV_Synthesizable-SystemVerilog_paper.pdf)

* VHDL standards [IEEE Std 1076-2000](http://edg.uchicago.edu/~tang/VHDLref.pdf)
* SystemC standards [IEEE Std 1666-2011](http://paginas.fe.up.pt/~ee07166/lib/exe/fetch.php?media=1666-2011.pdf)


## HDL simulators and compilers

   * Verilog
      - [Verilator](https://www.veripool.org/wiki/verilator) Verilog to C++ transpiler
      - [Icarus Verilog](http://iverilog.icarus.com/) - simulator
      - [Yosys](http://www.clifford.at/yosys/) - RTL synthesis
   * VHDL
      * [nvc](https://github.com/nickg/nvc) - GPLv3 VHDL compiler and simulator, IEEE 1076-2002, writen in C
      * [GHDL](https://github.com/ghdl/ghdl) - VHDL compiler and simulator, IEEE 1076-2002, writen in ADA

## Meta HDL and Transpilers

* C/C++
   - [autopiper](https://github.com/google/autopiper)

* Haskel
   - [concat](https://github.com/conal/concat)
   - https://github.com/conal/talk-2015-haskell-to-hardware
   - [CλaSH](https://github.com/clash-lang/clash-compiler) - A functional hardware description language

* Java
   - [jhdl](http://www.jhdl.org/) ..2006
   - [PSHDL](http://pshdl.org/)

* JavaScript
   - [reqack](https://github.com/drom/reqack) -  elastic circuit toolchain
   - [hdl-js](https://github.com/DmitrySoshnikov/hdl-js) - Hardware description language (HDL) parser, and Hardware simulator.
   - [shdl](https://github.com/jcbuisson/shdl) - Simple Hardware Description Language

* Julia
   - [Julia-Verilog](https://github.com/interplanetary-robot/Verilog.jl) - a Verilog-generation DSL for Julia.

* Python
   - [HWT](https://github.com/Nic30/hwt)
   - [MyHDL](https://github.com/myhdl/myhdl) - hardware description and verification language
   - [PyRTL](https://github.com/UCSBarchlab/PyRTL) - A collection of classes providing simple hardware specification, simulation, tracing, and testing suitable for teaching and research. 
   - [Pyverilog](https://github.com/PyHDI/Pyverilog) - Design Processing Toolkit for Verilog HDL
   - [PyMTL](https://github.com/cornell-brg/pymtl) - framework for multi-level hardware modeling

* Ruby
   - [RHDL](https://github.com/philtomson/RHDL) ..2013

* Rust
   - [hoodlum](https://github.com/tcr/hoodlum) - nice-looking hardware description language that compiles to Verilog

* Scala
   - [chisel](https://github.com/freechipsproject/chisel3) - hardware construction language to support advanced hardware design and circuit generation
   - [SpinalHDL](https://github.com/SpinalHDL/SpinalHDL)


## HLS

* [legup](http://legup.eecg.utoronto.ca/) - 2011-2015, LLVM based c->verilog 
* [bambu](http://panda.dei.polimi.it/?page_id=31) - 2003-?, GCC based c->verilog 
* [augh](http://tima.imag.fr/sls/research-projects/augh/) - c->verilog, DSP support
* https://github.com/utwente-fmt - abstract hls, verification libraries
* [Shang](https://github.com/etherzhhb/Shang) - 2012-2014, LLVM based, c->verilog
* [xronos](https://github.com/endrix/xronos) - 2012, java, simple HLS
* [Potholes](https://github.com/SamuelBayliss/Potholes) - 2012-2014 - polyhedral model preprocessor, Uses Vivado HLS, PET
* [hls_recurse](https://github.com/m8pple/hls_recurse) - 2015-2016 - conversion of recursive fn. for stackless architectures
* [hg_lvl_syn](https://github.com/funningboy/hg_lvl_syn) - 2010, ILP, Force Directed scheduler
* [abc](https://people.eecs.berkeley.edu/~alanmi/abc/) <2008-?, A System for Sequential Synthesis and Verification 
* [polyphony](https://github.com/ktok07b6/polyphony) - 2015-2017, simple python to hdl
* [DelayGraph](https://github.com/ni/DelayGraph) - 2016, C#, register assignment alghorithms
* [coreir](https://github.com/rdaly525/coreir) - 2016-?, LLVM HW compiler## License


# Open Hardware

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Aliaksei Chapyzhenka](http://drom.io) has waived all copyright and related or neighboring rights to this work.
