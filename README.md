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
4. Open `http://127.0.0.1:4000/professional_website/`.

## Publish on GitHub Pages
1. Push this repository to GitHub.
2. In **Settings -> Pages**, set **Source** to **GitHub Actions**.
3. Do not also configure **Deploy from branch** for this repo. The workflow in `.github/workflows/jekyll.yml` handles deployment.
4. After the workflow succeeds, the site should publish at `https://twang2000.github.io/professional_website/`.

## Notes for This Repo
- This is a project site, not a user site, so links must respect the repository base path.
- The repository base path is currently `/professional_website`.
- The Pages workflow uses GitHub's built-in Jekyll Pages action.

## Next Customizations
- Replace LinkedIn and Calendly placeholders.
- Add project screenshots and architecture diagrams.
- Add additional blog posts and case studies.
