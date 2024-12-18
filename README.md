# Unsafe Raw Pointer Modification of a Vector in Rust

This repository demonstrates a common error in Rust: using raw pointers to modify a vector's contents. While raw pointers offer low-level control, they're easily misused, causing undefined behavior or memory corruption.

The `bug.rs` file showcases the problematic code, while `bugSolution.rs` provides a safer, more idiomatic solution.

**Key takeaway:**  Always prefer safe Rust methods for vector manipulation over unsafe raw pointers unless absolutely necessary and you fully understand the risks.