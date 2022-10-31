# How to run Gafi Node?

Following are the steps to help you build the Gafi node on **Linux**:

1. **Setup environment**

**- Install dependencies**

```
$ sudo apt update
$ sudo apt install clang
$ sudo apt-get install build-essential libssl-dev
```

**- Install Rust**

```
$ curl https://sh.rustup.rs -sSf | sh
$ source ~/.cargo/env
```

**- Rust toolchain**

```
$ rustup default stable
$ rustup update
```

**- Rust nightly**

```
$ rustup update nightly
$ rustup target add wasm32-unknown-unknown --toolchain nightly
```

**- Verify**

```
$ rustc --version
$ rustup show
```

_**- CMake:**_

```
$ wget https://github.com/Kitware/CMake/releases/download/v3.20.0/cmake-3.20.0.tar.gz
$ tar -zxvf cmake-3.20.0.tar.gz
$ cd cmake-3.20.0
$ ./bootstrap
$ make
$ sudo make install
$ cmake --version
```

1.  **Clone Gafi**

    ```
    $ git clone https://github.com/grindytech/gafi.git
    $ cd gafi/
    ```
2.  **Build Gafi Node**

    ```
    $ make build-dev
    ```
3.  **Run Gafi**

    ```
    $ make run-dev
    ```

__
