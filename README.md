# StackFox SDKs

This repository contains the standalone StackFox SDKs.

It includes:

- the in-progress Luau SDK for Roblox
- the future JavaScript SDK

## Packages

- `stackfox/sdk-js`: Placeholder npm package for a future JS/TS SDK
- `stackfox/sdk-luau`: Wally package for the Luau SDK

## Requirements

- Node.js and npm when working on the JavaScript SDK
- Rokit when working on the Luau SDK

## Setup

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

## Contributing

Contributions are welcome. Keep package docs and root docs aligned when you add or remove SDK capabilities so the repository stays coherent as the SDK surface grows.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
