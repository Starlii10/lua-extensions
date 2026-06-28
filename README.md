# Scratch Everywhere! Lua Extensions

A collection of Lua extensions for Scratch Everywhere!, including ports of
TurboWarp extensions.

> [!WARNING]
> Custom extensions in Scratch Everywhere! are still in development.

# Building

To build a Lua extension, use
[`seec`](https://github.com/ScratchEverywhere/seec):

```bash
seec -i /path/to/main.lua -m /path/to/meta.json -o /path/to/output.see
```

Alternatively, simply run `seec` in the directory with `main.lua` and
`meta.json`:

```bash
cd /path/to/extension
seec
```

Then it should be as simple as copying the `.see` file to
`scratch-everywhere/extensions` and running Scratch Everywhere!!
