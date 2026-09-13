# Discord Theme — Yellow Black (Complete Edition)

A sleek **highlighter-yellow & black** theme for Discord, built for **Equicord** (and compatible with Vencord/Bunny/Vendetta). Dark mode only.

## What's themed
The theme covers the whole Discord UI via CSS variables **plus** component-specific tweaks:

- **Server list** — yellow unread/active pill, yellow action buttons, glow on hover, folder styling
- **Channel sidebar** — black rails, yellow selected channel, yellow search bar & hover accents
- **Chat** — black pane, yellow mentions/code/links, styled embeds with yellow border, dividers, "new messages" bar, jump bar, typing indicator, reactions, attachments & threads
- **Input bar** — black rounded message box with yellow focus glow
- **Members list & user panel** — black panels, yellow status name tag, yellow voice/mic toggles
- **Modals, popouts & context menus** — black floating surfaces with yellow selected/hover items
- **Settings** — yellow active nav icon, yellow toggles/sliders/checkboxes, boost progress accent
- **Tooltips, scrollbars, loading/login screen** — all yellow-on-black
- **Effects** — subtle moving light sheen, smooth transitions, accent pulse animation (both respect `prefers-reduced-motion`)

## Files
- `YellowBlack.theme.css` — the actual CSS theme (import this).

## Installation (Equicord)

1. **Online theme (recommended):**
   - Open Discord → **Settings → Themes** (or `QuickCSS`).
   - Paste the URL where `YellowBlack.theme.css` is hosted (e.g. a GitHub raw link), or copy the file into your Equicord themes folder and refresh.
2. **Local file:**
   - Put `YellowBlack.theme.css` inside your Equicord `themes` folder, then toggle it on in **Settings → Themes**.

> Make sure **Dark Mode** is enabled (Settings → Appearance → Theme: Dark) for the best look.

## Customizing
Edit the palette at the top of `YellowBlack.theme.css`. The main switches:

| Variable | Purpose | Default |
|----------|---------|---------|
| `--yb-yellow` | Main accent (buttons, links, brand) | `#f2c400` |
| `--yb-yellow-bright` | Hover / highlight | `#ffd93d` |
| `--yb-yellow-dark` | Pressed accent | `#c9a200` |
| `--yb-bg-deep` / `--yb-bg-soft` | Black background shades | `#0a090d` / `#17161c` |
| `--yb-font` | App font stack | `"gg sans", …` |
| `--yb-sheen` | The moving light sweep — set to `transparent` to disable | `rgba(255,217,61,.40)` |

You can also change the `@author`, `@source`, and `@invite` values in the header comment to credit yourself.