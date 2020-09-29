You may update specific submodules with for example:

```
git submodule update --remote --merge libopencm3
```

Or go in to the lib, in this example libopencm3 and perform a normal
pull and then commit on the directory:

```
git pull
git submodule update --init
```

`git pull` changes which commit their submodule directory points to.
`git submodule update` actually merges in the new code.
