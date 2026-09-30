# Raspberry Pi Hello World

A small Node.js project written in TypeScript and compiled with `tsc`.

## Run it

Install Node.js and npm on the Raspberry Pi, then from this directory run:

```sh
npm install
npm run build
npm start
```

The program prints `Hello, Raspberry Pi!`. The TypeScript source is in `src/index.ts`; `tsc` writes the runnable JavaScript to `dist/`.
