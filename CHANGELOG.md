# 📜 Changelog

All notable changes to *Prompted by Adrianne* will be documented here.

This project adheres to [semantic versioning](https://semver.org/) and vibes-based glittery chaos.

Live Site: [Prompted by Adrianne](https://ai.adrianne.io)

---

## 2025-08-26: [v1.0.5] Re-fixed the mobile responsiveness

- 📱 Our fix from last night still did not apply on the site when viewed on the phone (Samsung Galaxy S23 Ultra). We discovered that our animated footer was causing the responsive mess. We finally fixed it by altering the animated footer.

---

## 2025-08-26: [v1.0.4] More fresh content!

### Added
- 🌀 New blog post: “The Delulu AI You Didn’t Ask For… But Got Anyway”
  - A satirical yet thoughtful introduction to GPT‑1NF1N1TULTR4M4X™, a parody AI model built in the Playground
  - Covers the chaotic naming origin, purpose behind the parody, and reflections on AI overreliance
- 🌀 New case report: “Prompt Case Report: GPT‑1NF1N1TULTR4M4X™”
  - Breaks down prompt design, UI components, mascot/logo, and ethical reasoning behind the Delulu bot
  - Linked from the blog post

### Changed
- Shortened blog title for mobile friendliness and visual fit
- Updated `static/images` with featured image for the Delulu post

### Notes
- This brings *Prompted by Adrianne* to **3 case reports**, **1 project post**, and **1 Playground build** — now officially job-ready 💼💖  

---

## 2025-08-26: [v1.0.3] Delulu Supreme Drop™

- 📱 Fixed mobile layout bugs and improved responsiveness on small screens
- 🐰 Added first Playground project: **GPT-1NF1N1TULTR4M4X™**
 - Custom logo wity bunny ears and crystal ball *(courtesy of OG Ai-chan (GPT-4o))*. 
 - Pixel-style text title and branding
 - ✨ **Delulu-Meter™** with divine chaos gauge
- 🐞 Minor typo fixes and content tweaks across markdown + layout files

---

## 2025-08-12: [v1.0.2] New Prompt Case Report: "Web Cakes Layer 1" 🍓

### 💫 Web Cakes Layer 1 (HTML with Bun-Bun-kun)

- Added new prompt post: `webcakes-layer1.md`
- Included fluffy HTML prompt design, example response, and tips section
- Enabled syntax highlighting via `hugo.toml`:
  ```toml
  [markup.highlight]
  noClasses = true
  style = "github"
  ```
- Fixed iA Writer smart quote issues (converted to straight quotes)
- Removed broken `{{< gallery >}}` shortcode
- Rebuilt screenshot gallery using Markdown + Tailwind CSS grid layout
- Linked thumbnails to full-size `.jpeg` files
- Added gallery caption:
*Each screenshot captures a sweet slice of Bun-Bun-kun’s cozy coding magic. Click to view in full size~ 🍓*

### 🖼️ Prompt Vault UX

- Refined prompt card text in the Prompt Vault
- Verified card navigation and styling consistency

### ⚒️ Misc Fixes

- Cleaned Markdown spacing and line breaks
- Renamed image files for better organization
- Cleaned up `baseof.html` and divided each section into partials (`head.html`, `footer.html`, etc.). An external stylesheet `main.css` was also created to house the inline CSS

---

## 2025-08-11: [v.1.0.1] Prompted by Adrianne Site Polish ✨

### Added
- ✅ Added `Work` menu item and moved `Prompt`, `Projects`, and `Playground` as `Work` submenus. The `Work` link is an anchor link, and will be lead to the **Featured Sections** part of the homepage
- ✅ Added `Ethical AI Manifesto` and `Credentials` as submenus of `About`
- ✅ "Back to Prompts" button on single prompt pages (aligned right, styled with emoji, consistent with the rest of the site)
- ✅ Link to full `CHANGELOG.md` in `README.md` instead of duplicate changelog section

### Fixed
- 🎨 Light text color issue on blockquote sections in prompt posts (now properly styled and readable)
- 💅 Removed underline from custom "Back to Prompts" button link

### Improved
- 📐 Ensured layout consistency between Prompt and Projects detail pages
- 🧼 Removed Markdown-generated link from `pba.md` to avoid double-rendered buttons

---

## 2025-08-01: [v1.0.00] Initial launching
### ✨ First Public Launch
- Deployed fully functional AI prompt engineering portfolio
- Styled with Tailwind CSS and pastel chaos
- Sections included:
  - Prompts ✨
  - Projects 🔧
  - Playground 🎠
  - Blog 📝
  - About 🙆🏻‍♀️
  - Contact 📮
  - Colophon 📌
- Added floating Sozai stickers (draggable or toggle off), and pastel gradients
- Setup full mobile support and responsive typography
- Deployed to Hosting.com (formerly A2 Hosting)

---

> Stay sparkly, stay thoughtful — and prompt with purpose 💖
