A minimum WAT (WASM Text format) of a WASM Component printing `Hello, world!` via `wasi:cli/run` of WASI Preview 2.

```sh
wasm-tools parse helloworld.wat -o helloworld.wasm && wasmtime run helloworld.wasm
```
```
Hello, world!
```
