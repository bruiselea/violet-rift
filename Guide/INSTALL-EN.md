# Install Violet Rift

Preview 0.2.0. Dark mode only. Minimum declared Obsidian version: 1.14.4.

1. Note your current theme and enabled appearance snippets.
2. In Settings → Appearance, open the themes folder.
3. Copy the entire `Theme/Violet Rift` folder into your vault's `.obsidian/themes/`.
   The final files are `.obsidian/themes/Violet Rift/theme.css` and `manifest.json`.
4. Reopen Appearance, select Violet Rift and select the Dark base color scheme.
5. Disable the older crying-obsidian snippet if installed. Other visual snippets may conflict.
6. For themed menus on macOS, turn off Settings → Interface → Native menus. OS-rendered menus cannot be styled by the theme.

The theme does not change fonts automatically. It does not edit notes or plugin preferences.
No network, activation service or community plugin is required. Light mode uses the default look.

## Optional type

For Obsidian only, copy `Optional CSS/rift-pixel-display.css` into `.obsidian/snippets/`,
reload the snippet list in Appearance and enable it. It embeds the font locally.
It styles Latin interface labels and heading levels 1–2; the body text font is retained.
Unsupported scripts, including Japanese, fall back to existing fonts.

For other desktop apps, install `Fonts/RiftPixel-Regular.ttf` using your OS font manager.
For web design, use the WOFF and supplied web CSS, for personal, non-commercial use as described in LICENSE.

Rift Pixel is a monospace display font with 112 encoded characters and one Regular weight.
It includes printable ASCII, NBSP and selected punctuation, symbols and arrows.
It does not include Japanese, accented Latin, emoji, ligatures, bold or italic masters.
Use for titles and short labels. Multiples of 10px align its design grid; rendering varies by OS.

## Optional appearance snippets

Copy only the desired files from `Optional CSS` into `.obsidian/snippets/` and enable them:
- `violet-rift-still.css`: static tears; no scrolling animation.
- `violet-rift-quiet.css`: remove rain and textures, retain the palette.
- `violet-rift-wake.css`: optional styling for Wake Dashboard; plugin not included.

OS Reduce Motion preferences also stop rain movement.

## Undo

Select your previous theme or Default and disable this pack's snippets.
To uninstall, remove only the theme folder and snippets you added.
Remove a desktop-installed font through your OS font manager if desired.

Windows, Linux, mobile and arbitrary plugin compatibility have not been tested.
This is a creator preview; consult the release checklist before selling it.
