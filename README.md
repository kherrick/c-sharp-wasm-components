# [C# Wasm Components](https://kherrick.github.io/c-sharp-wasm-components/)

## dependencies

* [dotnet](https://dotnet.microsoft.com/en-us/download)
* [wasmtime](https://wasmtime.dev/)
* [jco](https://github.com/bytecodealliance/jco#readme)
* [node](https://nodejs.org/en/download) ([npx](https://docs.npmjs.com/cli/v8/commands/npx))

## build

`dotnet build`

## run

`wasmtime run --invoke 'add(1, 2)' bin/Debug/net10.0/wasi-wasm/publish/c-sharp-wasm-components.wasm`

## transpile

`jco transpile bin/Debug/net10.0/wasi-wasm/publish/c-sharp-wasm-components.wasm -o out-dir`

## view

`npx serve .`
