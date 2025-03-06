# Fork of [ejs-grammar](https://github.com/Digitalbrainstem/ejs-grammar) but like without any prongs

I don't know how to add this as a vscode extension, so I just took the `snippet.json` and created my own snippets.

## Installation

Windows: Place `html.json` in `%appdata%/Code/User/snippets`.
If snippets aren't appearing, add the following to `%appdata%/Code/User/settings.json`:

```
    "emmet.includeLanguages": {
        "ejs": "html",
    },
```

## Snippets

→ Denotes the `TAB` key.

| Snippet→    | Output                         | Remarks                                                           |
| ----------- | ------------------------------ | ----------------------------------------------------------------- |
| `ejs→`      | `<% %>` - No output tag        |
| `ejse→`     | `<%= %>` - Outputs HTML value. | This doesn't follow the other prefixes because `=` can't be used. |
| `ejs-→`     | `<%- %>` - Outputs unescaped   |
| `ejs--→`    | `include` statement            |
| `ejsforof→` | `for...of` Javascript Loop     |
