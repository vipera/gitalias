# Vipera's Git Aliases

A collection of useful or not-so-useful Git aliases collected over time.

## Getting Started

To add these aliases to your Git setup, first get a copy of the included gitconfig file in this repository by whichever means you prefer. Some suggestions:

1. Cloning this repository
        
        git clone https://github.com/vipera/gitalias

2. Using wget, for example:

        wget -O vipera_gitalias https://github.com/vipera/gitalias/blob/master/gitconfig

### Prerequisites

Git 1.7.10+

### Installing

Assuming you have a sufficiently recent version of Git installed (1.7.10), simply add this to an appropriate Git config file (e.g. /etc/gitconfig for having these aliases globally available):

```
[include]
    path = /path/to/gitalias/gitconfig
```

If you have an older version of Git include won't work, but you can copy the aliases in the provided gitconfig file into your own git config.

## Authors

* [Marin Rukavina](https://github.com/vipera)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Thanks to [Jason Crome](https://github.com/cromedome)'s personal Git aliases, `unstage` and `standup` are in the selection.

