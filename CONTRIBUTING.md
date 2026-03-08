# Contributing to GitPersona ⚡

First off — thank you for being here! GitPersona is an open source project built by a developer in their vibe coding era, and every contribution helps make it better for everyone.

This guide explains how to contribute, no matter your experience level.

---

## 🙋 Who Can Contribute?

Anyone. Seriously. You don't need to be an expert developer. If you can edit a JSON-like object or tweak some CSS, you can contribute to GitPersona.

---

## 🚀 How to Get Started

1. **Fork the repo** — click the Fork button at the top right of the repo page
2. **Make your changes** — directly in the browser or locally
3. **Submit a Pull Request** — describe what you changed and why
4. **Wait for review** — we'll get back to you as soon as possible

---

## 🎭 How to Add a New Vibe

Vibes live inside `index.html` in two places:

**1. Add the vibe card in the HTML** (inside the `vibe-grid` div):
```html
<div class="vibe-card" onclick="selectVibe(this, 'yourvibe')">
  <span class="emoji">🔥</span>
  <div class="vibe-name">Your Vibe Name</div>
  <div class="vibe-desc">One sentence describing the vibe.</div>
</div>
```

**2. Add the vibe instruction in the JavaScript** (inside the `vibeInstructions` object):
```javascript
yourvibe: "Write in [your tone description here]. Describe how the AI should write for this vibe.",
```

That's it! Submit a PR with the title: `feat: add [vibe name] vibe`

---

## 🎨 How to Add a New Colour Palette

Palettes also live in `index.html` in two places:

**1. Add the palette card in the HTML** (inside the `palette-grid` div):
```html
<div class="palette-card" onclick="selectPalette(this, 'yourpalette')">
  <div class="swatch">
    <span style="background:#hex1"></span>
    <span style="background:#hex2"></span>
    <span style="background:#hex3"></span>
  </div>
  <div class="palette-name">🟣 Palette Name</div>
  <div class="palette-desc">One sentence describing the mood.</div>
</div>
```

**2. Add the palette instruction in the JavaScript** (inside the `paletteInstructions` object):
```javascript
yourpalette: "Use shield.io badge color: hexcode. Suggest a [mood] aesthetic.",
```

Submit a PR with the title: `feat: add [palette name] palette`

---

## 🐛 How to Fix a Bug

1. Open an issue first describing the bug (or find an existing one)
2. Comment to claim it: *"I'd like to work on this!"*
3. Fix it in your fork
4. Submit a PR with the title: `fix: [short description of the bug]`

---

## 🎨 How to Improve the UI

UI improvements are welcome! Please:
- Keep the dark theme as the default
- Don't break existing functionality
- Test in at least one browser before submitting
- Submit a PR with the title: `style: [short description]`

---

## 📝 Pull Request Guidelines

- Keep PRs small and focused — one change per PR
- Write a clear title using conventional commits format:
  - `feat:` for new features (vibes, palettes)
  - `fix:` for bug fixes
  - `style:` for UI changes
  - `docs:` for documentation updates
- Link any related issues using `Closes #issue_number`

---

## 🏷️ Issue Labels

| Label | Meaning |
|---|---|
| `good first issue` | Perfect for first-time contributors |
| `help wanted` | We'd love community help on this |
| `bug` | Something is broken |
| `enhancement` | New feature or improvement |
| `ui` | Visual or design change |

---

## 💬 Questions?

Open an issue or reach out via email: **m.faraday99@gmail.com**

We're friendly here. No question is too small. 🙌

---

*Built with ideas, caffeine, and a refusal to die of analysis paralysis. ⚡*
