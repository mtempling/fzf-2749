# fzf-2749
## setup
    $ curl -sSL https://raw.githubusercontent.com/Ericsson/ove/master/setup | bash -s fzf https://github.com/mtempling/fzf-2749 main

## demo
    $ cd fzf
    $ source ove
    $ ove demo

## build and test
    $ cd fzf
    $ source ove
    $ ove fetch fzf
    $ ove buildme fzf
    $ ove test fzf

## tree
    $ tree -h
    .
    ├── [4.0K]  demo
    │   ├── [ 36K]  next-selection.log
    │   └── [ 783]  next-selection.timing
    ├── [1.0K]  LICENSE
    ├── [4.0K]  projects
    │   ├── [4.0K]  fzf
    │   │   ├── [  34]  build
    │   │   ├── [  40]  clean
    │   │   ├── [ 227]  install
    │   │   └── [ 242]  test
    │   └── [4.0K]  go
    │       ├── [ 229]  bootstrap
    │       └── [ 282]  install
    ├── [ 128]  projs
    ├── [ 832]  README.md
    ├── [ 178]  revtab
    └── [ 127]  SETUP
