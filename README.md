# Fork of [ejs-grammar](https://github.com/Digitalbrainstem/ejs-grammar) 

Contains different syntax for some snippets

## Snippets

→ Denotes the `TAB` key.

| Changed | Snippet→   | Alternate  | Output                                                                                                  |
| --- | ---------- | --------   | ------------------------------------------------------------------------------------------------------- |
| ☑ | `ejs→`    | `<%`       | `<% %>` - No output tag                                                                                 |
| ☑ | `ejs=→`  | `<%=`      | `<%= %>` - Outputs HTML value                                                                           |
| ☑ | `ejs-→`  | `<%-`      | `<%- %>` - Outputs unescaped                                                                            |
| | `ejscom→`  | `<%#`      | `<%# %>` - Comment tag                                                                                  |
| | `ejslit→`  | `<%%`      | `<%% %>` - Outputs Literal <%                                                                           |
| ☑ | `ejs--→`  | `<%`       | `include` statement                                                                                       |
| | `ejsfor→`  | `<%`       | `for` Javascript Loop                                                                                             |
| ☑ | `ejsforof→`  |        | `for...of` Javascript Loop                                                                                             |
| | `ejseach→` | `<%`       | `forEach` Javascript Loop                                                                                     |
| | `ejsif→`   | `<%`       | `if` Statement with condition                                                                                     |
| | `ejselif→` | `<%`       | `else if` Statement - *Middle section only.* Assumes you have already written the first `if` statement. |
| | `ejselse→` | `<%`       | `else` Statement - *Middle section only.* Assumes you have already written the first `if` statement.    |
