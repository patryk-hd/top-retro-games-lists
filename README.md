# 🕹️ Top Retro Games Lists

Community-curated rankings of the greatest games across classic platforms — hosted as a static site on GitHub Pages.

## 🌐 Browse Online

**[https://patryk-hd.github.io/top-retro-games-lists/](https://patryk-hd.github.io/top-retro-games-lists/)**

## 📋 Lists Included

| Platform Family | File | Consoles |
|---|---|---|
| **Nintendo** | [pages/nintendo-top-100-games.html](pages/nintendo-top-100-games.html) | NES, SNES, N64, GameCube, Wii, Wii U, Game Boy, Game Boy Color, Game Boy Advance, Nintendo DS, Nintendo 3DS |
| **Sega** | [pages/sega-top-100-games.html](pages/sega-top-100-games.html) | SG-1000, Master System, Mega Drive (Genesis), Game Gear, Sega CD, 32X, Saturn, Dreamcast |
| **PlayStation** | [pages/sony-top-100-games.html](pages/sony-top-100-games.html) | PlayStation 1, PlayStation 2, PSP, PS Vita |
| **Atari** | [pages/atari-top-100-games.html](pages/atari-top-100-games.html) | Atari 2600, 5200, 7800 ProSystem, Lynx, Jaguar |
| **NEC & SNK** | [pages/nec-snk-top-100-games.html](pages/nec-snk-top-100-games.html) | TurboGrafx-16, PC Engine CD-ROM, Neo Geo AES, Neo Geo Pocket Color |
| **Arcade** | [pages/arcade-top-100-games.html](pages/arcade-top-100-games.html) | MAME / Arcade, Capcom CPS, Sega NAOMI, Cave shooters |
| **Home Computers** | [pages/home-computers-top-100-games.html](pages/home-computers-top-100-games.html) | Commodore 64, Commodore Amiga, ZX Spectrum, MSX, MS-DOS/PC |

## 🆕 Arcade Page

The new arcade page adds a dedicated home for coin-op classics and emulator-era preservation favorites, with tabbed rankings covering:

- **MAME / Arcade** classics across the 1970s to 2000s
- **Capcom CPS** highlights from CPS-1, CPS-2, and CPS-3
- **Sega NAOMI / Atomiswave** arcade standouts
- **Cave shooters** and related bullet hell essentials

Like the rest of the site, the page is self-contained static HTML with built-in search and genre filtering.

## 🚀 Deploying to GitHub Pages

1. Push the repository to GitHub
2. Go to **Settings → Pages**
3. Set source to **Deploy from a branch** → `main` / `/ (root)`
4. The site will be live within a minute at the URL above

## 📁 Structure

```
index.html                        ← Landing page with links to all lists
pages/
  arcade-top-100-games.html
  atari-top-100-games.html
  home-computers-top-100-games.html
  nec-snk-top-100-games.html
  nintendo-top-100-games.html
  sega-top-100-games.html
  sony-top-100-games.html
```

All pages are self-contained static HTML with no build step or external dependencies (aside from Google Fonts).
