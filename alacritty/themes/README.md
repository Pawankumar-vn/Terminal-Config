# Alacritty Themes (Minimal & Clean Setup)

This folder contains a **curated selection of Alacritty color themes** that I personally use.

---

## Available Themes

Only the following themes are included:

* alabaster_dark
* baitong
* coolnight
* github_dark_high_contrast
* gotham
* hyper

---

## How to Use

### 1. Place Themes in Config Directory

Move this folder into your Alacritty config path:

```bash
mkdir -p ~/.config/alacritty/themes
cp -r themes ~/.config/alacritty/
```

---

### 2. Import Theme in Alacritty

Open your `alacritty.toml` and add:

```toml
[general]
import = [
    "~/.config/alacritty/themes/<theme>.toml"
]
```

Replace `<theme>` with any file name from the list above.

Example:

```toml
import = [
    "~/.config/alacritty/themes/gotham.toml"
]
```

---

### 3. Apply Changes
Restart Alacritty or reload the config for changes to take effect.

---

## Tip
If you want to switch themes quickly, just replace the theme name in `alacritty.toml` and restart the terminal.

---

Simple. Clean. Minimal. Practical.
