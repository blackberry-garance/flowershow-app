---
title: "Moving My Personal Website to Flowershow — Part 1"
date: 2025-05-19
author: rufuspollock
---

https://youtu.be/5qtoko0S5nI

> [!hint] **TL;DR**
> I’m migrating **rufuspollock.com** to **Flowershow** so I can write once and publish without shuffling files. Flowershow works with the folder structure I already have and eliminates the “two-copy” workflow that’s been slowing me down.
---

## 1. Background

I set up my site years ago with a static site generator that was fast, open, and dependable.  
It still *works*, but publishing has slowed down—not because I’ve stopped writing, but because the tooling has become a barrier.

Right now, my site includes:

- A landing page  
- Static pages (About, Speaking, etc.)  
- A blog section  

That structure stays. But how I manage it needs to change.

---

## 2. Where My Current Setup Falls Short

### 2.1 Folder Constraints  

The current system enforces a rigid structure that doesn’t match how I actually organize my content:

- Content structure requires specific nesting and sometimes specific filenames  
- Images must live in special asset directories  
- It’s hard to just drop in a `README.md` and call it a landing page  

### 2.2 Maintenance Overhead  

Every small update tends to become a multi-step process:

1. Update dependencies  
2. Relearn outdated tooling  
3. Fix broken layouts or theme bugs  
4. Rework Markdown that no longer renders cleanly  

### 2.3 The Two-Copy Problem  

- **Write** in Obsidian  
- **Adjust** front-matter and formatting  
- **Move** the file into the correct location for the site  
- **Repeat** for every edit  

It creates just enough friction to make publishing feel like a chore.

---

## 3. What I Need in 2025

1. Write once, publish directly  
2. A ready-made landing page and blog  
3. Minimal upkeep when I come back after a break  

---

## 4. Flowershow at a Glance

Flowershow is an open-source static-site generator built around **markdown-first knowledge bases**. Drop it into any folder and it will:

- Publish from your existing folder structure—no enforced hierarchy  
- Support Obsidian-style wiki links, callouts, and embeds  
- Ship with a landing page, blog, and search built-in  

In short, **your notes become your website**—with no copy-paste or restructuring required.

---

## 5. What’s Next?

In **Part 2**, I’ll share a live prototype, along with insights on build speed, theme flexibility, and vault compatibility.

Stay tuned—and happy hacking!