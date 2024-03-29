# crypt4gh-wasm

Encrypt a local file with [`crypt4gh`](https://github.com/EGA-archive/crypt4gh) using a web browser. **This is a proof of concept and not suitable for production**.

Requires a chromium browser (Google Chrome, Microsoft Edge) that supports the [File System Access API](https://developer.chrome.com/docs/capabilities/web-apis/file-system-access).

Files are encrypted with a hardcoded public key and randomly generated private keys.

The demo is [live on GitHub Pages](https://ebi-gdp.github.io/crypt4gh-wasm/). If you'd like to run a local development version:

```
$ cd crypt4gh-wasm
$ python3 -m http.server
```

And open `localhost:8000` in your web browser.
