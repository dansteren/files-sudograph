# Files

A monorepo for the files frontend, and a IC backend.

## Setup

1. Create a dfx.json file
2. Create a canisters folders with some canister folders in it.
3. Create an html file in one.
4. Create a package.json
5. Add an empty build script to package.json
6. Use `DFX_VERSION=0.7.0 sh -ci "$(curl -fsSL https://sdk.dfinity.org/install.sh)"`
7. `dfx deploy`
8. Add the rust wasm32 compilation target: `rustup target add wasm32-unknown-unknown`

## Getting Started

1. Git clone
2. dfx deploy

## Things to fix (Forum Posts)

* Add a full link to a canister in the output for local dev
* Search up for closest dfx.json. So if you're in a sub folder it still works
* add custom aliases to dfx command. For example `dfx d` for `dfx deploy`.
