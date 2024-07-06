# Setting up the Authoring Environment

## Setting up VS Code
VS Code is the recommended tool for working with the markdown source files of these docs pages, but almost any text editor can be used.

## Setting up mdBook
These docs pages are built using mdBook, a free and open source tool built by the Rust community for building easy documentation.
While having mdBook installed on your computer is by no means necessary to help contribute to these docs, it does improve the writing
experience by allowing you to live preview the docs pages with your changes as you make them, before a full deploy to the docs site happens.

mdBook is built in Rust, so the best way to install it is using the rust package manager, cargo, to compile and install mdBook locally.

### Installing Rust on Windows
1) Go to the [download page for rustup](https://rustup.rs/) and download rustup-init.exe
2) Run the installer and follow the directions to install the rust toolchain and cargo

### Installing Rust on Linux
Rust can be installed on your system both by using the [rustup installer](https://rustup.rs/) or by using your system's package manager.

You will also need to add the cargo binaries directory `~/.cargo/bin` to your $PATH variable manually.
This can be done by adding this line to your `~/.profile` file:
```
export PATH=$HOME/.cargo/bin:$PATH
```

### Installing mdBook
Open a command prompt or terminal window and run the following command:
```bash
cargo install mdbook
```
You can then verify that mdBook is correctly installed simply by running this command:
```bash
mdbook
```
