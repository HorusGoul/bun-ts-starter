# Bun TypeScript Starter

## Getting started

1. Clone this repository and open it

```bash
$ bun create HorusGoul/bun-ts-starter your-next-project
$ cd your-next-project
```

2. Install dependencies

```bash
$ bun install
```

3. Launch the dev mode

```bash
$ bun dev
```

4. You can start coding! The entry point is located in `src/index.ts`.

## What's preconfigured?

This starter intends to be slim so it's not a nightmare to remove or change stuff. That's why there are just a few things preconfigured:

- TypeScript
- ESLint
- Prettier with defaults
- A few npm scripts

## Scripts

- `bun dev`. Runs the project in dev mode, which means that it won't check types and will restart with every change you make.
- `bun start`. Runs the program.
- `bun typecheck`. Runs type-checking against the project. Ideally, you implement this in your CI pipeline.
- `bun lint`. Runs ESLint.
- `bun lint:fix`. Run ESLint and automatically fixes the errors that can be fixed. This includes formatting with Prettier.
- `bun test`. Runs the tests using the built-in test runner.
- `bun test:coverage`. Runs the tests and generates a coverage report.

## What to do next

Adapt the configuration to your needs and start coding!

This package uses my own ESLint and TypeScript configurations. If you want to use your own, you can take mine as a reference, or just remove them and start from scratch.

Since my configurations aren't available on GitHub yet, you can find them on npm:

- [@horus.dev/eslint-config](https://www.npmjs.com/package/@horus.dev/eslint-config?activeTab=code). You want to take a look at `base.js` and `package.json`.
- [@horus.dev/tsconfig](https://www.npmjs.com/package/@horus.dev/tsconfig?activeTab=code). `bun.json` is the file that this starter uses.
