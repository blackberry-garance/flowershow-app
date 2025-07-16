# 🚧 Best blog solutions for Obsidian users

## Cloud

**Need:** I'm authoring my blog in Obsidian. What are the best hosted (cloud) platforms where I could publish my blog? I want to keep authoring in Obsidian.

### Obsidian Publish

**Workflow**:

Click “Publish” from any note (or a folder) inside Obsidian and your site is live.

**Markdown syntax support**:

All the core Obsidian syntax features supported.

**Pricing & features**:

- $8 / month per site when billed annually
- $10 / month when billed monthly)

**Pros**:
- minutes to set up,
- all core Obsidian syntax features supported.

**Cons**:
- pricey,
- ...

### Ghost(Pro) + Obsidian plugin

**Workflow**:

Obsidian "Send to Ghost" plugin lets you push a note straight to your Ghost site via its Admin API.

**Markdown syntax support**:

Ghost renders standard Markdown (plus GitHub-flavoured features like tables and footnotes when used inside a Markdown card) and lets you mix in rich “cards” for images, embeds or raw HTML. Math or Mermaid require adding your own JS/CSS, and Obsidian-style [[wikilinks]] are not recognised—you’d need a pre-publish conversion or switch to regular Markdown links.

**Pricing**:

Ghost(Pro) starts at $9 / month for fully managed hosting with CDN, email newsletter, memberships, Stripe integration, backups, and security.  
￼
**Pros**:
- Managed “everything-in-one” stack—blog, newsletter, paid memberships, Stripe—so you can monetise and control branding without self-hosting.

**Cons**:
- Starts at $9/month and scales with audience; custom themes require developer effort.

### HashNode (Pro)

**Workflow**:

Enable Hashnode’s “Publish articles from GitHub”. Every markdown file pushed to a chosen repo is auto-published (or updated) on your Hashnode blog; front-matter controls title, tags, draft state, etc. Use the free Obsidian Git community plugin to sync your vault (or just a /blog folder) to GitHub on save or on demand.

**Pricing**

Hashnode gives you comments, reactions, built-in newsletter, custom domain, and a dev-centric audience.

**Pros**:
- ...

**Cons**:
- Publishin from GitHub is only available on the Pro plan

### Blot.im

**How it works**

Blot watches a folder you control (via Dropbox, Git, Google Drive, or iCloud). Any Markdown file you save there from Obsidian is auto-converted into static HTML and published within seconds—no manual builds or dashboards required.

**Markdown syntax support**

Blot renders standard CommonMark plus most Pandoc-style extras—tables, footnotes, definition lists, fenced-code with syntax highlighting, and KaTeX maths. Crucially for Obsidian users, it resolves `[[wikilinks]]` for pages, provided you keep Obsidian’s New link format → Relative path to file. It doesn't support `![[…]]` embeds for images or other files.

### Micro.blog

**Workflow**:

Write your post in Obsidian, then run the free "Micro.publish" community plugin. After you paste an app-token from Micro.blog into the plugin’s settings, a single command (“Post to Micro.blog”) pushes the note over the Micropub API, letting Micro.blog host it instantly under your custom domain. You can override title, categories, visibility, or a future publish-date in a review dialog before sending, and the post’s URL is written back into the note so you can update it later.

**Markdown syntax support**:

Standard Markdown works, but Micro.blog purposely strips or truncates heavy markup in its social “timeline” view to keep micro-posts readable. Anything over 300 characters loses inline Markdown/HTML in the timeline excerpt (your full post still keeps it). 

**Featues and Pricing**: https://micro.blog/about/pricing

| Plan | Price | Key features |
| --- | --- | --- |
| Micro.one | $1/month | Use your own domain name; Short or long posts; Photo hosting; Podcast hosting; Publish from the web or native apps |
| Micro.blog | $5/month | Everything in Micro.one plus: Automatic cross-posting to Mastodon, Threads, Bluesky, and other services; Manual cross-posting to Twitter / X; Photo and video hosting; Custom themes |
| Micro.blog Premium | $10/month | All standard Micro.blog features plus: Up to 5 blogs; Email newsletters; Private and shared notes; Strata mobile app for notes; Bookmark archiving and highlighting |
| Micro.blog Family | — | Add up to 5 people to any of your blogs; Members can write or edit blog posts; Includes everything from Micro.blog Premium |

**When to choose:**

Pick Micro.blog if you want a “write in Obsidian → publish anywhere” flow with no server maintenance, don’t mind its minimalist design philosophy, and like the idea of your blog doubling as a small fediverse-enabled social network.

**Pros:**
- Cheap entry price
- Zero-setup hosting that still lets you export everything as plain Markdown + Hugo theme
- Built-in ActivityPub timeline and automatic cross-posting keep your content discoverable without extra work  ￼
- Open Micropub API, so you could swap the Obsidian plug-in for any script or automation later  ￼
- Community plug-in scene for themes, analytics, photo galleries, etc.

**Cons**:
- The Micro.publish plug-in is not first-party; its last released version is a year old, so you’re at the mercy of volunteer maintenance (though commits in the repo show activity ~80 days ago)  ￼
- Markdown extras (footnotes, tables, code highlighting) work on your site but are stripped in timeline previews once a post exceeds 300 characters, which can surprise readers  ￼
- Theme customization is possible but still Hugo-centric; deep changes require Hugo template skills or third-party plug-ins  ￼
- No built-in advanced SEO or monetization tools (ads, paywalls, etc.) — you would add those manually in a theme.


## Self-hosted

...
