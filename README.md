# My Personal Website

A simple personal website built with Jekyll and hosted on GitHub Pages.

## Quick Start

1. Replace the placeholder content in `_config.yml` with your information
2. Edit `index.md` with your bio
3. Update `projects.md` and `talks.md` with your content
4. Push to GitHub and your site will be live!

## File Structure

```
├── _config.yml          # Site settings (edit this first!)
├── _layouts/
│   ├── default.html     # Main page template
│   └── post.html        # Blog post template
├── _posts/              # Blog posts go here
│   └── 2024-01-01-welcome-to-my-blog.md
├── css/
│   └── style.css        # Styles (customize colors, fonts here)
├── images/              # Put your images here
├── index.md             # Homepage
├── projects.md          # Projects page
├── talks.md             # Talks page
└── blog.md              # Blog listing page
```

## Customization

### Update Your Info
Edit `_config.yml` and replace:
- `title` with your name
- `description` with your tagline
- `url` with your GitHub Pages URL
- Social usernames (linkedin, github, twitter, email)

### Add Your Photo
1. Add your photo to the `images/` folder (e.g., `profile.jpg`)
2. Uncomment the image line in `index.md`

### Change Colors
Edit `css/style.css` to customize:
- Link color: search for `#0066cc` and replace
- Text color: search for `#333`
- Background: search for `background-color`

### Add Blog Posts
Create new files in `_posts/` with the format:
```
YYYY-MM-DD-post-title.md
```

Each post needs this at the top:
```yaml
---
layout: post
title: "Your Post Title"
date: YYYY-MM-DD
description: "A short description"
---

Your content here...
```

## Local Development (Optional)

To preview locally before pushing:

```bash
# Install Jekyll (one time)
gem install bundler jekyll

# Run local server
bundle exec jekyll serve

# View at http://localhost:4000
```

## License

Feel free to use this template for your own site!
