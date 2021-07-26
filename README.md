# spimjs

A rawer fork of [JsSpim](https://shawnzhong.github.io/JsSpim/)'s [emscripten](https://emscripten.org/)-generated SPIM that's more like the [TIO SPIM runner](https://tio.run/#spim), but faster because it runs in the browser.

### See also

- [Spim](http://spimsimulator.sourceforge.net/)
- [Spim source on TIO](https://github.com/TryItOnline/spim)

### TODO

- Re-implement code/stack/register inspection and single-stepping from the original JsSpim
- Run on server and accept POST requests of code and stdin (no need for wasm, just build SPIM from source and host on Glitch, for example)
- Codemirror editor/better UI
