# Mavins Lee: Deadly Simple Haskell Scotty Tutorial

Source code for the tutorial [API REST em Haskell usando o
Scotty](https://mavins.com.br/blog/api-rest-em-haskell-usando-o-scotty) (PT-BR)
written by [Alexandre Lucchesi](https://github.com/alexandrelucchesi).

## Building and running

Make sure you have [Stack](https://docs.haskellstack.org/en/stable/README/)
installed and run:

```bash
$ git clone https://github.com/alexandrelucchesi/haskell-scotty-tutorial.git
$ cd haskell-scotty-tutorial
$ stack build
$ stack exec -- mavins-lee
```

Optionally, instead of running `build` and `exec`, you can load the application
into GHCi with `stack ghci` and call `main` from there. This is particurlaly
useful during development.
