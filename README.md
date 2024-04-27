# Touch-Grass

A simple menu that will prompt you to upgrade your system before you go touch grass

## Usage

As default it will prompt you in the terminal using [`fzf`](https://github.com/junegunn/fzf)

```sh
./grass
```

But if you don't have access to input, you can provide another menu,
in this example we will show you how to do with `wofi`:

```sh
./grass --menu='wofi --show dmenu'
```

For more help:

```sh
./grass --help
```
