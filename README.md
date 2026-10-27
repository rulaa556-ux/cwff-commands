# cwff command guide

The public command reference for cwff: ten Discord menus, 55 tools and 124 actions. Search by feature, browse categories, filter by access and follow setup walkthroughs.

## Hosting

This is a buildless static site hosted by GitHub Pages from the root of the main branch. Relative asset URLs support both project sites and custom domains. The `.nojekyll` file skips Jekyll processing.

## Updates

Update the static files, preview them with a local HTTP server, and push to main. GitHub Pages publishes the new version automatically. The bot maintainer can regenerate catalog.json from the bot’s static command definitions using npm run docs:web.

This repository contains only public website files. Bot credentials, settings, payment destinations and member records are excluded.
