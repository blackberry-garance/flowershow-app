---
title: How to Enable Page Comments
description: A step-by-step guide to enabling and configuring Giscus-powered comments on your Flowershow Cloud sites, allowing readers to engage with your content through GitHub Discussions.
date: 2025-01-23
authors:
  - olayway
---

This tutorial will guide you through the process of enabling comments on your Flowershow Cloud site using Giscus - a comments system powered by GitHub Discussions. You'll learn how to set up GitHub Discussions, configure the Giscus app, and integrate comments into your site.

## Step 1: Enable GitHub Discussions

1. Go to your site's repository Settings
2. Scroll down to the Features section
3. Check the "Discussions" checkbox

## Step 2: Install Giscus GitHub App

1. Visit [github.com/apps/giscus](https://github.com/apps/giscus)
2. Click "Configure"
3. Select the repository with your site's content
4. Click "Save"

## Step 3: Get Configuration IDs

1. Visit [giscus.app](https://giscus.app)
2. Enter your repository name in the configuration form
3. Select your preferred discussion category
4. Locate the following IDs in the configuration section at the bottom of the page:
   - Repository ID (starts with 'R_')
   - Category ID (starts with 'DIC_')

Note: You can ignore other settings as they are pre-configured in Flowershow Cloud.

## Step 4: Configure Your Site

1. Go to your site's Settings page in the Flowershow Cloud dashboard
2. Find the "Comments" section
3. Toggle the switch to enable comments
4. Enter the Repository ID and Category ID from Step 3
5. Save your changes


![](/assets/cloud-comments-demo.mp4)

## Features and Benefits

Comments powered by Giscus offer several advantages:

1. **GitHub Integration**
   - All comments are stored as GitHub Discussions
   - Easy moderation through GitHub's interface
   - Automatic backup and version control

2. **Rich Text Support**
   - Full Markdown support in comments
   - Code syntax highlighting
   - Image embedding capabilities

3. **Security**
   - Spam protection through GitHub authentication
   - No anonymous comments

## Troubleshooting

Common issues and solutions:

1. **Comments section not appearing?**
   - Verify GitHub Discussions is enabled in your repository
   - Check if Giscus app has correct repository permissions
   - Ensure Repository ID and Category ID are entered correctly

2. **Users can't comment?**
   - Confirm they are logged into GitHub
   - Check if Discussions are locked in your repository
   - Verify the discussion category still exists
