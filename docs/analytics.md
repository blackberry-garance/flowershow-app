---
title: Analytics Configuration
---

> [!note]
> You are viewing documentation for Flowershow Cloud. For Flowershow Self-hosted documentation, visit [[/docs/self-hosted/README|docs/self-hosted]].

Flowershow supports Google Analytics 4 integration through a simple configuration in your site's `config.json` file. This guide covers how to set up analytics tracking for your Flowershow site.

## Configuration Structure

Analytics configuration is defined using the `analytics` field in your `config.json`:

```json
{
  "analytics": "G-XXXXXXXXXX"
}
```

## Properties

- `analytics`: Your Google Analytics 4 Measurement ID (starts with "G-")

## Data Stream Setup

Before configuring analytics, you need a Google Analytics 4 data stream:

1. Go to Google Analytics Admin > Data Streams
2. Click "Add Stream" > "Web"
3. Configure the stream:
   - URL: Your Flowershow site URL (e.g., `my.flowershow.app/@johndoe/abc`)
   - Stream name: A descriptive name (e.g., "My Flowershow Site")

Your Measurement ID will be displayed in the stream details after creation.

For detailed setup instructions and testing procedures, see our [[how-to-configure-google-analytics|analytics setup guide]].