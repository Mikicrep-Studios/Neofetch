# Minimal version of neofetch just for Mikicrep OS

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
Note: This should not change system functionality

Original: https://github.com/dylanaraps/neofetch
