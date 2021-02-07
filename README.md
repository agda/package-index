# Package Index for Agda Libraries

This repository is an index of libraries for the package manager
[Agda-Pkg](http://github.com/agda/agda-pkg). I do the indexing
manually at the moment, but this can change in the future. The number
of libraries here is still small, and the libraries releases are not very
often.

This is the structure of a library in this index:

```
└── standard-library
  ├── url
  └── versions
    ├── v1.4
    │ ├── sha1
    │ └── standard-library.agda-lib
    └── v0.5
      ├── sha1
      └── standard-library.agda-lib
```

This index is used by [Agda-Pkg](http://github.com/agda/agda-pkg)
to install automatically the library you want.

```
$ pip3 install agda-pkg
$ apkg init
$ apkg --help
```

