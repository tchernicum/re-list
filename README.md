# RE list

A list of open-source reverse engineering tools with a focus on binary analysis.

- **[Amoco](https://github.com/bdcht/amoco)**: A python package dedicated to the (static) analysis of binaries.

- **[Angr](http://angr.io/)**: A python framework for analyzing binaries. It combines both static and dynamic symbolic ("concolic") analysis, making it applicable to a variety of tasks.

 - **[Avatar²](https://github.com/avatartwo/avatar2)**:  Avatar is a target orchestration framework with focus on dynamic analysis of embedded devices' firmware.
 
- **[BARF](https://github.com/programa-stic/barf-project)**: An open source binary analysis framework. It is a scriptable platform that supports instruction lifting from multiple architectures, binary translation to an intermediate representation, an extensible framework for code analysis plugins and interoperation with external tools such as debuggers, SMT solvers and instrumentation tools.

- **[BAP](https://github.com/BinaryAnalysisPlatform/bap)**: The Binary Analysis Platform is a reverse engineering and program analysis platform that targets binaries, i.e., compiled programs without the source code. BAP supports multiple architectures (more than 30), though the first tier architectures are x86, x86-64, and ARM. 

- **[BinCAT](https://github.com/airbus-seclab/bincat)**: A static Binary Code Analysis Toolkit, designed to help reverse engineers, directly from IDA. It features: value analysis (registers and memory), taint analysis, type reconstruction and propagation, backward and forward analysis

- **[Bindead](https://bitbucket.org/mihaila/bindead/wiki/Home)**: An analyzer for executable machine code. It features a disassembler that translates machine code bits into an assembler like language (RREIL) that in turn is then analyzed by the static analysis component using abstract interpretation. As Bindead operates on the machine code level, it can be used without having the source code of the program to be analyzed.

- **[BitBlaze](http://bitblaze.cs.berkeley.edu/)**: BitBlaze Binary Analysis Platform features a novel fusion of static and dynamic analysis techniques, dynamic symbolic execution, and whole-system emulation and binary instrumentation. 

- **[Cemu](https://github.com/hugsy/cemu)**: Cheap EMUlator: lightweight multi-architecture assembly playground

- **[Cutter](https://github.com/radareorg/cutter)**: A Qt and C++ GUI for radare2.

 - **[DECAF](https://github.com/sycurelab/DECAF)**: DECAF(short for Dynamic Executable Code Analysis Framework) is a binary analysis platform based on QEMU.
 
 - **[Deepstate](https://github.com/trailofbits/deepstate)**: A framework that provides C and C++ developers with a common interface to various symbolic execution and fuzzing engines. Users can write one test harness using a Google Test-like API, then execute it using multiple backends without having to learn the complexities of the underlying engines.
 
 - **[DynamoRIO](http://www.dynamorio.org/)**: DynamoRIO is a runtime code manipulation system that supports code transformations on any part of a program, while it executes. DynamoRIO exports an interface for building dynamic tools for a wide variety of uses: program analysis and understanding, profiling, instrumentation, optimization, translation, etc.
 
 - **[ERESI](https://github.com/thorkill/eresi)**: The ERESI Reverse Engineering Software Interface is a multi-architecture binary analysis framework with a domain-specific language tailored to reverse engineering and program manipulation.
 
- **[Falcon](https://github.com/falconre/falcon)**: A formal binary analysis framework in Rust. Falcon seeks to implement data-flow analysis, abstract interpretation, and constraint solving over compiled, binary executables.

- **[Gdbgui](https://github.com/cs01/gdbgui)**: A modern, browser-based frontend to gdb (gnu debugger). Add breakpoints, view stack traces, and more in C, C++, Go, and Rust! Simply run gdbgui from the terminal and a new tab will open in your browser.

- **[Insight](https://insight.labri.fr/)**: The Insight project is devoted to binary analysis to serve several purposes such as:    Binary verification, Reverse engineering, Binary test cases extraction, Decompilation to higher-level languages.

- **[Jakstab](http://www.jakstab.org/)**: An Abstract Interpretation-based, integrated disassembly and static analysis framework for designing analyses on executables and recovering reliable control flow graphs.

- **[Kaitai Struct](http://kaitai.io/)**: A declarative language used for describe various binary data structures, laid out in files or in memory: i.e. binary file formats, network stream packet formats, etc.

- **[LIEF](https://github.com/lief-project/LIEF)**: Library to Instrument Executable Formats. The purpose of this project is to provide a cross platform library which can parse, modify and abstract ELF, PE and MachO formats.

- **[LuaQEMU](https://github.com/Comsecuris/luaqemu)**: A QEMU-based framework exposing several of QEMU-internal APIs to a LuaJIT core injected into QEMU itself. Among other things, this allows fast prototyping of target systems without any native code and minimal effort in Lua.

- **[Manticore](https://github.com/trailofbits/manticore)**: A prototyping tool for dynamic binary analysis, with support for symbolic execution, taint analysis, and binary instrumentation.

- **[Mcsema](https://github.com/trailofbits/mcsema)**: Framework for lifting x86, amd64, and aarch64 program binaries to LLVM bitcode.

- **[Metasm](https://github.com/jjyg/metasm)**: Ruby assembly manipulation suite

- **[Medusa](https://github.com/wisk/medusa)**: A disassembler designed to be both modular and interactive. 

- **[Miasm](https://github.com/cea-sec/miasm)**: Free and open source (GPLv2) reverse engineering framework. Miasm aims to analyze / modify / generate binary programs.

- **[Multiverse](https://github.com/utds3lab/multiverse)**: A static binary rewriter with an emphasis on simplicity and correctness. It does not rely on heuristics to perform its rewriting, and it attempts to make as few assumptions as possible to produce a rewritten binary. 

- **[Panda](https://github.com/panda-re/panda)**: PANDA is an open-source Platform for Architecture-Neutral Dynamic Analysis. It is built upon the QEMU whole system emulator, and so analyses have access to all code executing in the guest and all data. PANDA adds the ability to record and replay executions, enabling iterative, deep, whole system analyses. 

- **[Panopticon](https://github.com/das-labor/panopticon)**: A cross platform disassembler for reverse engineering written in Rust. It can disassemble AMD64, x86, AVR and MOS 6502 instruction sets and open ELF files. Panopticon comes with Qt GUI for browsing and annotating control flow graphs.

- **[Pharos](https://github.com/cmu-sei/pharos)**: The framework is designed to facilitate the automated analysis of binary programs. It uses the ROSE compiler infrastructure for disassembly, control flow analysis, instruction semantics, and more.

- **[Pimp](https://github.com/radare/radare2-extras/tree/master/pimp)**: Triton based R2 plugin for concolic execution

- **[PINCE](https://github.com/korcankaraokcu/PINCE)**: A front-end/reverse engineering tool for the GNU Project Debugger (GDB), focused on games. But it can be used for any reverse-engineering related stuff.

- **[Ponce](https://github.com/illera88/Ponce)**: An IDA Pro plugin that provides users the ability to perform taint analysis and symbolic execution over binaries in an easy and intuitive fashion. With Ponce you are one click away from getting all the power from cutting edge symbolic execution.

- **[PyREBox](https://github.com/Cisco-Talos/pyrebox)**: PyREBox is a Python scriptable Reverse Engineering sandbox. It is based on QEMU, and its goal is to aid reverse engineering by providing dynamic analysis and debugging capabilities from a different perspective. PyREBox allows to inspect a running QEMU VM, modify its memory or registers, and to instrument its execution, by creating simple scripts in python to automate any kind of analysis.

- **[Pysymemu](https://github.com/feliam/pysymemu)**: A symbolic execution tool, capable of automatically generating interesting inputs for x86/x64 binary programs.

- **[QBDI](https://github.com/quarkslab/QBDI)**: A modular, cross-platform and cross-architecture DBI framework. It aims to support Linux, macOS, Android, iOS and Windows operating systems running on x86, x86-64, ARM and AArch64 architectures

- **[Remill](https://github.com/trailofbits/remill)**: A static binary translator that translates machine code instructions into LLVM bitcode. It translates x86 and amd64 machine code into LLVM bitcode. 
Remill focuses on accurately lifting instructions. It is meant to be used as a library for other tools, e.g. McSema.

- **[REDasm](https://github.com/REDasmOrg/REDasm)**: An interactive, multiarchitecture disassembler written in C++ using Qt5 as UI Framework, its core is light and it can be extended in order to support new instructions and file formats.

 - **[S²E](http://s2e.systems/)**: S²E is a platform for writing tools that analyze the properties and behavior of software systems. S²E comes as a modular library that gives virtual machines symbolic execution and program analysis capabilities. S²E runs unmodified x86, x86-64, or ARM software stacks, including programs, libraries, the kernel, and drivers. Symbolic execution then automatically explores hundreds of thousands of paths through the system, while analyzers check that the desired properties hold on these paths and selectors focus path exploration on components of interest.
 
- **[ScratchABit](https://github.com/pfalcon/ScratchABit)**: An interactive incremental disassembler with data/control flow analysis capabilities. ScratchABit supports well-known in the community IDAPython API to write disassembly/extension modules.

- **[Simplify](https://github.com/CalebFenton/simplify)**: Simplify virtually executes an app to understand its behavior and then tries to optimize the code so that it behaves identically but is easier for a human to understand. Each optimization type is simple and generic, so it doesn't matter what the specific type of obfuscation is used.

- **[SimplifyGraph](https://github.com/fireeye/SimplifyGraph)**: IDA Pro plugin to assist with complex graphs

- **[Sibyl](https://github.com/cea-sec/Sibyl)**: Identifies function by studying its side-effects. Uses Miasm under the hood.

- **[SymGDB](https://github.com/SQLab/symgdb)**: Symbolic execution extention for gdb. Uses triton for symbolic execution.

- **[Triton](https://triton.quarkslab.com/)**: A dynamic binary analysis (DBA) framework. It provides internal components like a Dynamic Symbolic Execution (DSE) engine, a Taint Engine, AST representations of the x86 and the x86-64 instructions set semantics, SMT simplification passes, an SMT Solver Interface and, the last but not least, Python bindings.

- **[Vivisect](https://github.com/vivisect/vivisect)**: Python based static analysis and emulation framework.
