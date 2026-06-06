# 📜 Changelog

All notable changes to *Prompted by Adrianne* will be documented here.

This project adheres to [semantic versioning](https://semver.org/) and vibes-based glittery chaos.

Live Site: [Prompted by Adrianne](https://ai.adrianne.io)

---

## 2026-06-05 [v1.8] 💻 WordPress Headless CMS → Hugo Sync Workflow

### Added

- Added `static/sync-prompted.mjs` to synchronize content from a headless WordPress CMS into Hugo-compatible Markdown files.
- Added support for Prompt Cases, Projects, Playground entries, and Blog posts.
- Automatically generates Hugo frontmatter, tags, featured images, excerpts, and metadata from WordPress content.
- Established the content publishing workflow for Prompted by Adrianne.
- Laid the groundwork for future integration with additional sites in the Adrianne portfolio ecosystem.

---

## 2026-04-24 [v1.7] 🏷️ Tags and 🧹Cleanups

### Added
- Tags system using reusable `tags.html` partial
- Tags displayed on:
  - Blog posts
  - Prompt Case Reports
  - Projects
  - Playground posts
- New `playground/single.html` layout

### Changed
- Standardized post layout structure across all content types:
  - Content → Tags → Navigation
- Updated navigation buttons:
  - Blog → Back to Blog
  - Prompts → Back to Prompts
  - Projects → Back to Projects
  - Playground → Back to Playground
- Improved Colophon page:
  - Added link to Master Colophon (`adrianne.io`)
  - Adjusted spacing and layout for clarity

### Fixed
- Tags not rendering due to missing layout logic
- Inconsistent tag placement across templates
- Navigation buttons linking to incorrect pages (e.g. Home instead of section pages)

---

## 2025-12-28: [v1.6] 🎓📒🤦🏻‍♀️ AI Slop-based fake journals exist!

### 📝 Added
- Published new blog post: **AI Idgit Chronicles II: Fake Journals & AI Delulu**
  - Discusses the rise of fake academic journals generated with AI
  - Explores the ethical implications of misusing AI in scholarly work
  - Highlights the importance of critical thinking and verification when using AI tools

### ❌ Removed
- Deleted unused image assets no longer referenced by the site

---

## 2025-11-05: [v1.5] 🔗 Unified Credentials Page

### ✨ Updates
- Removed the local `Credentials` page from *Prompted by Adrianne* (`ai.adrianne.io`)
- Navigation link for `Credentials` now points to the master Credentials page at [Prompted by Adrianne](https://adrianne.io/credentials)
- Updated navbar template to support `target="_blank"` so external links open in a new tab

### 🧹 Cleanup
- Deleted outdated `content/about/credentials.md` file
- Confirmed working redirect behavior and cleaned up related configuration

## 2025-10-21: [v1.4] AI Idgit Chronicles I: The Math Ain't Mathing
- Added new blog post: **AI Idgit Chronicles I: The Math Ain't Mathing (OpenAI's Embarrassing Equation)**
- **AI Idgit Chronicles** series launched to highlight AI mishaps caused by human error, overconfidence, and lack of criticical thinking. I see a lot of anti-AI haters throwing shade at AI when in reality, many AI failures are due to people misusing or misunderstanding the technology

---

## 2025-09-29: [v1.13] 🔐 Privacy Notice and more

### 💫 Content Updates
- Added the **Privacy Notice** link to the page hosted by my link-in-bio/collective domain, [index.adrianne](https://adrianne.me/) on the footer partial
- Also added the **Changelog** link on the footer, right next to the **Privacy Notice** link. This is for the people who are too lazy to go on my repo and want a direct link to the changelog instead
- Added the sub-certifications of all the courses under the Google Data Analytics specialization in the `Credentials` page

### 🔧 Fixes
- Fixed the Markdown/HTML font-weight code on the **LinkedIn Certifications** box in the `Credentials` page
- Made the site title `Prompted by Adrianne` linkable to the homepage on the navbar partial. Many users tend to click on the site's title/logo to return to the home page, rather than the `Home` link

---

## 2025-09-22: [v1.12] 🎓 Responsible AI Certified

### 🌠 Content Updates
- New blog post: **Why I Pursued the Responsible Generative AI Certificate**
- Added the certificate link in `About > Credentials` page
- Updated `About` page to reflect current learning goals (including Responsible AI, Cybersecurity, and QA Testing)
- Updated `Colophon` page to include **Adobe Express** and royalty-free image sources for blog featured images

### 📝 Fixes
- Changed Shields badge on `README.md` to **Netlify**, since I recently moved its hosting from **Hosting.com**. I decided to host Hugo-powered (or any SSG-powered) sites on Netlify for its ease of use and convenient updates.

---

## 2025-09-20: [v1.11] ✝️ Beware of the Golden Calf

### ⭐️ Content Updates
- New blog post: **GPT Jesus: Water Into Vibes? 🤯✝️**

### 🔧 Fixes
- Moved a few blog post-specific images to the new `/static/images/blog/` folder for organization and consistency

---

## 2025-09-15: [v1.10] 🛠️ Big SAMPAL SQUAD Push

### ✨ New Additions
- Added **Not By AI** badge to footer (responsive + accessible)
- Added section about Not By AI on the Indie Web blog post
- Included "Written by a human..." message near footer
- New character sticker added: **🌠 Comet-kun** (illustrator: yours truly)
- Expanded **About** section to include full **SAMPAL SQUAD™** intro
- Added 🥪 **Sampal Sandwich** reference and internal lore (bread emoji power!)

### 📝 Content Updates
- Revised **Manifesto** with new section on human authorship
- Revised Indie Web blog post to clarify difference between AI-generated websites and AI-generated content
- Added backlink to NotByAI explanation page
- Added/linked more certs in the **Credentials** page

### 🔧 Fixes & Layout Tweaks
- Adjusted placements of footer stickers (Sprout-kun, Bun-Bun-kun, Potto-chan)
- Smoothed spacing below "Written by a human" text
- Footer layout improvements for responsiveness on mobile
- Fixed the **About** link on the mobile version... I hope it works, I still have yet to check it on my phone...

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
