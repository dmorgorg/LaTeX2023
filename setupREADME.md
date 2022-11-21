1. To install texlive on ubuntu: https://fahim-sikder.github.io/post/installing-texlive-latest-ubuntu/

1. To enable access to gnuplot from texlive, add `shell_escape = t` to `/usr/local/texlive/2022/texmf.cnf` using `sudo vim texmf.cnf`!

1. To access `tlmgr`, the texlive package manager, as root (which is not in the path) `sudo env PATH="$PATH" tlmgr --gui`