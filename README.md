# JsSpim-Lite

A rawer fork of [JsSpim](https://shawnzhong.github.io/JsSpim/) that's more like the [TIO SPIM runner](https://tio.run/#spim), but faster because it doesn't send a POST request.

See also:
- [Spim](http://spimsimulator.sourceforge.net/)
- [Spim source on TIO](https://github.com/TryItOnline/spim)
- [Emscripten](https://emscripten.org/)

TODO:
- Re-implement some of the register stuff from the original JsSpim
- Run on server and accept POST requests of code and stdin (no need for wasm, just build SPIM from source and host on Glitch, for example)
- Codemirror editor
