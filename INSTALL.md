### [Fish Shell](http://fishshell.com)

#### Install with a package manager

##### [Fisher](https://github.com/jorgebucaran/fisher)

```sh
fisher install getomni/fish
```

##### [Oh My Fish](https://github.com/oh-my-fish/oh-my-fish)

```sh
omf install https://github.com/getomni/fish
```

##### [fundle](https://github.com/danhper/fundle)

Open `~/.config/fish/config.fish` and add:

```fish
fundle plugin getomni/fish
```

Then run:

```sh
fundle install
```

#### Install manually

1. Download the latest version of [`omni.fish`](https://github.com/getomni/fish/releases/latest/download/omni.fish).
2. Place the `omni.fish` file in the `~/.config/fish/conf.d/` directory.
3. Then reload the fish shell (e.g. `exec fish`).
