# zksync-foundry-template

zksync foundry template contract

## Install deps

Tested it on Linux

```sh
git clone https://github.com/matter-labs/foundry-zksync.git 
cd foundry-zksync
cargo build --release -p foundry-cli
cp ./target/release/zkcast ~/bin # copy to your own PATH
cp ./target/release/zkforge ~/bin
```

## Build

```sh
zkforge zk-build --use 0.8.19 # default 0.8.20 will fail
```

## Refs

* <https://github.com/sammyshakes/sample-fzksync-project>
