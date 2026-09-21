# esc

[![Netlify Status](https://api.netlify.com/api/v1/badges/a885bdee-a84c-41ef-9592-6db9b59b7417/deploy-status)](https://app.netlify.com/sites/ybw0014-esc/deploys)

This repository contains the Hello World page. It uses the standard HTML5 boilerplate and plain HTML with no CSS, as required by the assignment. The body includes a heading and paragraph, plus a figure.

Site is available at: https://ybw0014-esc.netlify.app/

## Head metadata

The head contains metadata beyond the standard boilerplate. The description provides a page summary for search engines and link previews. The theme-color value tells mobile browsers which color to use for their own interface; it does not style the page.

Open Graph tags control how the page appears when its link is shared. og:type identifies it as a website, og:title supplies the title, and og:description supplies the summary. HTML comments in index.html explain these additions.

## Workspace

The figure in the body displays workspace.png, a screenshot of the editor with this repository open. It shows the workspace where the page was written.

## Deployment

The site is hosted on Netlify and connected to the GitHub repository's master branch. Every push to master triggers a new deploy. Netlify initially generated a random site name, which was changed to ybw0014-esc.

Build settings are stored in netlify.toml in the repository, rather than only in the Netlify dashboard. There is no build command, and the publish directory is the repository root.

The _headers file adds X-Content-Type-Options, Referrer-Policy and Permissions-Policy to every response. It also tells browsers to cache workspace.png for a year.

## AI Disclosure

The Netlify badge, **Head metadata**, **Deployment** section in README was added by AI.
