# test-rustaceanvim

A dynamic linking test project for rustaceanvim.

Windows use will require:

```shell
cargo install -f cargo-binutils
rustup component add llvm-tools-preview
```

to let `cargo` use LLD's linker. See https://bevyengine.org/learn/book/getting-started/setup/.
