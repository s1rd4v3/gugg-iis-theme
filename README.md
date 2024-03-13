# gugg-iis-theme

## Screen shots

[TBD]

## Features

- Works nicely with all existing cards but best with the [Advanced Tile Card](https://github.com/s1rd4v3/advanced-tile-card)
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
