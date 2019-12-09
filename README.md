# ibc-demo

```
$ cd node-template
$ cargo build --release
$ cargo build --release -p relayer
$ ./target/release/node-template --base-path /tmp/chain-1 --dev
$ ./target/release/node-template --base-path /tmp/chain-2 --port 20333 --ws-port 8844 --grafana-port 8855 --dev
$ ./target/release/cli create-client 127.0.0.1:8844
$ ./target/release/relayer run 127.0.0.1:9944 127.0.0.1:8844
```