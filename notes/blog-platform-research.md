# Best Cloud Blogging Platforms for Obsidian Users

Obsidian users looking to publish a blog directly from their vault have a few hosted options. Below, we compare the top platforms and how they support an Obsidian-centric workflow, including setup, Markdown features (CommonMark, GFM, Obsidian wiki links, embeds, Mermaid diagrams, and LaTeX math), pricing, key features (search, newsletter sign-ups, sidebars, indices), pros, cons, and ideal use cases.

### Obsidian Publish (Official Service)

https://obsidian.md/publish

<img width="1454" height="908" alt="image" src="https://github.com/user-attachments/assets/ed7e41e9-7fb6-49d3-b4b8-01a017591754" />


**Workflow**

Obsidian Publish is Obsidian’s official hosted publishing service. It requires **no technical setup** – you simply sign up and use the **built-in Publish plugin** in Obsidian to select which notes to publish. Once enabled, you can keep writing in Obsidian and with a few clicks push updates to your published site. Your vault’s folder structure and internal links become a website automatically, with Obsidian’s familiar navigation sidebar showing folders and notes.

**Markdown syntax support**

Obsidian Publish fully supports **standard Markdown (CommonMark)** and **GitHub Flavored Markdow**n elements (tables, task lists, etc.) since it essentially mirrors Obsidian’s preview. Critically, it supports **Obsidian’s wiki-links and embeds** out of the box – your `[[Internal Links]]` between notes work seamlessly online. **Mermaid diagrams** (in mermaid code blocks) and **LaTeX math** (using $...$ or $$...$$) render as they do in Obsidian, since these are core features of Obsidian. However, note that third-party Obsidian plugins (especially those using code fences for things like dataview queries or charts) do not run on Publish, so any content relying on community plugin-specific syntax might not display as expected.

**Pricing**

Obsidian Publish is a paid add-on, **$8 USD per site per month (annual billing)** or **$10 month-to-month**. This is charged **per published site** (vault). There’s no free tier.

**Features:**

A published Obsidian site retains unique Obsidian features like the **interactive graph view** of your notes and backlink lists. You can apply a **custom theme or CSS for styling**. A **sidebar with folder navigation** is standard, and recent updates allow customizing which pages appear in the sidebar and in what order. Obsidian Publish sites now include a search bar with **full-text search**. There is **no built-in newsletter or commenting system** – Publish is oriented toward a knowledge-base or digital garden style site rather than a traditional blog with subscriptions. Likewise, there’s no automatic blog index by date, but you can create index pages or use tags to organize posts manually. **SEO metadata** is supported via frontmatter. 

**Pros:**
- Easiest setup: entirely managed solution with no technical skills required.
- Native Obsidian features: supports wiki links, embeds, graph view, backlinks, Mermaid, math, etc., preserving the feel of Obsidian in the browser.
- Instant updates: changes can be published within seconds via the Obsidian interface.
- Customizable look: can use Obsidian themes/snippets for styling.
- Reliable and secure: official service maintained by the Obsidian team, with priority support for subscribers.

**Cons:**
- Cost: $96/year per site may be expensive for hobby blogging.
- Limited extensibility: Does not support third-party plugins or dynamic features like comment sections, forms, or certain advanced Markdown extensions (e.g. dataview queries).
- Single site per subscription: If you want multiple separate sites from different vaults, you pay per site (no multi-site bundle) ￼.
- No built-in newsletter: Followers can’t “subscribe” via email (but there is a basic RSS feed generated).
- No build-in comments: Visitors can't comment on the content.

**When to Choose:**: Obsidian Publish is ideal if you want the most hassle-free experience and full fidelity with Obsidian’s features. It’s great for publishing a digital garden, wiki, or notes collection where interactive graph and internal links shine. If you don’t mind the subscription cost and don’t need fancy blog-specific features (comments, newsletters), Publish offers a polished experience with minimal setup. Less tech-savvy users who want their Obsidian vault online with just a few clicks will appreciate this official solution. However, if budget is a concern or you need advanced blog features or plugin support, consider the alternatives below.

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
