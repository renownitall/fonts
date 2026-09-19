# Fonts

Hi. This is my repository for swapping out the default UI fonts in Discord (`ggsans`, `ggmono`, `ABCGintoNord`) with custom ones. I use it to host the raw font files and the JSON mapping, so I can apply my theme across my mobile devices.

This repository contains only the theme I use. That theme uses Google Sans for headers and UI text with Google Sans Code for code blocks, so nothing else is in here.

## Repository layout

The repository contains the following files:

- `/src/Google_Sans` holds the TrueType font files for Google Sans, which the theme uses for headers and UI text.
- `/src/Google_Sans_Code` holds the TrueType font files for Google Sans Code, which the theme uses for code blocks.
- `/mappings/raincord/google_sans.json` holds the JSON configuration that loads the hosted fonts instead of Discord's default fonts.

## Install the theme

I use this with the [rain](https://raincord.dev) client mod on mobile. To apply the theme, follow these steps:

1. In rain, open the settings menu.
2. Open the **Fonts** section.
3. Tap **Install from URL** or the **+** button.
4. Tap **Import font entries from a link**.
5. Paste the raw link to the JSON mapping file, for example:

   ```text
    https://raw.githubusercontent.com/renownitall/fonts/main/mappings/raincord/google_sans.json
   ```
