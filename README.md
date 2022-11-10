# Raven
Dragonflight hotfixes for the latest version of Raven, a World of Warcraft addon, while we reach out to the official maintainer of Raven.

**Note**: For now, download the latest [here](https://dicebar.net/raven/). Do not download Raven directly from Github, the addon Raven_Options is not part of this repository and you'll end up with an incomplete addon.

## Known issues
- Masque doesn't play nice at the moment ([#3](https://github.com/Dicebar/raven/issues/3))

## Changelog
- 10 Nov 2022:
  - Fixed bug that prevented the player cast to not be hidden ([#11](https://github.com/Dicebar/raven/issues/11))
- 09 Nov 2022:
  - Fixed a new bug introduced by the fix for an earlier bug related to bugs cancelling ([#1](https://github.com/Dicebar/raven/issues/1), [#15](https://github.com/Dicebar/raven/issues/15))
  - Fixed a bug with bar groups attached to Parent Frames ([#9](https://github.com/Dicebar/raven/issues/9))
  - Fixed a bug with the sparkler animation ([#6](https://github.com/Dicebar/raven/issues/6))
- 01 Nov 2022:
  - Fixed bug that could lead to RMB removing the wrong buff.
- 30 Oct 2022:
  - Restored the ability to cancel buffs ([#1](https://github.com/Dicebar/raven/issues/1))
  - Hiding blizzard buffs and debuffs now also hides debuffs again ([#8](https://github.com/Dicebar/raven/issues/8))
- 30 Oct 2022:
  - Fixed bug with tooltips flickering when using weapon enchants (ie Flametongue Weapon) ([#2](https://github.com/Dicebar/raven/issues/2))
- 27 Oct 2022:
  - Created a better fix for the problems on the Spells tab.
  - Disabled bugged code related to cancelling weapon buffs (ie Flametongue Weapon).
- 26 Oct 2022:
  - Added support for the new talent system.
  - Fixed problem with the Spells tab (probably anyway).
  - Fixed issue with Blizzard buffs not being disabled properly when using the 'Hide Blizzard' option.
