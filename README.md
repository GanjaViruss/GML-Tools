# GML Tools

A growing suite of free, open-source, browser-based tools for GameMaker developers. No install, no account — just open and use.

🔗 **[Open the portal »](https://ganjaviruss.github.io/GML-Tools/)**

✦ Built with AI · by [GanjaViruss](https://github.com/GanjaViruss)

---

## Tools

| Tool | Description |
|------|-------------|
| [GML Lengthdir Visualizer](https://github.com/GanjaViruss/GML-Lengthdir-Visualizer) | Visual lengthdir_x/y generator — drop points on a sprite, rotate, get GML |
| [GML GUI Creator](https://github.com/GanjaViruss/GML-GUI-Creator) | Visual Draw GUI editor — drag elements, get resolution-aware GML |
| [GML Formatter](https://github.com/GanjaViruss/GML-formatter) | Auto-format GML — ASI, Allman/K&R, safe var handling, batch mode |

More tools coming.

## Adding a new tool

Drop a new entry into the `TOOLS` array in `index.html`:

```js
{
  icon: '💡',
  name: 'My Tool',
  slug: 'GML-My-Tool',
  desc: 'Short description.',
  tags: ['category'],
  tool: PAGES('GML-My-Tool'),
  readme: RAW('GML-My-Tool', 'README.md')
}
```

That's it — the tile appears automatically.

## License

MIT — free to use, modify and share.

---

*Built by [GanjaViruss](https://github.com/GanjaViruss) with Claude Opus 4.8 & Sonnet 4.6.*
