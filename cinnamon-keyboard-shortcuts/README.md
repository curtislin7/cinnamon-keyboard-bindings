# cinnamon-keyboard-shortcuts

Generated using the `dconf-cli` tool. 

To install `dconf-cli` with apt:
`sudo apt-get install dconf-cli`

To dump keyboard shortcuts in Cinnamon for Linux Mint:
`dconf dump /org/cinnamon/desktop/keybindings/ > dconf-settings.conf`

To load keyboard shortcuts in Cinnamon for Linux Mint:
`dconf load /org/cinnamon/desktop/keybindings/ < dconf-settings.conf`