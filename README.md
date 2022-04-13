# vscode-rust-analyzer-config

I don't like a inlay hints, so I try to disabled it, mostly I disabled parameter hints, but left type hints (because its same as you declare variables with a type).

Disabled All

```
"rust-analyzer.inlayHints.enable": false
```

Type Hints

![screenshots/type-hint.png]

```
"rust-analyzer.inlayHints.typeHints": false
```

Parameter Hints

![screenshots/parameter-hints.png]

```
"rust-analyzer.inlayHints.parameterHints": false
```
