# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Creative Balance Works is a static single-page website for a professional bookkeeping service. The site is hosted on GitHub Pages and uses Tailwind CSS via CDN.

## Architecture

- **Single-page application**: All content is in `index.html` with smooth-scrolling navigation between sections
- **Styling**: Tailwind CSS loaded via CDN (`https://cdn.tailwindcss.com`)
- **Hosting**: GitHub Pages with custom domain `creativebalanceworks.com` (configured via CNAME)
- **No build process**: The site is pure HTML/CSS/JS with no compilation or bundling steps

## Development

### Local Testing
Open `index.html` directly in a browser to preview changes. No local server is required, though one can be used:
```bash
python3 -m http.server 8000
# or
npx serve .
```

### Deployment
Changes pushed to the `main` branch are automatically deployed to GitHub Pages at `creativebalanceworks.com`.

## Site Structure

The single-page site contains these sections (accessible via anchor links):
- `#home` - Hero section with call-to-action
- `#about` - Background on the business and owner
- `#services` - Six service offerings (QuickBooks Setup, Monthly Bookkeeping, etc.)
- `#contact` - Footer with contact information and business hours

## Contact Information

The site displays:
- Email: contact@creativebalanceworks.com
- Phone: (555) 555-1234 (placeholder number)
- Business hours: Monday-Friday 9 AM - 5 PM
