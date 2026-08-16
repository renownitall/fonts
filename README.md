# Fonts

Hi.

This is my repo for swapping out Discord's default UI fonts (`ggsans`, `ggmono`, `ABCGintoNord`) with custom ones. I use this to host the raw font files and the JSON mappings so I can easily apply my themes across my mobile devices.

## What's inside

- **/src**: The raw `.ttf` font files for the various typefaces.
- **/mappings**: The configuration files that load my hosted fonts instead of Discord's default ones.

## How I install this

I mainly use this with the [rain](https://raincord.dev) client mod on mobile. Here's how to apply it:

**1.** Open Rain and go to the settings menu.

**2.** Navigate to the **Fonts** section.

**3.** Tap `Install from URL` (or the `+` button), then tap `Import font entries from a link`.

**4.** Paste the raw link to the JSON mapping file you want to use, for example:

```text
https://raw.githubusercontent.com/renownitall/fonts/main/mappings/raincord/noto_jetbrains.json
```
