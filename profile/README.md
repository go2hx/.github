*Work in progress, check back later!*

# Working Haxelibs (precompiled)

## [lzma](https://github.com/go2hx/lzma) [[api]](https://go2hx.github.io/lzma/api) [[examples]](https://github.com/go2hx/lzma/blob/master/samples/)
LZMA compression/decompression
```sh
haxelib git go2hx_lzma https://github.com/go2hx/lzma
```

## [regexp2](https://github.com/go2hx/regexp2) [api](https://go2hx.github.io/regexp2/api) [[examples]](https://github.com/go2hx/regexp2/blob/master/samples/)
A full-featured regex engine, based on the .NET engine 
```sh
haxelib git go2hx_regexp2 https://github.com/go2hx/regexp2
```

## [Go's std](https://github.com/go2hx/go2hx/blob/master/stdgo) [api](https://go2hx.github.io/api) [[examples]](https://github.com/go2hx/go2hx.github.io/tree/master/samples/cases)
```sh
haxelib git go2hx https://github.com/go2hx/go2hx
```
``stdgo.X``, where ``X`` is the stdlib, [Table of working stdlibs](https://go2hx.github.io/).
```haxe
trace(stdgo.unicode.Unicode.isGraphic('x'.code));
trace(stdgo.image.color.Color.yCbCrToRGB(81, 240, 90)); // red
```
