![](https://avatars1.githubusercontent.com/u/28916798?s=64) AssemblyScript Examples
=======================

## Instructions

This repository contains one example per directory. All examples can be obtained by cloning the repository:

```
$> git clone https://github.com/AssemblyScript/examples.git
$> cd examples
```

Afterwards, select the example you'd like to run and follow the instructions in its README file.

## Low-level perspective

The following examples make use of AssemblyScript's low-level capabilities, i.e. to essentially write WebAssembly with a nicer syntax.

* [Conway's Game Of Life](./game-of-life) ([demo](https://assemblyscript.github.io/examples/game-of-life/))<br />
  An implementation of the game of life with slight modifications. Updates an image buffer in memory, that is then presented on a canvas.

  <img src="./game-of-life/preview.jpg" />

* [Mandelbrot Set](./mandelbrot) ([demo](https://assemblyscript.github.io/examples/mandelbrot/))<br />
  Computes 2048 offsets of a color gradient in memory, line by line, and presents the set using the gradient's actual colors, as computed on the JavaScript side, on a canvas.

  <img src="./mandelbrot/preview.jpg" />

* [Interference effect](./interference) ([demo](https://assemblyscript.github.io/examples/interference/))<br />
  Colin Eberhardt's and Ben Smith's WebAssembly interference effect, if it was written in AssemblyScript.

  <img src="./interference/preview.jpg" />

## High-level perspective

These examples cover slightly higher level aspects, like working with managed objects or interfacing with them.

* [N-body system](./n-body) ([demo](https://assemblyscript.github.io/examples/n-body/))<br />
  This is actually a benchmark - visualizing it just so happened.

  <img src="./n-body/preview.jpg" />

* [Loader](./loader)<br />
  Utilizes the [loader](https://docs.assemblyscript.org/basics/loader) to perform various common tasks on the WebAssembly/JavaScript boundary, like passing along strings and arrays between both worlds.

  <img src="./loader/preview.jpg" />

## Other

General examples showing how to utilize specific AssemblyScript features.

* [Browser SDK](./sdk)<br />
  Shows how to use the browser SDK to run the AssemblyScript compiler in the browser.

  <img src="./sdk/preview.jpg" />