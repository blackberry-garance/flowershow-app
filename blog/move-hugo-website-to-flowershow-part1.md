---
title: "Moving My Personal Website from Hugo to Flowershow — Part 1"
date: 2025-05-19
author: rufuspollock
---

https://youtu.be/5qtoko0S5nI

> [!hint] **TL;DR**
> I’m migrating **rufuspollock.com** from Hugo to **Flowershow** so I can write my content once and publish without shuffling files. Flowershow respects whatever folder-structure I’m already using and eliminates the “two-copy” workflow that’s been slowing me down.

---

## 1. Background

I launched my Hugo site years ago because it was blazing fast, reliable, and open-source.  
It still *works*, but lately I’ve published less and less—and the culprit isn’t writer’s block; it’s friction in the toolchain.

Today my site includes:

- A landing page  
- Other static pages (About, Speaking, etc.)  
- A blog section 

All of that stays, but the way I maintain it needs to change.

---

## 2. Where Hugo Now Gets in My Way

### 2.1 Directory Rigidity  

Hugo’s philosophy is *“project tree mirrors website tree.”* That has advantages, but it also locks you into a specific layout:

- to create a landing page you need to create `/content/_index.md` (I just want to use a standard `README.md` file)
- `/content` folder can only include folders (apart from the above mentioned landing page file)
- to create a top level single page - e.g. About page - you need to do `/content/about/index.md` (I just want `/content/about.md`...)
- images need to be places either in a top level `/assets` folder or places carefully within `/images` folders next to the pages I use them on
- ... and more

### 2.2 Dependency Drift  

Every “quick tweak” turns into:

1. Install the latest Hugo  
2. Update NPM dependencies  
3. Debug theme breakage  
4. Fix Markdown that renders differently in the new version  

### 2.3 The Two-Copy Workflow  

- **Write** in Obsidian  
- **Copy / tweak** front-matter  
- **Move** Markdown + assets into Hugo’s folders (different from my vault's structure)
- **Repeat** for every new page or edit  

Result: context-switching tax that nudges me toward “I’ll publish this later.”

---

## 3. What I Need in 2025

1. Zero-copy content management  
2. A solid landing page + blog out of the box  
3. Minimal maintenance whenever I return after months away  

---

## 4. Flowershow at a Glance

Flowershow is an open-source static-site generator built around **markdown-first knowledge bases**. Drop it into any folder and it will:

- Treat *every* sub-folder as publishable content—no enforced structure
- Render Obsidian-style wiki links, call-outs, and embeds without hacks.  
- Ship a landing page, blog, and search with sensible defaults.  

In short, **my vault becomes my website**—no copy-paste, no folder contortions.

---

## 5. Migration Plan

| Phase | Goal | Status |
|-------|------|--------|
| **1. Scaffold** | Init Flowershow next to Hugo for side-by-side testing | 🔄 In progress |
| **2. Landing Page** | Re-implement hero, CTAs, and basic branding | ⬜ Pending |
| **3. Content Import** | Point Flowershow at my vault and check links/media | ⬜ Pending |
| **4. Redirects & SEO** | Preserve existing URLs with redirect rules | ⬜ Pending |
| **5. Cut-over** | Swap DNS, decommission Hugo build | ⬜ Pending |

---

## 6. What’s Next?

In **Part 2** I’ll cover getting a Flowershow prototype live and measuring build speed, theme flexibility, and Vault compatibility. 

Stay tuned—and happy hacking!