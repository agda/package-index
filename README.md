# Package Index for Agda Libraries

This an index of libraries for the package manager [Agda-Pkg](http://github.com/agda/agda-pkg).


<img src="https://github.com/agda/agda-pkg/raw/master/assets/installation.gif"
 alt="agda package manager installation" width=256 align="right" />
  

This is the structure of a library in this index:

```
└── standard-library
  ├── url
  └── versions
    ├── v0.16.1
    │ ├── sha1
    │ └── standard-library.agda-lib
    └── v0.17
      ├── sha1
      └── standard-library.agda-lib
```

### Libraries for Agda-Pkg

```
$ pip3 install agda-pkg
$ apkg init
$ apkg list     
```

In the future, we'll provide an
[integration](https://github.com/jonaprieto/agda-pkg-server) with
Github to make all this process automatically for indexing your
library. For now, we must do this manually.
