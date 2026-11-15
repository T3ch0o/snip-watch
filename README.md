# snip-watch

The page people watch a [Snip](https://github.com/T3ch0o) screen share in. Open a share link
(`https://t3ch0o.github.io/snip-watch/#…`): the page connects straight to the sharing PC over
WebRTC. The part of the link after `#` stays in the browser and signs the handshake.

Built from `snipping-tool/viewer` (Rust compiled to WebAssembly); `snip_viewer.js` is the loader
wasm-bindgen generates.
