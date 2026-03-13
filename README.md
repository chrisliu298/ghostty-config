# Ghostty Config

Personal [Ghostty](https://ghostty.org/) terminal emulator configuration for macOS.

## Setup

Clone this repo and symlink to Ghostty's config directory:

```bash
git clone https://github.com/chrisliu298/ghostty-config.git
ln -sf "$(pwd)/ghostty-config/config" ~/.config/ghostty/config
ln -sf "$(pwd)/ghostty-config/themes" ~/.config/ghostty/themes
```

Or copy the files directly:

```bash
cp config ~/.config/ghostty/config
cp -r themes ~/.config/ghostty/themes/
```

## Highlights

- **Font**: Berkeley Mono, size 18
- **Theme**: GitHub Dark (custom themes included)
- **Window**: Transparent titlebar, non-native fullscreen, system theme
- **Keybindings**: Cmd-based splits, tab movement, and navigation

## Custom Themes

| Theme | Description |
|-------|-------------|
| GitHub Dark | Dark theme based on GitHub's VS Code extension |
| GitHub Dark Dimmed Modified | Modified dimmed variant of GitHub Dark |
| Grok Dark | Stark black and white minimalism with cosmic accents |
| Grok Light | Light variant of the Grok theme |
