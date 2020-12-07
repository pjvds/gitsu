# gitsu

A simple cli tool for switching git user easily inspired by [Git-User-Switch](https://github.com/geongeorge/Git-User-Switch)

![screenshot](images/demo.gif)

## Installation

Binary releases are [here](https://github.com/matsuyoshi30/gitsu/releases).

**Homebrew**

```bash
brew install matsuyoshi30/gitsu/gitsu
```

**Arch (AUR)**

> git clone https://aur.archlinux.org/gitsu.git
> cd gitsu
> makepkg -si

If you're using an AUR helper you can install directly from that, for example (in the case of yay), run

yay -S gitsu

**Go (Not recommended)**

```bash
go get github.com/matsuyoshi30/gitsu
```

## Usage

```bash
Usage: 
  git su [flags] # via Homebrew 
  gitsu [flags]  # via Go

Flags:
  --global              Set user as global.
```

## LICENSE

[MIT](LICENSE)
