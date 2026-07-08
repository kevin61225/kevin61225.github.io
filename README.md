# Kevin Tu's GitHub Pages

This repository powers a small resume-style personal site on GitHub Pages using Jekyll. The homepage presents a clean portfolio landing page, and the assignment subpage keeps coursework or practice work organized in the same visual style.

## What is included

- A shared Jekyll layout in `_layouts/default.html`
- A polished resume homepage at the repository root
- An assignment subpage for ECV-related work
- A site-projects page for supporting portfolio pages
- A responsive layout that works on desktop and mobile
- Simple content pages with front matter and no custom build step required on GitHub Pages

## Project Structure

```text
.
├── _config.yml
├── _layouts/
│   └── default.html
├── index.html
├── README.md
├── site-projects/
│   └── index.html
└── assignment/
	└── index.html
```

## Local Preview

Because the pages use Jekyll front matter and a shared layout, you must serve them through Jekyll for correct rendering. The recommended approach is to use Bundler:

```bash
bundle install
bundle exec jekyll serve
```

Then visit `http://localhost:4000/`.

If you open the repository in a VS Code Dev Container, Bundler is preconfigured and you can run:

```bash
bundle exec jekyll serve --host 0.0.0.0 --livereload
```

The container exposes port `4000` and sets `JEKYLL_ENV=development` so the site behaves like a local preview environment.

## GitHub Pages

If GitHub Pages is enabled for this repository, Jekyll will render the shared layout and the root `index.html` becomes the public homepage. The assignment page is available at `assignment/`.

## Editing the Site

- Update the homepage content in `index.html`
- Add more assignment or project pages under `assignment/`
- Add supporting site pages under `site-projects/`
- Update shared chrome in `_layouts/default.html`
- Replace the placeholder contact and profile details with your own information

## Next Ideas

- Add education and experience sections
- Add links to GitHub, LinkedIn, or email
- Expand the projects section with screenshots and write-ups