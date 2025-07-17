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

### Flowershow

<img width="1454" height="908" alt="image" src="https://github.com/user-attachments/assets/df3ca630-52bc-4a78-8e74-ab4ef2c9bf0b" />

**Workflow:**

Flowershow is a cloud platform specifically designed to publish Markdown/Obsidian content as a beautiful website. It offers both an **Obsidian plugin** and a GitHub-integrated workflow. In practice, you create a GitHub repository for your notes and the Flowershow platform will auto-sync the content and build the site. The Obsidian plugin (Flowershow Publish) can help by pushing notes to GitHub for you and tracking which are published. Once set up, your editing remains in Obsidian; whenever you commit changes (or use the plugin to sync), Flowershow regenerates the site. Overall, for a user, the flow is: **Write in Obsidian → push/sync to GitHub (with Flowershow Obsidian plugin) → Flowershow auto-updates site.**

**Markdown Support:**

Flowershow was built with Obsidian users in mind and strives for **full Obsidian Markdown compatibility**. It explicitly supports **CommonMark** and **GFM** specs, plus **Obsidian’s extensions like wiki-links, embeds and callouts** – essentially all core Markdown and Obsidian syntax. **Mermaid diagrams** render natively by just including a mermaid code block. **Math** is supported via KaTeX – writing inline $math$ or $$display$$ math will render equations on your site. (One current limitation: Flowershow does not yet support the Obsidian graph view visualization – it focuses on content rendering rather than replicating the entire Obsidian UI). In summary, content compatibility is excellent – you won’t need to rewrite or re-arrange your notes to publish with Flowershow.

**Pricing:**

Flowershow offers a generous free tier. **Free plan: $0/month for a site**, which includes all core markdown support and basic site features. The free plan does require you to use a Flowershow subdomain and includes attributions in the footer. The **Premium plan is $5/month (or $50/year)**. Premium unlocks using a custom domain, removal of the “Built with Flowershow” branding, and adds advanced features like full-text search for your site. Premium users also get unlimited site size and priority support. Notably, most features are available on free sites – even math, Mermaid, custom styles, and even forms and comments are included in free tier. This makes Flowershow’s free tier very functional for personal blogs or notes, while serious bloggers or businesses can pay a modest fee for professional touches.

**Features:**

Flowershow comes with many features out of the box:

- **Site structure & navigation**: Flowershow supports a **sidebar navigation** menu and automatic **table of contents** on pages. It also can generate content catalog pages with pagination – essentially blog index pages that list your posts or notes in a structured way. This is great for blogs: you can have a homepage showing recent posts, or separate sections for tutorials vs. articles. On the premium plan, Flowershow provides built-in **full-text search** across your site.
- **Blog-specific features**: There is support for page authors with avatars (useful if you have multiple authors or want a bio shown), hero sections for a nice banner on your homepage, and comments integration via Giscus. Flowershow also supports forms – you can embed a newsletter signup form or contact form easily. You can also integrate with your **Google Analytics**. 
- **Customization**: Both free and paid users can apply custom CSS to style their site. You can also customize social share images, favicon, etc. on Premium plan. It basically provides a modern, professional website setup for your Obsidian content.
- **Integration & plugin**: The official Flowershow Obsidian plugin helps automate publishing so you never need to leave Obsidian to publish changes, after initial setup.

**Pros:**
- **Excellent Obsidian syntax support:** CommonMark, GFM, wiki-links, embeds, Mermaid, math, callouts, footnotes – all just work ￼ ￼. Minimal friction in publishing your notes.
- **Rich feature set:** Even the free version includes features like comments, forms (for newsletter sign-ups), theme customization, blog indexes, etc., which can make your Obsidian vault feel like a polished blog or documentation site.
- **Affordable premium:** At $5/month, you get custom domain, full search, and branding removal ￼ – cheaper than Obsidian Publish and on par with Markbase’s paid tier, but arguably with more features.
- **Active development:** Flowershow is actively developed. You benefit from regular improvements and can get help instantly.
- **Auto-sync and Obsidian plugin**: Publishing updates is relatively easy after setup. The integration with GitHub means your content is version-controlled too. Non-technical users get a UI-driven setup, and tech-savvy users can customize their workflow.

**Cons:**
- **Initial setup complexity:** Compared to Obsidian Publish, Flowershow’s onboarding is a bit more involved. You need a GitHub account and must create a repo for your notes.
- **Missing Graph view:** If the interactive graph of Obsidian is important to you, Flowershow currently does not provide a graph visualization of your notes on the site (unlike Obsidian Publish or Markbase). It focuses on content and navigation over visual graphs.
- **Learning curve for advanced customization:** While powerful, using features like custom React components or deeply altering the theme will require technical knowledge. The out-of-box style is nice but might not please everyone (though you can change it with CSS).

**When to choose:**

Flowershow is an excellent choice if you want a **full-featured blog or knowledge site** and don’t mind a bit of initial configuration. It shines for users who desire Obsidian’s benefits and traditional blogging features like newsletters, comments, and structured indexes. If you have some comfort with tools like GitHub (or are willing to follow step-by-step instructions to set it up), you’ll be rewarded with a very powerful platform at minimal cost. Flowershow is ideal for content creators or small businesses using Obsidian: for example, a personal blog, a documentation site for a project, or an academic digital garden that needs search and taxonomy. Less tech-savvy users can use it too – the interface guides you – but it’s best if you’re not completely allergic to using an extra service (GitHub) during setup. Choose Flowershow if you value extensive Markdown support and blog features and are looking for a cost-effective, community-driven solution.

### Ghost(Pro)

**Workflow**:

Ghost does not natively integrate with Obsidian but you can use a **community plugin (Obsidian Ghost Publish)** to send a note directly to Ghost as a draft post using the Ghost API. With this plugin, you write in Obsidian and click a Ghost icon to upload the post. Without the plugin, the common workflow is manual: create a new post in Ghost Admin, switch to Markdown mode (/md command in the editor), then paste the Markdown. Ghost’s editor will automatically convert Markdown to its native format for editing. For bulk publishing of many Markdown files, Ghost provides migration tools and an Admin API that accepts raw HTML or Markdown, but some scripting is required. 

**Markdown syntax support**:

Ghost has solid Markdown support built in. The Ghost editor will auto-parse standard Markdown as you type or paste, turning it into formatted content. Most CommonMark and basic GFM elements work (headings, bold/italic, code blocks, links, lists, etc.), but there are a few limitations. Ghost does not support Markdown tables natively (tables must be inserted as HTML or via a specialized card) ￼ ￼. Nested lists and blockquotes are only partially supported in the editor ￼. Ghost does support strikethrough, inline code, syntax-highlighted code fences, and even footnotes (via a special “Markdown card”) ￼ ￼. For example, you can insert a Markdown card in Ghost and write footnote syntax; Ghost will render a footnotes section at the end of that card ￼ ￼. Obsidian’s wiki-links ([[Internal Link]]) are not understood by Ghost out-of-the-box – you would need to manually convert those to normal hyperlinks. Mermaid diagrams and LaTeX math are not supported natively by Ghost’s editor; achieving these requires adding custom scripts or using theme modifications (e.g. injecting a MathJax script for LaTeX, or a Mermaid.js script and an HTML card for diagrams). In summary, Ghost handles standard Markdown well ￼ but will require workarounds for Obsidian-specific syntax, tables, and advanced extensions.

**Pricing**:

No free tier (aside from a 14-day trial). Pricing is tiered by audience size. The Starter plan is $9/month (billed yearly) for up to 500 members ￼. The Creator plan is $25/month (yearly) for up to 1,000 members. Higher tiers like Team ($50/mo) and Business ($199/mo) raise member limits (Team still 1,000 members, Business 10,000) and add staff users and support. All plans include the core Ghost features: custom domain, CDN, SSL, etc. Notably, the Starter plan is limited to 1 staff user and 18 free themes only (no custom themes on Starter) ￼ ￼. Upgrading to Creator or above allows unlimited custom themes and integrations. Ghost does not have a free hosted plan, but you can self-host Ghost for free if you have your own server (this requires technical know-how). For Obsidian bloggers just starting out, the $9/mo Ghost(Pro) is the entry point (with the constraint of using official themes only on that tier).
￼
**Pros**:
- Powerful Publishing Platform: Rich feature set (memberships, newsletters, analytics, SEO settings) all in one. Great if you want your blog to also serve as a newsletter or a community hub with memberships ￼.
- Polished Editing Experience: Ghost’s web editor is user-friendly with formatting cards and preview. Even if you write in Obsidian, it’s nice that Ghost can handle the content well and let you refine it in the Ghost editor if needed.
- Customizability: If you want a custom design or advanced site structure, Ghost can accommodate with custom themes and robust theming options. No coding limitation if on a higher tier ￼.
- Scalability: Handles large audiences (with higher plans) and content heavy blogs. Built-in caching/CDN means performance is solid.
- Official Support and Community: As a mature platform, Ghost has good documentation and a community/forum (as well as Ghost staff support on paid plans).

**Cons:**
- Complex Setup for Obsidian Workflow: No native Obsidian integration – you must rely on a plugin or manual copy-paste ￼ ￼. This is more cumbersome than Blot’s seamless folder sync. If the plugin or API setup glitches, it’s extra overhead.
- Higher Cost: $9/mo (annual) is the minimum for Ghost(Pro), which is higher than Blot or Micro.blog’s basic options. And that Starter tier has theme limitations ￼. If you need multiple users or many members, costs rise quickly (Ghost can get pricey for large newsletters because of member count billing).
- Overkill for Simple Needs: If you just want a straightforward blog for notes, Ghost’s features might be overkill. It’s like using a professional publishing suite for a personal notebook – powerful, but you might not use 80% of its capabilities.
- Markdown Quirks: Some Obsidian-written content might need tweaking (e.g., tables won’t render without adjustment ￼, wiki-links not recognized). You may need to pre-process or edit after paste. That adds friction for large volumes of content.
- Hosting Lock-In: Using Ghost(Pro) means your content is in a database on their server. It’s exportable (Ghost can export JSON/HTML), but you can’t just pull the Markdown files back easily. In contrast, Blot keeps your source as Markdown files on your drive.

### Blot.im

**Workflow**

Blot is designed for file-based publishing. It “turns a folder into a website". The workflow is extremely simple: you sync a folder (via Dropbox, Google Drive, Git, iCloud, or local folder) with your Blot blog, and any Markdown files in that folder become blog posts automatically. For Obsidian users, this means your Obsidian vault (or a subset of it) can be your blog – just save or drag-and-drop a Markdown file into the synced folder and it publishes. There’s no web UI for writing posts; you use Obsidian (or any text editor) and let Blot detect file changes. Blot will generate the site within seconds of file sync. You can also organize content with subfolders (e.g. a _drafts folder for unpublished drafts). Images placed in the folder are uploaded and served by Blot as well. In short, Blot offers a mostly automated Obsidian-to-blog workflow with minimal setup.

**Markdown syntax support**

Blot directly converts your Markdown files to HTML and has excellent support for Markdown (including some Obsidian goodies). Under the hood, Blot uses a parser (similar to Goldmark/Pandoc) that supports GFM features like tables, footnotes, and more. Notably, Blot supports Obsidian wiki-links: you can enable “wikilinks” in your blog settings, allowing [[Wiki Link]] syntax to link between posts ￼ ￼. Blot will resolve a [[Linked Note]] by finding the post with that title or filename and inserting the correct URL ￼ ￼. This is a huge plus for Obsidian users with interlinked notes. Blot also supports Markdown footnotes, strikethrough, and tables (since these are part of standard Markdown specs or extensions). For images, you simply use the usual ![alt](image.png) syntax and ensure the image file is in the folder – Blot will handle it ￼. Regarding diagrams and math: Blot has built-in TeX/LaTeX math rendering support. By wrapping expressions in $$…$$, you can include LaTeX math, which Blot will typeset (it likely uses KaTeX under the hood) ￼. This means equations will display properly without extra effort. For Mermaid diagrams (flowcharts, etc.), Blot doesn’t natively render them, but you can achieve it by adding the Mermaid JS library. Blot allows custom JavaScript in posts or templates, so if you include the Mermaid script in your theme (or within an HTML segment of a post), you can render mermaid code blocks. In fact, Blot users have successfully embedded scripts like Mermaid.js by ensuring the script links use HTTPS and are included in the post’s HTML head ￼ ￼. Once the script is loaded, any Mermaid code fence in your Markdown will render as a diagram when the page loads ￼. Overall, Blot is very Markdown-friendly (with complete GFM support) and Obsidian-friendly (wiki-links, math, etc.), but Mermaid diagrams or other JS-based extensions require a bit of manual setup.

**Pricing**

Blot keeps pricing simple – there is one plan at $6 per month per site ￼. This includes hosting, all features, and support. You can create multiple sites, and each would be $6/mo. There’s no free tier, but Blot’s source code is open source (AGPL) ￼, so technically you could self-host it for free; however, most users will opt for the hosted service for convenience. Blot allows an annual payment after signup if you prefer (with no discount mentioned, it would be $72/year) ￼. All features (publishing via folder, templates, etc.) are included at the $6 price – there are no higher tiers. This flat pricing is quite affordable compared to Ghost and Micro.blog’s higher plans. Keep in mind Blot doesn’t impose member limits or anything, since it doesn’t have membership features built-in. It’s just one price for the blog.

**Pros**:
- Seamless Obsidian Integration: Your Markdown files are the content. This is as close as it gets to Obsidian Publish without the price – just save files in a folder and it’s live. The support for Obsidian’s wikilinks and relative links is a huge plus ￼ ￼, making cross-note references on your blog work automatically.
- Simplicity and Speed: There’s no complex CMS to learn. If you know how to save a Markdown file, you know how to publish on Blot. The automation (via Dropbox/Git etc.) is reliable and almost instant. No need to log into a dashboard for each post.
- Low Cost: $6 a month for everything – this is very affordable, especially given unlimited storage (within reason) and bandwidth (1 TB/yr soft limit) ￼. You get personal support from the developer as well.
- Flexibility with Sources: You can write in Obsidian, Word, Google Docs, or even export Jupyter Notebooks – Blot accepts various file types (it can convert Word docs to posts, etc.) ￼. So if some content isn’t in Obsidian, you can still include it easily by dropping the file in.
- Privacy and Ownership: Your content stays as files in your control (especially if using Git). You have a local copy always. Leaving Blot is easy – just export to WordPress format or use your files to generate a new site ￼. There’s no proprietary data format.
- Obsidian-esque Blogging: Blot’s support for math (LaTeX) ￼ and other nerdy markdown features makes it great for technical blogs or digital gardens. It feels like an extension of Obsidian.

**Cons:**
- Limited Platform Features: Blot is intentionally minimal. There’s no built-in commenting, no native search, no built-in newsletter, no content scheduler, no analytics dashboard. It’s essentially a static site generator in the cloud. Any additional feature (comments, search, etc.) requires manual addition (e.g., adding a Disqus code or embedding a search script). If you need lots of bells and whistles without coding, Blot might disappoint.
- Design Customization Requires HTML/CSS: While there are some ready-made templates, to really tweak your site you’ll have to edit template files. This is not as point-and-click as some modern blogging platforms. Non-technical users might find deep customization challenging (though basic changes like text in footer or colors are doable if the template is designed for it).
- Media Handling: You can include images easily, but handling large media (videos) or image galleries might require some work. There’s no media library interface – you manage files via your folder. Also, you must be mindful of image placement: if an image file is in the main posts folder, Blot might treat it as a post (some users encountered images appearing on the homepage when not handled properly) ￼. Organizing images in subfolders is a good practice.
- Small Community: Blot is a one-man project (with a loyal user base, but small). While support is personal, you won’t find as many tutorials, themes, or community plugins as with Ghost. It’s a niche tool – which also means it’s not going to suddenly copy big platform trends, but you might have to solve problems yourself via the forums.

### Micro.blog

**Workflow**:

Micro.blog is a hybrid of a blogging platform and a social network. It doesn’t use a folder sync; instead, you publish via Micro.blog’s apps, web interface, or API. For Obsidian users wanting automation, Micro.blog supports the Micropub API and has a **community plugin called Micro.publish** that lets you publish notes from Obsidian to your Micro.blog-hosted site with one command. After obtaining an API token, the plugin can send your Markdown post to Micro.blog as either a blog post or a page. (Notably, the developer collaborated with Micro.blog’s founder to extend the API for creating pages via Micropub.) Without the plugin, you would copy-paste from Obsidian into Micro.blog’s web editor or use a third-party app like MarsEdit. Micro.blog treats short, titleless posts as “microblog” entries and longer notes with titles as full blog posts. Content you publish appears on your blog and in the Micro.blog social timeline for others to read. Overall, Micro.blog’s workflow can be semi-automated (with the Obsidian plugin) or manual via its posting interfaces.

**Markdown syntax support**:

Micro.blog’s publishing system is based on Hugo (a static site generator), which means it supports Markdown (CommonMark via Goldmark) and many GFM extensions. In practice, you can use standard Markdown for formatting posts on Micro.blog-hosted blogs: headings, bold/italic, lists, blockquotes, links, images, and code fences all work as expected. Hugo’s Markdown processor supports tables and footnotes by default, so those should work on Micro.blog (e.g. a Markdown table will be rendered to HTML, and footnote syntax [^1] will produce footnotes). One caveat is that Micro.blog’s social timeline will strip out complex HTML or styling for consistency ￼ ￼. They recommend sticking to simple formatting (no advanced embeds) so that your posts also look good in the Micro.blog feed ￼. Obsidian’s wiki-links are not natively supported on Micro.blog – a [[Note]] will just appear as literal text unless you convert it. The Obsidian-to-Micro.blog plugin may eventually handle such conversion, but currently you’d need to replace wiki-links with standard Markdown links manually. Mermaid diagrams are not directly supported out-of-the-box. However, because you can use custom Hugo templates or plugins on Micro.blog (with the $5/mo plan or above), it’s possible to enable Mermaid via a Hugo Diagrams render hook or a shortcode. In fact, Micro.blog now allows using Hugo 0.117, which supports an internal tool called Goat for diagrams ￼ ￼. Enabling this requires a custom theme or opting into the newer Hugo version in your blog settings ￼. Some users have managed to use Mermaid by adding a custom render hook template and the Mermaid JS library in a custom theme ￼. For LaTeX math, Micro.blog similarly has no native support, but you can add MathJax via a theme customization ￼. The Micro.blog help docs confirm that to use LaTeX, you need to edit your theme to include MathJax (there are tutorials guiding this) ￼. In summary, Micro.blog handles basic Markdown well, including GFM elements, but requires custom theme work for advanced features (diagrams, math). Users on the lower-tier plan (which doesn’t allow custom themes) might be limited to simpler Markdown.

**Pricing**: 

Micro.blog offers a free social-only account and several paid plans for hosting. If you just join Micro.blog without paying, you get a username and can follow/reply to others, and even connect an external RSS feed, but no hosted blog of your own ￼. For a hosted blog, the entry plan is Micro.one at $1/month ￼. Micro.one gives you a hosted microblog (username.micro.blog or custom domain), with basic features: you can post via web or apps, include photos, short videos (up to 75 MB), basic podcast hosting (75 MB episodes), custom CSS, and use a custom domain ￼ ￼. However, Micro.one does not include cross-posting or full theme editing. The next level, Micro.blog (standard) at $5/month, includes everything in Micro.one plus automatic cross-posting to other networks (Mastodon, Threads, Bluesky, Medium, Tumblr, LinkedIn, etc.) ￼. It also unlocks custom themes (you can edit the HTML templates or use community themes) and features like posting to private blogs or shared blogs ￼. Above that, Micro.blog Premium at $10/month adds the ability to create up to 5 blogs and includes an email newsletter feature, bookmarks and highlights, and a beta notes app ￼. There’s also a Family plan at $15/month which is basically Premium + up to 5 collaborators (family or friends) who can post to your blogs ￼. All paid plans include a 7-day free trial, and there are yearly billing options with discounts (e.g. standard plan is $50/year instead of $60) ￼. In summary, Micro.blog can cost as little as $1/month for a basic blog, but Obsidian users might want at least the $5/month plan to get custom theme support (for better Obsidian integration and features). The $10 plan is relevant if you want the integrated newsletter or multiple blogs.

**When to choose:**

Pick Micro.blog if you want a “write in Obsidian → publish anywhere” flow with no server maintenance, don’t mind its minimalist design philosophy, and like the idea of your blog doubling as a small fediverse-enabled social network.

**Pros:**
- Integrated Social Experience: Micro.blog is both a blog host and a community. Every post you publish can appear in the Micro.blog timeline, where others can discover and comment on it. If you enjoy the idea of a small, friendly social network around your writing, Micro.blog offers that out-of-the-box. It also federates with Mastodon/ActivityPub, so your blog can be followed by Mastodon users automatically ￼. This can increase the reach of your Obsidian musings without extra effort.
- Ease of Use: For short-form posts, Micro.blog is as easy as tweeting. You don’t need to worry about titles or formatting if you don’t want to – just write and publish. This lowers the friction to share quick thoughts, which might encourage you to blog more frequently. The Micro.blog official apps (iOS, Android, Mac) and web interface make publishing convenient anywhere.
- Cross-Posting: If you still use legacy social media, Micro.blog can auto-post your content to Twitter (X), Mastodon, Tumblr, Medium, LinkedIn, and more ￼. This is a huge time-saver if you want to maintain an presence on those platforms by writing once in Obsidian/Micro.blog.
- Adaptable Length: You can mix micro-posts (no title, short) and longer articles on the same blog. This is nice for Obsidian users who might want to publish both quick snippets (perhaps like atomic notes or inspirations) and full articles or tutorials. Micro.blog handles both gracefully – short posts show up as status updates, longer ones as blog entries with titles.
- Newsletter & Podcast in One: With the premium plan, Micro.blog can send out your posts as a newsletter ￼, and even host a podcast (audio uploads are turned into an RSS feed for podcast apps). It’s quite versatile for different content types, which could be a pro if you plan to venture beyond text (Ghost also does email well, but doesn’t natively turn your audio into a podcast feed; Micro.blog does).
- Low Cost Entry: The $1/month plan allows anyone to get started with a full blog (with some limitations). Even the $5 plan is affordable for the features it offers (multiple integrations, custom theming, etc.). It’s cost-effective for personal blogging.
- Content Ownership and Export: You can export your Micro.blog content at any time (it provides a JSON or Markdown export). Since it’s built on Hugo, your content remains largely Markdown and easily movable. And because it sits on the open web (no walled garden for your blog posts), you maintain control.

**Cons:**
- Not Focused on Long-Form Editing: While Micro.blog does support long posts, the interface is spartan for heavy editing. It’s essentially a simple text box (or you use an external editor via Micropub). There’s no preview on the web (though you can use third-party editors). If you rely on Obsidian for preview and polishing, this may be fine. But Ghost’s editor is far superior for composing long articles with embedded media, and even Blot allows you to use Obsidian’s full editing prowess locally. With Micro.blog, you might miss some advanced editing comfort (e.g., you can’t insert a footnote easily in the Micro.blog web editor without knowing Markdown by heart).
- Limited Advanced Formatting: Because Micro.blog strips out certain HTML in the timeline and doesn’t natively handle things like footnotes or complex embeds, you might feel a bit constrained if your posts rely on those. For instance, an Obsidian note with a fancy HTML table or iframe might not carry over cleanly. You have to ensure your content stays in the “simple Markdown” lane for best results ￼. Advanced content is possible with custom templates, but that raises the technical bar.
- Customization Requires Hugo Knowledge: For serious customization (beyond colors and fonts), you have to dive into Hugo templating. This can be daunting if you’re not familiar with it. The learning curve might not be worth it unless you have very specific needs. Ghost’s theming might actually be easier for some, thanks to more documentation and a simpler structure, whereas Hugo is very powerful but complex.
- Fragmented Content vs. Vault: If you use Micro.blog for frequent short posts, those posts might live only on Micro.blog (unless you keep copies in Obsidian). An Obsidian plugin can publish notes as posts, but if you impulsively post from your phone via Micro.blog, that content isn’t automatically pulled back into Obsidian. You’d have to manually paste it if you want it in your vault. This can lead to a split brain where some content is in Obsidian, some only on Micro.blog. With Blot, by contrast, your vault is the source of truth for everything on the site.
- Social Aspect Not for Everyone: The flip side of Micro.blog’s community is that it’s another social feed to keep up with. If you just want a quiet place to publish essays, Micro.blog’s social notifications and timeline might be a distraction. Also, the community, while positive, is relatively small – if your aim is to reach a large audience or build an SEO powerhouse, Micro.blog itself doesn’t directly provide that (you’d rely on search engines indexing your site and the network effect of cross-posting). Ghost, being independent, might actually rank better for long content and doesn’t emphasize social features.


### HashNode (Pro)

**Workflow**:

Enable Hashnode’s “Publish articles from GitHub”. Every markdown file pushed to a chosen repo is auto-published (or updated) on your Hashnode blog; front-matter controls title, tags, draft state, etc. Use the free Obsidian Git community plugin to sync your vault (or just a /blog folder) to GitHub on save or on demand.

**Pricing**

Hashnode gives you comments, reactions, built-in newsletter, custom domain, and a dev-centric audience.

**Pros**:
- ...

**Cons**:
- Publishin from GitHub is only available on the Pro plan

...
