##before running
```
rustup override set nightly
rustup target add thumbv7em-none-eabihf
rustup component add llvm-tools-preview
rustup default stable
```
##run
```
cargo bootimage
```
then
```
cargo run
```

or

```
qemu-system-x86_64 -drive format=raw,file=target/x86_64-os/debug/bootimage-os.bin
```
