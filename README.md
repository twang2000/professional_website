# Professional Website (GitHub Pages)

Personal website for **Tuan Wang**, focused on SDET experience, projects, and technical blogging.

## Site Map
- `/` Home (SDET-first landing page)
- `/resume/` Resume details
- `/projects/` Project portfolio (currently Groundhog template)
- `/blog/` Blog index (posts live under `_posts/`)
- `/contact/` Contact and scheduling links

## Tech Stack
- GitHub Pages + Jekyll
- Minima theme

## Local Development
1. Install Ruby + Bundler.
2. Install dependencies:
   ```bash
   bundle install
   ```
3. Run local server:
   ```bash
   bundle exec jekyll serve
   ```
4. Open `http://127.0.0.1:4000`.

## Publish on GitHub Pages
1. Push this repository to GitHub.
2. In **Settings → Pages**, set source to **GitHub Actions** or **Deploy from branch**.
3. If using branch deploy, use `main` (or your default branch) and root folder.

## Next Customizations
- Replace LinkedIn and Calendly placeholders.
- Add project screenshots and architecture diagrams.
- Add additional blog posts and case studies.
