Kernel tools directory
======================

This tools directory, contains a copy of (some of the files from) the
kernels tools directory.

The primary purpose is to get a a working out-of-kernel-tree version
of libbpf, which will (hopefully) become the common library that
C-programs will use and link against, for loading BPF-ELF files
generated by LLVM/clang.

No distro is shipping this library yet.  And existing users like perf
and bpftool, are static linking directly with the library or specific
object files.
