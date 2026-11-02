# Installation

1. **Backup your existing Neovim configuration (if any):**

   ```bash
   # Linux / macOS
   mv ~/.config/nvim ~/.config/nvim.bak
   mv ~/.local/share/nvim ~/.local/share/nvim.bak
   mv ~/.local/state/nvim ~/.local/state/nvim.bak
   mv ~/.cache/nvim ~/.cache/nvim.bak
   ```

   ```cmd
   :: Windows (CMD)
   ren %USERPROFILE%\AppData\Local\nvim nvim.bak
   ren %USERPROFILE%\AppData\Local\nvim-data nvim-data.bak
   ```

2. **Clone this repository into your Neovim configuration directory:**

   ```bash
   git clone https://github.com/DaniDMoura/neovim-dots.git ~/.config/nvim
   ```

3. **Start Neovim:**

   ```bash
   nvim
   ```

   `lazy.nvim` will automatically bootstrap and install all configured plugins.
