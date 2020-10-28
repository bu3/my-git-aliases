## Install

Download the file [`custom-alias`](custom-alias):

```sh
curl -O https://raw.githubusercontent.com/GitAlias/gitalias/master/gitalias.txt
```

Typical usage for a typical user:

  * Save this file as a dot file in your home directory: `~/.gitalias.txt`

  * `git config --global include.path ~/.gitalias.txt` in terminal.  Or manually edit your git config dot file in your home directory such as `~/.gitconfig`, include the path to this file.

Example file `~/.gitconfig` with an entry to include the file `~/.gitalias.txt`:

```gitalias
[include]
  path = gitalias.txt
```
