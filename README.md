# Neofetch for Mikicrep OS
Modified neofetch code for Mikicrep OS, will probably work on other distos but it has only Mikicrep OS ASCII

## Install from source:
1. `git clone https://github.com/Mikicrep-Studios/Neofetch`
2. `cd Neofetch`
3. `make install`

## Uninstall:
1. `make uninstall`

## Show Mikicrep OS logo if it doesnt work:
1. Open `/etc/os-release` in your editor
2. Edit lines:
`NAME="Mikicrep OS"`
`PRETTY_NAME="Mikicrep OS"`
`ID=mikicrep`
`ID_LIKE=mikicrep`
`LOGO=mikicrep-os`
3. Open `/etc/lsb-release` in your editor
4. Edit lines:
`DISTRIB_ID="Mikicrep"`
`DISTRIB_DESCRIPTION="Mikicrep OS"`

Note: Use "old" branch for fetchcord support

Original: https://github.com/dylanaraps/neofetch
