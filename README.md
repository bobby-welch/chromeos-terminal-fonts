# ChromeOS Terminal Font Support

## Supported Fonts

- JetBrains Mono Nerd Font
- Iosevka Term Nerd Font
 
NOTE: All fonts included are the mono variants.  This means that existing and added glyphs are single-width. 

## CDN Links for CSS Files

- [JetBrains Mono Nerd Font](https://cdn.jsdelivr.net/gh/bobby-welch/chromeos-terminal-fonts@v1.1.0/chromeos-terminal-jetbrains-mono-nerd-font.css)
- [Iosevka Term Nerd Font](https://cdn.jsdelivr.net/gh/bobby-welch/chromeos-terminal-fonts@v1.1.0/chromeos-terminal-iosevka-term-nerd-font.css)

## Setting Nerd Fonts for ChromeOS Terminal

To set a supported Nerd Font (found in this repo) for the ChromeOS terminal, follow these steps:

- Open the preferences editor by navigating to:

```plaintext
chrome-untrusted://terminal/html/nassh_preferences_editor.html
```

- In the **Custom CSS (URI)** field, enter the details for the Nerd Font you want to use (one of the CDN links).
- In the **Text font family** field, specify the exact name of the font.
