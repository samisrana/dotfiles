<h2 align="center"> ━━━━━━  ❖  ━━━━━━ </h2>

### ❖ Information

   My personal dotfiles for macOS. Here's what I use:

   - **OS:** [MacOS](https://www.apple.com/macos)
   - **WM:** [yabai](https://github.com/koekeishiya/yabai)
   - **Hotkeys:** [skhd](https://github.com/koekeishiya/skhd)
   - **Status Bar:** [SketchyBar](https://github.com/FelixKratz/SketchyBar)
   - **Terminal:** [Kitty](https://sw.kovidgoyal.net/kitty/)
   - **Shell:** [zsh](https://www.zsh.org/)
   - **Prompt:** [starship](https://starship.rs/)
   - **Editor:** [neovim](https://github.com/neovim/neovim/)
   - **Multiplexer:** [tmux](https://github.com/tmux/tmux)
   - **Top:** [bottom](https://github.com/ClementTsang/bottom)
   - **File Manager:** [yazi](https://github.com/sxyazi/yazi)
   - **Theme:** [catppuccin](https://github.com/catppuccin)
   - **Spotify:** [spicetify](https://github.com/khanhas/spicetify-cli)
   - **Browser:** [firefox](https://www.mozilla.org/en-US/firefox/new/)
   - **Application Launcher:** [Alfred](https://www.alfredapp.com/)

---

### ❖ Setup

   Config files live in `~/.config/` as symlinks to this repo. For zsh, add the following to `~/.zshenv` so zsh picks up configs from `~/.config/zsh/`:
   ```sh
   export ZDOTDIR=$HOME/.config/zsh
   ```

   **yabai + skhd** require some extra steps beyond brew — follow the [yabai wiki](https://github.com/koekeishiya/yabai/wiki).

   Caps Lock is bound as **hyper** when held and **esc** when tapped via Karabiner.

---

### ❖ Acknowledgements

   - [dotzenith](https://github.com/dotzenith/dotconfig) for the original config this was based on.
   - [catppuccin](https://github.com/catppuccin) for the colors.
