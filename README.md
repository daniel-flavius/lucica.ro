# lucica.ro

Static personal website for Daniel-Flavius Lucica.

## Deploy with GitHub + cPanel

1. Create a GitHub repository, e.g. `lucica-ro`.
2. Put the contents of this folder in the repository.
3. Upload/push the files to GitHub.
4. In cPanel, open **File Manager**.
5. Open the document root for `lucica.ro` (usually `public_html`).
6. Upload the website files so that `index.html` is directly inside the document root.
7. Visit https://lucica.ro

## Updating

Edit files locally, then:

git add .
git commit -m "Update website"
git push

For cPanel, either upload the changed files manually or configure cPanel Git Version Control to deploy from the GitHub repository.

## Notes

- No database is required.
- No PHP/Node backend is required.
- The site is responsive.
- The current content is based on publicly indexed professional information.
- Review all career dates/titles before publishing.
- Replace the generic LinkedIn article links with direct article URLs if desired.
- Google Fonts is loaded externally; remove the @import line if you want the site to have zero third-party runtime requests.
