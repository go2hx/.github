# Working Haxelibs (precompiled)

## [harmonica](https://github.com/go2hx/harmonica) [[example]](https://github.com/go2hx/harmonica/blob/master/Example.hx) ( original [[go library]](https://github.com/charmbracelet/harmonica) )
An agnostic physics based animation library
```sh
haxelib git go2hx_harmonica https://github.com/go2hx/harmonica
```
![example](https://github.com/go2hx/harmonica/blob/master/example.gif)

## [regexp2](https://github.com/go2hx/regexp2) [[api]](https://go2hx.github.io/regexp2/api/github_dot_com/dlclark/regexp2/Regexp2.html) [[example]](https://github.com/go2hx/regexp2/blob/master/Example.hx) ( original [[go library]](https://github.com/dlclark/regexp2) )
A full-featured regex engine, based on the .NET engine 
```sh
haxelib git go2hx_regexp2 https://github.com/go2hx/regexp2
```

## [Go's standard library](https://github.com/go2hx/go2hx/blob/master/stdgo) [[api]](https://go2hx.github.io/api) [[examples]](https://github.com/go2hx/go2hx.github.io/tree/master/samples/cases) ( original [[go documentation]](https://pkg.go.dev/std) )
```sh
haxelib git go2hx https://github.com/go2hx/go2hx
```
``stdgo.X``, where ``X`` is the stdlib, [Table of working stdlibs](https://go2hx.github.io/).
```haxe
trace(stdgo.unicode.Unicode.isGraphic('x'.code)); // true
trace(stdgo.image.color.Color.yCbCrToRGB(81, 240, 90)); // red
```
