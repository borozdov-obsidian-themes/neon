# Borozdov Neon

A theme from the Borozdov collection. Two faces — light **Afterimage**, the pale bone paper
left behind once the glow fades, and dark **Blacklight**, void-black velvet under the tube.
One violet line — never a filled shape — carries every accent: links, the open file, the
active tab, the button that matters.

![Borozdov Neon in light mode](https://raw.githubusercontent.com/borozdov-obsidian-themes/neon/main/screenshots/light.png)

![Borozdov Neon in dark mode](https://raw.githubusercontent.com/borozdov-obsidian-themes/neon/main/screenshots/dark.png)

## Principles

- **One violet line.** No filled accent shapes: the open file gets a violet edge, the active
  tab a violet underline, the note's own title a violet rule beneath it. The button that
  matters stays a violet outline at rest and only fills on hover.
- **Void black, bone paper.** Blacklight is a true-black canvas behind hairline graphite
  cards; Afterimage is a paper white with the faintest violet cast, as if the glow were
  still printed on it.
- **Commit Mono for code.** Every code span, block and property value reads in a monospace
  voice; prose stays in the platform's own sans.
- **Square, not round.** 6px controls, 12–16px cards, small rectangular tags — no pills.

## Features

- Light and dark modes, following Settings → Appearance → Base color scheme
- The highlighter as a violet word on an opaque wash, readable on both faces
- Callouts as cards with the title in the type's colour; the plain note on a violet-wash chip
- The open file marked by a violet edge line, not a fill
- Quiet editing: no focus ring around the note, its title or form fields while you type;
  property names read as labels, not boxed fields
- Text colours meet WCAG contrast on both faces
- The phone layout keeps the same colours and shapes
- No embedded fonts: the sans is the platform's own, code names Commit Mono as a system font
  and falls back cleanly when it isn't installed, and the theme stays around 12 KB
- No `!important`: every rule can be overridden with a CSS snippet

## Installation

**From the community directory:** Settings → Appearance → Themes → Manage, search for
**Borozdov Neon**, then **Install and use**.

**By hand:** download `manifest.json` and `theme.css` from the [latest
release](https://github.com/borozdov-obsidian-themes/neon/releases/latest) into
`<vault>/.obsidian/themes/Borozdov Neon/`, then choose Borozdov Neon under
Settings → Appearance → Themes.

## License

MIT — see [LICENSE](LICENSE).

---

**По-русски.** Тема из коллекции Borozdov. Два лика: светлый «Afterimage» — бледная бумага,
которая остаётся после того, как погас неон, и тёмный «Blacklight» — чёрный бархат под
лампой. Одна фиолетовая линия — никогда не заливка — несёт весь акцент: ссылки, открытый
файл, активную вкладку, единственную важную кнопку. Шрифты не встроены, код набран именем
Commit Mono с аккуратным откатом на системный моноширинный. Устанавливается из каталога:
Настройки → Оформление → Темы → Настроить → Borozdov Neon → Установить и применить.
