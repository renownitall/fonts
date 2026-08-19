# Fonts

Hi. This is my repo for swapping out the default UI fonts in Discord (`ggsans`, `ggmono`, `ABCGintoNord`) with custom ones. I use it to host the raw font files and the JSON mappings, so I can apply my themes across my mobile devices.

## Repository layout

- `/src`: The raw TTF font files for the various typefaces.
- `/mappings`: The JSON configuration files that load my hosted fonts instead of Discord's default ones.

## Install a theme

I use this with the [rain](https://raincord.dev) client mod on mobile. To apply a theme, follow these steps:

1. In rain, open the settings menu.
2. Open the **Fonts** section.
3. Tap **Install from URL** or the **+** button.
4. Tap **Import font entries from a link**.
5. Paste the raw link to the JSON mapping file you want to use, for example:

```text
https://raw.githubusercontent.com/renownitall/fonts/main/mappings/raincord/noto_jetbrains.json
```
