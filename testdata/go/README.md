# Compiling the Go guest example

To compile this example WASM guest you must have the latest version of TinyGo installed.

```console
$ tinygo build -o hello.wasm -target wasi main.go
```

The `hello.wasm` file included in this directory was compiled with TinyGo v0.19.0.
