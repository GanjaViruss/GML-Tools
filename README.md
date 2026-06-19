# GML Tools

A growing set of free, browser-based tools for GameMaker developers. No install, no account, just open and use.

Each tool was built around real code from my own GameMaker projects, so they reflect how things actually get written in GML, not just theory.

🔗 **[Live demo] (https://ganjaviruss.github.io/GML-Tools/)**

---

## Tools

**[Lengthdir Visualizer](https://ganjaviruss.github.io/GML-Lengthdir-Visualizer/)** Drop points on a sprite, move the origin, rotate the whole thing, and get ready-to-paste `lengthdir_x` / `lengthdir_y` GML. Useful for muzzle flashes, held weapons, shells, collision offsets. Anything that needs to stay attached to a sprite at any angle without hardcoding positions per angle.

**[GUI Creator](https://ganjaviruss.github.io/GML-GUI-Creator/)** Lay out your Draw GUI by dragging elements around a virtual screen. Generates clean GML with resolution-aware anchors (`display_get_gui_width` / `height`). Supports text, rectangles, sprites, health bars, circles. You can also paste existing Draw GUI code and it rebuilds it on the canvas.

**[State Machine Builder](https://ganjaviruss.github.io/GML-State-Machine/)** Draw your state machine visually. Drop state boxes, connect them with conditional transitions, set the conditions. Generates a clean `enum` + `switch/case` with correct `if` / `else if` / `else` priority chains. Built-in snippet bar with common GML functions to tap and copy. Only useful if you already know GML and how a state machine works — it speeds up the tedious part, it doesn't replace knowing what you're doing.

**[Cheat Console](https://ganjaviruss.github.io/GML-Cheat-Console/)** Build a full in-game dev console. Type your cheats in plain lines — toggles, set/adjust commands, actions, and a give command that takes an item ID or name — and get one ready script. Paste it once, call three functions. Comes with a built-in setup guide.

**[GML Formatter](https://ganjaviruss.github.io/GML-formatter/)** Paste your GML code and it fixes formatting: missing semicolons (ASI), Allman or K&R brace style, safe var deduplication. Batch mode lets you drop a whole folder of `.gml` files and format them all at once.

---

## Offline build

All tools are bundled into a single HTML file. Download it, open it in any browser. No server, no internet needed after that. Click a tool to use it right there, or open it in a new tab.

The offline build is a snapshot — when a tool gets updated, the bundle is rebuilt. For the always-current version, use the live links above or each tool's own repo.

| Tool | Live | Repo |
|------|------|------|
| Lengthdir Visualizer | [open](https://ganjaviruss.github.io/GML-Lengthdir-Visualizer/) | [GitHub](https://github.com/GanjaViruss/GML-Lengthdir-Visualizer) |
| GUI Creator | [open](https://ganjaviruss.github.io/GML-GUI-Creator/) | [GitHub](https://github.com/GanjaViruss/GML-GUI-Creator) |
| State Machine Builder | [open](https://ganjaviruss.github.io/GML-State-Machine/) | [GitHub](https://github.com/GanjaViruss/GML-State-Machine) |
| Cheat Console | [open](https://ganjaviruss.github.io/GML-Cheat-Console/) | [GitHub](https://github.com/GanjaViruss/GML-Cheat-Console) |
| GML Formatter | [open](https://ganjaviruss.github.io/GML-formatter/) | [GitHub](https://github.com/GanjaViruss/GML-formatter) |

---

## Why these exist

I've been making games in GameMaker since version 8.1. I know how frustrating some parts of it get, especially the repetitive code you write over and over. These tools came out of that. They take some of the tedium out of the work so you get a few more minutes actually building your game.

They're built with AI and released open source on purpose — so anyone can see how the code is put together, learn from it, or rebuild the idea in whatever language they like.

---

## A note on using them

These tools speed up the boring parts, they don't think for you. If you don't know GameMaker's functions or how the engine works, they won't do much — the State Machine Builder especially assumes you already know your stuff. They're a help, not a shortcut around learning.

Everything is generated as plain, readable GML. Open it, change it, make it yours.

---

## License

MIT. Free to use, modify and share.

*Built by [GanjaViruss](https://github.com/GanjaViruss) with Claude Opus 4.8 & Sonnet 4.6.*
