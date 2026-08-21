🛠️ Noctalia & Niri DotfilesA clean, modern Wayland desktop setup using Niri and Noctalia Shell.



🎨 ScreenshotsDesktopLockscreen  






📦 Required Applications & DependenciesMake sure you have these packages installed before applying the configuration:
Compositor & Shell: niri, noctalia-shell
Terminal: kitty
Shell & Fetch: fish, fastfetch
System Monitors: btop, cava
Fonts:Lexend (Primary UI Font) Unifont (Clock / Lockscreen Font) Maple mono (Terminal Font)
A Nerd Font (e.g., ttf-nerd-fonts-symbols or JetBrainsMono Nerd Font for icons)





🚀 Installation Guide1. Clone the RepositoryCode snippetgit clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git ~/dotfiles







2. Copy Configurations to ~/.config/Code snippet# Create config directories if they don't exist
mkdir -p ~/.config ~/.local/state/noctalia

# Link / Copy configuration folders
cp -r ~/dotfiles/config/niri ~/.config/
cp -r ~/dotfiles/config/kitty ~/.config/
cp -r ~/dotfiles/config/fastfetch ~/.config/
cp -r ~/dotfiles/config/fish ~/.config/

# Copy Noctalia configuration
cp ~/dotfiles/config/noctalia/settings.toml ~/.local/state/noctalia/
cp ~/dotfiles/config/noctalia/noctalia.kdl ~/.config/niri/
