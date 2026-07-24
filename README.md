# EtherLink — Xenoblade

A Xenoblade-inspired Steam redesign built on the excellent
[SpaceTheme/Steam](https://github.com/SpaceTheme/Steam) framework.

EtherLink preserves SpaceTheme's mature layouts and plugin compatibility while
reworking its visual language around deep navy interfaces, cyan Ether lighting,
Monado-red active states, gold achievement accents, angular panels, and a
subtle configurable Ether grid.

## Features

- Library, game pages, downloads, Store, Community, Friends, chat, settings,
  menus, dialogs, notifications, and overlays
- Ether cyan and Monado red palette
- Angular sci-fi panels without altering Steam's clickable regions
- Adjustable Ether glow: Low, Standard, or High
- Optional ambient grid
- Millennium color editor support
- Existing SpaceTheme layout and customization options
- HLTB for Steam and Size on Disk plugin compatibility inherited from
  SpaceTheme
- Reduced-motion support and responsive glow reduction

## Installation

1. Install [Millennium](https://docs.steambrew.app/users/getting-started/installation).
2. Download this repository as a ZIP.
3. Extract the repository folder into:
   `C:\Program Files (x86)\Steam\steamui\skins\`
4. Open `Steam > Millennium > Themes`.
5. Select `EtherLink — Xenoblade` and reload Steam.

If Steam is installed elsewhere, use that installation's `steamui\skins`
directory.

## Customization

Open the theme editor in Millennium. The **Xenoblade** tab controls glow
strength and the ambient grid. The existing SpaceTheme tabs continue to control
the sidebar, Library layout, Store width, game-page presentation, fonts, and
other interface options.

## Design notes

The Xenoblade layer is loaded after SpaceTheme's normal patches. It changes
visual styling while deliberately avoiding scaled controls, translated buttons,
or other geometry changes that can move hitboxes away from visible elements.

## Credits and license

- Original SpaceTheme framework by
  [SpaceEnergy and contributors](https://github.com/SpaceTheme/Steam)
- Xenoblade-inspired EtherLink conversion by Willtheconqueror179 with OpenAI
- Released under the original project's MIT License

This is an unofficial fan-made theme and is not affiliated with Nintendo,
Monolith Soft, Valve, or the Millennium project.
