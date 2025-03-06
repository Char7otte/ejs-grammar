# Fork of [ejs-grammar](https://github.com/Digitalbrainstem/ejs-grammar) but like without any prongs

I don't know how to add this as a vscode extension, so I just took the `snippet.json` and created my own snippets.

## Installation

Install the [EJS language support extension](https://marketplace.visualstudio.com/items?itemName=DigitalBrainstem.javascript-ejs-support) in order to create snippets for `.ejs` files. \
\
On the top left of vscode, go to `File > Preferences > Configure Snippets`. This will bring up the command palette, where you can type in `ejs` to create snippet for `.ejs` files. Paste the contents of the `snippets.json` file inside the newly created `.json` file.

## Snippets

→ Denotes the `TAB` key.

| Snippet→ | Output |
| --- | --- |
| `ejs→`    | `<% %>` - No output tag         |
| `ejs=→`  | `<%= %>` - Outputs HTML value    |
| `ejs-→`  | `<%- %>` - Outputs unescaped     |
| `ejs--→`  | `include` statement             |
| `ejsforof→`  | `for...of` Javascript Loop   |
