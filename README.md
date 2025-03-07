# Express app snippets for use in vscode

Contains snippets for EJS and express.

## Installation

Windows: Copy the `snippets` folder to `%appdata%/Code/User`.\
If EJS snippets aren't appearing, add the following to `%appdata%/Code/User/settings.json`:

```
    "emmet.includeLanguages": {
        "ejs": "html",
    },
```

## Snippets

→ Denotes the `TAB` key.\
Each header indicates the file type the snippet will work in.

### `.EJS`(HTML)

Basically `ejs` with whatever extra character to create a tag.

| Snippet→    | Output                         | Remarks                                                           |
| ----------- | ------------------------------ | ----------------------------------------------------------------- |
| `ejs→`      | `<% %>` - No output tag        |
| `ejse→`     | `<%= %>` - Outputs HTML value. | This doesn't follow the other prefixes because `=` can't be used, so I just took the first letter of 'equal'. Your finger should also already be on 'e'. |
| `ejs-→`     | `<%- %>` - Outputs unescaped   |
| `ejs--→`    | `include` statement            |
| `ejsforof→` | `for...of` Javascript Loop     |

### `.JS`

| Snippet→    | Output                         | Remarks                                                           |
| ----------- | ------------------------------ | ----------------------------------------------------------------- |
| `exp!`      | Boilerplate for Express, method-override, EJS, and Mongoose. | Follows the `!` prefix for HTML boilerplate snippet. A `package.json` file is included with the NPM packages.
| `appget` | `app.get("/", (req, res) => {})` |
| `appost` | `app.post("/", (req, res) => {})` | Typing `p` 3 times in a row is uncomfortable
| `appatch` | `app.patch("/", (req, res) => {})` | Typing `p` 3 times in a row is uncomfortable
| `appdel` | `app.delete("/", (req, res) => {})` |


## Credits

Originally forked from [ejs-grammar](https://github.com/Digitalbrainstem/ejs-grammar) with an edit to the snippet prefixes, but I don't know how to make it a vscode extension.
