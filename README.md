<div align="center">
  <h1><code>Conway's GAME OF LIFE</code></h1>

  <strong>Rust - Wasm - JavaScript.</strong>

  <sub>Built with 🦀🕸 by <a href="https://rustwasm.github.io/">The Rust and WebAssembly Working Group</a></sub>
</div>

## Rules
Every cell interacts with its eight neighbours, which are the cells that are horizontally, vertically, or diagonally adjacent. At each step in time, the following transitions occur:
- Any live cell with fewer than two live neighbours dies, as if caused by underpopulation.

- Any live cell with two or three live neighbours lives on to the next generation.

- Any live cell with more than three live neighbours dies, as if by overpopulation.

- Any dead cell with exactly three live neighbours becomes a live cell, as if by reproduction.


## 🚴 Usage

Inside main directory (**rustwasm_game-of-life/**)
```
cargo update
cargo build
wasm-pack build
```

Inside www directory (**www/**)
```
npm install
npm run start
```
Development server: **localhost:8000/**

### Template: 
[wasm-pack-template](https://github.com/rustwasm/wasm-pack-template)
and
[wasm-app](https://github.com/rustwasm/create-wasm-app)


### Credit: https://rustwasm.github.io/docs/book/

