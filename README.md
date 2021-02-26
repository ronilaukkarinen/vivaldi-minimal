# Minimal Vivaldi layout

These custom CSS styles make Vivaldi browser more minimal and macOS Safari-like.

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
- No tab bar visible if there's only one tab (like in Safari)

![Screenshot](https://i.imgur.com/EqWHbwW.png "Screenshot with only 1 tab")
With only one tab open.

![Screenshot](https://i.imgur.com/WEs5l8F.png "Screenshot with multiple tabs")
With multiple tabs open.

## Requirements

- macOS (for now)
- Vivaldi ≥ 3.6

## Installation

1. Git clone this repository to your documents (not downloads folder)
2. Open [vivaldi://experiments](vivaldi://experiments)
3. Enable "Allow for using CSS modifications"
4. Open Appearance section in settings
5. Choose the dist folder under this repository
6. Restart Vivaldi

If you want even more cleaner look, disable left side panel by pressing <kbd>F4</kbd> and change **Appearance > Status Bar** to _Status Info Overlay_.

If you are interested in my Midnight theme colors, they are:<br>
**Background:** #191c2a<br>
**Foreground:** #8489b3<br>
**Highlight:** 4c70f0<br>
**Accent:** 191c2a

## Development

1. `cd /path/to/vivaldi-minimal`
2. `npm install`
3. `scss --watch src/custom.scss:dist/custom.css --style compressed`
4. Start coding by running in separate Terminal: `code .` or just use any editor you wish
5. Open [vivaldi://inspect/#apps](vivaldi://inspect/#apps) and click first Inspect to Inspect the browser UI