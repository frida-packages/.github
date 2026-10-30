Packages for building on [Frida](https://github.com/frida/frida), published to
npm. Install them in your agent project with `npm install`, or search and
install with `frida-pm`.

## Runtime bridges

| Package | Description |
|---|---|
| [frida-java-bridge](https://github.com/frida-packages/frida-java-bridge) | Java runtime interop |
| [frida-objc-bridge](https://github.com/frida-packages/frida-objc-bridge) | Objective-C runtime interop |
| [frida-swift-bridge](https://github.com/frida-packages/frida-swift-bridge) | Swift runtime interop |
| [frida-electron-bridge](https://github.com/frida-packages/frida-electron-bridge) | Electron/Node.js runtime interop |
| [frida-amiga-bridge](https://github.com/frida-packages/frida-amiga-bridge) | Amiga emulator instrumentation |

## Agent development

| Package | Description |
|---|---|
| [frida-compile](https://github.com/frida-packages/frida-compile) | Compile an agent made of one or more modules |
| [@frida/injest](https://github.com/frida-packages/injest) | Test runner for code running inside GumJS, with a VS Code extension |
| [frida-itrace](https://github.com/frida-packages/frida-itrace) | Instruction tracer |
| [frida-elf-pattern, frida-macho-pattern, frida-pe-pattern](https://github.com/frida-packages/frida-patterns) | ImHex patterns for the executable formats Frida meets |

## Node.js compatibility

Node.js built-in modules for GumJS, so that npm packages written for Node.js
work in your agent. Frida's compiler, which `frida-compile` uses, maps Node.js
built-ins to these automatically.

[assert](https://github.com/frida-packages/gumjs-assert) ·
[base64-js](https://github.com/frida-packages/gumjs-base64) ·
[buffer](https://github.com/frida-packages/gumjs-buffer) ·
[crosspath](https://github.com/frida-packages/gumjs-crosspath) ·
[crypto](https://github.com/frida-packages/gumjs-crypto) ·
[depd](https://github.com/frida-packages/gumjs-depd) ·
[diagnostics_channel](https://github.com/frida-packages/gumjs-diagnostics-channel) ·
[events](https://github.com/frida-packages/gumjs-events) ·
[fetch](https://github.com/frida-packages/gumjs-fetch) ·
[http](https://github.com/frida-packages/gumjs-http) ·
[http-parser-js](https://github.com/frida-packages/gumjs-http-parser) ·
[https](https://github.com/frida-packages/gumjs-https) ·
[ieee754](https://github.com/frida-packages/gumjs-ieee754) ·
[net](https://github.com/frida-packages/gumjs-net) ·
[os](https://github.com/frida-packages/gumjs-os) ·
[path](https://github.com/frida-packages/gumjs-path) ·
[process](https://github.com/frida-packages/gumjs-process) ·
[punycode](https://github.com/frida-packages/gumjs-punycode) ·
[querystring](https://github.com/frida-packages/gumjs-querystring) ·
[readable-stream](https://github.com/frida-packages/gumjs-readable-stream) ·
[reserved-words](https://github.com/frida-packages/gumjs-reserved-words) ·
[stream](https://github.com/frida-packages/gumjs-stream) ·
[string_decoder](https://github.com/frida-packages/gumjs-string-decoder) ·
[timers](https://github.com/frida-packages/gumjs-timers) ·
[tty](https://github.com/frida-packages/gumjs-tty) ·
[url](https://github.com/frida-packages/gumjs-url) ·
[util](https://github.com/frida-packages/gumjs-util) ·
[vm](https://github.com/frida-packages/gumjs-vm) ·
[web-streams](https://github.com/frida-packages/gumjs-web-streams)

All published as `@frida/<name>`.

## App-side

| Package | Description |
|---|---|
| [@frida/react-use-r2](https://github.com/frida-packages/react-use-r2) | React hook for radare2 integrations, used by the `frida-trace` web UI |
| [@frida/rtc-stream](https://github.com/frida-packages/rtc-stream) | Node.js Duplex stream from a WebSocket or RTCDataChannel |
