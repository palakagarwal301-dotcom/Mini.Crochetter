# Mini Crochetter Deployment Notes

## Files

- `index.html` is the publish entry file for Netlify and GitHub.
- `mini_crochetter_website.html` is the working source file.
- `images/` contains the local image assets used by the page.

## Free Netlify Deploy

1. Create a GitHub repository.
2. Upload `index.html`, `mini_crochetter_website.html`, and the `images/` folder.
3. Log in to Netlify and choose `Add new site` -> `Import an existing project`.
4. Connect GitHub and select the repository.
5. Build settings:
   - Build command: leave blank
   - Publish directory: `.`
6. Deploy the site.

## Custom Domain Later

1. Buy the domain you want.
2. In Netlify, open `Domain management`.
3. Add the custom domain and follow the DNS instructions Netlify gives you.

## Optional Next Step

- If you want a contact form that actually sends submissions somewhere, add Netlify Forms or a backend later.
