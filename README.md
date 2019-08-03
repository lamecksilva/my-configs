<p>
  <h1 align="center">Custom Scripts</h1>
</p>

> Repository to save some commands and scripts

---

## Make executable file run in any path:

To run this scripts in any dir, cp the files to `/bin`, e.g:

```sh
$ sudo cp gitpush /bin
```

_**OBS**: The files must have `+x` permissions._

## Save credentials to git:

#### Edit git configs in VSCODE:

```sh
$ git config --global core.editor "code --wait"
$ git config --glboal -e
```

OR

```sh
$ git config credential.helper store
$ git pull

# Again, git pull to test
$ git pull
```

OR:

```sh
git config --global user.email "lameck@lsdev.com"
git config --global user.name "lamecksilva"
```

## Interesting Links:

- [Complete list of github markdown emoji markup :v:](https://gist.github.com/rxaviers/7360908)
