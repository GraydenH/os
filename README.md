##before running
`rustup override set nightly`
`rustup target add thumbv7em-none-eabihf`
`rustup component add llvm-tools-preview`

##build
`cargo bootimage -Zbuild-std  --target x86_64-os.json`
