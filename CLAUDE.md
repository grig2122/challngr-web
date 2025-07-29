# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is the Challngr app support website, created to fulfill App Store requirements for a support URL. The website provides:
- Support information and FAQs
- Contact details
- Privacy Policy
- Terms of Service

## Project Structure

```
challngr_web/
├── index.html       # Main support page with FAQ and contact info
├── privacy.html     # Privacy policy page
├── terms.html       # Terms of service page
└── styles.css       # Shared styles for all pages
```

## Development

This is a static website with no build process required. To make changes:
1. Edit the HTML files directly
2. Test by opening files in a web browser
3. Ensure all links between pages work correctly

## Deployment

The site is deployed to Firebase Hosting:
- **Live URL**: https://whats-your-challenge.web.app
- **Firebase Project**: whats-your-challenge
- **Deploy Command**: `firebase deploy --only hosting`

To deploy updates:
1. Make your changes to the HTML/CSS files
2. Run `firebase deploy --only hosting`
3. The changes will be live within minutes

Alternative deployment options:
- GitHub Pages
- Netlify
- Vercel

## App Store Requirements

This website satisfies the App Store requirement for a Support URL. The URL should be added to the App Store Connect listing in the "Support URL" field.