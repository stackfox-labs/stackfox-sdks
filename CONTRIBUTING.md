# Contributing

## Setup

Choose the package you are changing and use its native tooling.

JavaScript SDK:

1. Change into `packages/sdk-js`.
2. Run `npm install` if that package starts declaring dependencies.

Luau SDK:

1. Change into `packages/sdk-luau`.
2. Run `rokit install` to install the Roblox CLI tools.

## Verification

Run the checks that exist for the package you touched.

If you change the Luau SDK, also verify that the Wally manifest, Rojo project files, and example place files still match the package layout.
