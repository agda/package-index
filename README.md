# Package Index for Agda Libraries

This is the index of libraries for the package manager [Agda-Pkg](http://github.com/agda/agda-pkg).


<img src="https://github.com/agda/agda-pkg/raw/master/assets/installation.gif"
 alt="agda package manager installation" width=256 align="right" />
  

Nowadays, if you want to make available your library, please make a PR
following the structure showed in one of the libraries in the `src`
folder of this repository.

```
└── standard-library
        ├── url
        └── versions
            ├── v0.16.1
            │   ├── sha1
            │   └── standard-library.agda-lib
            └── v0.17
                ├── sha1
                └── standard-library.agda-lib
```

### Libraries included with Agda-Pkg

```
$ pip3 install agda-pkg
$ apkg init
$ apkg list --short
Name                 Last version 
----------------------------------
agda-metis           v0.2.1       
agda-prelude         4e0caf0      
agda-prop            v0.1.2       
agdarsec             v0.1.1       
alga-theory          0fdb96c
ataca                f12efee
cat                  v1.6.0
cubical              0b8372d        
fotc                 apia-1.0.2   
hott-core            937e227      
hott-theorems        937e227      
standard-library     v0.17        
```

In the future, we'll provide an
[integration](https://github.com/jonaprieto/agda-pkg-server) with
Github to make all this process automatically for indexing your
library. For now, we must do this manually.