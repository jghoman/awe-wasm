[<img src="https://github.com/jghoman/awe-wasm/raw/master/wasm-logo.png" align="right">](https://webassembly.org/)
# awe-wasm
awe-wasm = awesome WASM - repo for tracking WASM related resources I come across while bringing myself up to speed on this new ecosystem.

## Introductory articles on WASM and its ecosystem
* [Standardizing WASI: A system interface to run WebAssembly outside the web](https://hacks.mozilla.org/2019/03/standardizing-wasi-a-webassembly-system-interface/), 2019-03-27 - [Lin Clark](https://twitter.com/linclark) walks throuh WASI (WebAssembly System Interface) - a proposed standard library system for WASM designed to provide core, modular libraries for WASM apps.  The proposal is being tracked [here](https://wasi.dev/).

## Tutorials
* [WASM by example](https://wasmbyexample.dev/) - [Aaron Turner](https://aaronthedev.com/) has built a tutorial that walks through WASM from first concepts to workings with graphics, with examples in both Rust and Typescript.

## Frameworks and libraries
* [Smithy.rs](https://www.smithy.rs/) ![Activity badge](https://img.shields.io/github/commit-activity/m/rbalicki2/smithy)- Rust framework for writing idiomatic WebAssembly web applications.

## Prominent community members
* [Lin Clark](https://twitter.com/linclark) - Mozilla developer focusing on WebAssembly and Rust who has written many great articles linked above.
* [Till Schneidereit](https://twitter.com/tschneidereit) - Manager at Mozilla working on the WebAssembly efforts.

## Books and other resources
* [WASM Weekly](https://wasmweekly.news/) - A weekly newsletter (with all its previous issues archived online) of WASM-related news.
* [Programming WebAssembly with Rust](https://pragprog.com/book/khrust/programming-webassembly-with-rust) by [Kevin Hoffman](https://twitter.com/KevinHoffman).  Covers WebAssembly from the ground up with a focus on using Rust to write apps.

## Runtimes
*n.b. Many entries for this list were originally sourced from the very useful [awesome-wasm-runtimes](https://github.com/appcypher/awesome-wasm-runtimes) by [Steve Akinyemi](https://twitter.com/theappcypher).*
### **Rust**
* [Ice Core](https://github.com/losfair/IceCore) ![Activity badge](https://img.shields.io/github/commit-activity/m/losfair/IceCore) ![Language](https://img.shields.io/github/languages/top/losfair/IceCore)
* [wasmi](https://github.com/paritytech/wasmi) ![Activity badge](https://img.shields.io/github/commit-activity/m/paritytech/wasmi) ![Language](https://img.shields.io/github/languages/top/paritytech/wasmi)
* [serverless-wasm](https://github.com/Geal/serverless-wasm) ![Activity badge](https://img.shields.io/github/commit-activity/m/Geal/serverless-wasm) ![Language](https://img.shields.io/github/languages/top/Geal/serverless-wasm)
* [Motor](https://github.com/penberg/motor) ![Activity badge](https://img.shields.io/github/commit-activity/m/penberg/motor) ![Language](https://img.shields.io/github/languages/top/penberg/motor)
* [JumpJet](https://github.com/jawm/jumpjet) ![Activity badge](https://img.shields.io/github/commit-activity/m/jawm/jumpjet) ![Language](https://img.shields.io/github/languages/top/jawm/jumpjet)
* [Lucet](https://github.com/fastly/lucet)  ![Activity badge](https://img.shields.io/github/commit-activity/m/fastly/lucet) ![Language](https://img.shields.io/github/languages/top/fastly/lucet) - [Fastly](https://www.fastly.com/)'s compiler and runtime designed to be embedded within applications.
* [Nebulet](https://github.com/nebulet/nebulet) ![Activity badge](https://img.shields.io/github/commit-activity/m/nebulet/nebulet) ![Language](https://img.shields.io/github/languages/top/nebulet/nebulet)
* [wasmer](https://github.com/wasmerio/wasmer) ![Activity badge](https://img.shields.io/github/commit-activity/m/wasmerio/wasmer) ![Language](https://img.shields.io/github/languages/top/wasmerio/wasmer)
* [wasmo](https://github.com/appcypher/wasmo) ![Activity badge](https://img.shields.io/github/commit-activity/m/appcypher/wasmo) ![Language](https://img.shields.io/github/languages/top/appcypher/wasmo)
* [wasmtime](https://github.com/CraneStation/wasmtime) ![Activity badge](https://img.shields.io/github/commit-activity/m/CraneStation/wasmtime) ![Language](https://img.shields.io/github/languages/top/CraneStation/wasmtime)
### **C**
* [WASM Micro Runtime](https://github.com/intel/wasm-micro-runtime) ![Activity badge](https://img.shields.io/github/commit-activity/m/intel/wasm-micro-runtime) ![Language](https://img.shields.io/github/languages/top/intel/wasm-micro-runtime) - Intel has released a a runtime focused on minimizing its footprint and running on a wide variety of systems.
* [m3](https://github.com/soundandform/m3) ![Activity badge](https://img.shields.io/github/commit-activity/m/soundandform/m3) ![Language](https://img.shields.io/github/languages/top/soundandform/m3)
* [wac](https://github.com/kanaka/wac) ![Activity badge](https://img.shields.io/github/commit-activity/m/kanaka/wac) ![Language](https://img.shields.io/github/languages/top/kanaka/wac)
* [WAMR](https://github.com/intel/wasm-micro-runtime) ![Activity badge](https://img.shields.io/github/commit-activity/m/intel/wasm-micro-runtime) ![Language](https://img.shields.io/github/languages/top/intel/wasm-micro-runtime)
* [VMIR](https://github.com/andoma/vmir) ![Activity badge](https://img.shields.io/github/commit-activity/m/andoma/vmir) ![Language](https://img.shields.io/github/languages/top/andoma/vmir)
* [WebAssembly](https://github.com/dcodeIO/webassembly) ![Activity badge](https://img.shields.io/github/commit-activity/m/dcodeIO/webassembly) ![Language](https://img.shields.io/github/languages/top/dcodeIO/webassembly)
### **C++**
* [WasmVM](https://github.com/LuisHsu/WasmVM) ![Activity badge](https://img.shields.io/github/commit-activity/m/LuisHsu/WasmVM) ![Language](https://img.shields.io/github/languages/top/LuisHsu/WasmVM)
* [InNative](https://github.com/innative-sdk/innative) ![Activity badge](https://img.shields.io/github/commit-activity/m/innative-sdk/innative) ![Language](https://img.shields.io/github/languages/top/innative-sdk/innative)
* [EOSVM](https://github.com/EOSIO/eos-vm) ![Activity badge](https://img.shields.io/github/commit-activity/m/EOSIO/eos-vm) ![Language](https://img.shields.io/github/languages/top/EOSIO/eos-vm)
* [WasmRT](https://github.com/rhitchcock/wasmrt) ![Activity badge](https://img.shields.io/github/commit-activity/m/rhitchcock/wasmrt) ![Language](https://img.shields.io/github/languages/top/rhitchcock/wasmrt)
* [Wasm JIT Prototype](https://github.com/WebAssembly/wasm-jit-prototype) ![Activity badge](https://img.shields.io/github/commit-activity/m/WebAssembly/wasm-jit-prototype) ![Language](https://img.shields.io/github/languages/top/WebAssembly/wasm-jit-prototype)
### **WebAssembly**
* [Swam](https://github.com/satabin/swam) ![Activity badge](https://img.shields.io/github/commit-activity/m/satabin/swam) ![Language](https://img.shields.io/github/languages/top/satabin/swam)
* [Wasm Runtime](https://github.com/kgtkr/wasm-runtime) ![Activity badge](https://img.shields.io/github/commit-activity/m/kgtkr/wasm-runtime) ![Language](https://img.shields.io/github/languages/top/kgtkr/wasm-runtime)
### **OCaml**
* [CMM of wasm](https://github.com/SimonJF/cmm_of_wasm) ![Activity badge](https://img.shields.io/github/commit-activity/m/SimonJF/cmm_of_wasm) ![Language](https://img.shields.io/github/languages/top/SimonJF/cmm_of_wasm)
### **Kotlin**
* [Asmble](https://github.com/cretz/asmble) ![Activity badge](https://img.shields.io/github/commit-activity/m/cretz/asmble) ![Language](https://img.shields.io/github/languages/top/cretz/asmble)
### **Python**
* [py-wasm](https://github.com/ethereum/py-wasm) ![Activity badge](https://img.shields.io/github/commit-activity/m/ethereum/py-wasm) ![Language](https://img.shields.io/github/languages/top/ethereum/py-wasm)
* [Warpy](https://github.com/kanaka/warpy) ![Activity badge](https://img.shields.io/github/commit-activity/m/kanaka/warpy) ![Language](https://img.shields.io/github/languages/top/kanaka/warpy)
### **Go**
* [Life](https://github.com/perlin-network/life) ![Activity badge](https://img.shields.io/github/commit-activity/m/perlin-network/life) ![Language](https://img.shields.io/github/languages/top/perlin-network/life)
* [Wagon](https://github.com/go-interpreter/wagon) ![Activity badge](https://img.shields.io/github/commit-activity/m/go-interpreter/wagon) ![Language](https://img.shields.io/github/languages/top/go-interpreter/wagon)
### **Javascript**
* [FDVM](https://github.com/funcdef/fdvm) ![Activity badge](https://img.shields.io/github/commit-activity/m/funcdef/fdvm) ![Language](https://img.shields.io/github/languages/top/funcdef/fdvm)
### **Swift**
* [WAKit](https://github.com/akkyie/WAKit) ![Activity badge](https://img.shields.io/github/commit-activity/m/akkyie/WAKit) ![Language](https://img.shields.io/github/languages/top/akkyie/WAKit)
