# How to run Gafi Node?

Following are the steps to help you build the Gafi node:

1. **Setup environment**\
   **- Install Rust**\
   $ _curl https://sh.rustup.rs -sSf | sh_\
   $ _source \~/.cargo/env_\
   __\
   __\
   __**- Rust toolchain**\
   $ _rustup default stable_\
   $ _rustup update_\
   \
   **- Rust nightly**\
   $ _rustup update nightly_\
   $ _rustup target add wasm32-unknown-unknown --toolchain nightly_\
   __\
   __**- Verify**\
   _$ rustc --version_\
   $ _rustup show_
2. **Build Gafi Node**\
   **- Clone gafi repository**\
   ****$ **** _git clone_ [_https://github.com/cryptoviet/gafi.git_](https://github.com/cryptoviet/gafi.git)__\
   _$ cd gafi/_\
   _$ make build-dev_
3. **Run Gafi**\
   _$ make run-dev_

__
