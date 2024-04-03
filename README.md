# Runic WASM

Expose functions from [the Runic parser library](https://github.com/a-barjo/runic) to the JavaScript global scope using WebAssembly.

## Installation

`go get github.com/a-barjo/runic_wasm`

## Build

```sh
GOOS=js GOARCH=wasm go build -o main.wasm
```
