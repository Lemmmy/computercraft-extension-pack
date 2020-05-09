# computercraft-extension-pack

This is the official extension pack for ComputerCraft and CC:Tweaked development. It comes with a few extensions to make writing Lua programs for CC significantly easier:

* [ComputerCraft API autocomplete extension](https://marketplace.visualstudio.com/items?itemName=jackmacwindows.vscode-computercraft) by [JackMacWindows](https://marketplace.visualstudio.com/publishers/jackmacwindows)
* [Lua Language Server](https://marketplace.visualstudio.com/items?itemName=sumneko.lua) by [sumneko](https://marketplace.visualstudio.com/publishers/sumneko)

You may also be interested in manually installing these optional extensions:

* [Share Code](https://marketplace.visualstudio.com/items?itemName=RolandGreim.sharecode) by [RolandGreim](https://marketplace.visualstudio.com/publishers/RolandGreim) &ndash; To upload your code to [Pastebin](https://pastebin.com/) or [GitHub Gist](https://gist.github.com/).

## Configuration

The following configuration is recommended (<kbd>F1</kbd> → `Preferences: Open Settings (JSON)`):

```json
    "Lua.diagnostics.disable": [
        "unused-local",
        "lowercase-global",
        "unused-function"
    ],
    "Lua.diagnostics.severity": {
        "redefined-local": "Warning"
    },
    "Lua.diagnostics.globals": [
        "printError",
        "sleep",
        "read",
        "write",
        "print",
        "colours",
        "colors",
        "commands",
        "disk",
        "fs",
        "gps",
        "help",
        "http",
        "paintutils",
        "parallel",
        "peripheral",
        "rednet",
        "redstone",
        "keys",
        "settings",
        "shell",
        "multishell",
        "term",
        "textutils",
        "turtle",
        "pocket",
        "vector",
        "bit32",
        "window",
        "_CC_DEFAULT_SETTINGS",
        "_HOST",
        "_VERSION",
        "_"
    ],
    "Lua.runtime.version": "Lua 5.1",
```