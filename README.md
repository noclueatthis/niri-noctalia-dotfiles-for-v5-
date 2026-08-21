## Noctalia & Niri Dotfiles
A clean, modern Wayland desktop setup using Niri and Noctalia Shell.


## Previews 

## Previews


## Previews
| | |
| :---: | :---: |
| ![Screenshot 1](Pictures/Screenshots/screenshot1.png) | ![Screenshot 2](Pictures/Screenshots/screenshot2.png) |
| ![Screenshot 3](Pictures/Screenshots/screenshot3.png) | ![Screenshot 4](Pictures/Screenshots/screenshot4.png) |



### Required Applications & Dependencies 
* Compositor & Shell: `niri, noctalia-shell`
* Terminal: `kitty`
* Shell & Fetch: `fish, fastfetch`
* System Monitors: `btop, cava`
* Fonts:`Lexend` (Primary UI Font) `Unifont` (Clock / Lockscreen Font) `Maple mono` (Terminal Font)
* A Nerd Font (e.g., `ttf-nerd-fonts-symbols` or `JetBrainsMono Nerd` Font for icons)





## Installation 
1. Clone the Repository
  ` git clone https://github.com/noclueatthis/niri-noctalia-dotfiles-for-v5-git ~/dotfiles`



3. Copy Configurations to ~/.config (Create the config directories if they don't exist)
   
* `mkdir -p ~/.config ~/.local/state/noctalia`

## Link / Copy configuration folders
* `cp -r ~/dotfiles/config/niri ~/.config/`
* `cp -r ~/dotfiles/config/kitty ~/.config/`
* `cp -r ~/dotfiles/config/fastfetch ~/.config/`
* `cp -r ~/dotfiles/config/fish ~/.config/`

## Copy Noctalia configuration
* `cp ~/dotfiles/config/noctalia/settings.toml ~/.local/state/noctalia/`
* `cp ~/dotfiles/config/noctalia/noctalia.kdl ~/.config/niri/`

## Supported Distributions
These configurations are completely **distribution-agnostic** and work on any Linux OS running a modern Wayland environment. They have been verified or are fully supported on:
* **Arch based distros** (Packages avaliable in AUR)
* **Fedora / Bazzite** (Fully supported)
* **Void Linux** (Natively supported via official repositories)
* **NixOS** (Highly recommended)

