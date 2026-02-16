# binsnake

Low-level x86_64 binary analysis, lifting, and emulation tooling.

## Core

| Project | Description |
|---------|-------------|
| [KUBERA](https://github.com/binsnake/KUBERA) | x86_64 software emulator |
| [picanha](https://github.com/binsnake/picanha) | x86_64 disassembler / lifter / recompiler (WIP) |
| [winhorse](https://github.com/binsnake/winhorse) | Minimalistic Windows compatibility layer for KUBERA |

## Lifting & Deobfuscation

| Project | Description |
|---------|-------------|
| [omill](https://github.com/binsnake/omill) | Binary lifter and deobfuscator using remill for x86_64 Windows binaries |
| [remill](https://github.com/binsnake/remill) | Library for lifting machine code to LLVM bitcode |
| [HayLift](https://github.com/binsnake/HayLift) | Experimental x86_64 PE lifter for KIRA |
| [souper-llvm21](https://github.com/binsnake/souper-llvm21) | Superoptimizer for LLVM IR, updated for LLVM 21 |

## Decoding & Disassembly

| Project | Description |
|---------|-------------|
| [iced](https://github.com/binsnake/iced) | x86/x64 disassembler, assembler, decoder, encoder (C++ port) |

## Testing & Fuzzing

| Project | Description |
|---------|-------------|
| [Mona](https://github.com/binsnake/Mona) | Oracle-based differential fuzzer for KUBERA |
| [x86Tester](https://github.com/binsnake/x86Tester) | x86-64 automated test data generator |
| [x86Tester-parser](https://github.com/binsnake/x86Tester-parser) | Parser for x86Tester output |
| [x86Tester-results](https://github.com/binsnake/x86Tester-results) | x86Tester results for different CPUs |

## Tools & Misc

| Project | Description |
|---------|-------------|
| [uwp](https://github.com/binsnake/uwp) | Silent moonwalk approach for payloads |
| [vmx_intrinsics](https://github.com/binsnake/vmx_intrinsics) | VMX intrinsics plugin for IDA 9.2 Pro |
| [vergilius-scrapper](https://github.com/binsnake/vergilius-scrapper) | Vergilius structure scraper |
