# git-mv
Rename your files in order to keep git history. Whenever you need to rebase or undo a git commit while using `$ git mv` the history is reverted back. This util will allow you to convert your files back to the original name then back into the new name in order for `git` to keep it's history

internally the code does
```bash
mv newname.js oldname.js
git mv oldname.js newname.js
```
