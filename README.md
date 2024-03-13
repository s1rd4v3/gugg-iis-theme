# gugg-iis-theme

## Screen shots
![CleanShot 2024-03-13 at 20 59 12@2x](https://github.com/s1rd4v3/gugg-iis-theme/assets/914248/56996527-9a56-4d6d-afd1-2c7920eab4b8)
![CleanShot 2024-03-13 at 21 00 38@2x](https://github.com/s1rd4v3/gugg-iis-theme/assets/914248/f1af5ac6-302f-4d3f-af58-d965f01095d0)
![CleanShot 2024-03-13 at 21 01 50@2x](https://github.com/s1rd4v3/gugg-iis-theme/assets/914248/84c8e82a-e495-4ac4-b0a0-c58bc79dcafc)
![CleanShot 2024-03-13 at 21 00 15@2x](https://github.com/s1rd4v3/gugg-iis-theme/assets/914248/0efb2425-814e-40e9-a9d4-0bda5ee63805)
![CleanShot 2024-03-13 at 21 04 21@2x](https://github.com/s1rd4v3/gugg-iis-theme/assets/914248/94ff0066-3638-41ad-b50e-242606231421)



## Features

- Works nicely with all existing cards but best with the [Advanced Tile Card](https://github.com/s1rd4v3/advanced-tile-card)
 ![CleanShot 2024-03-13 at 20 53 44@2x](https://github.com/s1rd4v3/gugg-iis-theme/assets/914248/6426eb75-e892-497f-97ee-de1fad103837)

- Simple UI. Ideal for tablet view hanging on a wall
- View type: Sections
  - Use the new drag'n'drop functionality Home Assistant introduced with v2024.3
  - Makes use of the grid system but enhanced from 2/2 to a 4/4 grid to have more control
  - Increased the 4 columns with to 6 columns

## Installation instructions

> Will try to add this theme directly to hacs for easier installation in the future

### Prerequisites

#### I. Enable themes and install card-mod

1. Install [`card-mod`](https://github.com/thomasloven/lovelace-card-mod "card-mod")

2. Make sure in your **configuration.yaml** file you have the following:

```yaml
frontend:
  themes: !include_dir_merge_named themes
  extra_module_url:
    - /local/community/lovelace-card-mod/card-mod.js #or wherever you ended up putting card-mod.js
```

3. Under the Home Assistant **Config** folder, if not already present, add a new folder named **themes**.
4. **Restart** Home assistant to apply the changes.

#### II. Install `Gugg Iis` theme

1. Download the [latest release](https://github.com/s1rd4v3/gugg-iis-theme/releases/latest), extract it and drop the themes/gugg-iis.yaml file into your themes folder.

### Enable theme

- From your profile page
- From a view

## Inspiration ❤️

- This theme is heavily inspired by [matt8707](https://github.com/matt8707) [hass-config](https://github.com/matt8707/hass-config) config and the main reason I created this theme
