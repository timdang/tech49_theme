# Change Log

All notable changes to the "theme-tech49" extension may be documented in this file.

## 1.0

- Updated to new VS Code theme format with support for workbench customization.

## 1.1

- Removed bold text.

## 1.3

- Updated legibility of commented text.
- Very minor tweak to HTML formatting.
- Updated screenshot.

## 1.4

- Added some more theme-specific editor colors.

## 1.5

- Added some theme-specific VCS colors.

## 1.6

- Added some VCS colors to the Overview ruler.

## 1.7

- Added high contrast comments theme variant.

## 1.8

- Enabled sematic highlighting. Not sure if it works, honestly.

## 1.9

- Major workbench coverage update: applied the existing palette to many more UI
  elements (tabs, breadcrumbs, terminal ANSI colors, menus, notifications,
  peek/hover/suggest widgets, git decorations, minimap, scrollbars, inputs,
  buttons, status bar items, bracket-pair colorization, and more).
- Added a proper `semanticTokenColors` map so semantic highlighting actually
  works, using the same palette as the TextMate token colors.
- Brought the "Vivid Comments" high-contrast variant up to the same coverage.

## 1.9.1

- Added an MIT license.

## 1.9.2

- Refreshed the Marketplace screenshot with a full-window shot of the expanded
  theming, and updated the README/attributions.

## 1.10.0

- Refreshed the default "Tech49" theme with a modernized take inspired by the Sky
  Tower / Tech 49 station rather than the night-drone mood. The previous default is
  still available as "Tech49 (Classic)". The refresh keeps the existing syntax
  palette but modernizes the workbench chrome:
  - Replaced the flat pure-black surfaces with a deep cool-teal near-black and a
    proper elevation ladder (editor `#03070a`, chrome `#060d10`, raised
    surfaces `#0c1518`, popups/widgets `#0a1316`) so panels and popups read as
    distinct glass layers.
  - Lifted the dim chrome text (status bar, inactive tabs, breadcrumbs,
    activity bar) from `#396269` to `#5d8a92` for readability.
  - Leaned the holographic cyan into focus states (`focusBorder`,
    `sash.hoverBorder`), reserving the drone-eye orange for action accents.

## 1.10.1

- Refreshed the Marketplace screenshot to show the new default Tower theme.
