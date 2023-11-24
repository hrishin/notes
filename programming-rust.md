# Chapter 1: system programmers can have nice things

- Same restrictions that ensures memory safetyin Rust also ensures that Rust programs are free of data races. Programmer can share the data between threads as long its not changing. Data that does
change can only be accessed using synchronization primitives and all tradional concurrency premitives are available.
- Language is designed to exploting the abilities of multicore machines. Its designed to distribute the complex loads across polls of processors, use lock-free synchronization mechanism likfe READ-COPU-UPDATE and more.
- The language is designed with efficient defaults and gives programmer the ability to control the how memory gets used and how processors attention is spent
- Cargo takes care of downloading the library, together with other dependent library it uses in turn and linking the whole lot together.
