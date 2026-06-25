# Fonts

This is my personal repository for swapping out Discord's default UI fonts (`ggsans`, `ggmono`) with [IBM Plex](https://www.ibm.com/plex/). I use this to host the raw font files and the JSON mappings so I can easily apply my custom typography across my devices.

## What's inside

- **/src**: The raw `.ttf` font files for the IBM Plex superfamily.
- **/mappings**: The configuration files that trick Discord into loading my hosted fonts instead of its default ones.

## How I install this

I mainly use this with the [rain](https://raincord.dev) client mod on mobile. Here's how to apply it:

**1.** Open Rain and go to the settings menu.

**2.** Navigate to the **Fonts** section.

**3.** Tap `Install from URL` (or the `+` button), then tap `Import font entries from a link`.

**4.** Paste the raw link to my JSON mapping file:

  ```text
  https://raw.githubusercontent.com/renownitall/fonts/main/mappings/raincord/ibm_plex.json
  ```

  and tap `Import`.

**6.** Once the entries load, tap `Import` again at the bottom. You will be redirected to the previous page, and `IBM Plex` should now appear in the list.

**7.** Tap `Apply`. You will receive a reminder to reload the client for the changes to take effect.

All done!
