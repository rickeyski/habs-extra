# Extra Haskell packages repository for Arch Linux

These are [cblrepo](http://hackage.haskell.org/package/cblrepo) files to build the repository.

If you want to check and build this, you'll need [cblrepo](http://hackage.haskell.org/package/cblrepo) and *Cabal Install*. If you are looking for the actual repo add this to your `/etc/pacman.conf` **before** `[Extra]`:

~~~~~ { .bash }

[haskell]
Server = http://xsounds.org/~haskell/$arch

[haskell-extra]
Server = http://archhaskell.mynerdside.com/$repo/$arch

~~~~~

Please note that this is a temporary repository. Hopefully it will be merged with the main one.
