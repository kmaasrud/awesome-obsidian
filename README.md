![](media/banner.png)

<div align="center">

A curated list of awesome themes and plugins for [Obsidian](https://obsidian.md/).

</div>

---

# Table of contents

- [Handy tools](#handy-tools)
- [Themes](#themes)
- [CSS Tweaks](#css-tweaks)

# Handy tools

| Name | Description | Credits |
| :--: | :---------- | ------: |
| [Markdownload](https://github.com/deathau/markdown-clipper) | A Firefox and Google Chrome extension to clip websites and download them into a readable markdown file. | [deathau](https://github.com/deathau) |
| [Copy Selection as Markdown](https://github.com/0x6b/copy-selection-as-markdown) | Firefox add-on to copy a selection or link as formatted Markdown | [0x6b](https://github.com/0x6b) |
| [Notion to Obsidian converter](https://github.com/connertennery/Notion-to-Obsidian-Converter) | Simple script to convert exported Notion notes to Obsidian | [connertennery](https://github.com/connertennery) |

# Themes

Most themes should be available through the Community Themes pane in Obsidian's settings. If not, enable Custom CSS under Plugins, download `obsidian.css` from the desired repository and place it in the vault root.

| Name | Description | Image | Credits |
| :--: | :---------- | ----- | ------: |
[Dracula](https://github.com/jarodise/Dracula-for-Obsidian.md) | A dark theme for Obsidian. | ![](https://raw.githubusercontent.com/jarodise/Dracula-for-Obsidian.md/master/screencap.jpg) | [jarodise](https://github.com/jarodise)
[80s Neon](https://github.com/deathau/80s-Neon-for-Obsidian.md) | A retro-future 80s inspired theme for Obsidian.  | ![](https://raw.githubusercontent.com/deathau/80s-Neon-for-Obsidian.md/master/screenshot.jpg) | [deathau](https://github.com/deathau)
[Base2Tone](https://github.com/deathau/Base2Tone-For-Obsidian.md) | A theme for Obsidian based on http://base2t.one/ with default hues from http://simurai.com/duotone-dark-sky-syntax/. | ![](https://raw.githubusercontent.com/deathau/Base2Tone-For-Obsidian.md/master/colours.gif) | [deathau](https://github.com/deathau)
[Clean theme](https://github.com/kmaasrud/clean-theme-obsidian) | A minimal and clean theme designed to be clutter-free and easy on the eye. | ![](https://raw.githubusercontent.com/kmaasrud/clean-theme-obsidian/master/media/dark_shadow.png) | [kmaasrud](https://github.com/kmaasrud)
[OneDark Theme](https://github.com/pionxzh/OneDark-obsidian) | This theme is based on One Dark Pro and One Dark Pro is based on Atom's default One Dark theme. Currently only supports Dark mode. | ![](https://raw.githubusercontent.com/pionxzh/OneDark-obsidian/master/img/sample_1.png) | [pionxzh](https://github.com/pionxzh)
[Comfort Color Dark Theme](https://github.com/obsidian-ezs/obsidian-comfort-color-dark) | A dark theme for Obsidian. | ![](https://raw.githubusercontent.com/obsidian-ezs/obsidian-comfort-color-dark/master/screencap.png) | [obsidian-ezs](https://github.com/obsidian-ezs)
[Gruvbox Theme](https://github.com/insanum/obsidian_gruvbox) | This is a gruvbox theme for Obsidian. It supports both light and dark modes. | ![](https://raw.githubusercontent.com/insanum/obsidian_gruvbox/master/dark.png) | [insanum](https://github.com/insanum)
[Gastown](https://github.com/dogwaddle/obsidian-gastown-theme.md) | A light theme for Obsidian. | ![](https://raw.githubusercontent.com/dogwaddle/obsidian-gastown-theme.md/master/ObsidianOne.png) | [dogwaddle](https://github.com/dogwaddle)
[Ursa](https://github.com/obsidian-ezs/obsidian-ursa) | A light and dark theme for Obsidian featuring "zen mode" with collapsing side panels and improved single pane viewing. | ![](https://raw.githubusercontent.com/obsidian-ezs/obsidian-ursa/master/light-theme_full.png) | [obsidian-ezs](https://github.com/obsidian-ezs)
[Obsidian Solarized](https://github.com/Slowbad/obsidian-solarized) | This is just a recolor based on the solarized color scheme. | ![](https://raw.githubusercontent.com/Slowbad/obsidian-solarized/master/light.png) | [Slowbad](https://github.com/Slowbad)
[Red Graphite](https://github.com/seanwcom/Red-Graphite-for-Obsidian) | A light theme for Obsidian, based on Bear.app's Red Graphite theme. | ![](https://raw.githubusercontent.com/seanwcom/Red-Graphite-for-Obsidian/master/screenshot01.png) | [seanwcom](https://github.com/seanwcom) |

# CSS Tweaks

Small tweaks to add to your `obsidian.css` file

- [Andy Matuschak mode](#andy-matuschak-mode)
- [Collapsing sidebar](#collapsing-sidebar)

### Andy Matuschak mode

```
.workspace-split.mod-vertical { overflow-x:auto; }
.workspace-leaf, .workspace-split > .workspace-split { min-width: 500px; min-height: 500px; }
.workspace-split.mod-horizontal { overflow-y: auto; } 
```

Credits to [deathau](https://github.com/deathau)

---

### Collapsing sidebar

```
.side-dock-ribbon.mod-left.is-collapsed:not(:hover), .side-dock-ribbon.mod-right.is-collapsed:not(:hover) {
  width: 15px !important;
  opacity: 0;
}
.side-dock-ribbon {
  transition-property: width, opacity;
}
```

Credits to [kmaasrud](https://github.com/kmaasrud)

---
