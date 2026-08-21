## Noctalia & Niri Dotfiles
A clean, modern wayland desktop setup using Niri and Noctalia Shell.



## Previews
<img width="1920" height="1080" alt="screenshot1" src="https://github.com/user-attachments/assets/0cb82fb3-5293-4fc8-9e47-2f5288c9698c" />
<img width="1916" height="1080" alt="screenshot2" src="https://github.com/user-attachments/assets/86f036c0-0c23-458a-8f7b-bc8cf8b4cdf5" />
<img width="1920" height="1080" alt="screenshot3" src="https://github.com/user-attachments/assets/905448b3-46ec-478b-b1be-a70b3f34311f" />
<img width="1920" height="1024" alt="screenshot4" src="https://github.com/user-attachments/assets/9436ffed-f56c-436e-abf9-ebbbec6aa809" />


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
* **NixOS** (Highly recommended and personally used)

