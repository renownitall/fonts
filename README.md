# Fonts

This is my personal repository for swapping out Discord's default UI fonts (`ggsans`, `ggmono`) with [IBM Plex](https://www.ibm.com/plex/). I use this to host the raw font files and the JSON mappings so I can easily apply my custom typography across my devices.

## What's inside

- **/src**: The raw `.ttf` font files I'm using.
- **/mappings**: The configuration files that trick Discord into loading my hosted fonts instead of its default ones.

## How I install this

I mainly use this with the [raincord](https://raincord.dev) client mod on mobile. Here's how to apply it:

1. Open Rain and go to the settings menu.
2. Navigate to the **Fonts** section.
3. Tap the "+" button and select "Import font entries from a link".
4. Paste the raw link to my JSON mapping file:

   ```text
   https://raw.githubusercontent.com/renownitall/fonts/main/mappings/raincord/ibm_plex.json
   ```
