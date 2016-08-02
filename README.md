# wonderland-fsharp-katas

Work in progress: one day, this will be an F# port of [@gigasquid](https://twitter.com/gigasquid)'s
[*wonderland-clojure-katas*](https://github.com/gigasquid/wonderland-clojure-katas).

![Alice and the tiny door](/images/alicedoor.gif)

>“Curiouser and curiouser!”
>-- ― Lewis Carroll, Alice in Wonderland

## How to Do the Katas

First, clone or fork this repo. All the katas are located in the folder `/wonderland-fsharp-katas/`. Each kata is an independent, self-contained F# script, and a companion instructions file (for example, alphabet-cipher.fsx and alphabet-cipher.md). Read the instructions, open the script file in your favorite editor or IDE, select all the code (<kbd>control</kbd>+<kbd>A</kbd>) and execute it (<kbd>Alt</kbd>+<kbd>Enter</kbd>) - and fix the code until the tests pass.

## Dependencies

If you don't have F# installed yet, follow the instructions from the **use** section of [**fsharp.org**](http://www.fsharp.org).

Before running any of the katas, you will need to download some dependencies, using [Paket](https://fsprojects.github.io/Paket/). A boostrapper will download the latest version of Paket, which in turn will download the package dependencies.

### On Windows

``` 
> .paket\paket.bootstrapper.exe
> .paket\paket.exe install
```

### On macOS/Linux 

```
> mono .paket/paket.bootstrapper.exe
> mono .paket/paket.exe install
```

## License

Copyright (c) 2015 Mathias Brandewinder, [MIT License](LICENSE).

Original Clojure version: Copyright © 2014 Carin Meier, distributed under the Eclipse Public License either version 1.0 or (at
your option) any later version.
