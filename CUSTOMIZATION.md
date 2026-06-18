# Customization Guide

This document explains how to personalize your GitHub profile over time.

---

## The Simple Rule

**All your profile data lives in one file:** `profile-data.json`

To change anything — your name, tagline, projects, tech stack, goals — you edit that one file, then regenerate `README.md` using the editor.

---

## Using the Editor

1. Double-click `editor.html` to open in your browser.
2. Click **"📂 Load profile-data.json"** to load your current data.
3. Navigate using the sidebar tabs:
   - **Personal Info** — Name, title, bio, social links
   - **Tech Stack** — Click chips to select/deselect technologies
   - **Projects** — Add, edit, or remove projects
   - **Hackathons** — Add achievements
   - **Goals** — Update your goals
   - **Settings** — Change stats theme, toggle sections
4. Click **"💾 Save"** to download updated `profile-data.json`.
5. Click **"📄 README"** to download the generated `README.md`.
6. Replace both files in your repo and push.

---

## What to Update and When

### After completing a project
- Go to **Projects** tab → add the project with repo link and live URL.
- Change status from "In Development" to "Live".

### After learning a new technology
- Go to **Tech Stack** tab → click the chip to select it.
- If the technology isn't listed, use the **Custom Technology** form to add it.

### After a hackathon or competition
- Go to **Hackathons** tab → click "+ Add Hackathon".

### After earning a certification
- Edit `profile-data.json` directly and add to the `certifications` array.

### When you get a portfolio website
- Go to **Personal Info** tab → fill in the Portfolio URL field.
- A Portfolio badge will automatically appear on your profile.

---

## Tech Stack Badge Customization

Each technology badge uses [shields.io](https://shields.io) with logos from [Simple Icons](https://simpleicons.org).

To add a custom technology in the editor:
1. Go to the **Tech Stack** tab.
2. Scroll to **Custom Technology**.
3. Enter the name, category, logo slug (from simpleicons.org), and hex color.
4. Click **"+ Add Technology"**.

---

## Stats Theme Options

Available themes for GitHub stats cards:

| Theme | Style |
|-------|-------|
| `tokyonight` | Dark blue (default) |
| `radical` | Neon pink/purple |
| `dracula` | Dark purple |
| `synthwave` | Retro neon |
| `algolia` | Blue gradient |
| `onedark` | Atom One Dark |
| `cobalt` | Deep blue |
| `highcontrast` | Maximum contrast |

Change the theme in **Settings** tab → **Stats Theme**.

---

## Section Visibility

You can toggle these sections on/off in **Settings**:

- **Snake Animation** — The contribution graph snake
- **GitHub Trophies** — Achievement badges
- **Metrics Workflow** — Advanced GitHub metrics

---

## Profile Banner

The `banner.svg` file contains a custom SVG banner. You can edit it in any text editor or SVG editor to change:
- Name text
- Title/subtitle
- Accent color (currently `#58A6FF`)
- Background color (currently `#0D1117`)

> **Note:** The current README uses `capsule-render` for the header instead of the banner SVG. You can switch to the banner by editing the README manually if preferred.

---

## Commit Message Convention

When pushing profile updates, use clear commit messages:

```
feat: add new project XYZ
update: refresh tech stack
fix: correct LinkedIn URL
docs: update README with new goals
```

---

Keep the profile clean, honest, and project-focused. Let your work speak for itself. 🚀
