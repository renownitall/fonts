# Fonts

Hi. This is my repository for swapping out the default UI fonts in Discord (`ggsans`, `ggmono`, `ABCGintoNord`) with custom ones. I use it to host the raw font files and the JSON mapping, so I can apply my theme across my mobile devices.

This repository contains only the theme I use. That theme uses Source Sans 3 for headers and UI text with Source Code Pro for code blocks, so nothing else is in here.

## Repository layout

The repository contains the following files:

- `/src/Source_Sans_3` holds the TrueType font files for Source Sans 3, which the theme uses for headers and UI text.
- `/src/Source_Code_Pro` holds the TrueType font files for Source Code Pro, which the theme uses for code blocks.
- `/mappings/raincord/source_sans_3.json` holds the JSON configuration that loads the hosted fonts instead of Discord's default fonts.

## Install the theme

I use this with the [rain](https://raincord.dev) client mod on mobile. To apply the theme, follow these steps:

1. In rain, open the settings menu.
2. Open the **Fonts** section.
3. Tap **Install from URL** or the **+** button.
4. Tap **Import font entries from a link**.
5. Paste the raw link to the JSON mapping file, for example:

   ```text
     https://raw.githubusercontent.com/renownitall/fonts/main/mappings/raincord/source_sans_3.json
   ```
