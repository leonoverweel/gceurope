# Generation Climate Europe

![GCE Logo](static/images/gceurope-opengraph.png)

This is the repository for the [Generation Climate Europe website](https://gceurope.org).
The site runs on [Hugo](https://gohugo.io/), a static site generator that takes content written in Markdown (the demands and organizations attached to GCE) and builds them into the HTML landing page.
It's hosted on [Netlify](https://www.netlify.com).

To build the site locally:

1. Download and install [Hugo](https://gohugo.io/).
1. Clone this repository.
1. Run `hugo server` in the base directory (where this file resides).
1. Navigate to `localhost:1313/` to see the site live.

Some common file locations for editing the site:

* Demands are in `content/demands`.
* Organizations are in `content/organizations`. To add a new one, add a new file to that folder and fill in the appropriate fields.
    * Logos for organizations are in `static/images/logos`.
* The main files for the landing page are:
    * `themes/gceurope/layouts/index.html`
    * `themes/gceurope/layout/partials/head.html`
    * `themes/gceurope/static/css/main.css`
