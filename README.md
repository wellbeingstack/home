# WellbeingStack

Personal website for the WellbeingStack mentorship program by Xiao Yue.

**Live site:** https://wellbeingstack.github.io (after GitHub Pages is enabled)

## Structure

```
/
├── index.html          # Homepage (Hero, About, Mentorship, Blog preview)
├── blog/
│   └── index.html      # Blog listing page (placeholder until first posts)
└── README.md
```

## Deploying to GitHub Pages

1. Push this repo to `github.com/wellbeingstack/<repo-name>`
2. Go to **Settings → Pages**
3. Under **Source**, select `Deploy from a branch`
4. Choose `main` branch, `/ (root)` folder
5. Click **Save** — your site will be live in ~60 seconds

## Customizing

### Add your Calendly link
Search for `YOUR_LINK_HERE` in `index.html` and replace with your actual Calendly URL.

### Update your name / bio
Edit the `about` section in `index.html`.

### Add a blog post
Create a new folder inside `blog/`, e.g. `blog/my-first-post/index.html`.
Then link to it from `blog/index.html`.

### Custom domain (optional)
1. Add a `CNAME` file to the root with your domain: `wellbeingstack.com`
2. Configure DNS with your registrar to point to `wellbeingstack.github.io`
3. Enable HTTPS in GitHub Pages settings
