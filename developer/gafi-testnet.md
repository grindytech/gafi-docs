# Gafi Testnet

Steps to run Testnet



1.  Download Gafi Testnet

    ```
    wget https://github.com/grindytech/gafi/archive/refs/tags/testnet-v0.2.8.tar.gz

    tar -xf testnet-v0.2.8.tar.gz

    cd gafi-testnet-v0.2.8
    ```
2. Build Gafi\
   [How to build Gafi](https://wiki.gafi.network/developer/how-to-run-gafi-node)\

3.  Join Testnet

    ```
    ./target/release/gafi-node \
    --base-path tmp  \
    --chain resources/gafiTestnetSpecRaw.json \
    --port 30336 \
    --unsafe-rpc-external \
    --unsafe-ws-external \
    --ws-port 9944 \
    --rpc-port 9933 \
    --rpc-cors "all" \
    --bootnodes /ip4/45.32.123.147/tcp/30336/p2p/12D3KooWMxnVrSjwssvmsVNDcDH7sirKRXXJPbuSYL2ie4Jc8x4K \
    --pruning=archive
    ```
