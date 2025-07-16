# Blog platforms

## Related threads / blog posts:

### (Andrej Karpathy tweet) [https://x.com/karpathy/status/1751350002281300461](https://x.com/karpathy/status/1751350002281300461)

SUMMARY:  
**Needs:**

1. **Writing**  
- True WYSIWYG Markdown editor (no split-view hacks)  
- Seamless image insertion and management (drag-drop, clipboard paste)  
2. **Deploying**  
- Static-site output (e.g. Jekyll/Hugo-style)  
- Minimal, hand-crafted HTML/CSS (no extra bloat)  
- One-step deployment to a custom URL (e.g. via Git push)  
3. **Maintaining**  
- Built-in analytics dashboard (or easy Google Analytics integration)  
- Native comments support (e.g. Disqus-style plug-and-play)  
4. **Ownership & Portability**  
- Full access to raw source files (Markdown, assets, config)  
- Easy export/migration path at any time

**Issues with the current setup:**

1. **Editor frustrations**  
- VS Code \+ markdown extensions: no true WYSIWYG, clumsy image handling **💬later used Obsidian and liked it based on the comments**  
- Typora export workflow: still feels like a two-step hack rather than seamless writing  
2. **Jekyll \+ GitHub Pages**  
- Heavy (Bloaty HTML/CSS output)  
- Frequent breakages (Jekyll)  
- Painless git push  
- No built-in analytics/comments—must bolt on and pay for GA/Disqus separately

**Comments on Medium/Substack:**

- Lock-in via proprietary platform, dark patterns (login walls, highlights, popups)  
- Lack of easy export to clean markdown \+ assets

### Alex Oliveira Blogging Manifesto [https://alexoliveira.cc/essay/blogging-manifesto](https://alexoliveira.cc/essay/blogging-manifesto)

SUMMARY:  
**Needs:**

1. **File-based simplicity**  
- Everything lives as plain Markdown files—no databases, adapters or migrations.  
2. **Total ownership & portability**  
- Full control over design, domain, file structure; easily moveable (even to a Raspberry Pi).  
3. **Offline writing**  
- No internet dependency—write anywhere (camping, airplane, etc.) on desktop or mobile.  
4. **A delightful editor**  
- A writing interface as pleasing as iA Writer, but not tied to a specific backend.  
5. **One-click publishing**  
- Write offline, then publish with a simple button press—no manual copy-paste or terminal gymnastics.  
6. **Rapid iteration**  
- Ability to push drafts immediately and refine over time (e.g. via a “deploy” hotkey).  
7. **Low-cost hosting**  
- Host static files for free or near-free (e.g. GitHub Pages).  
8. **Second-brain integration**  
- Seamlessly bridge personal note-taking (Obsidian’s linked Markdown vault) with public content, so tiny ideas and long essays alike can coexist and be shared.

**Issues with existing tools:**

1. **Excessive technical overhead**  
- Static-site generators like Jekyll (and custom Rails admin panels) force you into git-and-terminal workflows just to write or publish.  
- Self-hosted frameworks (Rails, Ember, etc.) require you to manage servers, migrations, build pipelines, plugins…  
2. **Vendor lock-in & migration friction**  
- Platforms like WordPress, Ghost or Substack “just work,” but tie your content and data model to their back ends—making future moves (or full exports) painful.  
- Proprietary note-apps (Evernote, Roam, etc.) hide your information behind opaque databases or APIs.  
3. **Poor offline support**  
- Many “modern” editors and platforms assume you’re always online; writing or publishing when you’re disconnected (camping, flying, etc.) is impossible or painful.  
4. **Disjointed authoring vs. publishing UX**  
- Tools that feel great for writing (iA Writer, Obsidian) often lack an integrated, one-click publish mechanism.  
- Conversely, “publishers” (WordPress dashboards, Netlify UIs) force you to copy-and-paste or reformat in-browser rather than editing in your favorite local editor.  
5. **Slow iteration cycles**  
- Even “static” workflows can require multiple commands or page-reloads to push small changes, discouraging quick drafts and incremental edits.  
6. **Cost & complexity for simple needs**  
- Hosting a few Markdown files shouldn’t require paid plans, container orchestration, or database licenses, yet many “full-featured” solutions push you toward ever-higher hosting tiers.  
7. **Lack of unified note-to-blog flow**  
- Personal “second-brain” note apps seldom expose a path to easily repurpose fragments or atomic notes as public posts, so your Zettelkasten and your blog live in separate silos.

**Also blogged about Jekyll \+ Obsidian setup: [https://alexoliveira.cc/guide/jekyll-with-obsidian](https://alexoliveira.cc/guide/jekyll-with-obsidian)**

### **Steph Ango \- File over app [https://stephango.com/file-over-app](https://stephango.com/file-over-app)** 

“*File over app* is a philosophy: if you want to create digital artifacts that last, they must be files you can control, in formats that are easy to retrieve and read. \[...\] accept that all software is ephemeral, and give people ownership over their data”

### **The Surprisingly High Table Stakes of Modern Blogs [https://www.swyx.io/the-surprisingly-high-table-stakes-of-modern-blogs](https://www.swyx.io/the-surprisingly-high-table-stakes-of-modern-blogs)** 

