## Rust environment for the Windows Kernel-Mode Drivers

Contains:

* Cargo profile with kernel-mode x86 and x64 targets
* [Patched](https://github.com/thepowersgang/rust-barebones-kernel/blob/master/libcore_nofp.patch) libcore Rust library to disable floating point use (see the [#1364: Float-free libcore](https://github.com/rust-lang/rfcs/issues/1364) discussion)
* Rest of `std` crate libraries: liballoc, libcollections, librustc_unicode


