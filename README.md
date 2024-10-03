# git-learning

### [Multiline Commit for Windows](https://dev.to/behainguyen/windows-10-multi-line-git-commit-messages-3je6)

## Commit Title

The title will be inferred by git from the first line in the comment. For example this

`git commit -m "Edit main.c" -m "add function main"`

will produce commit with title "Edit main.c" and a detail comment "add function main"

## Commit with multiple lines


```
git commit -m "Edit main.c" -m "add function main"^
"in the main call printf"^
"in printf present Hello world"^
```

## Additional information regarding markdown language formatting rules

### [Markdown basic syntax guide](https://www.markdownguide.org/basic-syntax/\#code)

Small change
Uno mass