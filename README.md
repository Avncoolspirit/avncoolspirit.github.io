# Avnish Kumar Static Website

This is a no-build static website generated from `website.pdf`.

## Files

- `index.html` - page content and metadata
- `styles.css` - responsive visual system
- `script.js` - mobile navigation behavior
- `assets/` - source imagery extracted from the PDF

## Deploy on GitHub Pages

1. Push the `site/` folder contents to a repository.
2. In GitHub, open Settings > Pages.
3. Select the branch and folder that contain `index.html`.

## Deploy on Cloudflare Pages

1. Create a Pages project connected to your repository.
2. Set the build command to empty.
3. Set the output directory to `site` if this folder is inside a larger repo, or `/` if the repository root is this folder.

## Notes

The LinkedIn buttons point to `https://www.linkedin.com/in/avnish-kumar-40a54328`, which matched the public AWS Bedrock profile found during setup.
