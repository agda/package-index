# Package Index for Agda Libraries

This is the package index for the package manager [Agda-Pkg](http://github.com/apkgbot/agda-pkg).


<img src="https://github.com/apkgbot/agda-pkg/raw/master/assets/installation.gif"
 alt="agda package manager installation" width=256 align="right" />
  

Nowadays, if you want to make available your library, please
make a PR following the structure showed in one of the libraries in the `src` folder.
Otherwise, open an issue, we will try to add the package as soon as I can.

### Libraries

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
fotc                 apia-1.0.2   
hott-core            937e227      
hott-theorems        937e227      
standard-library     v0.17        
```

In the future, we'll provide an integration with Github to make
all this process automatically. This Github bot is already
[working in progress](https://github.com/jonaprieto/agda-pkg-server).