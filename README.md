# MertLang

MertLang is a programming language to develop Mert based programs.

# Usage

`.mert` file contains a list of arguments. Mert Compiler will parse them and will give you result.
```
# test.mert
Apple çok iyi.
Tesla efsane
```

```
$ mert test.mert
> Ooo Apple devrim abi.
> Abi Elon Musk ya.
```

If the program doesn't contain `Apple`, `Tesla`, `Steve Jobs`, `iPhone` or `Elon Musk` the compiler will throw error.

```
# test.mert
Microsoft efsane.
```

```
$ mert test.mert
An error occured:
  Abi ne alakası var ya.

$ mert test.mert
An error occured:
  Abi olaya farklı yerden bakıyorsun ya.
```

## License

Licensed by MERT PUBLIC LICENSE. You should give 5₺ to use this program. If you want to pay more, it's free.
