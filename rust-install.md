rfikki@ROCKY-STRIX-ASUS:~$ curl https://sh.rustup.rs -sSf | sh
info: downloading installer

Welcome to Rust!

This will download and install the official compiler for the Rust programming
language, and its package manager, Cargo.

It will add the cargo, rustc, rustup and other commands to Cargo's bin
directory, located at:

  /home/rfikki/.cargo/bin

This path will then be added to your PATH environment variable by modifying the
profile file located at:

  /home/rfikki/.profile

You can uninstall at any time with rustup self uninstall and these changes will
be reverted.

Current installation options:

   default host triple: x86_64-unknown-linux-gnu
     default toolchain: stable
  modify PATH variable: yes

1) Proceed with installation (default)
2) Customize installation
3) Cancel installation
>1

info: syncing channel updates for 'stable-x86_64-unknown-linux-gnu'
info: latest update on 2019-05-23, rust version 1.35.0 (3c235d560 2019-05-20)
info: downloading component 'rustc'
 88.4 MiB /  88.4 MiB (100 %)  43.7 MiB/s in  2s ETA:  0s
info: downloading component 'rust-std'
 59.1 MiB /  59.1 MiB (100 %)  44.0 MiB/s in  1s ETA:  0s
info: downloading component 'cargo'
info: downloading component 'rust-docs'
info: installing component 'rustc'
 88.4 MiB /  88.4 MiB (100 %)  16.3 MiB/s in  5s ETA:  0s
info: installing component 'rust-std'
 59.1 MiB /  59.1 MiB (100 %)  19.4 MiB/s in  3s ETA:  0s
info: installing component 'cargo'
info: installing component 'rust-docs'
 10.4 MiB /  10.4 MiB (100 %)   7.7 MiB/s in  1s ETA:  0s
info: default toolchain set to 'stable'

  stable installed - rustc 1.35.0 (3c235d560 2019-05-20)


Rust is installed now. Great!

To get started you need Cargo's bin directory ($HOME/.cargo/bin) in your PATH
environment variable. Next time you log in this will be done automatically.

To configure your current shell run source $HOME/.cargo/env
rfikki@ROCKY-STRIX-ASUS:~$
