# StackFox SDKs

This repository contains the standalone StackFox SDKs.

The packages stay independent because they target different languages and toolchains.

It includes:

- the in-progress Luau SDK for Roblox
- the reserved package location for the future JavaScript SDK

## Packages

- `@stackfox/sdk-js`: placeholder npm package for a future JS/TS SDK in `packages/sdk-js`
- `stackfox/sdk`: Wally package for the Luau SDK in `packages/sdk-luau`

## Requirements

- Node.js and npm when working on the JavaScript SDK
- Rokit when working on the Luau SDK

## Setup

Use the tooling required by the package you are changing.

JavaScript SDK:

```bash
cd packages/sdk-js
npm install
```

Luau SDK:

```bash
cd packages/sdk-luau
rokit install
```

## Verification

Run package-local checks for the SDK you changed.

Current status:

- `packages/sdk-js` is still a placeholder package and does not ship implementation scripts yet.
- `packages/sdk-luau` currently ships Roblox tooling config instead of an npm-based test pipeline.

If you change the Luau SDK, verify the Rojo project files, Wally manifest, and example place content still match the source layout.

## Repository Layout

- `packages/sdk-js`: reserved npm package for the future JavaScript SDK
- `packages/sdk-luau`: Luau SDK source, Rojo project files, Wally manifest, and example place content

## Contributing

Contributions are welcome. Keep package docs and root docs aligned when you add or remove SDK capabilities so the repository stays coherent as the SDK surface grows.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
