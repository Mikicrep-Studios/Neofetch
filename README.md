# Neofetch with Mikicrep OS support

## Install from source:
1. `git clone https://github.com/Mikicrep-Studios/Neofetch`
2. `cd Neofetch`
3. `make install`
Note: You can also run `make uninstall`

## Show Mikicrep OS logo:
1. Open `/etc/os-release` in your editor
2. Edit specific lines to be exactly like this:
- `NAME="Mikicrep OS"`
- `PRETTY_NAME="Mikicrep OS"`
- `ID=mikicrep`
- `ID_LIKE=mikicrep`
- `LOGO=mikicrep-os`
Note: If your OS also has `/etc/lsb-release`, change that:
- `DISTRIB_ID="Mikicrep"`
- `DISTRIB_DESCRIPTION="Mikicrep OS"`
Note2: Probably not all names will not be same, do not touch name, just value

Note: This should not change system functionality
Note2: If you want to use fetchcord with it, please use "old" branch

Original: https://github.com/dylanaraps/neofetch
