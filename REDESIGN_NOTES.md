# Research website redesign

This version preserves the existing AcademicPages/Jekyll site and adds a research-led portfolio design.

## What changed

- Rebuilt the homepage around a concise research identity and selected contributions.
- Added a dedicated Research page organized around four complementary research pillars.
- Added a separate About page with professional background and contact links.
- Reworked Teaching into a Teaching & Mentoring page.
- Updated the primary navigation while retaining the complete publications, talks, and CV pages.
- Added responsive styling for desktop, tablet, and mobile displays.
- Updated the site description, social-profile metadata, and default social image.

## Most useful files to edit later

- `_pages/about.md` — homepage wording and featured publications
- `_pages/research.md` — research themes and future directions
- `_pages/about-bio.md` — professional biography
- `_pages/teaching.md` — teaching and mentoring content
- `_data/navigation.yml` — main navigation
- `_sass/_research-site.scss` — redesign styling
- `_config.yml` — site-wide description, social links, and metadata

## Put this version into the existing GitHub Desktop repository

1. Make a backup copy of the current local repository folder.
2. Extract this ZIP into a separate folder.
3. Copy the extracted contents into the existing local `StopkaKris.github.io` repository folder and allow the changed files to be replaced.
4. In GitHub Desktop, review the listed changes before committing.
5. Commit with a message such as `Redesign research website` and push when ready.

The ZIP intentionally does not contain a `.git` folder. Your existing local repository remains the source of Git history and remote settings.

## Local preview

If Ruby and Bundler are installed, run the following from the repository folder:

```bash
bundle install
bundle exec jekyll serve
```

Then open the local address shown by Jekyll. GitHub Pages will perform the same general build after the changes are pushed.
