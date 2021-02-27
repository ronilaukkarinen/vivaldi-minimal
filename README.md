## Minimal Vivaldi layout

[![GitHub release](https://img.shields.io/github/tag/ronilaukkarinen/vivaldi-minimal.svg?style=flat-square)](https://github.com/ronilaukkarinen/vivaldi-minimal/releases) [![Vivaldi](https://img.shields.io/badge/tested%20with%20vivaldi-3.6-green.svg?style=flat-square)](https://github.com/ronilaukkarinen/vivaldi-minimal) 
[![GitHub contributors](https://img.shields.io/github/contributors/ronilaukkarinen/vivaldi-minimal.svg?style=flat-square)](https://github.com/ronilaukkarinen/weed/graphs/contributors) 
[![Twitter Follow](https://img.shields.io/twitter/follow/rolle.svg?style=social&label=Follow)](https://twitter.com/rolle)

This Vivaldi theme (custom CSS) makes the browser more minimal and macOS Safari-like.


## Requirements

- macOS or Windows 10
- Vivaldi ≥ 3.6

## Features

- Supports all color themes
- Tabs under address bar
- Less buttons
- No new tab button
- No profile button
- No sync and trash tabs buttons
- No search bar
- No favicons
- Equal width tabs (like in Safari)
- Centered tab titles (like in Safari)
- No tab bar visible if there's only one tab (like in Safari)
- Remove speed dial related things like dials and extra search input to have _real blank_ new tab page instea of that about:blank bug

![Screenshot](https://i.imgur.com/8FWwGPD.png "Screenshot with only 1 tab")
With multiple tabs open.

![Screenshot](https://i.imgur.com/WEs5l8F.png "Screenshot with multiple tabs")
With only one tab open.

## Installation

1. Git clone this repository to your documents (not downloads folder)
2. Open [vivaldi://experiments](vivaldi://experiments)
3. Enable "Allow for using CSS modifications"
4. Open Appearance section in settings
5. If you are using macOS, choose dist/mac folder under this repository, if Windows, choose dist/windows
6. Restart Vivaldi

If you want even more cleaner look, disable left side panel by pressing <kbd>F4</kbd> and change **Appearance > Status Bar** to _Status Info Overlay_.

If you are interested in my Midnight theme colors, they are:

**Background:** #161b2e<br>
**Foreground:** #8489b3<br>
**Highlight:** #6272a4<br>
**Accent:** #0c1220

No tickboxes in **Theme Preferences**.

## Development

1. `cd /path/to/vivaldi-minimal`
2. `npm install`
3. `scss --watch src/mac/custom.scss:dist/mac/custom.css --style compressed` or `scss --watch src/windows/custom.scss:dist/windows/custom.css --style compressed`
4. Start coding by running in separate Terminal: `code .` or just use any editor you wish
5. Open [vivaldi://inspect/#apps](vivaldi://inspect/#apps) and click first Inspect to Inspect the browser UI
