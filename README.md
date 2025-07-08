# Awesome HDL、Python HDL and eDSL for IC

A curated list of amazingly awesome hardware description language projects.


# Hardware development

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
      * [nvc](https://github.com/nickg/nvc) - GPLv3 VHDL compiler and simulator, IEEE 1076-2002, written in C
      * [GHDL](https://github.com/ghdl/ghdl) - VHDL compiler and simulator, IEEE 1076-2002, written in ADA
   * chisel/firrtl
      * [essent](https://github.com/ucsc-vama/essent) - firrtl to optimized C++ transpiler
      * [treadle](https://github.com/chipsalliance/treadle) - firrtl simulator written in Scala
   * [Lola-2](https://inf.ethz.ch/personal/wirth/Lola/Lola2.pdf)
      - [Oberon-2013](https://inf.ethz.ch/personal/wirth/Lola/) - Project Oberon, 2013 Edition, written in [Oberon-07](http://www-oldurls.inf.ethz.ch/personal/wirth/Oberon/) [License](https://inf.ethz.ch/personal/wirth/ProjectOberon/license.txt)


## Meta HDL and Transpilers

* C++
   - [SystemC](https://www.doulos.com/knowhow/systemc/) - an IEEE standard meta-HDL
   - [VisualHDL](http://sysprogs.com/legacy/visualhdl/) - an integrated development environment (IDE) rapid design for FPGAs

* Dart
   - [ROHD](https://github.com/intel/rohd) - A framework for hardware description and verification, 2021+

* Haskell
   - [concat](https://github.com/conal/concat) Haskell to hardware, 2016+
   - https://github.com/conal/talk-2015-haskell-to-hardware
   - [CλaSH](https://github.com/clash-lang/clash-compiler) - A functional hardware description language
   - [pipelineDSL](https://github.com/p12nGH/pipelineDSL) - A Haskell DSL for describing hardware pipelines
   - [Bluespec](https://github.com/B-Lang-org/bsc) - Compiler, simulator, and tools for the Bluespec Hardware Description Language.
   - [sv2v](https://github.com/zachjs/sv2v) - SystemVerilog to Verilog conversion

* Java
   - [jhdl](http://www.jhdl.org/) ..2006
   - [PSHDL](http://pshdl.org/)

* JavaScript
   - [reqack](https://github.com/drom/reqack) -  elastic circuit toolchain
   - [hdl-js](https://github.com/DmitrySoshnikov/hdl-js) - Hardware description language (HDL) parser, and Hardware simulator.
   - [shdl](https://github.com/jcbuisson/shdl) - Simple Hardware Description Language

* Julia
   - [Julia-Verilog](https://github.com/interplanetary-robot/Verilog.jl) - a Verilog-generation DSL for Julia., 2017

* OCaml
   - [Hardcaml](https://github.com/janestreet/hardcaml/blob/master/docs/index.mdx) An OCaml library for designing hardware, complete with testing and simulation tools.

* Kotlin
  - [Verik](https://github.com/frwang96/verik) HDL for design and verification. generates SV. UVM.

* Python
  - [HWT](https://github.com/Nic30/hwt) Meta HDL, verification env. IP-core generator, analysis tools, HDL glue
  - [garnet](https://github.com/StanfordAHA/garnet) Coarse-Grained Reconfigurable Architecture generator based on magma, 2018+
  - [magma](https://github.com/phanrahan/magma/) - Meta HDL, 2017+
  - [migen](https://github.com/m-labs/migen) - Meta HDL, 2011+
  - [Amaranth](https://github.com/amaranth-lang/amaranth) (previously nMigen) - A refreshed Python toolbox for building complex digital hardware, 2018+
  - [MyHDL](https://github.com/myhdl/myhdl) - Process based HDL, verification framework included, 2004+
  - [Pyrope](https://masc.soe.ucsc.edu/pyrope.html) - Python-like language supporting "fluid pipelines" and "live flow", 2017+
  - [PyRTL](https://github.com/UCSBarchlab/PyRTL) - Meta HDL, simulator suitable for research.
  - [PyMTL](https://github.com/cornell-brg/pymtl) - Process based HDL, verification framework included, 2014+
  - [veriloggen](https://github.com/PyHDI/veriloggen) - Python, Verilog centric meta HDL with HLS like features, 2015-?
  - [Hdl21](https://github.com/dan-fritchman/Hdl21) - Analog HDL in Python
  - [PyHGL](https://github.com/PyHGL/pyhgl) - Meta HDL, three-state event-driven simulation, 2022+

* Ruby
   - [RHDL](https://github.com/philtomson/RHDL)

* Rust
   - [hoodlum](https://github.com/tcr/hoodlum) - Meta HDL, 2016+
   - [kaze](https://github.com/yupferris/kaze) - Meta HDL, 2019+
   - [calyx](https://github.com/cucapra/calyx) - Intermediate Language (IL) for Hardware Accelerator Generators, 2020+
   - [Spade](https://gitlab.com/spade-lang/spade) - A hardware description language inspired by modern software languages like Rust.

* Scala
   - [chisel](https://github.com/freechipsproject/chisel3) - Meta HDL, 2012+
   - [SpinalHDL](https://github.com/SpinalHDL/SpinalHDL) - Meta HDL 2012+

* C#
   - [Quokka](https://github.com/EvgenyMuryshkin/qusoc) - C# to low-level RTL translator (Verilog, VHDL) and simulation toolkit examples (gates, components, RISC-V, SoC)

* Veryl
   - [Veryl](https://github.com/dalance/veryl) - An original HDL based on SystemVerilog / Rust syntax, and transplier to SystemVerilog
 
* [autofpga](https://github.com/ZipCPU/autofpga) - C++, A utility for Composing FPGA designs from Peripherals
* :skull: [baremetal](https://github.com/dawsonjon/baremetal) - Python, simple HCL
* [BinPy](https://github.com/BinPy/BinPy) - Python, An electronic simulation library
* :skull: [pervognsen/Bitwise](https://github.com/pervognsen/bitwise) - Python, HDL which translates python directly
* :skull: [jamesjiang52/Bitwise](https://github.com/jamesjiang52/Bitwise) - Python, simple HCL.
* [blarney](https://github.com/blarney-lang/blarney) - Haskell, HCL
* [bsc](https://github.com/B-Lang-org/bsc) - Haskell, C++, BSV - Bluespec Compiler
* [Cement HDL/CmtHDL](https://github.com/pku-liang/Cement) - Rust, eHDL
* [chisel](https://chisel.eecs.berkeley.edu/) - 2012-?, Scala, HCL
* [Chips-2.0](https://github.com/dawsonjon/Chips-2.0) - , , FPGA Design Suite based on C to Verilog design flow
* [circt](https://github.com/llvm/circt) - 2020-?, C++/LLVM, compiler infrastructure
* [circuitgraph](https://github.com/circuitgraph/circuitgraph) - Tools for working with circuits as graphs in python
* [concat](https://github.com/conal/concat) - 2016-?, Haskell, Haskell to hardware
* [DUH](https://github.com/sifive/duh) - JS, simple convertor between verilog/scala/ipxact
* [DFiant](https://github.com/DFiantHDL/DFiant) 2019-?, Scala, dataflow based HDL
* [edalize](https://github.com/olofk/edalize) - 2018-?, Python, abstraction layer for eda tools
* [garnet](https://github.com/StanfordAHA/garnet) -2018-?, Python, Coarse-Grained Reconfigurable Architecture generator based on magma
* [hammer](https://github.com/ucb-bar/hammer) - 2017-?, Python, Highly Agile Masks Made Effortlessly from RTL
* [heterocl](https://github.com/cornell-zhang/heterocl) - 2017-?, C++, A Multi-Paradigm Programming Infrastructure for Software-Defined Reconfigurable Computing
* [hoodlum](https://github.com/tcr/hoodlum) - 2016-?, Rust, HCL
* [ILAng](https://github.com/Bo-Yuan-Huang/ILAng) - modeling and verification platform for SoCs where Instruction-Level Abstraction (ILA) is used as the formal model for hardware components.
* :skull: [jhdl](https://github.com/larsjoost/jhdl) - ?-2017, C++ Verilog/VHDL -> systemC, prototype
* [Kactus2](http://funbase.cs.tut.fi) - IP-core packager
* [kratos](https://github.com/Kuree/kratos) - C++/Python, hardware generator/simulator
* [lgraph](https://github.com/masc-ucsc/lgraph) - C, generic graph library
* [llhd](https://github.com/fabianschuiki/llhd) - Rust, HCL
* [livehd](https://github.com/masc-ucsc/livehd) - mainly C++, An infrastructure designed for Live Hardware Development.
* [Lucid HDL in Alchitry-Labs](https://github.com/alchitry/Alchitry-Labs) - Custom language and IDE inspired by Verilog
* [magma](https://github.com/phanrahan/magma/) - 2017-?, Python, HCL
* [amaranth](https://github.com/amaranth-lang/amaranth)/[migen](https://github.com/m-labs/migen) - 2013-?, Python, HCL
* [mockturtle](https://github.com/lsils/mockturtle) - logic network library
* [moore](https://github.com/fabianschuiki/moore) - Rust, HDL -> model compiler
* [msdsl](https://github.com/sgherbst/msdsl) - Python, real number model -> verilog
* [MyHDL](https://github.com/myhdl/myhdl) - 2004-?, Python, Process based HDL
* [Amaranth HDL](https://github.com/amaranth-lang/amaranth) -, Python, (previously nMigen) A refreshed Python toolbox for building complex digital hardware
* [OpenTimer](https://github.com/OpenTimer/OpenTimer) - , C++,  A High-Performance Timing Analysis Tool for VLSI Systems
* [percy](https://github.com/whaaswijk/percy) - Collection of different synthesizers and exact synthesis methods for use in applications such as circuit resynthesis and design exploration.
* [PyChip-py-hcl](https://github.com/scutdig/PyChip-py-hcl) - , Python, Chisel3 like HCL
* [pygears](https://github.com/bogdanvuk/pygears) - , Python, function style HDL generator
* [PyMTL3](https://github.com/cornell-brg/pymtl3) 2018-?
* [PyMTL](https://github.com/cornell-brg/pymtl) - 2014-?, Python, Process based HDL
* [PipelineC](https://github.com/JulianKemmerer/PipelineC) - 2018-?, Python, C++ HLS-like automatic pipelining as a language construct/compiler
* [PyRTL](https://github.com/UCSBarchlab/PyRTL) - 2015-?, Python, HCL
* [Pyverilog](https://github.com/PyHDI/Pyverilog) - 2013-? Python-based Hardware Design Processing Toolkit for Verilog HDL
* [rogue](https://github.com/slaclab/rogue) , C++/Python - Hardware Abstraction & Data Acquisition System
* [rohd](https://github.com/intel/rohd), 2023-?, dart, HCL
* [sail](https://github.com/rems-project/sail) 2018-?, (OCaml, Standard ML, Isabelle) - architecture definition language
* :skull: [SFGen](https://github.com/dillonhuff/SFGen) - Python, arithmetic function generator
* [spatial](https://github.com/stanford-ppl/spatial) - Scala, an Argon DSL like, high level abstraction
* [SpinalHDL](https://github.com/SpinalHDL/SpinalHDL) - 2015-?, Scala, HCL
* [Silice](https://github.com/sylefeb/Silice) - ?, C++, Custom HDL
* :skull: [SyDpy](https://github.com/bogdanvuk/sydpy) - ?-2016, Python, HCL and verif. framework operating on TML/RTL level
* [systemrdl-compiler](https://github.com/SystemRDL/systemrdl-compiler) - Python,c++, register description language compiler
* [UHDM](https://github.com/alainmarcel/UHDM) - C++ SystemVerilog -> C++ model
* :skull: [Verilog.jl](https://github.com/interplanetary-robot/Verilog.jl) - 2017-2017, Julia, simple Julia to Verilog transpiler
* [veriloggen](https://github.com/PyHDI/veriloggen) - 2015-?, Python, Verilog centric HCL with HLS like features
* :skull:  [wyre](https://github.com/nickmqb/wyre) - 2020-2020, Mupad, Minimalistic HDL
* [phi](https://github.com/donn/Phi) - 2019-?, custom language, llvm based compiler of custom hdl
* [prga](https://github.com/PrincetonUniversity/prga) - 2019-?. Python, prototyping platform with integrated yosys
* [Hardcaml](https://github.com/janestreet/hardcaml) - OCaml, HCL
* [magia-hdl](https://github.com/magia-hdl/magia) - 2023-?, Python, HCL
* [Metron](https://github.com/aappleby/Metron) - C++, C++ -> SystemVerilog syntax translator

## HLS

* [hlslibs](https://github.com/hlslibs) - ac_math, ac_dsp, ac_types
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
* [DelayGraph](https://github.com/ni/DelayGraph) - 2016, C#, register assignment algorithms
* [ahaHLS](https://github.com/dillonhuff/ahaHLS) - 2019, An open source high level synthesis (HLS) tool using LLVM
* [combinatorylogic/soc](https://github.com/combinatorylogic/soc) - 2019, An experimental System-on-Chip with a custom compiler toolchain.
* [Quokka](https://github.com/EvgenyMuryshkin/QuokkaEvaluation) - C# to HL RTL translator
* [Vitis](https://github.com/Xilinx/HLS) - LLVM based, made by Xilinx. [user manual](https://www.xilinx.com/support/documentation/sw_manuals/xilinx2020_2/ug1399-vitis-hls.pdf)
* [XLS](https://google.github.io/xls/) - 2020, HLS toolchain from Google


## Other HDL languages

* [act](https://github.com/asyncvlsi/act) - asynchronous circuit/compiler tools
* [autopiper](https://github.com/google/autopiper)
* [Silice](https://github.com/sylefeb/Silice) - A language for hardcoding algorithms into FPGA hardware
* [TL-Verilog](https://makerchip.com) - 2015+, Supports "timing-abstract" and "transaction-level design" methodologies; supported by proprietary and open-source tools


## Hardware Intermediate Representations

* [CIRCT](https://circt.llvm.org) - 2020+, LLVM / MLIR framework "Circuit IR Compilers and Tools"
* [coreir](https://github.com/rdaly525/coreir) - 2016-?, LLVM HW compiler## License
* [lgraph](https://github.com/masc-ucsc/lgraph) - 2017-?, A Multi-Language Synthesis and Simulation IR for Hardware Design
* [firrtl](https://github.com/freechipsproject/firrtl) - 2016-?, Flexible Intermediate Representation for RTL
* [LLHD](https://github.com/fabianschuiki/llhd) - Low Level Hardware Description — A foundation for building hardware design tools
* [SpyDrNet](https://byuccl.github.io/spydrnet/) - 2019+, Framework for parsing and manipulating structural netlists in Python
* [VLSIR](https://github.com/Vlsir/Vlsir) - IC Interchange Formats, defined in Google Protobuf SDL

## Synthesis tools

* [vtr-verilog-to-routing](https://github.com/verilog-to-routing/vtr-verilog-to-routing)
* [yosys](https://github.com/YosysHQ/yosys) - RTL synthesis framework


## Visualization and Documentation generators

* [bitfield](https://github.com/drom/bitfield) - Javascript bit field diagram renderer
* [d3-wave](https://github.com/Nic30/d3-wave) - Javascript wave graph visualizer for RTL simulations
* [d3-hwschematic](https://github.com/Nic30/d3-hwschematic) - Javascript hierarchical schematic visualizer for HDLs
* [wavedrom](https://github.com/drom/wavedrom) - Javascript wave graph visualizer for documentations and sim.
* [netlistsvg](https://github.com/nturley/netlistsvg) - Javascript schematic visualizer
* [sphinx-hwt](https://github.com/Nic30/sphinx-hwt) - Plugin for sphinx documentation generator which adds schematic into html documentation.
* [Visual Debug](https://redwoodeda.com/viz) - Custom simulation visualization framework, available within the [Makerchip.com](https://makerchip.com) IDE.


## HDL parsers

* [hdlConvertor](https://github.com/Nic30/hdlConvertor) - Fast (System) Verilog/VHDL parser written as C++ extension for Python
* [pyVHDLParser](https://github.com/Paebbels/pyVHDLParser) - VHDL parser written in Python
* [rust_hdl](https://github.com/kraigher/rust_hdl) - VHDL parser and language server written in Rust
* [sv-parser](https://github.com/dalance/sv-parser) -  IEEE 1800-2017 System Verilog Parser written in Rust
* [verible](https://chipsalliance.github.io/verible/) - Verible provides a SystemVerilog parser, style-linter, and formatter.
* [slang](https://github.com/MikePopoloski/slang) - SystemVerilog compiler and language service.
* [pyverilog](https://github.com/PyHDI/Pyverilog) - Python-based Hardware Design Processing Toolkit for Verilog HDL
* [Surelog](https://github.com/chipsalliance/Surelog) - SystemVerilog 2017 Pre-processor, Parser, Elaborator, UHDM Compiler. Provides IEEE Design/TB C/C++ VPI and Python AST API.

## Other Simulation tools

* [midas](https://github.com/ucb-bar/midas) - FPGA-Accelerated Simulation Framework Automatically Transforming Arbitrary RTL
* [cocotb](https://github.com/potentialventures/cocotb) - A coroutine based co-simulation library for writing VHDL and Verilog testbenches in Python
* [osvvm](https://github.com/OSVVM/OsvvmLibraries) -  A VHDL verification framework, verification utility library, verification component library, and a simulator independent scripting flow
* [uvvm](https://github.com/OSVVM/OsvvmLibraries) - A free and Open Source Methodology and Library for VHDL verification of FPGA and ASIC.

## Other Design Automation tools

* [peakrdl](https://github.com/SystemRDL/PeakRDL) - CSR toolchain to generate RTL, UVM RAL models, document(html and markdown), IPXACT, c header from SystemRDL or IPXACT.
* [RgGen](https://github.com/rggen/rggen) - Code generator tool to generate RTL, UVM RAL models and Wiki documents from CSR specifications
* [sv-tests](https://symbiflow.github.io/sv-tests) - Test suite designed to check compliance with the SystemVerilog standard
* [tbengy](https://github.com/prasadp4009/tbengy) - Code generator tool to generate SV/UVM RTL and Testbech as well scripts with support for bitstream generation for Digilent FPGAs
* [HDLGen](https://github.com/WilsonChen003/HDLGen) - Tool for processing of embedded Perl or Python scripts in Verilog source code.
* [fusesoc](https://github.com/olofk/fusesoc) -  Package manager and a set of build tools for HDL.
* [bender](https://github.com/pulp-platform/bender) -  Dependency management tool for hardware design projects.
* [hbs](https://github.com/m-kru/hbs) - A lean dependency management and build system for hardware description projects.

## PSS : Portable test and Stimulus Standard

* [Accellera](https://www.accellera.org/downloads/standards/portable-stimulus) - specification to create a single representation of stimulus and test scenarios
* [PSS 2.1 LRM](https://www.accellera.org/images/downloads/standards/pss/Portable_Test_Stimulus_Standard_v2.1.pdf) - PDF Spec
* [PSSTools Org](https://github.com/PSSTools) - PSS releated tools on GitHub. Parsers, editor plugins.
* [Matthew Ballance](https://github.com/mballance) PSS Blog posts:
   - [Automating Bare-Metal Tests with PSS](https://bitsbytesgates.com/pss/2023/02/25/AutomatingBareMetalTestsWithPSS.html)
   - [PSS Fundamentals: Actions, Components, and Test Generation](https://bitsbytesgates.com/pss/2023/03/03/ActionsComponents_and_TestGeneration.html)
   - [Declarative Programming and Multi-Core Tests](https://bitsbytesgates.com/pss/2023/03/11/DeclarativeMultiCoreTests.html)
   - [Relating Actions with Dataflow](https://bitsbytesgates.com/pss/2023/03/18/RelatingActionsWithDataflow.html)
   - [Modeling DMA Test Scenarios with PSS](https://bitsbytesgates.com/pss/2023/03/25/ModelingTestScenariosForDMA.html)
   - [PSS Memory Management Fundamentals](https://bitsbytesgates.com/pss/2023/04/02/ManagingMemoryInPSS.html)
   - [PSS Concurrency and Resources](https://bitsbytesgates.com/pss/2023/04/09/PSSConcurrencyAndResources.html)
   - [Interacting with Devices via PSS Registers](https://bitsbytesgates.com/pss/2023/04/18/InteractingWithDevicesViaRegisters.html)
   - [Relating Actions with Dataflow Part2 -- Parallelism](https://bitsbytesgates.com/pss/2023/05/07/RelatingActionsWithDataflowPart2.html)
* [PSS CookBook](https://github.com/LeeKaiXuan/PSS_Cookbook) - Documentation for introducing the usage of PSS language

