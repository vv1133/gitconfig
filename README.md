##Creating source files##

Any file which matches the shell glob _* will be linked into $HOME as a symlink with the first _ replaced with a .

For example:

`_gitconfig`

becomes

`${HOME}/.gitconfig`
