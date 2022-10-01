# computercraft-extension-pack

This is the official extension pack for ComputerCraft and CC:Tweaked development. It comes with a few extensions to make writing Lua programs for CC significantly easier:

* [ComputerCraft API autocomplete extension](https://marketplace.visualstudio.com/items?itemName=jackmacwindows.vscode-computercraft) by [JackMacWindows](https://marketplace.visualstudio.com/publishers/jackmacwindows)
* [Lua Language Server](https://marketplace.visualstudio.com/items?itemName=sumneko.lua) by [sumneko](https://marketplace.visualstudio.com/publishers/sumneko)

You may also be interested in manually installing these optional extensions:

* [Share Code](https://marketplace.visualstudio.com/items?itemName=RolandGreim.sharecode) by [RolandGreim](https://marketplace.visualstudio.com/publishers/RolandGreim) &ndash; To upload your code to [Pastebin](https://pastebin.com/) or [GitHub Gist](https://gist.github.com/).

## Configuration

The following configuration is recommended (<kbd>F1</kbd> → `Preferences: Open Settings (JSON)`):

```json
    "Lua.runtime.version": "Lua 5.2",
    "Lua.diagnostics.globals": [
        "bit",
        "colors",
        "colours",
        "commands",
        "disk",
        "fs",
        "gps",
        "help",
        "http",
        "keys",
        "multishell",
        "paintutils",
        "parallel",
        "peripheral",
        "pocket",
        "rednet",
        "redstone",
        "rs",
        "settings",
        "shell",
        "term",
        "textutils",
        "turtle",
        "vector",
        "window",
        "_CC_DEFAULT_SETTINGS",
        "_HOST",
        "printError",
        "write",
        "read",
        "sleep"
    ],
    "Lua.runtime.builtin": {
        "bit32": "enable",
        "bit": "disable",
        "utf8": "enable"
    },
    "Lua.diagnostics.disable": [
        "undefined-field",
        "deprecated"
    ],
```
