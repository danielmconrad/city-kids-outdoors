# City Kids Outdoors — Project TODO

## Setup (one-time, developer tasks)

- [x] Create Jekyll + GitHub Actions deploy pipeline (no Gemfile needed)
- [x] Create site layouts and pages (Home, Programs & Events, About, Contact)
- [x] Create Sveltia CMS admin panel (`/admin/`)
- [ ] **Enable GitHub Pages in repo settings**
      Go to Settings → Pages → Source: "GitHub Actions"
- [ ] **Set up OAuth for Sveltia CMS** (required for content editing)
      Sveltia CMS needs an OAuth proxy to authenticate editors via GitHub.
      Recommended: deploy the free `sveltia-cms-auth` Cloudflare Worker.
      Instructions: https://github.com/sveltia/sveltia-cms-auth
      Once deployed, add `base_url: https://YOUR_WORKER.workers.dev` to `admin/config.yml`.
- [ ] **Set up contact form**
      The contact form in `_layouts/contact.html` points to a placeholder Formspree URL.
      Sign up at https://formspree.io (free tier available) and replace `YOUR_FORM_ID`.
- [ ] Update `_config.yml` with final site URL (custom domain or GitHub Pages URL)

## Content (client tasks — can be done via CMS once OAuth is set up)

- [ ] Home: Add tagline and hero photo
- [ ] Home: Fill in programs summary text
- [ ] Home: Add Google Calendar link
- [ ] Home: Confirm contact email
- [ ] Programs: Write Playdates description and add photos
- [ ] Programs: Write Classes description and add photos
- [ ] Programs: Write Community section
- [ ] Programs: Add Google Calendar link
- [ ] About: Write Mission statement
- [ ] About: Write Vision statement
- [ ] About: Add founder photo (Megan)
- [ ] About: Write founder bio
- [ ] Contact: Confirm email address
- [ ] Contact: Add Instagram URL
- [ ] Contact: Add Facebook URL

## Later (from sitemap)

- [ ] FAQs page
- [ ] Registration page/flow
- [ ] In The Media page
- [ ] Instagram feed embed (home page gallery section)
