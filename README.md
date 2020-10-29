## Install

Download the file [`custom-alias`](custom-alias):

```sh
curl -O https://raw.githubusercontent.com/bu3/my-git-aliases/main/custom-alias
```

Typical usage for a typical user:

  * Save this file as a dot file in your home directory: `~/.custom-alias`

  * `git config --global include.path ~/.custom-alias` in terminal.  Or manually edit your git config dot file in your home directory such as `~/.gitconfig`, include the path to this file.

Example file `~/.gitconfig` with an entry to include the file `~/.custom-alias`:

```gitalias
[include]
  path = .custom-alias
```
