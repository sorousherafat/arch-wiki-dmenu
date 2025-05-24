# arch-wiki-dmenu

Search your offline ArchWiki HTML docs using `dmenu`.

## Dependencies

- **`arch-wiki-docs`** provides the offline HTML files under `/usr/share/doc/arch-wiki/html/`.
- Optional:
  - **`rofi`** is required if on X11 and `dmenu` is not installed.
  - **`dmenu`** is required if on X11 and `rofi` is not installed.
  - **`fuzzel`** is required if on Wayland.
  - Any XDG‐compliant browser or terminal‐based viewer.

## Usage

```
arch-wiki-dmenu [menu-options]
```

Any argument passed to the script is directly passed to the menu launcher application.
