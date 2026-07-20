# Scratch Everywhere! Lua Extensions

A collection of Lua extensions for Scratch Everywhere!, including ports of
TurboWarp extensions.

> [!WARNING]
> Custom extensions in Scratch Everywhere! are still in development.

# Building

To build the Lua extensions, use `bun`:

```sh
bun build.ts
```

The compiled extensions can be found in the `bin` folder.

Then it should be as simple as copying the `.see` files to
`scratch-everywhere/extensions` and running Scratch Everywhere!!

# Using in an Editor

`bun` will also build JavaScript versions of the extensions. These are intended
for use in a Scratch editor that supports loading custom extensions.

> [!NOTE]
> These extensions will likely not work correctly in the editor.
