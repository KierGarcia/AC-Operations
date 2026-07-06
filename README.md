# AC Operations static website

This folder is ready to publish as a WordPress-free static site for GitHub Pages.

## What is included

- Static HTML pages
- Shared CSS
- Recovered media assets under `assets/uploads/`
- No WordPress, PHP, database, or plugins required

## Pages

- `/` Home
- `/services/` Offered Services
- `/our-story/` Our Story
- `/team/` Meet the AC Operations Team
- `/contact-us/` Contact Us

## Contact form behavior

The contact page uses a direct email link to `a.chingatum@acoperations.com`, so the site remains fully functional without WordPress or a server-side form processor.

## GitHub Pages deployment

1. Create a GitHub repository and upload this folder to the repository root.
2. Open Settings > Pages in GitHub.
3. Select the main branch as the source.
4. Save the changes and wait for deployment to complete.

A GitHub Actions workflow is included to publish the site automatically on each push to the main branch.
